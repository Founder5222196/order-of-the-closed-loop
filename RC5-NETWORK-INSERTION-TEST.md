# rc.5 INSERTION TEST — Network Integrity

> **STATUS: INSERTION TEST — NOT CERTIFIED DOCTRINE**
>
> Sources under test:
> - current `main` at `7b6b8624ade9cabb0c90a3379c3a1165da2ccb51`;
> - `README.md` / rc.4 Closing Condition;
> - `ATTESTATION-INTEGRITY.md`;
> - `RRE.md`;
> - `PURPOSE.md`;
> - `RC5-NETWORK-INTEGRITY-REFINEMENT.md`.
>
> Required ruling: **READY FOR INTEGRATION DRAFT** or **BLOCKED**.
>
> This test asks whether the refined Network Integrity material can be inserted without duplicating doctrine, weakening terminality, creating perpetual surveillance, manufacturing legitimacy, or changing the existing adjudication sequence.

# 1. Executive Ruling

**READY FOR INTEGRATION DRAFT — WITH REQUIRED PLACEMENT AMENDMENTS.**

The network refinement is not a competing architecture. Its strongest surviving material fits as a distributed application layer over doctrines that already exist:

- the **Closing Condition** governs whether any network file may close;
- **Attestation Integrity** governs whether the durable account and later treatment actually update;
- **RRE** governs whether a correction is revised, persisted, installed, and carried;
- **Network Integrity** adds the missing distributed questions: lineage, propagation paths, node reachability, stale-state precedence, cross-node transferability, and bounded network scope.

The insertion is blocked only if the refined candidate is inserted verbatim as a self-contained parallel closure/RRE architecture. It is insertion-ready once the amendments below are applied.

# 2. Gate A — Closing Condition and Terminality

## Pressure

Does Network Integrity preserve the rc.4 rule that Attestation terminates the adjudication it closes, that reopening requires an admissible defeater, and that closure creates no general duty of perpetual surveillance?

## Finding

**SURVIVES NARROWED.**

The refined candidate correctly says dormant copies do not create perpetual surveillance and makes later reactivation decision-triggered. But its current wording can still be misread as reviving a duty inside an already closed network file.

The rc.4 rule is stronger and must control:

- a closed historical file remains closed unless an admissible defeater reopens it;
- Carry Forward concerns a later decision and does not reopen the original file;
- a continuously current claim requires its monitoring horizon and signal channel to have been declared before closure.

## Required amendment

A later reactivation of stale state must be treated as a **new later-decision file** unless it satisfies the original file's predeclared defeater rule.

Replace any wording that implies:

> later reactivation resumes review of the closed network file

with:

> **When a controlled stale record is later reactivated for a materially relevant decision, that later use is evaluated as a new decision file under Carry Forward and Network Integrity. It does not reopen or diminish the original Attestation unless the original file's admissible defeater rule is independently satisfied. No dormant-node rule creates perpetual monitoring of a closed file.**

For a network claim that purports to remain continuously current, rc.4's existing monitoring rule controls unchanged.

# 3. Gate B — Does Network Integrity Duplicate Attestation Integrity?

## Pressure

Are Network Attestation Gap, proof-cost, correction-versus-treatment, and later standing already covered?

## Finding

**PARTIAL OVERLAP, NOT REDUNDANCY.**

Attestation Integrity already establishes:

- Behavioral vs Explicit Attestation;
- Attestation Gap and Split File;
- Recognition Arbitrage;
- Proof-Cost Reset;
- Carry Forward;
- archival vs operative downstream effect;
- later decisions as new files;
- scope, alternatives, falsifiers, and motive separation.

Network Integrity should therefore **not** create a second doctrine for those same failures.

Its distinct contribution is narrower:

1. **claim lineage across nodes**;
2. **independence vs dependent repetition**;
3. **propagation channels**;
4. **lawful reachability and transferability**;
5. **stale-state precedence in distributed systems**;
6. **bounded network closure and node sampling**.

## Required amendment

Define a **Network Attestation Gap** only as a distributed subtype/application of Attestation Integrity, not a new parallel form of Attestation.

Recommended text:

> **A Network Attestation Gap is an Attestation Gap expressed across a distributed decision path: a valid correction or closed finding is applicable and available through the declared network state path, yet one or more materially relevant downstream decisions continue to operate from the superseded file without a documented independent defeater, scope limit, expiry rule, or other legitimate basis. The classification inherits Attestation Integrity's evidentiary, scope, falsifier, and motive limits.**

If the evidence establishes only transport failure, record **propagation failure**, not an Attestation Gap.

# 4. Gate C — RRE and the Status Model

## Pressure

Does the refined four-status network model create a second revision engine?

## Finding

**BREAKS IF INSERTED VERBATIM.**

The refined candidate's sequence:

- Source corrected;
- Correction propagated;
- Network-installed;
- Network-carried;

is useful operationally, but `RRE.md` already owns the formal revision states:

- Stated Correction;
- Replayed Correction;
- Installed Revision;
- Carried Revision.

The word **installed** is especially dangerous to duplicate. In RRE, an Installed Revision is demonstrated when behavior changes on analogous recurrence. Merely placing corrected state in a path that *should* govern behavior is persistence, not yet installation.

## Required amendment

Do **not** create a second formal status ladder.

Use the existing RRE states and add network transport/persistence facts beneath them:

- **Propagated** — the correction reached the declared downstream state path. This is a transport fact, not an RRE revision state.
- **Persisted at node** — the correction is stored where the node's normal execution path reads it, with stale-state precedence addressed. This is the network form of RRE **Persist**.
- **Installed Revision at node** — on analogous recurrence, the node actually behaves from the corrected state. This retains the existing RRE meaning.
- **Carried Revision** — later relevant decisions preserve the installed correction within scope, retaining the existing RRE meaning.

Therefore:

> **Transport is not persistence. Persistence is not installation. Installation is not Carry Forward.**

This is compatible with RRE and sharpens it without adding a stage.

# 5. Gate D — Distributed Carry Forward

## Pressure

Does Candidate B turn one node's finding into universal reputation portability?

## Finding

**SURVIVES NARROWED.**

The refinement correctly added transferability, lawful access, jurisdiction, expiry, case-independent verification, and local defeaters.

This is consistent with existing Carry Forward, which already requires that the finding remain relevant and applicable under the later decision's governing rule.

## Required final text

> **When a closed finding is lawfully available through a declared network state path, remains current and materially relevant, and is transferable to a later decision under that node's case-independent governing rule, the node must consider it without requiring proof already satisfied by that finding to be repurchased. The node may narrow, defeat, or decline the finding through a documented scope rule, expiry rule, jurisdictional limit, case-independent verification requirement not already satisfied, or independently supported local defeater. The later decision is a new file; it does not reopen or rewrite the original Attestation.**

The phrase **proof already satisfied by that finding** matters. Network Integrity does not abolish legitimate verification.

# 6. Gate E — Lineage Integrity

## Pressure

Can the framework distinguish dependent repetition from genuinely independent convergence without inventing ancestry?

## Finding

**SURVIVES.**

This material is genuinely new and belongs in Network Integrity.

The insertion must preserve two different questions:

### Evidentiary weight

How many materially independent evidence-generation paths support the proposition?

### Network-state evidence

How many nodes received, repeated, stored, or acted on the proposition?

A thousand dependent copies may still be strong evidence of network state while remaining one lineage for the truth of the underlying claim.

## Required final text

> **Repetition does not create independent evidence. Materially dependent observations or analyses remain one evidence-generation lineage even when repeated across many nodes. Common citation alone does not establish common evidentiary lineage, and missing provenance establishes neither independence nor dependence; provenance remains UNRESOLVED until evidence settles it. Dependent repetition may nevertheless establish the separate fact that a claim has propagated through the network.**

This survives the anti-shrine test because unknown lineage cannot be collapsed merely because common influence is suspected.

# 7. Gate F — Propagation Symmetry

## Pressure

Does correction propagation create unlimited repair or surveillance duties?

## Finding

**SURVIVES NARROWED.**

The doctrine may require a participant to use a controlled path to correct a consequential claim it materially propagated through that path.

It may not require:

- monitoring unknown copies indefinitely;
- contacting unreachable nodes;
- violating privacy;
- publishing beyond legitimate jurisdiction;
- forcing downstream agreement;
- erasing historically accurate records.

## Required final text

> **A participant that materially propagated a consequential claim through channels it controls cannot count the affected decision path corrected merely by changing the origin record. When the claim is validly defeated or materially narrowed, the participant must place a sufficient correction, supersession, or non-reliance notice into the same or a functionally equivalent controlled state path for reachable, decision-relevant nodes within lawful scope. Where literal redistribution is unauthorized, the smallest sufficient authorized notice may satisfy the propagation duty. The rule is symmetric as to favorable and unfavorable claims.**

Then append the terminality clause from Gate A: later stale use is a new later-decision file, not silent reopening of the original file.

# 8. Gate G — Network Closure and Legitimacy

## Pressure

Can the builder define a convenient node set, inspect favorable samples, and certify "network closure"?

## Finding

**BREAKS WITHOUT A STRONGER INHERITANCE RULE.**

The refined D correctly invokes the trust boundary, but it partially restates the Closing Condition and therefore risks creating a weaker parallel closure test.

The network doctrine should not define its own general Closing Condition.

## Required amendment

Network files inherit the **entire ordinary Closing Condition** unchanged.

Network Integrity adds only network-specific eligibility declarations:

- bounded network scope;
- relevant node class;
- claim-lineage rule;
- propagation/correction path;
- lawful reachability rule;
- node sampling and aggregation rule, if exhaustive inspection is not used;
- stale-state precedence rule;
- transferability rule for later nodes.

The node inclusion, sampling, and aggregation rule must be fixed before the network-level outcome or supplied case-independently.

Recommended text:

> **A bounded Network Integrity file may close only under the ordinary Closing Condition of the Order of the Closed Loop. In addition, the network scope, relevant node class, lineage rule, correction path, reachability rule, and any node-sampling or aggregation rule must have been fixed before the network-level outcome or supplied case-independently. The closure authority and evidence custody inherit the existing Trust-Boundary Ratification requirements. If those conditions are unavailable, the system may attest narrower local or propagation facts but may not claim ratified network closure. An unbounded network is not eligible for global closure merely because bounded portions have been inspected or corrected.**

This directly imports the rc.4 prohibition on self-legitimation rather than recreating it.

# 9. Gate H — Correction vs Repair

## Pressure

Must every historical consequence be repaired before network correction can close?

## Finding

**SURVIVES.**

`PURPOSE.md` already distinguishes what changes now from consequences that still require repair, preservation, or a new file.

Therefore:

> **Corrected is not repaired.**

A correction file can close when the stale classification no longer governs the bounded decision path, while separate repair files remain open for material consequences already produced.

The opposite mistake is also forbidden: correction cannot erase the consequence record.

Recommended rule:

> **Network correction records whether stale state still governs. Repair records what must be done about consequences already produced. Closing one does not silently close the other.**

# 10. Gate I — Justification Substitution

## Pressure

Is Candidate E actually Network Integrity doctrine?

## Finding

**NO. ITS MECHANISM SURVIVES, BUT ITS PLACEMENT CHANGES.**

Justification Substitution can occur inside a single person, office, model, or institution. It does not require multiple nodes, propagation, or network lineage.

It therefore belongs in **Attestation Integrity**, with Network Integrity referencing it when a downstream node preserves a consequence after the original basis collapses.

## Required doctrinal placement

Add **Justification Substitution** under `ATTESTATION-INTEGRITY.md`, preferably after **Operative Attestation**, because it concerns whether a corrected account actually changes the basis of continuing treatment.

Recommended text:

### Justification Substitution

> **Justification Substitution occurs when a justification that materially supported a consequential action, classification, or treatment is defeated or materially narrowed, substantially the same consequence is preserved, and a new justification is supplied without independently adjudicating whether that new justification legitimately supports the continuing consequence under its own evidence, scope, authority, and governing rule.**

> **A defeated justification cannot be considered reconciled merely because another justification is found for preserving its consequence.**

The guard clause is mandatory:

> **Failure of the original justification does not require the consequence to change where an independent and sufficient basis legitimately supports the same result. The later basis must earn the continuing consequence under its own rule.**

## Additional non-retroactivity clause

The insertion test exposes one further requirement:

> **A later independent justification may support a new or continuing decision prospectively. It does not retroactively become the justification for an earlier decision that was actually made on another basis. Historical Attestation preserves the basis that governed the decision at the time.**

This prevents justification substitution from laundering the historical file even when the same outcome becomes legitimate later for a different reason.

# 11. Gate J — Architecture Placement

## Finding

The clean insertion shape is:

### `NETWORK-INTEGRITY.md` — new doctrine file

Contains:

- network purpose and definitions;
- Lineage Integrity;
- distributed Carry Forward constraints;
- Propagation Symmetry;
- network-specific RRE application;
- bounded network closure inheritance;
- network test;
- compact laws.

It explicitly imports, rather than duplicates:

- Closing Condition;
- Attestation Integrity;
- RRE;
- Trust-Boundary Ratification.

### `ATTESTATION-INTEGRITY.md`

Add **Justification Substitution**, including its independent-J2 guard and non-retroactivity clause.

Network Integrity references this section rather than redefining it.

### `README.md`

Minimal integration only:

- identify Network Integrity as the distributed application of correction/Carry Forward;
- state that network files inherit the ordinary Closing Condition;
- link to `NETWORK-INTEGRITY.md`.

Do not duplicate the network doctrine in README.

### `RRE.md`

Minimal integration only:

- clarify that network propagation is a transport fact;
- network persistence is verified at the node's normal state path;
- Installed Revision and Carried Revision retain their existing meanings;
- link to Network Integrity.

### `PURPOSE.md`

**No doctrinal change required.**

Its existing scale-independent and reconciliation framing already supports the extension without amendment.

### `mirror-prompt.txt`

**No insertion required for certification.**

A later implementation update may teach the Mirror the network test, but Mirror behavior should not be made a condition of doctrinal certification.

# 12. Surviving Compact Laws

The insertion test admits these as candidate laws for the integration draft:

> **Repetition is not independence.**

> **Propagation is not proof of truth; it is evidence of network state.**

> **Local closure is not network closure.**

> **Transport is not persistence. Persistence is not installation. Installation is not Carry Forward.**

> **A correction must be able to travel through the controlled path the consequential error traveled, within lawful scope.**

> **Do not make a subject repurchase proof already satisfied and legitimately available to the later decision node.**

> **Do not count echoes as independent witnesses.**

> **A defeated justification cannot be reconciled merely by replacing it with an unearned one.**

> **Corrected is not repaired.**

> **A network can preserve a stale file without any single node authoring the whole failure.**

# 13. What the Integration Draft Must Not Do

The next draft fails automatically if it:

1. creates a fifth adjudication stage;
2. creates a second formal RRE status ladder;
3. weakens the ordinary Closing Condition;
4. lets a network file manufacture its own legitimacy;
5. treats missing provenance as proof of common ancestry;
6. makes one node's finding universally portable;
7. creates perpetual surveillance of dormant nodes;
8. requires private evidence to be rebroadcast where a sufficient authorized correction can do the work;
9. makes correction synonymous with repair;
10. leaves Justification Substitution network-only;
11. allows a later J2 to be backdated as the rationale for a decision actually made under J1;
12. treats propagation as evidence that the underlying proposition is true.

# Final Ruling

The refined Network Integrity candidate **belongs in the architecture**, but not verbatim.

The decisive placement results are:

- **A — Lineage Integrity:** insert into Network Integrity.
- **B — Distributed Carry Forward:** insert into Network Integrity as a constrained application of existing Carry Forward.
- **C — Propagation Symmetry:** insert into Network Integrity, with rc.4 terminality controlling dormant/later use.
- **D — Bounded Network Closure:** replace the parallel closing rule with full inheritance of the existing Closing Condition plus network-specific eligibility declarations.
- **E — Justification Substitution:** move to Attestation Integrity and reference it from Network Integrity.
- **Network status ladder:** do not insert as a second RRE ladder; express propagation/persistence facts through existing RRE semantics.
- **Correction vs repair:** preserve as a network law and separate-file rule.

**READY FOR INTEGRATION DRAFT — NOT CERTIFIED.**