# C3G prior-art foundations and corrected contribution boundary

Status: controlling attribution note for v1.13.1  
Date: 29 July 2026

## Withdrawn novelty characterizations

| Earlier C3G characterization | Correct classification | Retained C3G artifact |
|---|---|---|
| Independent freshness does not imply compatible governance/memory state; “compatible dual cut” | Repository/metadata consistency and stale-derived-state security are prior art | A C3G-specific cross-head regression and effect-gate binding |
| Forge/equivocation/halt algebra, including weighted hazards | Quorum/access-structure metrics, general adversary structures, shared-risk groups, and set-cover/hitting-set optimization are prior art | Executable bounded analysis for an agentic/prose-adversary deployment |
| Constitutional series duality | Standard AND/OR attack-tree and access-structure composition; repeated actors make per-layer summaries insufficient | Explicit-incidence counterexamples and a fail-closed Cartesian-composition API |

These corrections withdraw priority language; they do not invalidate the
counterexamples or the reference monitor.

## Standard notation

For a minimal-quorum family \(\mathcal Q\):

\[
c(\mathcal Q)=\min_{Q\in\mathcal Q}|Q|,
\]

\[
IS(\mathcal Q)=
\min_{Q\ne Q'}|Q\cap Q'|,
\]

\[
MT(\mathcal Q)=
\min\{|T|:\forall Q\in\mathcal Q,\;T\cap Q\ne\varnothing\}.
\]

If fewer than two distinct quorums exist, \(IS(\mathcal Q)\) is undefined; a
quorum is never paired with itself. C3G v1.13.1 uses `c(Q)`, `IS(Q)`, and
`MT(Q)` in executable reports.

Per-layer triples do not determine serial composition. Two 3-of-4 layers have
the same `(c(Q),IS(Q),MT(Q))=(3,2,2)` whether their actor sets are disjoint or
identical, yet their minimum serial quorum-union costs are respectively six and
three. Cross-layer actor incidence and the compatibility relation are required.

## Overlapping shared-risk model

A single-valued actor-to-domain map is only a partition diagnostic. It is not a
failure model because one actor can belong to several hazards simultaneously.
C3G therefore represents a hazard scenario \(j\) as an arbitrary actor set
\(S_j\) with positive weight \(w_j\). The weighted covers of quorums,
distinct-quorum intersections, and transversals are standard set-cover/hitting-
set specializations. Configured labels are never accepted as proof of physical,
credential, administrative, or observation-path independence.

## Defensible C3G contribution

The contribution claimed by this artifact is:

1. a threat model for AI agents that can manipulate prose, persuasion, context,
   and proposals while lacking the effect capability;
2. concrete composition-breakage counterexamples across governance, retrieval,
   continuity, identity, and execution boundaries; and
3. a dependency-free executable reference monitor plus non-vacuous bounded
   regressions that make those boundaries inspectable.

No novelty or production claim is made for access structures, quorum
intersection, shared-risk groups, set cover, attack trees, transparency logs,
metadata consistency, or reference monitors themselves.

## Primary foundations

- Malkhi, Reiter, and Wool, “The Load and Availability of Byzantine Quorum
  Systems,” *SIAM Journal on Computing* 29(6), 2000:
  <https://doi.org/10.1137/S0097539797325235>.
- Hirt and Maurer, “Player Simulation and General Adversary Structures in
  Perfect Multiparty Computation,” *Journal of Cryptology* 13, 2000:
  <https://crypto.ethz.ch/publications/HirMau00.html>.
- Garay, Johnson, Kiayias, and Yung, “Resource-Based Corruptions and the
  Combinatorics of Hidden Diversity,” 2012:
  <https://eprint.iacr.org/2012/556.pdf>.
- Samuel, Mathewson, Cappos, and Dingledine, “Survivable Key Compromise in
  Software Update Systems” (The Update Framework), CCS 2010:
  <https://theupdateframework.io/papers/survivable-key-compromise-ccs2010.pdf>.
- RFC 4202, “Routing Extensions in Support of Generalized Multi-Protocol Label
  Switching,” Shared Risk Link Groups:
  <https://www.rfc-editor.org/rfc/rfc4202>.
- RFC 7926, “Problem Statement and Architecture for Information Exchange
  between Interconnected Traffic-Engineered Networks”:
  <https://www.rfc-editor.org/rfc/rfc7926>.
- Kordy and Wideł, “On Quantitative Analysis of Attack–Defense Trees with
  Repeated Labels,” POST 2018:
  <https://doi.org/10.1007/978-3-319-89722-6_14>.

## Standing research rule

Search and cite before formalizing. A bounded proof establishes behavior of the
implemented finite model; it does not establish novelty, priority, production
security, source completeness, or correctness of real-world independence
claims.
