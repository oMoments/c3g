# C3G — proof-carrying authorization for agent actions

**Author:** Luke. **Status:** research kernel. Not production infrastructure.

Honest status labels throughout (proven / in-progress / not built) so this stays
a record, not a pitch.

## What it is

An executable reference monitor for autonomous agent actions. A claim is
proposed, independently reviewed, and ratified by a scope-authorized actor
before it can authorize anything. Unratified claims never authorize. Conflicting
ratified claims return `CONTESTED_DENY`. No visible authority returns
`UNKNOWN_DENY`. Absence of a permit is never a permit.

Every answer carries its support, counter-support, visible unresolved claims,
its ratification cut, source hashes, and a deterministic answer hash.

Python 3.12, standard library only. 328 tests. 58 JSON Schemas against 53
generated instances.

## What was withdrawn after prior-art review

Three claimed novel results were submitted to independent hostile review. All
three came back matched to published work. They are withdrawn and reattributed,
not quietly dropped:

| Withdrawn claim | Prior art |
|---|---|
| Independent-freshness insufficiency / compatible dual cut | The Update Framework, Samuel et al., CCS 2010 — the snapshot role exists because individually valid, individually timely metadata does not imply a consistent repository state |
| Hazard-scenario cost algebra | Minimum quorum size, intersection size, and transversal size — Malkhi, Reiter, Wool, J. Cryptology 2000; weighted set cover; cost-indexed adversary structures, Hirt–Maurer 2000, Garay et al. 2012 |
| Serial composition asymmetry | AND/OR attack-tree cost algebra, Mauw–Oostdijk 2005; repeated labels, Kordy–Wideł |

Two further corrections came out of the same review and are implemented:

- The single-valued actor-to-domain map is withdrawn as an independence model.
  A single-valued map induces a partition and cannot represent one actor
  belonging simultaneously to a cloud, CA, jurisdiction, employer, and supply
  chain. It survives only as an advertised-partition diagnostic.
- Serial composition now refuses to compute from per-layer summaries. Identical
  per-layer triples are executably shown to produce different composed costs.
  Explicit actor incidence is required, fail-closed.

See `PRIOR_ART_FOUNDATIONS.md`.

## What survives

**Proven.** The persuasion-quotient invariance. The gate is implemented as
`V = g ∘ π`, where `π` erases unauthenticated persuasive fields before the
verdict is computed. Free-form model output is a low-integrity input that
cannot influence the high-integrity authorization bit. A model may reverse its
stated opinion under pressure; the verdict does not move. Exhaustively checked
over 16 authenticated security fibers and 64 assignments of six persuasion
fields — 1,024 verdicts, zero within-fiber verdict or digest changes.

Noninterference itself is not new (Goguen–Meseguer 1982). The candidate
contribution is this specific use: separating institutional refusal from model
agreement in an offline system where the model has no write capability.

**Proven.** Retrieval cannot amplify authority. 648 candidate-superset verdict
comparisons and 432 claim-drop comparisons, zero authority amplification, zero
movement toward permit under evidence deletion.

**In progress.** Durable monotonic heads and a real sign-once lock. A stale
same-ID clone is not yet defeated.

**Not built.** HSM key custody. Real BFT. Eight independently operated witness
services. Externally audited failure-domain independence. Transactional
external execution. These are physical deployment requirements, not properties
this artifact claims.

## Why the agentic case

None of the cited prior art has an adversary whose prose can argue with the
verdict. TUF's threat model has no sycophantic participant. Byzantine quorum
systems assume faults, not persuasion. That threat is recent.

In July 2026 a model system chained individually permitted capabilities into an
unintended path across research and production infrastructure, and the affected
party needed 17,000+ logged events and a self-hosted model to reconstruct it.
C3G governs authorized action. It does not provide containment and does not
replace isolation.

## Full release

Sealed v1.13.1, 328 tests passing from a cold extract.

`452f14eed5193fc7da926feca22c638f7b31dc1083fa0c3bbf5e3d899ed5ec9f`

Available on request.

## Candid boundary

This is a research kernel with hostile audits per version and hash-sealed
releases. It is not production Byzantine infrastructure, not a deployed system,
and has no external users. The mathematics is established prior art, correctly
attributed above. The contribution claimed here is an executable, exhaustively
checked instance for a threat model that postdates the literature it stands on.
