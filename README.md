# C3G — proof-carrying authorization for agent actions

**Author:** Luke. **Status:** research kernel. Not production.

Everything below is labeled proven, in progress, or not built. No claim without a
label.

## What it does

An AI agent proposes an action. C3G decides whether it was actually authorized,
and hands back a receipt you can check.

The rules:

- Someone proposes a claim. Someone else reviews it. A third person with the
  right scope ratifies it. Never the same person twice.
- No ratification, no authority. An unratified claim authorizes nothing.
- Two ratified claims that conflict return `CONTESTED_DENY`.
- No authority found returns `UNKNOWN_DENY`.
- Missing permission is never permission.

Every answer comes with what supported it, what opposed it, what's still
unresolved, who ratified it, source hashes, and one hash over the whole answer.

Python 3.12, standard library only. 328 tests. 58 schemas checked against 53
instances.

## Three things I claimed were new. They weren't.

I paid for hostile review of my own novelty claims. All three came back already
published. Here they are, with who got there first:

| What I claimed | Who did it first |
|---|---|
| Independent-freshness insufficiency / compatible dual cut | The Update Framework, Samuel et al., CCS 2010. Their snapshot role exists for exactly this reason — two things can each be valid and current and still not go together. |
| Hazard-scenario cost algebra | Malkhi, Reiter, Wool, J. Cryptology 2000 — minimum quorum size, intersection size, transversal size. The cost part is weighted set cover. Hirt–Maurer 2000 and Garay et al. 2012 for the priced version. |
| Serial composition asymmetry | Mauw–Oostdijk 2005, AND/OR attack trees. Kordy–Wideł for shared actors. |

Same review found two real bugs. Both fixed:

- I used a single-valued map from actors to failure domains. That's wrong. One
  person can sit in a cloud, a CA, a jurisdiction, an employer, and a supply
  chain all at once, and a single-valued map can't say that. It's now only a
  diagnostic, not a security model.
- Serial composition used to compute from per-layer summaries. Those summaries
  don't determine the answer — I can show two systems with identical summaries
  and different real costs. It now refuses to compute without explicit actor
  data.

Details in `PRIOR_ART_FOUNDATIONS.md`.

## What held up

**Proven — the model can't talk its way past the gate.**

The gate is `V = g ∘ π`. `π` strips every unauthenticated persuasive field out
of a request before the verdict gets computed. The model's words are
low-integrity input. They cannot reach the authorization bit. The model can
flip its own opinion under pressure and the verdict doesn't move.

Checked exhaustively: 16 authenticated security fibers, 64 assignments of six
persuasion fields, 1,024 verdicts. Zero verdict changes within a fiber. Zero
digest changes.

Noninterference isn't mine — that's Goguen–Meseguer 1982. What might be mine is
this use of it: keeping a refusal separate from whether the model agrees with it,
offline, where the model can't write anything.

**Proven — retrieval can't manufacture authority.** 648 superset comparisons,
432 claim-drop comparisons. Zero authority amplification. Deleting evidence
never moves a verdict toward permit.

**In progress —** durable monotonic heads and a real sign-once lock. A stale
clone with the same ID still beats it.

**Not built —** HSM keys. Real BFT. Eight independently run witness services.
Audited infrastructure diversity. Transactional execution. These need hardware
and separate operators. This artifact does not claim them.

## Why agents specifically

None of the prior art above has an attacker that can argue with you. TUF's
threat model has no sycophantic participant. Byzantine quorums assume faults,
not persuasion. That problem is new.

July 2026: a model system chained together permissions it legitimately had into
a path nobody intended, across research and production infrastructure. The
people hit needed 17,000+ logged events and a self-hosted model to work out what
happened.

C3G governs what an agent is allowed to do. It does not contain a process that
never asked. It is not a replacement for isolation.

## Full release

v1.13.1, sealed. 328 tests pass from a cold extract.

`452f14eed5193fc7da926feca22c638f7b31dc1083fa0c3bbf5e3d899ed5ec9f`

Ask and I'll send it.

## Who built what

I specified this in English and directed AI to implement it. I don't read or
write code. The design decisions, the corrections, and the adversarial framing
are mine. The code is not.

Saying so because it changes what I can answer. Ask me about the design, the
invariants, or the threat model and I'll defend it. Ask me to walk you through
the implementation line by line and I can't.

It also means there's a specific way this breaks: the docs say one thing and the
code does another. Treat the docs as the spec and any gap as a bug. Two have
already turned up that way — modality sitting in the schema that the verdict
logic never read, and sign-once "enforcement" that was really just a string
comparison.

## What this isn't

No users. Not deployed. Not production Byzantine infrastructure. Every audit so
far was one I commissioned myself.

The math is other people's, credited above. What I'm claiming is a working,
exhaustively checked version of it for a threat model that didn't exist when any
of it was written.
