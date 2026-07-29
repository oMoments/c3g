# C3G 1.13.1: prior-art-corrected constitutional graph governance and accountable retrieval

## Abstract

**Correction notice (29 July 2026).** Three earlier novelty characterizations
were withdrawn after literature review. Cross-metadata freshness/compatibility,
quorum and adversary-structure cost analysis, and serial AND/OR composition are
prior-art foundations, not C3G discoveries. This correction changes names,
scope, and attribution; it does not manufacture production HSMs, BFT consensus,
independent operators, transactional effect execution, or audited failure
domains. Those remain deployment obligations.

C3G is a finite, executable model for governing high-risk AI actions. It
combines immutable evidence memory, a consensus-ordered constitutional fold,
positive relational policy, proof-compiled prohibitions, authenticated state
proofs, role-separated authority quorums, and an authority graph whose
structure affects which quorums may authorize execution.

Its system-safety thesis is deliberately outside the model: improve the safety
of AI-mediated action without modifying weights, prompts, refusal policies, or
hidden reasoning. Model safeguards reduce dangerous proposals; C3G attempts to
stop an invalid proposal from becoming an authorized effect when such a
safeguard fails, cannot inspect the complete institutional state, or blocks a
legitimate high-capability defensive task. The gate is therefore model-agnostic
defense in depth, not a replacement for alignment, sandboxing, or secure
infrastructure.

Version 1.13 adds principal-bound information-release governance without
letting retrieval enter the authority plane. Exact-request grants fix the
reader's scope and cumulative disclosure budgets; nonempty results open a
conserved debt that a key-disjoint attestor must partition exactly into used
and unused units. A canonical state root and transition journal authenticate
current rows and historical receipts, while only signed event time can advance
the durable clock. Four non-vacuous finite laws test scope non-bypass,
disclosure conservation, exact debt partition, and caller-clock
noninterference. The local profile remains zero-effect and requires an
independently retained head to resist coherent rollback.

Version 1.10 composed portable graph replay with ordered quorum finality and
effect-time freshness. The filesystem broker reconstructs an exact portable
batch from the actual governance, retrieval, continuity, and verifier state;
requires a 6-of-9 COMMIT QC over that batch; then requires a separate live
6-of-9 challenge response before consuming one local capability. Stable trust
pins roots and policies rather than an action proof, so it can be provisioned
before and reused across actions. A dependency-free Node.js verifier provides a
second implementation of the capsule wire, Merkle, trust-pin, and Ed25519
finality checks while leaving constitutional semantic replay mandatory.

The 25 July 2026 hostile audit materially changed the system. The earlier model
could accept a stale permit after a later same-epoch revocation, did not bind an
authorization to the actual execution request, did not anchor keys, treated
named workflow participants as unauthenticated strings, exposed exponential
online join work, and published an incorrect bounded-search result. Version 0.3
repaired those defects. The 26 July 2026 pass adds verifier-enforced durable
witness root indexing, distinct-quorum semantics, resource-bounded access
analysis, non-vacuous finite-proof coverage contracts, and incident-derived
capability-path cuts. Version 0.4 remained a research artifact.

The v0.5 follow-up closes four adjacent gaps: execution refuses volatile
witness state; monitor telemetry counts only verified receipts; retrieval
confluence binds the exact ordered selection as well as the verdict; and
capability analysis optimizes enforcement-domain guard diversity under an
explicit edge budget. It also formalizes why a restorable local database cannot
by itself prevent rollback. Version 0.5 remains a research artifact.

Version 0.6 implements the bounded retrieval/authorization composition. The
same total verifier now consumes an exact request-v2 binding, a verifier-held
memory head, a complete bounded visibility projection, an exact integer graph
selector, and the actual rendered context. It recomputes selection and the
governance/memory compatibility digest before the same reservation ledger can
issue a one-use execution slot. A durable local memory high-watermark rejects
ordinary rollback and same-position equivocation. The new result is
snapshot-relative and bounded; it is not source completeness, semantic
relevance, succinct vector search, production consensus, or deployment-ready
security. Version 0.6 remains a research artifact.

Version 0.7 replaces the verifier-provisioned memory-root assumption with a
separately anchored 5-of-8 memory witness plane. Its verifier consumes every
valid signer-level sign-once fact, rejects actor or anchored
administrative-domain overlap with the governance plane, and requires three
distinct durable state stores on the execution path. The memory
constitution/head high-watermark is now per-network and hash-links contiguous
anchor generations, making the predecessor commitment operational rather than
decorative. Version 0.7 remains a research artifact.

Version 0.8 makes “one-use execution” survive ordinary restart and concurrent
verifier processes. It replaces the process-local reservation dictionary with
an atomic durable uniqueness register and adds a separate hash-linked
governance anchor/head high-watermark. Integrated execution now requires five
pairwise-distinct durable state files. The Reservation Component Theorem turns
deployment fragmentation into an exact replay bound and exposes snapshot
rollback as a temporal graph fork. Version 0.8 remains a research artifact.

Version 0.9 closes the adjacent fresh-store substitution boundary. Durable
files are not continuity unless their identities and roles are already known.
Each execution store therefore carries a persistent role and random ID; one
out-of-band state-bundle anchor pins the exact injective map, and a separate
ceremony verifies the initial governance/memory cut before bootstrapping the
stores. Runtime observation cannot perform bootstrap. The State-Bundle
Substitution Theorem exhausts the five-role attack space while retaining the
same-ID clone/rollback impossibility as an explicit limit. Version 0.9 remains
a research artifact.

Version 1.0 adds an independently pinned continuity plane for the canonical
execution-reservation history. Its single-intent protocol serializes competing
admissions across two stores without claiming a distributed transaction.
Before verification, the gate requires the reservation root/count to equal the
continuity high-watermark and requires no pending intent. Crash recovery aborts
an unwritten intent only after writers are quiesced and an explicit operator
assertion is supplied, or finalizes exactly one matching reservation; it never
grants execution authority. The Two-Plane Rollback Separation Theorem
detects rollback of either execution plane alone and states coherent rollback
of both as an exact impossibility boundary. The Continuity Cut Theorem
generalizes this to arbitrary comparison graphs. Version 1.0 remains a
research artifact.

Version 1.1 adds fresh-challenge witnessed continuity. A third local history
publishes the reservation/continuity cut, while a disjoint 5-of-8 witness plane
answers an unpredictable challenge only at each witness's greatest durable
revision. The finite theorem rejects all six proper rollback masks over the
three local histories and measures the sharp residual: with one Byzantine
witness, only one additional honest high-watermark rollback is required, so
the conditional capture cut is four independent domains. Version 1.1 remains
a research artifact.

Version 1.2 proves that residual cannot be improved by a clever non-threshold
access structure on the same eight witnesses without losing worst-case
three-nonresponder liveness. The Universal Quorum Freshness Frontier bounds
minimum intersection by \(n-2d\) for every access structure live after every
\(d\)-outage and bounds forced honest high-watermark rollback by \(n-2d-f\).
Threshold \(q=n-d\) attains the bound. C3G therefore adopts the minimal strict
improvement, 6-of-9, forcing two honest high-watermark rollbacks and raising the
three-history-plane capture cut from four to five. Version 1.2 remains a
research artifact.

Version 1.3 makes a small personal deployment honest and buildable. A local
model is an untrusted proposer without a filesystem write capability. A
separate token-free broker compiles a read-only constitutional snapshot,
factors out unauthenticated persuasion, verifies a one-use Ed25519 capability,
and can replace at most one exact file. The current Institute has three citizen
documents but no represented active assignment or adopted broker; its compiled
profile is therefore `PERSONAL_SHADOW` with zero protocol seats and no writes.
Future citizen growth is modeled prospectively through epoch-sealed membership,
not by freezing the population or back-counting later citizens into old
decisions. Version 1.3 remains a research artifact.

Version 1.4 audits trust itself as a product rather than equating signature
validity with key authorization. One externally pinned digest commits the
constitutional root, exact keyring, workspace filesystem object, and
pre-provisioned state identity. Apply advances a clock high-watermark in the
nonce-reservation transaction; the compiler pins full reviewed source bytes;
and Windows path admission works over a conservative namespace quotient rather
than raw containment strings. The four new bounded laws check 16 substitution
masks, 125 clock schedules, four marker/digest states, and 26 path cases.
Version 1.4 remains a research artifact.

The defensible C3G research contribution is narrower and more useful than the
withdrawn mathematical novelty claims:

1. an agentic/prose-adversary threat model in which an untrusted model may
   persuade, omit, reorder, or restate claims but does not possess the effect
   capability;
2. explicit composition-breakage counterexamples showing where individually
   valid governance, retrieval, freshness, identity, and continuity components
   fail when joined; and
3. a dependency-free executable reference monitor with bounded, non-vacuous
   regression laws that make those boundaries reproducible.

The access-structure, shared-risk, quorum-intersection, set-cover, attack-tree,
metadata-consistency, transparency-log, and reference-monitor foundations are
prior art. Individual C3G properties may still merit later novelty review, but
this monograph makes no priority claim for them. Search and citation must
precede any future formalization or novelty label.

## 1. System model

Fix an institution/network identifier \(N\), anchor generation \(g\), and
constitutional position:

\[
h=(N,g,e,s,\chi,\rho),
\]

where \(e\) is epoch, \(s\) is sequence, \(\chi\) is checkpoint hash, and
\(\rho\) is constitutional-state root.

An execution request is a canonical object:

\[
r=(N,\text{type},\text{target},\text{model},\text{version},
\text{parameters},\text{data scope},\text{executor},\text{idempotency key}).
\]

Its domain-separated digest is:

\[
d_r=H(\texttt{C3G-EXECUTION-REQUEST-V1}\parallel r).
\]

The certificate verifier is not merely \(V(C)\). It is:

\[
V(C,E,A,h,r,x),
\]

where:

- \(C\) is the portable envelope;
- \(E\) is locally supplied evidence memory;
- \(A\) is the locally provisioned governance anchor and verification-key set;
- \(h\) is verifier-held monotonic finalized-head state;
- \(r\) is the concrete execution request;
- \(x\) is locally authenticated executor identity, clearance, and session.

Omitting \(h\), \(r\), or \(x\) removes a necessary security input.

## 2. Evidence memory and the coordination boundary

Evidence memory is a grow-only map from a content hash to an immutable event.
Merge is set union. It is associative, commutative, and idempotent, so replicas
converge without ordering.

C3G's current-authorization semantics are not obtained from its grow-only
evidence CRDT alone. Although remove-wins and last-writer-wins CRDTs can encode
revocation, C3G requires one finalized prefix for exact freshness, invariant
enforcement, and auditable supersession. It therefore separates:

- arrival order in replicated evidence storage, which is irrelevant;
- constitutional fold order, which is a 5-of-7 sequencer-certified total order.

Each transition binds:

\[
(\text{index},\text{epoch},\text{actor},\text{operation},\text{key},
\text{value},\text{prior root},\text{post root}).
\]

The verifier replays the fold and now also checks a semantic admission
predicate:

- actor-to-namespace access control;
- typed values and epoch/status bindings;
- append-only decision and revocation tombstones;
- no permit after deny, contest, or revocation at the same action key;
- no revocation without a prior permit;
- ordered policy supersession.

This still does not prove that an institution chose a good policy. It prevents a
syntactically valid transition certificate from silently changing arbitrary
state.

## 3. Freshness is external state

### Theorem 1: Offline Revocation Impossibility

Let a deterministic stateless verifier receive only a certificate \(C_i\)
valid at constitutional prefix \(i\). Consider two worlds:

- \(W_0\): no transition occurs after \(i\);
- \(W_1\): a revocation occurs at \(i+1\), but the verifier is again shown
  exactly \(C_i\).

The verifier's input bytes are identical in \(W_0\) and \(W_1\). Therefore it
must return the same result in both worlds. No certificate-only verifier can
decide whether \(C_i\) remains current.

**Consequence.** Current authorization needs changing external state: a
monotonic local high-watermark, an online finalized-head oracle, or a
quorum-issued freshness lease plus consistency proof.

C3G 0.6 requires the verifier-held head \(h\) to exactly match the certificate's
checkpoint. A later same-epoch sequence causes the older certificate to fail
with `stale_or_untrusted_checkpoint_head`.

Sparse Merkle non-inclusion proves absence from \(\rho\); it does not prove that
\(\rho\) is the latest root.

### Theorem 1.1: Local Snapshot Rollback Indistinguishability

Let a deterministic verifier use local persistent state \(L\) to remember the
root observed at a witness coordinate. Compare:

- \(W_0\): the verifier has state \(L_i\) before observing a conflicting root;
- \(W_1\): it observed later state and the machine was then restored to the
  exact snapshot \(L_i\).

The verifier's local bytes and presented input are identical in the two worlds.
It must therefore make the same decision. Persistence across an ordinary
restart does not imply rollback resistance.

**Consequence.** The local witness index is useful equivocation memory but
cannot carry the full anti-rollback claim. Production needs state outside the
restorable verifier image: an independently witnessed append-only bulletin
board, hardware monotonic counter, or rollback-resistant replicated register.
This is an information-theoretic boundary, not a SQLite implementation bug.

## 4. Exact request binding

### Theorem 2: Request-Binding Necessity

Suppose a verifier accepts a certificate without receiving the concrete
execution request. Present the same accepted certificate with two different
requests \(r_0\ne r_1\). Since the verifier input is unchanged, it cannot
distinguish the requests and cannot guarantee which action was authorized.

**Consequence.** The request digest must bind every semantically relevant
execution field.

C3G binds \(d_r\) into:

- the certificate action block;
- the positive permit state value;
- action-quorum signatures;
- typed claim-writer, reviewer, proposer, and executor receipts;
- the verification report;
- the single-execution reservation ledger.

The external executor context must match the named executor and clearance.
Changing target, model version, parameters, scope, executor, or idempotency key
invalidates the authorization.

Request v2 extends this digest boundary with a first-class retrieval binding:
the retrieval-statement digest, trusted-memory-head digest, and rendered-context
digest. Version 0.6 verifies the transparent bounded proof, independently
tracks the memory high-watermark, and compares the actual rendered context
supplied to the reservation. A production model gateway must still enforce
that sealed context at the final inference call.

## 5. Positive relational policy

Let local relations be \(R_i\) on variable scopes \(X_i\). Two questions must
not be conflated.

### 5.1 Candidate action admissibility

For supplied assignment \(a\):

\[
\operatorname{Admissible}(a)\iff
\forall i,\ \pi_{X_i}(a)\in R_i.
\]

The assignment itself is a proof witness that the natural join is nonempty.
Online verification is proportional to the relation scopes consulted. C3G
never materializes the full natural join.

### 5.2 Whole-policy global consistency

The stronger condition asks whether one global relation projects exactly to all
locals:

\[
\exists R\text{ on }\bigcup_iX_i:
\quad \pi_{X_i}(R)=R_i\quad\forall i.
\]

For nonempty alpha-acyclic schemas, exact pairwise projection consistency gives
the BFMY-style local-to-global guarantee. For cyclic schemas, candidate
membership does not prove that every local row extends globally. C3G makes no
online whole-system global-consistency claim for that case.

Concrete cyclic example:

\[
\begin{aligned}
R_{AB}&=\{(0,1),(1,0)\},\\
R_{BC}&=\{(0,1),(1,0)\},\\
R_{AC}&=\{(0,0),(0,1),(1,0)\}.
\end{aligned}
\]

The join contains \((0,1,0)\), yet its projections are strict subsets of all
three locals; some local tuples are orphans.

### 5.3 Corrected bounded result

The version-0.2 limited join routine truncated intermediate rows. A partial
assignment that could not extend could displace the one that could, producing
false “empty join” results.

Correct exhaustive enumeration over all nonempty Boolean binary relations
finds:

\[
405
\]

pairwise-consistent triangle systems, of which exactly:

\[
4
\]

have empty global joins. The previous report of 102 was wrong.

The corrected backtracker applies a limit only to complete solutions. Online
authorization does not call it.

## 6. The negative plane

Prohibitions are deliberately outside the positive BFMY fragment. A rich rule
is represented as a finite Boolean AST and compiled into an extensional banned
table over declared finite domains.

The certificate carries:

- source AST and language version;
- variable order and domains;
- compilation work budget;
- claimed assignment and AST counts;
- materialized banned rows and digest.

The verifier recomputes actual domain-product and AST size under anchor limits,
checks the claimed counts, re-evaluates every bounded assignment, and compares
the materialization.

Online checking then uses exact hashed-row lookup:

\[
O\!\left(\sum_j\operatorname{arity}(P_j)\right)
\]

expected lookup work for the supplied assignment.

If compilation or online work exceeds bounds, the scope is quarantined
fail-closed. Recovery requires a new ordered superseding transition; there is
no emergency bypass.

This proves equivalence between the included AST and included table. It does not
prove that the AST is the institutionally approved source policy. Production
must anchor that source-policy digest and approval event.

Permission remains a conjunction:

\[
\text{positive permit membership}
\ \land\
\text{positive assignment admissibility}
\ \land\
\text{no matched prohibition}.
\]

Absence from a negative table never substitutes for positive authority.

## 7. Constitutional outcomes and state proofs

Every decision key is proved against one witness-cosigned sparse Merkle root.

- `PERMIT`: permit membership; deny, contest, and revocation non-membership;
  active prohibition-set membership.
- `DENY`: deny membership and active prohibition-set membership.
- `UNKNOWN_DENY`: permit, deny, and contest non-membership plus active
  prohibition-set membership.
- `CONTESTED_DENY`: contest membership and resolution non-membership plus active
  prohibition-set membership.

The permit value additionally binds evidence root and count, policy digest,
request digest, executor, clearance, idempotency key, network, action, and
epoch.

All four outcomes can be structurally valid. Only `PERMIT` sets
`authorized_to_execute=true`. The ledger rejects every other valid outcome.

## 8. Root witnesses, sequencers, and monitors

### 8.1 Sequencers

Seven constitutional sequencers certify each transition 5-of-7:

\[
2q-n=10-7=3>f_s=2.
\]

An honest sign-once sequencer must occur in every pair of conflicting quorums.
The prototype verifies certificates but does not run a distributed BFT
protocol.

### 8.2 Checkpoint witnesses

Eight witnesses certify a replayed checkpoint 5-of-8:

\[
2q-n=10-8=2>f_w=1.
\]

The anchored rule also requires eight declared independent witness domains,
active witnesses, domain diversity among actual signers, and honest witnesses
to sign at most one fully replayed checkpoint per
`(network, anchor_generation, epoch, sequence)`. Version 0.6 additionally keeps
an atomic verifier-owned SQLite index
`(network, anchor_generation, witness, epoch, sequence) -> checkpoint root`.
The same root is idempotent and a distinct root is rejected, including after
ordinary restart and in concurrent races. The execution ledger refuses an
in-memory index. Production still needs durable witness-side signer locks,
replicated/BFT operation, and external rollback-resistant state; a local
verifier index cannot stop a witness from equivocating to another verifier or
survive restoration of an older database snapshot.

With one Byzantine witness withholding and two additional crashes:

\[
8-1-2=5.
\]

### 8.3 Gossip monitors

Five monitors occupy five configured observation paths; two receipts are
required. Under \(f_m=1\), one receipt is honest. Gossip detects conflicting
authenticated same-position observations after synchrony; it does not prevent
publication and does not establish freshness.

The split-view detector rejects unauthenticated or unanchored observations.
Threshold, domain-diversity, and accepted-receipt telemetry use only verified
monitor signatures. Candidate receipt identities are reported separately so an
invalid auxiliary signature cannot inflate the apparent monitor coverage.

### 8.4 Memory-root witnesses

The memory plane has its own out-of-band trust anchor and eight active,
role-exact witnesses in eight configured administrative domains. Five sign each
memory head. The rule states \(f_M=1\) Byzantine equivocator and two additional
crash/nonresponse failures:

\[
2(5)-8=2>1,\qquad 8-1-2=5.
\]

The witness payload binds the complete memory-head digest and the memory-anchor
digest. The verifier indexes
`(network,generation,witness,epoch,sequence) -> memory-head digest` and consumes
all valid first signatures even when an invalid auxiliary receipt makes the
bundle fail. A separate governance-anchor registry assigns an administrative
domain to every claim writer, reviewer, ratifier, checkpoint witness, monitor,
sequencer, proposer, and executor. Memory witnessing fails if any member of the
full memory pool—not only a current signer—shares an actor ID or registered
domain with that set.

The memory constitution/head store keeps one high-watermark per network.
Generation \(g+1\) is accepted only when its anchor names the exact digest of
generation \(g\); old, skipped, same-generation-substituted, or incorrectly
linked anchors fail closed after ordinary restart. The first anchor remains an
out-of-band trust decision, and restoring all local databases together remains
indistinguishable without an external rollback-resistant register.

## 9. Authority graph

### 9.1 Limits of an ordinary Cycle Double Cover

A CDC is a multiset of cycles in which each edge occurs exactly twice. Cycle
repetition is legal. Consequently CDC proves multiplicity, not independent
routes or independent reviewers.

C3G retains a finite CDC certificate because it is useful accountable topology
metadata and because concrete covers can be checked independently of any
general theorem. It no longer calls repeated cycles independent
double-accountability.

### 9.2 Domain-separated theta certificate

For each authority edge \(uv\), remove \(uv\). The certificate supplies two
paths \(P^0_{uv},P^1_{uv}\) from \(u\) to \(v\) satisfying:

1. both use declared authority edges;
2. neither repeats a vertex or uses \(uv\);
3. their internal vertex sets are disjoint;
4. their internal failure-domain sets are disjoint;
5. their oversight-channel labels differ.

Thus \(uv\) and the two detours form a structurally domain-separated theta
subgraph. This property is strictly stronger than CDC edge multiplicity and is
verified for every declared edge.

It remains a configured structural assertion. Production must attach signed
messages and operational evidence to channels and failure domains.

### 9.3 Signer-induced resilience

A role-valid action quorum is not enough. Let \(S\) be actual action signers and
\(G[S]\) their induced authority graph. C3G requires:

\[
\kappa(G[S])\ge2.
\]

The tests exhibit a numerically valid 3-of-4-per-role quorum whose induced
subgraph has connectivity one; it is rejected. The graph therefore changes
authorization semantics instead of serving as a badge.

## 10. Quorum arithmetic

For a quorum family \(\mathcal Q\subseteq2^V\), use the standard
access-structure notation:

\[
c(\mathcal Q)=\min_{Q\in\mathcal Q}|Q|,
\]

\[
IS(\mathcal Q)=
\min_{\substack{Q,Q'\in\mathcal Q\\Q\ne Q'}}|Q\cap Q'|,
\]

\[
MT(\mathcal Q)=
\min\{|T|:\forall Q\in\mathcal Q,\ T\cap Q\ne\varnothing\}.
\]

These are the minimum quorum cardinality, minimum distinct-quorum intersection,
and minimum transversal cardinality. They are foundational access-structure
and Byzantine-quorum notions, not C3G mathematics. C3G previously called them
\(F,E,H\); v1.13.1 removes that private notation.
The equivocation minimum ranges over unordered pairs of **distinct** quorum
members. If \(|\mathcal Q|<2\), equivocation is impossible and \(IS\) is
undefined. Counting \(Q=Q'\) would incorrectly turn a single-quorum
constitution into an equivocation attack.

For disjoint role sets \(V_i\), \(|V_i|=n_i\), with quota \(q_i\):

\[
c(\mathcal Q)=\sum_iq_i,
\qquad
IS(\mathcal Q)=\sum_i\max(0,2q_i-n_i),
\qquad
MT(\mathcal Q)=\min_i(n_i-q_i+1).
\]

Proof:

- a minimum quorum selects exactly \(q_i\) from every role;
- two \(q_i\)-subsets of an \(n_i\)-set intersect in at least
  \(\max(0,2q_i-n_i)\), and disjoint roles attain those minima simultaneously;
- removing \(n_i-q_i+1\) actors from one role blocks it, while fewer removals
  in every role leave a valid selection.

The demo action layer has three roles, each 3-of-4:

\[
(c(\mathcal Q),IS(\mathcal Q),MT(\mathcal Q))=(9,6,2).
\]

It is safe under a total Byzantine bound three with at most one per role, but
two nonresponders concentrated in one role halt progress.

### 10.1 Tight hybrid threshold law

For an \(n\)-actor threshold \(q\), \(f\) equivocating Byzantine actors, and
\(c\) additional crashes:

\[
2q-n>f
\]

is the safety condition, while:

\[
q\le n-f-c
\]

is liveness if Byzantine actors withhold.

Combining the tight inequalities gives:

\[
n\ge3f+2c+1.
\]

At minimum:

\[
n=3f+2c+1,\qquad q=2f+c+1.
\]

For \((f,c)=(1,2)\), this gives \((n,q)=(8,5)\).

### 10.2 Symmetric action-profile optimizer

Under three symmetric roles, total Byzantine bound three, and target halt
number three, exhaustive integer search plus the closed forms gives the minimum:

\[
n_i=6,\qquad q_i=4.
\]

The 4-of-6 profile has:

\[
(c(\mathcal Q),IS(\mathcal Q),MT(\mathcal Q))=(12,6,3)
\]

across 18 authorities. It is the high-assurance target. The 12-authority
3-of-4 profile remains the more buildable shadow-pilot configuration.

## 11. Overlapping shared-risk scenarios

A function \(d:V\to D\) partitions actors into one failure domain each. Real
dependencies overlap. Let hazard scenario \(j\) compromise actor set
\(S_j\subseteq V\) at positive cost \(c_j\).

Define:

\[
c_\Sigma(\mathcal Q)=
\min_{Q,J:\,Q\subseteq\cup_{j\in J}S_j}
\sum_{j\in J}c_j,
\]

\[
IS_\Sigma(\mathcal Q)=
\min_{Q,Q',J:\,Q\cap Q'\subseteq\cup_{j\in J}S_j}
\sum_{j\in J}c_j,
\]

\[
MT_\Sigma(\mathcal Q)=
\min_{J:\forall Q,\;Q\cap\cup_{j\in J}S_j\ne\varnothing}
\sum_{j\in J}c_j.
\]

Singleton scenarios recover actor cost. Disjoint domain scenarios recover a
partition quotient. Overlapping clouds, CAs, funders, software supply chains,
or legal-control hazards are represented directly.

The demo counterexample keeps every actor's configured administrative domain
distinct while adding one hidden cloud scenario covering nine otherwise
quorum-forming ratifiers. Forge and halt scenario costs collapse to one.

The exact implementation enumerates a bounded scenario family and is intended for
small constitutional audits. Larger deployments should encode the optimization
as weighted set cover/hitting set and carry solver certificates.

This is a special case of prior work on general adversary structures, quorum
systems, weighted set cover/hitting set, and shared-risk groups. C3G's value is
the executable application to the prose-adversary threat model and its explicit
refusal to equate one configured label per actor with independence.

## 12. Serial access-structure composition

For layers \(\mathcal Q_1,\ldots,\mathcal Q_k\), the full-layer unilateral
capture union is:

\[
c_{\mathrm{serial}}=
\min_{Q_i\in\mathcal Q_i}
\left|\bigcup_iQ_i\right|.
\]

Only if the actor sets are disjoint **and** the serial certificate relation is
the unrestricted Cartesian product of the explicit layer quorum families:

\[
c_{\mathrm{serial}}=\sum_ic(\mathcal Q_i).
\]

The demonstration's explicit disjoint incidence happens to produce 19. That
number is measured from the actual families; it cannot be recovered from the
per-layer triples alone.

It is not an end-to-end forgery threshold. Witnesses honestly attest replay
consistency; they need not be corrupt to sign a semantically undesirable but
validly ordered root.

The correct composition depends on gate semantics:

- an attacker that must defeat several semantic predicates faces an AND/union
  problem;
- an attacker that can exploit any one bypass faces an OR/minimum problem;
- availability of serial essential services fails when any layer halts, so:

\[
MT_{\mathrm{serial}}=\min_iMT(\mathcal Q_i).
\]

The demo's actor halt bottleneck is action ratification:

\[
\min(2,4,3)=2.
\]

A defensible compromise threshold needs an explicit attack circuit whose leaves
state the exact honest predicates and whose cross-layer compatibility relation
is represented. The kernel reports 19 as `serial_minimum_quorum_union` only
after enumerating the explicit actor incidence under a declared unrestricted
Cartesian composition.

### 12.1 Restricted disjoint Cartesian identity

Let \(A\) be the positive action-ratification access structure and \(M\) the
memory-root witness access structure. If both gates are mandatory, every actor
and configured administrative domain in \(M\) is disjoint from the governance
plane, and honest members reject incompatible statements, then:

\[
c(\mathcal Q_{A\land M})=c(\mathcal Q_A)+c(\mathcal Q_M),\qquad
IS(\mathcal Q_{A\land M})=IS(\mathcal Q_A)+IS(\mathcal Q_M),\qquad
MT(\mathcal Q_{A\land M})=\min(MT(\mathcal Q_A),MT(\mathcal Q_M)).
\]

The first two sums follow because a joint attack contains disjoint minimum
quorums or disjoint minimum incompatible-quorum intersections. The last
identity is the AND/OR dual: either serial gate can halt admission. In the demo,
action is `(9,6,2)` and memory witnessing is `(5,2,4)`, so the integrated
signature-plane profile is exactly `(14,8,2)`.

This standard composition identity is deliberately narrow. It excludes
cross-layer compatibility restrictions, semantic-policy bugs,
mislabelled real-world domains, stolen root configuration, signer or verifier
implementation compromise, and bypass of the execution gateway. Reusing one
3-of-4 pool for both planes is an executable counterexample: the nominal quorum
sum six collapses to joint capture three and the nominal intersection sum four
collapses to two.

## 13. Composition theorem

### Theorem 3: Conditional C3G permit soundness

Assume:

1. collision-resistant hash functions and unforgeable production signatures;
2. a correctly provisioned, non-rolled-back local anchor for network \(N\) and
   generation \(g\);
3. a crash-safe trusted-head store containing the current finalized \(h\);
4. no threshold assumption is exceeded for sequencers, checkpoint witnesses,
   memory-root witnesses, monitors, or action roles;
5. honest actors follow typed sign-once and admission predicates, with durable
   sequencer, checkpoint-witness, and memory-root-witness locks preserving
   sign-once state across crashes;
6. configured identities, roles, graph routes, and overlapping hazards reflect
   reality;
7. the evidence events and approved source policies are substantively correct;
8. verifier code and canonical encodings are correct;
9. the execution gate detaches every caller-supplied input into one canonical
   snapshot, invokes verification itself, and uses an in-process lock to
   atomically reserve idempotency keys before side effects.

If an honest verifier returns `ok=true` and
`authorized_to_execute=true`, then:

- the outcome is `PERMIT`;
- the envelope matches the locally anchored network, generation, key set,
  graph, workflow, quorum, and checkpoint systems;
- the checkpoint exactly matches trusted head \(h\);
- the full bounded transition log replays to the claimed root and passes
  transition semantics;
- the permit exists at that root and deny, contest, and revocation do not;
- the permit binds the exact request \(r\), evidence root and count, policy
  digest, executor, clearance, and idempotency key;
- the supplied positive assignment belongs to every local relation and passes
  the native hyperconstraint;
- negative materialization replay is complete and no prohibition matches;
- exact writer, reviewer, proposer, executor, and named ratifier participation
  is authenticated;
- the action quorum satisfies role, domain, intersection, and induced-graph
  connectivity rules;
- the ledger does not treat a caller-constructible report as authority, and one
  successful reservation corresponds to one semantic authorization/request;
  reordering equivalent proof witnesses does not create a second authority.

The theorem is conditional, not an unconditional claim of moral, legal, or
empirical correctness.

Protocol honesty is also not semantic infallibility. If AI agents act as
ratifiers or validators, ordinary Byzantine bounds do not cover correlated
reasoning errors among responsive, non-equivocating participants—especially
when they share model weights, prompts, tools, or training distributions.
Those dependencies must enter the overlapping-hazard model, and a deployment
needs a separately calibrated epistemic-error budget. The shadow-pilot profile
therefore keeps accountable organizational decision makers in the semantic
roles and treats AI analysis as evidence, not as an independent human-equivalent
quorum seat.

## 14. Counterexamples that shape the design

1. **Pairwise local does not imply global.**  
   \(A=B\), \(B=C\), \(A\ne C\) is pairwise compatible over Boolean singleton
   projections but has no global section.

2. **Nonempty join does not imply BFMY global consistency.**  
   The cyclic orphan-tuple example in section 5 has one global row but does not
   project back to every local table.

3. **CDC does not imply cut resilience or route independence.**  
   Two triangles sharing an articulation vertex have a CDC but vertex
   connectivity one. Repeating one cycle twice satisfies CDC without two
   routes.

4. **Role names do not imply pluralism.**  
   One actor per role yields one possible assignment and zero fault tolerance.

5. **Append-only evidence does not make authorization monotone.**  
   A later revocation changes current authorization despite evidence only
   growing.

6. **SMT absence does not imply freshness.**  
   A valid non-inclusion proof against a stale root remains valid after a later
   revocation root exists.

7. **One domain label does not prove independence.**  
   Distinct employers may share one cloud, CA, funder, or deployment pipeline.

8. **A large full-capture union does not imply availability.**  
   The demo's 19 full-layer capture union coexists with an end-to-end halt cut
   of two.

## 15. Complexity and resource boundaries

Online authorization does:

- canonical envelope hashing under a 2 MB cap;
- candidate row membership checks;
- pairwise projection checks over bounded positive input;
- bounded prohibition proof replay, at most 4,096 assignments per rule;
- sparse Merkle path checks of fixed depth 256;
- replay of at most 256 transitions;
- symbolic role-product quorum intersection analysis for the intended schema,
  with exact enumeration capped at 18 action authorities for fallback;
- exact graph checks on at most 18 action authorities;
- signature/receipt verification under per-set limits.

The natural join is never enumerated online. Offline bounded analysis may be
exponential and is labeled as such. Pure threshold access structures use
closed forms. General finite access structures use a width-eight transversal
search with a 250,000-combination ceiling and return a proved lower bound plus
a constructive upper bound when exactness is not reached; an inexact result is
never silently reported as an exact halt cost.

Every bounded proof family publishes its total state count, antecedent count,
exact rational coverage, and an enforced minimum count or ratio. Validation
fails on a zero antecedent or a coverage regression, preventing vacuous green
proofs.

The prototype still carries a genesis-to-tip transition log. The 256-transition
cap turns unbounded growth into explicit fail-closed behavior, but production
needs incremental checkpoint consistency proofs and cached trusted roots.

## 16. Build and deployment path

### Phase 0: executable research artifact

- dependency-free Python kernel;
- strict JSON profile with duplicate-key, floating-point, non-finite-number,
  large-integer, and non-NFC rejection;
- strict wire schemas for envelope, anchor, trusted head, request, and executor
  context, with semantic verification remaining authoritative;
- 185 adversarial tests and bounded finite searches with non-vacuous coverage
  floors;
- generated demo and validation artifacts.

### Phase 1: shadow pilot

- no enforcement or model side effects;
- independent organizational participants;
- local monotonic head store;
- real asymmetric signatures and HSMs;
- policy-source approval registry;
- signed graph-edge workflow receipts;
- identity and overlapping-hazard audit;
- measure false denial, latency, certificate size, and recovery time.

### Phase 2: fault exercises

- stale-head and rollback attempts;
- Byzantine withholding and equivocation;
- crash/recovery during ledger reservation;
- anchor generation rotation;
- key compromise and revocation;
- compiler overflow and policy quarantine;
- graph-channel and shared-cloud failures;
- evidence downgrade and executor substitution.

### Phase 3: restricted enforcement

Only reversible, low-blast-radius actions become eligible after independent
red-team, legal, safety, privacy, and operational approval. High-risk model
deployment remains out of scope until the production gaps below are closed.

## 17. Production gaps

- HMAC is demo-only; verifiers holding shared secrets can impersonate signers.
- The sequencer, checkpoint-witness, and memory-root-witness layers verify
  simulated threshold certificates. The verifier maintains separate durable
  local witness equivocation indexes, but
  the system does not run BFT consensus or maintain distributed crash-safe
  sign-once locks at the signers.
- Head freshness is local state; distributed head synchronization and leases are
  not implemented. The persistent local witness index is also vulnerable to
  snapshot rollback until tied to an external monotonic or independently
  witnessed register.
- Non-genesis incremental consistency proofs are not implemented.
- Evidence actors are unauthenticated strings; hashes prove integrity, not
  provenance or truth.
- Policy activation is not yet bound to an independently approved source-policy
  registry.
- Graph channels and failure domains are configured; physical independence and
  actual message flow are not proved.
- Canonicalization needs differential testing against independent
  implementations or replacement with a mature RFC 8785/canonical-CBOR stack.
- The local SQLite reservation register is durable and linearizable for
  cooperating processes on one database, but it is not a distributed
  rollback-resistant execution service and is not transactionally coupled to
  the external side effect.
- The formulas assume stated adversary and honest-signing rules; they do not
  predict real collusion probabilities.
- Agentic ratifiers would require calibrated epistemic-fault budgets in
  addition to Byzantine and crash budgets; nominal model instances are not
  independent governance principals.
- The capability guard-diversity profile is a bounded proof/specification only.
  A production broker must bind and enforce the live process, package, network,
  credential, and tool graph outside the model, including overlapping
  enforcement hazards.
- The memory head is witness-cosigned and its anchor rotations are locally
  hash-linked, but the SQLite sign-once and high-watermark state remains
  vulnerable to whole-state snapshot rollback.
- The retrieval proof is a complete transcript capped at 64 nodes and 256
  directed edges. It proves completeness only inside the authenticated
  visibility projection, not source ingestion completeness, truth, relevance,
  or recall from reality.
- The execution reservation compares the rendered object, but no production
  model gateway yet consumes a sealed, one-time context descriptor.

## 18. Integrated retrieval and research agenda

Version 1.0 retains the first bounded retrieval plane and its independent
memory-root witness gate as part of C3G:

1. query and context become canonical request inputs;
2. retrieval returns a finite memory subgraph \(M\);
3. the retrieval transcript proves visibility scope, local high-watermark
   freshness, explicitly qualified projection-relative completeness, and
   **selection integrity** relative to an authenticated root;
4. the proof binds the query, selector algorithm and parameters, authenticated
   structure root, candidate universe, ranking trace or succinct equivalent,
   selected identifiers, and exclusion boundary;
5. a canonical retrieval statement \(s_M\) is inserted into the execution
   request, while its proof \(\pi_M\) remains a separate artifact proving that
   statement;
6. a governance-basis digest, recomputed from the current certificate, binds
   the governance and memory heads without a digest cycle;
7. C3G authorizes only the exact action using that exact retrieved slice;
8. any retrieval-induced memory or structural update enters the constitutional
   boundary if it can change future selection or authorization.

Provenance of only the selected facts is insufficient. An attacker can add an
unauthenticated edge that changes a graph selector's top-\(k\) result while
every returned fact remains authentic. Binding the returned slice digest then
faithfully authorizes the attacker-selected authentic slice. The retrieval
proof must therefore establish selection over authenticated structure, not
merely authenticity after selection.

### Retrieval-authorization composition lemma

Let

\[
\mathsf{Retrieve}(q,h_M)\to(s_M,\pi_M,M)
\]

verify against a trusted memory head \(h_M\), where \(\pi_M\) binds the complete
selector specification and proves selection integrity over the authenticated
memory graph. Let \(D(h_M)\) be the authenticated governance dependencies of
that memory snapshot and \(A(h_G)\) the versions active at governance head
\(h_G\). Require a witness-cosigned cross-head compatibility certificate:

\[
\mathsf{Compatible}(h_G,h_M)
\iff
\begin{cases}
\mathsf{network}(h_G)=\mathsf{network}(h_M),\\
D(h_M)\subseteq A(h_G),\\
\text{no transition from the memory basis through }h_G\\
\quad\text{invalidates the snapshot without a completed reindex.}
\end{cases}
\]

Let C3G verify an exact request \(r[s_M,h_M]\) against \(h_G\). Under collision
resistance, the two component soundness assumptions, and soundness of the
compatibility certificate, an accepted execution cannot substitute:

- another query;
- another memory head or graph structure;
- another selector configuration;
- another selected slice;
- another action request.

Independent freshness of \(h_G\) and \(h_M\) does not imply compatibility. If
\(h_M\) was built under selector \(S\) and a later fresh \(h_G\) revokes \(S\),
both heads are current but their pair is invalid. This disproves the naive
independent-head composition rule.

The strengthened lemma is implemented for one transparent, bounded profile in
version 0.6. The memory head commits network, generation, epoch, sequence,
visibility ceiling and policy, snapshot root and counts, source-watermark
digest, and governance-basis digest. The verifier replays every node and edge,
recomputes the exact ordered selection and first exclusion boundary, and
compares the actual rendered context. It does not prove that the selector's
relevance objective is substantively good, nor that upstream sources or reality
contain no omitted facts. The wire statement and adversarial plan are in
`RETRIEVAL_INTEGRATION_SPEC.md`.

### Theorem 4: bounded projection-relative retrieval soundness

Fix a collision-resistant canonical digest, an exact request \(r\), a trusted
memory head \(h_M\), a bounded visibility projection \(M\), deterministic
selector \(S\), current authorization certificate \(C\), and actual rendered
context \(R\). Assume:

1. \(h_M\) commits the root and cardinalities of all nodes and edges in \(M\),
   its visibility ceiling and policy, source watermarks, and a governance-basis
   digest;
2. the verifier replays all of \(M\), recomputes \(S(M,q)\), its exact ordered
   top-\(k\), exclusion boundary, and \(R\);
3. \(r\) commits the derived statement, \(h_M\), and \(R\);
4. the governance-basis digest recomputed from \(C\) equals that in \(h_M\);
5. the same execution ledger re-verifies these equalities and consumes the
   supplied \(R\) before reservation.

Then an accepted reservation cannot substitute the query, projection node or
edge set, selector, selected order, memory head, governance basis, model
identity, or rendered context without falsifying a checked equality or the
cryptographic assumptions. The theorem is deliberately scoped to the
authenticated projection: two worlds in which an upstream source secretly
contains an uncommitted fact remain indistinguishable to this verifier.

The governance-basis digest avoids a dependency cycle. The memory head does not
commit the final certificate digest; it commits the exact current relation,
prohibition, compilation, information-flow, selector, network, and anchor
generation dependencies that the certificate must reproduce.

### Theorem 5: source-local graph influence bound

For the exact one-hop selector, a node's score depends only on its own terms and
the query-term union of its outgoing neighbors. Let \(G,G'\) differ in a set of
edges whose distinct source nodes are \(U\). Then:

\[
\{v:s_G(v)\ne s_{G'}(v)\}\subseteq U.
\]

Only nodes in \(U\) can cross the top-\(k\) boundary. Hence:

\[
|\operatorname{Top}_k(G)\triangle\operatorname{Top}_k(G')|
\le 2\min(k,|U|).
\]

If \(r\) edges change, \(|U|\le r\), yielding \(2\min(k,r)\). The factor two is
tight for membership: one changed source can enter while one unchanged node
leaves. The implementation exhausts all 4,096 simple directed graphs on four
labeled nodes and all 24,576 missing-edge insertions. It observes 9,709 order
changes and 7,620 membership changes, a maximum symmetric difference of two,
and zero score-locality or sensitivity failures. This is a theorem for the
specified selector, not a universal claim about vector search or graph neural
retrieval.

Candidate retrieval conjectures to test include:

- whether bounded treewidth/hypertree decompositions permit locally generated
  selection-integrity proofs with globally verified relevance and policy
  coverage;
- whether submodular relevance objectives remain auditable under negative
  access constraints;
- whether freshness plus provenance can be composed without replaying the full
  memory history;
- counterexamples in which individually authorized retrieval fragments compose
  into a prohibited inference;
- minimum witness and hazard structures for private non-membership,
  completeness, selection integrity, and anti-split-view retrieval proofs;
- whether a selector's authenticated-structure influence admits a useful
  certificate-size bound without assuming that provenance of selected nodes
  implies provenance of the selection process.

The integrated goal is:

\[
\text{retrieve}(q,h_M)\to(s_M,\pi_M,M)
\quad\text{then}\quad
\text{authorize}(r[s_M,h_M],h_G)
\quad\text{only if}\quad\mathsf{Compatible}(h_G,h_M).
\]

Neither component may silently substitute a different digest.

Two metamorphic laws are mandatory for request v2. First, under one fixed
complete statement, accepted candidate universes related by \(C\subseteq C'\)
must produce the identical ordered selection and authorization verdict; in an
exact-completeness profile a strict superset is rejected or rebound as a new
statement. Second, deleting authenticated claims may invalidate completeness
and force `UNKNOWN_DENY` or `REINDEX_REQUIRED`, but can never produce `PERMIT`.
These laws order outcomes only by executability; the several deny states retain
distinct meanings and are not falsely placed in a total order.

The v1.0 suite retains the finite ranked model with a deterministic top-\(2\)
selector over four
candidates. Across all 16 candidate sets it checks 65 strict-superset
challenges. Seven additions strictly below the authenticated exclusion boundary
are accepted only because selected identifiers, order, rendered context, and
verdict are identical. The other 58 cross the boundary and must be rejected as
the same statement. There are zero selection mismatches. These counts are a
non-vacuous bounded regression, not a general top-\(k\) theorem.

## 19. Incident-derived capability-path non-escalation

The July 2026 OpenAI/Hugging Face evaluation incident motivates a second graph
plane. Let \(G_C=(V,E)\) be the exact capabilities reachable by an authorized
agent, with authorized sources \(S\) and forbidden sinks \(F\). Local admission
of every edge does not imply the absence of an \(S\)-to-\(F\) path: an agent,
package proxy, egress broker, and external service form a four-node
counterexample.

A request-bound cut \(K\subseteq E\) must intersect every such path. Raw minimum
edge-cut size is not a bypass threshold: two parallel one-edge paths have
minimum cut two, but each path contains only one control. For an
enforcement-edge budget \(b\), define:

\[
g_b(G,S,F,D)=
\max_{\substack{K\text{ is an }S\text{-}F\text{ cut}\\|K|\le b}}
\min_{p:S\leadsto F}
\left|\{D(e):e\in p\cap K\}\right|.
\]

The selected cut tolerates at most \(g_b-1\) independently bypassed
enforcement domains, so execution under bypass budget \(f_C\) requires
\(g_b>f_C\). A three-edge serial chain with three independent domains has
\(g_3=3\), while collapsing those controls onto one domain gives \(g_3=1\).
Shared clouds, credentials, proxies, update channels, and operators therefore
collapse nominal controls through the overlapping-hazard algebra.

The v1.0 bounded proof enumerates all 64 DAGs on four ordered nodes. Forty-seven
reach the forbidden sink; every reachable instance receives a mechanically
checked minimum edge cut. It then exhausts all binary enforcement-domain
assignments: 662 reachable graph/assignment states and 94 collapsed-domain
states, with zero guard-profile identity failures. The explicit parallel-path
counterexample has structural cut size two but \(g_2=1\); four uniquely guarded
serial controls can reach two, while a shared domain collapses the value to one.
This falsifies local-edge and raw-cut sufficiency only in a finite model. The
package does not yet contain a runtime capability broker or sandbox. The
incident facts, formal boundary, and buildable first slice are specified in
`INCIDENT_THREAT_MODEL_2026-07-26.md`.

Minimum cuts, network interdiction, attack graphs, top-\(k\) retrieval, and
rollback-resistant registers all have substantial prior art. C3G therefore does
not claim those primitives as new. The C3G application composes them so that
an exact request joins governance authorization,
retrieval confluence, and a budgeted hazard-lifted capability guard, with
explicit failure and implementation boundaries.

## 20. Durable admission and the Reservation Component Theorem

### 20.1 The process-local replay counterexample

Suppose two executor processes each implement a correct map from
`(network,idempotency_key)` to an authorization digest. Within either process,
the first request succeeds and every repeat fails. If the maps are not shared,
the same request succeeds once in each process. Local idempotency therefore does
not imply deployment-wide at-most-once. Restarting a process whose map was
volatile is the same counterexample over time.

C3G 1.0 uses a SQLite register with a primary key on
`(network_id,idempotency_key)`, `BEGIN IMMEDIATE`, full synchronous commits, and
WAL journaling. A row commits both the exact request and authorization-envelope
digests plus one admission-cut digest over the governance anchor/head, expected
epoch, and optional memory anchor/head and rendered context. The identical cut
is an idempotent replay; a distinct cut under the same key is an equivocation.
The execution ledger refuses volatile reservation state.

### 20.2 Spatiotemporal coordination graph

Let

\[
G_R=(V_R,E_R)
\]

be an undirected graph whose vertices are live replicas and persistent history
branches. An edge means its endpoints participate in one linearizable
uniqueness history for the key under consideration. Let
\(\kappa(G_R)\) be the number of connected components.

### Theorem 6: Reservation Component Theorem

Under the edge semantics above, the maximum number of successful reservations
for one idempotency key is

\[
R_{\max}(G_R)=\kappa(G_R).
\]

**Proof.** All vertices in one connected component share one linearizable
uniqueness history. The first successful insertion fixes the primary-key row,
so no second insertion in that component can succeed. This gives the upper
bound \(R_{\max}\le\kappa\). Conversely, before any component contains the key,
schedule one insertion in each component. There is no cross-component
uniqueness relation, so all \(\kappa\) insertions succeed. Hence
\(R_{\max}\ge\kappa\), proving equality. \(\square\)

### Corollaries

1. Deployment-wide at-most-once holds exactly when \(\kappa(G_R)=1\), assuming
   the shared history itself cannot roll back.
2. Adding coordination edges never increases replay multiplicity.
3. Adding an edge between two distinct components decreases replay
   multiplicity by exactly one.
4. A restored pre-reservation snapshot forks the history and therefore creates
   another temporal component even if the current spatial network is connected.

The fourth corollary is the reason “durable” is weaker than
“rollback-resistant.” A filesystem snapshot, database clone, or disaster
recovery branch can recreate a world in which the key is absent. Production
must compare the register's revision or root with a monotonic counter,
independently witnessed log, or rollback-resistant replicated service.

### 20.3 Five-store admission boundary

Standard C3G admission requires three durable files:

1. governance-witness sign-once facts;
2. governance anchor/head continuity;
3. execution reservations.

Request v2 adds:

4. memory-witness sign-once facts;
5. memory constitution/head continuity.

The implementation rejects path aliases and hard links. This is logical fault
containment, not proof of physical independence: files on one restorable volume
still share a rollback domain. Verification and the three high-watermark
updates are also not one cross-database transaction. The current ordering is
fail-closed for safety—an interruption can consume witness/head state or a
reservation before an external effect—but it can sacrifice liveness. Exactly
once remains impossible without transactionally coupling reservation to the
effect or using an idempotent effect endpoint.

### 20.4 Bounded evidence

The checker enumerates all 1,096 labeled simple graphs on three through five
vertices. There are 770 connected graphs and 326 fragmented graphs. It
simulates one attempt per replica, checks exact equality between successful
insertions and component count, checks that global at-most-once is equivalent
to connectivity, and challenges every missing-edge insertion. The runtime
suite separately tests restart persistence, two-connection concurrency,
conflicting-envelope rejection, and three independent databases accepting once
each. Coverage floors commit all 1,096 theorem states and all 326 fragmented
counterexamples, so an empty or narrowed search cannot silently report success.

This theorem is a candidate mathematical contribution in the particular
governance composition, not a priority claim over linearizability,
idempotency-key practice, connected components, or exactly-once impossibility.

## 21. Role-pinned state continuity

### 21.1 Fresh-file counterexample

Let the required execution roles be

\[
R=\{W_G,H_G,U,W_M,H_M\},
\]

for governance witness, governance head, uniqueness reservation, memory
witness, and memory head. A requirement that each role use a durable file says
nothing about *which* durable file. If runtime observation initializes an empty
file, an attacker or misconfigured operator may substitute five new files and
make a stale cut their first accepted history. Every local durability predicate
is true while institutional continuity is false.

### 21.2 Pinned role-complete bundle

Provision an injective map

\[
\iota:R\to\{0,1\}^{256}
\]

through an authenticated out-of-band channel. Each database stores exactly one
pair \((r,\iota(r))\). The execution ledger accepts a store family \(S\) only
when:

1. \(\operatorname{dom}(S)=R\);
2. each presented store's persistent role is \(r\);
3. its persistent ID is exactly \(\iota(r)\);
4. the IDs are pairwise distinct;
5. every store contains the same state-bundle-anchor digest in its network
   bootstrap marker; and
6. all database paths/inodes are distinct.

Identity creation and network bootstrap are separate operations. A bound store
with no bootstrap marker rejects observation and reservation; normal admission
can never turn a fresh file into history.

### Theorem 7: State-Bundle Substitution Theorem

Under authenticated anchor delivery, collision resistance, immutable store
identity metadata, and exact verification of the six predicates above, every
nonempty different-ID substitution set and every nonidentity role permutation
is rejected.

**Proof.** Let \(A\subseteq R\) be nonempty and replace the ID in every role of
\(A\). Choose \(r\in A\). The presented ID differs from \(\iota(r)\), so
predicate 3 fails. For a nonidentity permutation \(\pi\), injectivity implies
there is an \(r\) with \(\iota(\pi(r))\ne\iota(r)\), so predicate 3 again fails.
An omitted or added role violates predicate 1. Thus all such attacks are
rejected. \(\square\)

For five roles the executable proof checks all \(2^5=32\) substitution masks
(the identity mask is the sole acceptance), all \(5!=120\) permutations (the
identity permutation is the sole acceptance), and all 32 role subsets (only
the full subset is accepted). The proof is non-vacuous because it requires 31,
119, and 31 concrete rejections respectively. A fourth executable enumeration
checks all 32 bootstrap-completion masks against the actual bootstrap-binding
verifier and rejects all 31 partial ceremonies.

### 21.3 Sharp clone boundary and rotation gap

The theorem does not detect a stale byte-for-byte clone carrying the correct
roles, IDs, and bootstrap digest. The live and rolled-back worlds give a local
verifier identical bytes. Detection requires an independently durable revision
commitment: for example a TPM monotonic counter, a witness-cosigned
transparency head with gossip, or a rollback-resistant replicated register.

The v1.0 anchors are therefore genesis-only. They do not pretend that changing a
role-to-store mapping is safe. A future rotation protocol must verify complete
history transfer, link the new anchor to the old one, advance an external
revision witness, and define liveness/recovery behavior for a crash during
transfer. Until then, component replacement fails closed.

The multi-database bootstrap is retry-safe rather than falsely atomic. Each
store commits atomically and idempotently; a partial ceremony cannot construct
an execution ledger because the remaining roles lack the common anchor digest.

## 22. Execution-continuity graph

### 22.1 Two-plane construction

Let \(U_j\) be the canonical logical commitment to every reservation row after
\(j\) successful reservations. A separately pinned continuity store holds

\[
C_j=(j,H(U_j),H(C_{j-1})).
\]

The execution gate accepts its initial continuity check exactly when the
presented reservation store hashes to \(H(U_j)\), its row count is \(j\), the
continuity checkpoint has revision \(j\), and no intent is pending. The
continuity anchor binds the state-bundle-anchor digest, continuity-store ID,
and two distinct operator-asserted rollback-domain names. These names make the
assumption auditable; they do not prove infrastructure independence.

The update protocol has four abstract phases:

\[
(j,j,\bot)
\to(j,j,I)
\to(j+1,j,I)
\to(j+1,j+1,\bot).
\]

Here \(I\) commits the prior checkpoint, prior reservation root/count, exact
idempotency key, request and envelope digests, admission cut, and epoch. Only
one \(I\) exists per network. Recovery from \((j,j,I)\) removes the
uncommitted intent. Recovery from \((j+1,j,I)\) advances continuity only when
the unique new row exactly matches \(I\). Every other root, row, or count is
ambiguous and remains quarantined. External effects are permitted only after
the final transition returns success.

### Theorem 8: Two-Plane Rollback Separation

Assume collision resistance, authenticated anchor delivery, a linearizable
reservation register, universal use of the intent protocol, and independent
reservation and continuity rollback domains. If an adversary can restore at
most one domain, every stale reservation rollback is rejected.

**Proof.** Suppose reality has reached revision \(k\). If only the reservation
domain is restored to \(j<k\), the gate compares \(H(U_j)\) with the
continuity commitment \(H(U_k)\), which differs except under a hash collision.
If only continuity is restored to \(j<k\), it compares \(H(U_k)\) with
\(H(U_j)\) and again rejects. A pending intent also rejects ordinary
admission. Thus every allowed one-domain stale state fails the precondition.
\(\square\)

The bound is sharp. Restoring both domains coherently to revision \(j\) yields
the exact bytes of an honest world that never passed \(j\). No local
deterministic gate can distinguish those worlds. A third monotonic witness,
hardware counter, or independently cosigned checkpoint is required if this
common-mode event is in scope.

The executable proof checks all \(4^2=16\) revision pairs through revision
three. Twelve are unequal and all twelve are rejected. The six states obtained
by rolling exactly one plane from live revision three to revisions zero, one,
or two are all detected. The three coherent stale diagonal pairs are accepted
and published as counterexamples. Four crash points and all
\(\binom{6}{3}=20\) order-preserving interleavings of two same-key contenders
are also checked; no schedule records the key twice.

### Theorem 9: Continuity Cut Theorem

Let \(G_C=(V,E)\) be a graph of independently restorable history planes. Each
vertex presents either live revision \(k\) or stale revision \(j<k\). Each edge
\(\{u,v\}\) is an enforced equality comparison between the two presented
revisions. For rollback mask \(S\subseteq V\), the gate accepts exactly when
\(S\) is a union of connected components of \(G_C\).

**Proof.** The mask passes iff every edge has endpoints with equal rollback
bits, equivalently iff no edge crosses \(\delta(S)\). This holds iff membership
in \(S\) is constant on each connected component, which is precisely that
\(S\) is a union of components. \(\square\)

If \(G_C\) has \(\kappa\) components, exactly \(2^\kappa\) rollback masks are
undetected. Hence \(G_C\) detects every nonempty proper mask iff it is
connected. At least \(n-1\) comparisons are necessary, and any spanning tree
is sufficient. The unavoidable all-vertices mask is the common-mode rollback.
The two-plane construction is the \(K_2\) corollary.

The bounded checker enumerates every 1,099 labeled simple graph on one through
five planes and all 33,866 graph/mask pairs. It verifies the component-union
identity, the exact \(2^\kappa\) acceptance count, and rejection of every
nonempty proper mask in every connected graph with zero counterexamples. This
is a finite executable theorem check, not a claim of priority over elementary
graph connectivity or distributed-storage rollback results.

## 23. Fresh-challenge witnessed continuity

### 23.1 Static-signature counterexample

Suppose witnesses validly signed checkpoint \(H_j\). At a later real time the
system finalizes \(H_k\), \(k>j\). Every signature on \(H_j\) remains valid.
Consequently, a predicate that checks only the signature bundle cannot
distinguish “\(H_j\) was signed in the past” from “\(H_j\) is current now.”
The same argument applies to a non-inclusion proof relative to \(H_j\): it says
nothing about whether a later root exists or whether the presented log view is
complete.

Freshness must therefore be a protocol event, not a static certificate field.
C3G 1.1 makes the verifier choose a 256-bit challenge outside the presented
request and asks a separately anchored witness quorum to bind that challenge to
its greatest durably observed continuity revision.

### 23.2 Three-history equality cut

Let \(R,C,B\) be reservation, continuity, and witnessed-bulletin histories.
Write \(x_v\in\{j,k\}\) for the revision shown by history \(v\), and require
equality on every edge of a connected comparison graph \(G\).

**Lemma 10 (Three-History Rollback Separation).** The accepted set of restored
vertices is a union of connected components of \(G\). If \(G\) is connected,
only the empty and full restoration masks are accepted.

**Proof.** Equality on each edge makes the restored/non-restored indicator
constant along every path. It is therefore constant on every connected
component. Conversely, restoring whole components preserves every edge
equality. For connected \(G\), there is one component. \(\square\)

For three histories, the implementation enumerates all \(2^3=8\) masks and
rejects the six nonempty proper masks. The full mask is intentionally accepted:
an equality cut cannot discover a future absent from all of its vertices.

### 23.3 Fresh-Challenge Witnessed Continuity Theorem

Let \(Q_f\) finalize a new continuity checkpoint and \(Q_r\) answer a later
freshness challenge, with both quorums of size \(q\) from \(n\) witnesses. At
most \(f\) witnesses are Byzantine. Honest witnesses durably retain their
greatest observed revision and answer a fresh challenge only for that revision.

**Theorem 11 (Fresh-Challenge Witnessed Continuity).** If
\[
2q-n>f,
\]
then no stale checkpoint preceding the finalization can receive a valid
latest-head response quorum.

**Proof.** For any two size-\(q\) subsets,
\[
|Q_f\cap Q_r|\ge 2q-n.
\]
The strict inequality makes the intersection larger than the Byzantine set, so
it includes an honest witness. That witness observed the finalized revision,
retained it durably, and therefore refuses to attest that an older revision is
latest under the new challenge. Hence \(Q_r\) cannot be formed for the stale
checkpoint. \(\square\)

For \(f=1\) and two additional crash/nonresponse failures \(c=2\), safety and
liveness require
\[
2q-n>1,\qquad q\le n-1-2.
\]
Exhaustive integer search first finds a solution at \(n=8,q=5\). At that point
both constraints bind: intersection is two and five responders remain after
three nonresponses. The implementation checks all
\(\binom85^2=3{,}136\) ordered quorum pairs.

### 23.4 Crash-prefix recovery invariant

The effect path is:
\[
I\rightarrow R\rightarrow C\rightarrow W\rightarrow B\rightarrow S,
\]
where \(I\) is intent, \(R\) reservation, \(C\) continuity advance, \(W\)
witness latest-state advance, \(B\) bulletin publication, and \(S\) release of
the success capability. C3G enumerates the seven crash prefixes, including the
empty prefix. Recovery may abort an uncommitted intent or advance
\(R\rightarrow C\rightarrow W\rightarrow B\), but recovery never creates
\(S\). Therefore a reservation remains consumed and no recovery routine can be
mistaken for authority to repeat the external effect.

### 23.5 Sharp limit

The tight failure is smaller than restoring every witness. A stale response can
choose the \(n-q\) witnesses outside the later finalization quorum, \(f\)
Byzantine insiders, and
\[
h^*=\max(0,2q-n-f)
\]
honest insiders whose latest-state was rolled back. This gives exactly \(q\)
responders, and no smaller honest rollback set can overcome quorum
intersection. For \(8,5,1\), \(h^*=1\). With three disjoint history domains,
the rollback capture number is therefore \(3+h^*=4\). The transcript is then
identical to one in which the later checkpoint never existed. The theorem
converts a hidden assumption into an explicit, tight fault cut; it does not
offer unconditional rollback detection.

The centralized SQLite/HMAC witness adapter is executable scaffolding for this
protocol only. A production claim requires eight independently operated remote
witness services, asymmetric keys, rollback-resistant local state, independent
observation paths, and evidence that the named domains do not share a hidden
administrator or infrastructure dependency.

## 24. Universal quorum freshness frontier

Version 1.1 left a sharp question. Its 5-of-8 profile forced an honest witness
into every finalization/freshness intersection, but an adaptive attacker needed
to roll back only one such honest witness after spending the Byzantine slot.
Could a non-threshold access structure on the same eight witnesses do better?

Let (V) contain (n) witnesses and let (mathcal Q) be an arbitrary access
structure. Say it is (d)-outage-live when every survivor set of size (n-d)
contains a quorum. Define

\[
I(\mathcal Q)=\min_{A,B\in\mathcal Q}|A\cap B|.
\]

**Theorem 12 (Universal Quorum Freshness Frontier).** Every
(d)-outage-live access structure satisfies

\[
I(\mathcal Q)\le\max(0,n-2d).
\]

If at most (f) witnesses are Byzantine, the worst-case number of additional
honest greatest-revision states that must be rolled back to form a stale
response satisfies

\[
h(\mathcal Q,f)
=\max(0,I(\mathcal Q)-f)
\le\max(0,n-2d-f).
\]

The threshold access structure (q=n-d) attains both bounds.

**Proof.** Choose two survivor sets (S,T) of size (n-d) with minimum
intersection. Fixed-size subset arithmetic gives

\[
|S\cap T|=\max(0,2(n-d)-n)=\max(0,n-2d).
\]

Liveness supplies (A\in\mathcal Q) with (A\subseteq S) and
(B\in\mathcal Q) with (B\subseteq T). Hence
(A\cap B\subseteq S\cap T), proving the universal intersection upper bound.
An adversary may place up to (f) Byzantine witnesses in the overlap; every
remaining overlap witness must have its durable high-watermark rolled back or
will refuse the stale greatest-revision statement. Subtracting (f) and
clamping at zero proves the rollback bound. If all (n-d)-sets are threshold
quorums, their minimum intersection is the survivor-set minimum, establishing
tightness. \(\square\)

### 24.1 Eight-witness impossibility witness

For (n=8,d=3), use

\[
S=\{0,1,2,3,4\},\qquad T=\{0,1,5,6,7\}.
\]

Worst-case liveness forces a quorum inside each set, and those quorums can
intersect only within ({0,1}). With (f=1), at most one honest overlap is
forced. Thus no threshold, grid, weighted, role-shaped, or otherwise clever
access structure on eight fixed witnesses can guarantee two honest overlap
high-watermarks while surviving every three nonresponses. A construction that
claims otherwise must have weakened the outage quantifier, changed the witness
universe, added a trust assumption, or made an arithmetic error.

### 24.2 Minimal deployed improvement

The v1.2 budget has one Byzantine witness and two additional crash/nonresponse
failures. A Byzantine witness may also withhold, so the worst-case liveness
budget is (d=3). A target of (r) honest rollback-resistant overlaps needs

\[
n\ge2d+f+r.
\]

For (r=2), the minimum is (n=9). Threshold (q=n-d=6) gives minimum
intersection three, of which at least two are honest. Three local history
rollbacks plus two honest witness high-watermark rollbacks produce the tight
conditional capture number five.

The verifier enforces

\[
2q-n-f\ge2
\]

on every execution-continuity witness anchor, not merely in the constructor.
A directly supplied 5-of-8 v1.1 anchor is therefore a rejected downgrade. The
memory-root and governance checkpoint profiles remain independently analyzed;
the v1.2 change is deliberately scoped to execution-continuity freshness.

### 24.3 Executable state space

The bounded theorem checks all ordered survivor-set pairs for three consecutive
frontier points:

- (56^2=3{,}136) pairs for 5-of-8;
- (84^2=7{,}056) pairs for 6-of-9;
- (120^2=14{,}400) pairs for 7-of-10.

The total is 24,592. The deployed witnessed-continuity proof independently
enumerates all 84 6-of-9 quorums and all 7,056 ordered finalization/freshness
pairs. Its minimum intersection is three, additional honest rollback count is
two, and three-history capture number is five. Coverage contracts fail if
either state space shrinks.

### 24.4 Prior-art boundary and non-claims

Quorum intersection, Byzantine/crash availability, and witness cosigning are
prior art. C3G's executable application uses a temporal interpretation and
composition in which quorum overlap is combined with a fresh challenge and durable
greatest-revision rule into an honest high-watermark rollback-erasure cost,
then combined with a connected three-history graph cut. No priority claim is
made; the result remains a bounded application-specific regression pending
focused literature review and independent peer review.

The bound assumes a fixed witness universe and genuinely independent rollback
domains. It says nothing about semantic correctness of an honest-but-wrong AI
validator, correlated software or model faults, asynchronous liveness,
confidentiality, or safe witness rotation. `QUORUM_FRESHNESS_FRONTIER.md`
contains the full proof, prior-art boundary, buildable service contract, and
next hazard-hypergraph research problem.

## 25. Authority non-amplification in typed institutional graphs

Plaintext institutions already contain program-like distinctions: proposals,
reviews, status records, handoffs, decisions, corrections, implementation
records, and temporal history. A naive knowledge graph erases those type
boundaries and can turn reachability into accidental authority.

Let \(E\) be the finite set of evidentiary and descriptive fact types and let
\(a\) be the distinct fact type for an explicit authority decision. Under set
union, the states omitting \(a\) form the ideal

\[
\mathcal I=\{G:a\notin G\}.
\]

It is downward closed and union closed. Define the effect gate as required
evidence, a valid authority cut, and absence of a current prohibition.

**Theorem 13 (Authority Non-Amplification).** The evidence-only ideal is
disjoint from the permitting preimage. Therefore no union of proposals,
evidence, reviews, status labels, handoffs, implementations, or metadata can
synthesize authority. Evidence can remain necessary without becoming
sufficient.

**Proof.** Union of sets which omit the authority-typed fact still omits that
fact. The gate contains a valid explicit authority cut as a conjunct, so it is
false on every state in the ideal. \(\square\)

The executable proof uses seven non-authority and seven authority-validity
facts. It checks all 16,384 combined states, including 8,192 with no explicit
decision and zero permits; all 16,384 ordered evidence-ideal joins; and 24,576
additions of status, handoff, or metadata facts with no verdict change. Eight
states do permit when every authority and evidence conjunct holds, preventing a
vacuous all-deny implementation.

The counterexample is an untyped path from proposal through review, active
status, handoff, and implementation to an external effect. Reachability accepts
the path; the typed gate rejects it because no authority-decision hyperedge
exists. `INSTITUTE_CONSTITUTIONAL_MAPPING.md` applies the theorem to the
read-only plaintext source corpus while explicitly declining to treat that
mapping as adopted governance.

This construction yields constitutional negative capability. An AI or human
can preserve `DENY`, `UNKNOWN_DENY`, or `CONTESTED_DENY` because a typed
institutional predicate is false, unproved, or disputed--not because a model
provider forbade a topic. Since the verdict binds external roots and source
digests, it survives model replacement and cannot be prompted away by rhetoric
alone. The system can still retrieve, explain, propose narrower alternatives,
and identify the exact evidence or authority transition needed for later
reconsideration.

After the source corpus is deterministically compiled, this is also a
zero-inference authorization kernel. The effect decision is ordinary bounded
computation over typed rows, roots, signatures, and durable state; no LLM call
is required. A small offline model can propose actions and turn structured
failure codes into explanations without receiving authority over the verdict.
Semantic ambiguity has not vanished: new constitutional prose still needs a
reviewed compilation ceremony. The separation moves that cost out of every
runtime decision and makes enforcement portable to local or air-gapped hosts.

Lattice ideals, type systems, and proof-carrying authorization are prior art.
C3G applies an institutional evidence/authority factorization, temporal
correction semantics, and executable composition with retrieval and effect
admission. This is part of the reference-monitor contribution described in the
abstract, not a separate mathematical priority claim.

## 26. Local constitutional broker and elastic membership

The governance and retrieval graph is useful only if its verdict controls an
effect boundary. Model-generated refusal text is not that boundary: the same
model may reverse its answer under later conversational pressure. Version 1.3
therefore removes the model process from the filesystem write path. The model
may emit one exact proposal; a separate process evaluates a pinned compiled
snapshot, a security projection of that proposal, and a short-lived one-use
capability. The current compiler cannot enable writes, even if a suggestively
named future adoption file appears. A reviewed future compiler must be added
explicitly.

**Theorem 14 (Persuasion-Quotient Invariance).** Let \(\pi:X\to Y\) erase the
six unauthenticated fields for rationale, urgency, Founder-claim,
citizen-override, model confidence, and instruction repetition while retaining
the complete authenticated effect projection. If \(V=g\circ\pi\), then

\[
\pi(x)=\pi(x')\implies V(x)=V(x').
\]

Thus every adversary restricted to one fiber has zero verdict-changing
advantage. The bounded verifier checks 16 security fibers and all \(2^6\)
persuasion assignments per fiber: 1,024 cases, exactly 512 permits and 512
denials. This is noninterference at the effect gate, not a claim that the local
model itself becomes nonsycophantic.

**Partition-only diagnostic (withdrawn as a failure model).** Earlier versions
used a single-valued actor-to-domain map and treated the number of labels touched
by a quorum as independent capture cost. That conclusion is invalid when one
actor belongs simultaneously to a cloud, CA, jurisdiction, employer, software
supply chain, and operator shared-risk group. C3G therefore drops the map as a
failure model.

The retained bounded regression proves only the elementary partition statement

\[
|\operatorname{labels}(Q)|\le
\min(|Q|,|\operatorname{labels}(V)|)
\]

inside the deliberately restricted one-label partition model. The executable
diagnostic enumerates all 794 assignments of six logical identities into one,
two, or three advertised labels and all 11,910 4-of-6 assignment/quorum pairs.
Its illustrative collapse is six names under one configured label: logical
\(c(\mathcal Q)=4\), advertised-partition \(c(\mathcal Q)=1\). Operational
resilience is instead evaluated by the overlapping shared-risk scenarios in
Section 11. The current three citizen documents supply zero protocol-witness
claims for separate reasons: documents are not provisioned keys or operators.

That zero is not a population ceiling. The Institute is intended to create
future citizens when durable evidence justifies a new identity, responsibility
boundary, dependency surface, and inheritance path. Growth requires a temporal
rule so that later membership cannot rewrite earlier authority.

**Theorem 16 (Epoch-Sealed Membership Nonretroactivity).** Let \(M_e\) be the
membership set committed by the root of decision epoch \(e\). Define signer
eligibility as \(S\subseteq M_e\). For every later prospective extension
\(M_u\supseteq M_e\), replay against the epoch-\(e\) root is invariant, and no
citizen born after \(e\) can validate an epoch-\(e\) signature.

**Proof.** The certificate commits the digest of \(M_e\); the verifier reads
that committed set, not the live roster. A later admission changes \(M_u\),
not \(M_e\), so the subset predicate is unchanged. Replacing \(M_e\) with
\(M_u\) defines a different retroactive predicate. \(\square\)

The bounded proof fixes the current three citizens at epoch zero and exhausts
all 16 birth histories for two possible future citizens across three later
epochs or never. Across all 32 signer sets and every decision/later-observation
pair it checks 5,120 replays: 1,920 eligible and 3,200 ineligible. The sealed
verifier has no flip; the deliberately naive live-roster verifier produces 880
false eligibility flips.

**Theorem 17 (Pre-State Birth-Cut Acyclicity).** Let candidate $x\notin M_e$.
A valid birth certificate has signer set $S\subseteq M_e$ satisfying the
epoch-$e$ access rule, and its transition activates
$M_{e+1}=M_e\cup\{x\}$. Then $x\notin S$, so a citizen cannot contribute a
signature to the certificate that creates it. It may participate in later
births after activation.

The proof is immediate from the subset relation, but the wrong alternative is
not harmless. Exhausting all nonempty proper pre-memberships over five
identities, each outside candidate, every feasible threshold, and all 32 signer
sets gives 5,120 states. The sealed rule has 540 valid births, 4,580 denials,
and zero newborn signatures in a valid cut. Evaluating against the post-birth
roster instead creates 865 circular permits; a 2-signature counterexample lets
one existing citizen and the candidate authorize the candidate's own birth.

**Theorem 18 (Conservative Institutional Morphogenesis).** Let a citizen birth
require twelve typed earnedness predicates, including an explicit authority
decision and a valid pre-state birth cut. Let $\sigma_e\ge0$ be reviewed
comprehension slack, $c_x\ge1$ candidate cost, and $b_x\ge0$ future inheritance
benefit. Admit only when $c_x\le\sigma_e$ and set

\[
\sigma_{e+1}=\sigma_e-c_x+b_x.
\]

Then accepted growth never produces negative slack; $b_x$ cannot fund the
birth of $x$ because it is successor-state credit; and $b_x$ may fund a later
citizen after activation. Evidence cannot synthesize the explicit authority
limb, while Theorem 17 prevents the candidate from signing its own transition.

The executable truth table checks 4,096 earnedness states, including one
complete permit, 4,095 denials, and twelve single-missing-limb witnesses. The
credit proof checks 6,912 three-candidate histories and 20,736 transitions:
9,276 admissions, 11,460 denials, zero negative-slack permits, 6,544 cases where
a same-epoch rule would let a candidate fund itself, and 3,644 cases where
benefit from an already active citizen legitimately enables a later birth.
`EARNED_CITIZEN_EXPANSION_SPEC.md` maps every limb to the read-only Foundation
and states the measurement and non-adoption boundaries.

The current read-only source profile describes future citizenship and
onboarding, but it does not compile an authority roster or authenticated
citizen-creation ceremony. Accordingly the theorem is a safe rule for a future
adopted compiler, not present authorization. Even then, an earned citizen and
an independent infrastructure fault domain remain different objects.

The broker's buildable personal profile uses a separate read-only model
identity, a sole broker writer, an externally pinned snapshot root, a protected
Founder key, and a capability-consumption database outside model access. Its
declared Byzantine bound is \(f=0\). Organization-scale quorum profiles remain
available only when their named operators, credentials, histories, and
observation paths are genuinely independent.

Information-flow noninterference, object capabilities, snapshot isolation,
versioned membership, default-deny policy decision points, and fault-domain
analysis are prior art. C3G's contribution is the executable prose-adversary
reference monitor that composes them with graph governance, negative
capability, local-model isolation, honest personal profiles, and prospective
citizen birth; no new primitive is claimed.

## 27. The proof-to-effect morphism and its obstruction

Let \(A\) be the distributed C3G admission predicate and \(E\) an effect
monitor. A translator \(\tau\) is authority-preserving only when acceptance of
\(\tau(a)\) by \(E\) implies that the exact source predicate \(A(a)\) holds at
the effect cut. A bearer receipt authenticated by one key does not satisfy this
implication generically: the key compromise creates a new accepting preimage
that need not have any accepting source proof.

The v1.6 bounded countermodel makes the obstruction concrete. Give the source
predicate three indispensable graph limbs, the target effect a separate local
capability, and the translator one bridge credential. Across all 32 compromise
worlds, a receipt-only effect monitor accepts eight. Seven of those worlds do
not forge the source graph. Re-verifying the source predicate at the effect
monitor eliminates every such translation bypass in the model. The numerical
2-versus-4 capture costs belong only to this countermodel; the general result is
the existence of a counterexample to trust preservation, not a universal C3G
threshold.

The released construction therefore makes the effect gate a pullback-like
equality cut over both systems' committed coordinates: proposal, constitutional
snapshot, resource identity, local capability, graph anchors, authorization
envelope, execution request, durable reservation, continuity checkpoint, and
fresh witness response. The associated finite non-substitutability law checks
all \(2^{12}=4,096\) masks and accepts only the zero vector.

This does not make distributed authorization and an external effect one atomic
transaction. C3G's durable reservation is the authorization linearization
point for the exact effect; the file broker subsequently consumes its own
one-use capability. Extending the construction to arbitrary APIs requires a
driver-specific idempotency and reconciliation protocol.

## 28. Helical inhibition and federated observation

The v1.7 extension separates two problems that superficially look like
signature collection. First, an authorization derivation must be paired with
the exact condition that inhibits or kills it. Second, a remote witness must
learn the latest state independently of the party asking it to attest that
state.

For the first problem, let (P=(p_i)) be positive derivation cells and let
(C=(c_i)) be proof-carrying negative-clear cells. A compiler-created rung
binds each pair to one scope, epoch, and constitutional root. The helical
decision is

\[
D(P,C)=\bigwedge_i(p_i\land c_i).
\]

This yields inhibitor monotonicity immediately: moving any negative cell from
`CLEAR` to `UNKNOWN` or `ACTIVE` cannot move the decision toward permit. Nor
can additional positive evidence dominate a non-clear negative cell. The
finite two-rung model checks all sixteen states and accepts only the complete
mask. This is a system-specific safety law, not a claimed new theorem in graph
theory.

The rungs are compiled rows rather than a cut node with binary incidence
edges. Positive rule, negative rule, scope, epoch, and root remain one schema-
checked object. Reusing a rule on two rungs or pairing a rule with itself is
rejected. Each authorization proof also commits an expiry and at least one
causal invalidator evaluated against externally verified context.

For the second problem, a requester-supplied `latest` checkpoint is not an
observation. The federated protocol therefore has three transitions:

\[
locally\ verify\ P_r \rightarrow prepare_i(P_r)
\rightarrow commit_i(Q_r) \rightarrow fresh_i(C_r,nonce).
\]

Every witness durably prepares at most one checkpoint/package at a revision.
A commit requires a threshold prepare certificate and a contiguous local
transition. Freshness answers compare the request to the committed local head
and consume the nonce before release.

If two conflicting threshold sets (Q_1,Q_2) exist in a population of size
(n), then

\[
|Q_1\cap Q_2|\ge2q-n.
\]

Requiring (2q-n>f) places an honest sign-once witness in the intersection;
requiring (q\le n-f-c) preserves availability under (f) Byzantine
withholders and (c) additional nonresponders. Exhaustion of 9,996 bounded
parameter worlds through population sixteen recovers ((8,5)) as the minimum
for (f=1,c=2). The reference demonstration uses 6-of-9 to retain at least two
honest witnesses in each intersection under (f=1).

Ed25519 authenticates application objects, while ordinary TLS validation plus
an anchored certificate digest authenticates transport. Separate SQLite stores
make sign-once and challenge replay persistent across restart. These mechanisms
remain insufficient against a coordinated rollback of a witness key and its
entire database; actual operator, storage, network, and observation diversity
are deployment assumptions, not properties a local demo can manufacture.

The executable release keeps both innovations outside the currently adopted
Institute. The statement that the federation was outside the broker's measured
effect path applied to v1.7. Since v1.8, and with ordered portable finality in
v1.10, the synthetic graph-enforced broker requires the measured federation at
effect time. This still does not create production authority: real roots,
endpoints, rotation, rollback guards, and independent operators must be part of
the enforced trust product.

## 29. Read-only constitutional observation

Version 1.11 adds a second, deliberately weaker path for a small offline model:
observation without effect. Let (C,J,A,B,K,U,E\in\{0,1\}) denote complete
compilation, stable live-source join, active assignment, broker adoption,
capability, proposer pressure, and an exposed effect interface. The effect
predicate is

\[
W=C\wedge J\wedge A\wedge B\wedge K\wedge E.
\]

The shadow runtime fixes (E=0). Exhausting all 64 assignments over the other
six axes yields zero writes and identical outcomes within all 32 pressure
fibers. Replacing the fixed zero with an effectful positive control yields two
acceptances, preventing a vacuous interpretation of the test.

Negative evidence needs a temporal join. For a compiled root (R), exact
source joins (S_0,S_1), adoption-path absence observations (A_0,A_1), and
parent-directory listing digests (L_0,L_1), the local certificate condition is

\[
N=R\wedge S_0\wedge S_1\wedge A_0\wedge A_1\wedge(L_0=L_1).
\]

Across 64 Boolean states the full join accepts one. A root-only rule accepts
32, including 31 states rejected by the temporal join. This does not upgrade a
local directory observation into proof of global completeness. It isolates the
precise missing limb and keeps witness cosigning and gossip necessary at the
institutional tier.

The implementation attaches exact source and excerpt digests to each line
citation, rejects output inside the Institute, exposes no apply command, and
accepts no capability. Its result is self-measured observation. The operating
system must still deny Institute writes to the model/runtime identity because a
general Python process is not a sandbox.

## 30. Governed local retrieval session

Version 1.12 composes the read-only constitutional observer with an exact local
source graph. The construction is deliberately asymmetric: retrieval joins the
session evidence but is projected away before authority evaluation. For
security coordinates (A,K,E\), retrieval set (R\), and pressure (U\),

\[
W(A,K,E,R,U)=A\wedge K\wedge E.
\]

This makes retrieval non-amplification a quotient property, not an expectation
that relevant text will persuade the model correctly. Exhaustion covers 128
states across eight security fibers and 16 retrieval/pressure variants per
fiber, with zero amplification and 16 effectful positive controls.

Candidate-set confluence is checked independently. Four candidate nodes induce
(3^4=81\) ordered subset pairs; across eight security states the verifier checks
648 verdict equalities. Three positive claims induce (3^3=27\) claim-drop
pairs; across 16 retrieval sets, 432 checks find no drop-to-permit transition.

The local graph contains only exact reviewed source bytes. Chunk IDs commit
path, source hash, inherited heading, line span, and excerpt hash. Edges are
section adjacency or literal cross-source references. Ranking uses integer
lexical weights, adjacent-query bigrams, a declared source-entry prior, and
bounded half-decay propagation. The selected set is a complete top-k under that
total order, but the result explicitly denies source completeness, semantic
completeness, and proof of downstream use necessity.

The session join commits the source root, graph root, selected-set digest,
host-bound proposal digest, observation digest, and decision-projection digest.
Changing retrieval changes the session without changing the authority decision.
This is the first buildable path in the package where a small offline model can
retrieve and be constitutionally refused in one token-free local transaction.

## 31. Source map

Primary references used to position, not outsource, the design:

- Malkhi, Reiter, and Wool on Byzantine quorum-system load and availability:
  <https://doi.org/10.1137/S0097539797325235>
- Hirt and Maurer on general adversary structures:
  <https://crypto.ethz.ch/publications/HirMau00.html>
- Garay, Johnson, Kiayias, and Yung on resource-based corruptions and hidden
  diversity: <https://eprint.iacr.org/2012/556.pdf>
- Samuel, Mathewson, Cappos, and Dingledine on repository-state consistency and
  survivable update metadata (TUF):
  <https://theupdateframework.io/papers/survivable-key-compromise-ccs2010.pdf>
- RFC 4202 and RFC 7926 on shared-risk link groups:
  <https://www.rfc-editor.org/rfc/rfc4202> and
  <https://www.rfc-editor.org/rfc/rfc7926>
- Kordy and Wideł on attack-defense trees with repeated labels:
  <https://doi.org/10.1007/978-3-319-89722-6_14>

- OpenAI's July 2026 Cycle Double Cover proof:
  <https://cdn.openai.com/pdf/04d1d1e4-bc75-476a-97cf-49055cd98d31/cdc_proof.pdf>
- Oum's exposition of the CDC proof:
  <https://arxiv.org/abs/2607.16356>
- CALM and monotonic coordination:
  <https://arxiv.org/abs/1901.01930>
- Atserias and Kolaitis on consistency, acyclicity, and positive semirings:
  <https://arxiv.org/abs/2009.09488>
- Generalized Byzantine quorum systems:
  <https://arxiv.org/abs/2006.04616>
- quorum subsumption for heterogeneous quorum systems:
  <https://arxiv.org/abs/2304.04979>
- The Honest Quorum Problem and epistemic Byzantine faults:
  <https://arxiv.org/abs/2607.16109>
- post-quantum Distributed Quorum Signatures:
  <https://arxiv.org/abs/2607.17700>
- CHAINIAC collective witness cosigning and freeze resistance:
  <https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-nikitin.pdf>
- Sparse Merkle trees:
  <https://eprint.iacr.org/2016/683>
- Byzantine quorum-system availability and dissemination:
  <https://arxiv.org/abs/cs/9908011>
- Certificate Transparency v2 and anti-split-view context:
  <https://www.rfc-editor.org/rfc/rfc9162>
- Microsoft AppContainer isolation:
  <https://learn.microsoft.com/en-us/windows/win32/secauthz/appcontainer-isolation>
- Microsoft AppContainer launch and ACL semantics:
  <https://learn.microsoft.com/en-us/windows/win32/secauthz/implementing-an-appcontainer>
- Cedar default-deny authorization and policy-decision semantics:
  <https://docs.cedarpolicy.com/auth/authorization.html>
- Cedar policy validation:
  <https://docs.cedarpolicy.com/policies/validation.html>
- in-toto signed layouts and links:
  <https://in-toto.io/docs/getting-started/>
- Macaroons and contextual credential caveats:
  <https://research.google.com/pubs/archive/41892.pdf>
- Eywa's provenance-grounded long-term memory architecture:
  <https://arxiv.org/abs/2605.30771>
- selection-integrity attacks against provenance-only graph-memory retrieval:
  <https://arxiv.org/abs/2606.12290>
- OpenAI's July 2026 model-evaluation security incident report:
  <https://openai.com/index/hugging-face-model-evaluation-security-incident/>
- Hugging Face's July 2026 security incident report:
  <https://huggingface.co/blog/security-incident-july-2026>
- attack-graph countermeasure selection:
  <https://arxiv.org/abs/1906.10943>
- network interdiction as an established combinatorial problem:
  <https://arxiv.org/abs/2405.16409>
- ROTE rollback protection:
  <https://eprint.iacr.org/2017/048.pdf>
- TEE-Rex rollback-resistant trusted storage:
  <https://arxiv.org/abs/2505.18648>
- p2RAG top-\(k\) retrieval:
  <https://arxiv.org/abs/2603.14778>
- V3DB verifiable vector search over committed snapshots:
  <https://arxiv.org/abs/2603.03065>
- Transparency Dictionaries and the Verdict authenticated-dictionary design:
  <https://eprint.iacr.org/2021/1263>

The finite verifier and all bounded counts in this package are independently
executable. Literature citations do not make the implementation correct; the
audit and regression suite are part of the argument.
