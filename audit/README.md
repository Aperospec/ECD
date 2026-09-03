# Semantic Preservation Audit

Audit ID: `ECD-SPA-001`

Status: **active — Wave 1 baseline capture and initial trace complete; V3.1 is not yet semantically certified**

Audited candidate:

- branch: `v3-department-architecture`
- candidate commit before audit records: `b5b1d51453d70ae1afb6eb95284b6086bafb5f86`
- candidate version: `ECD Studio OS V3.1 / 3.1-alpha`

## Purpose

This audit determines whether V3.1 preserves the durable meaning of ECD while incorporating explicitly authorized changes. It does not compare wording or directory shape. It compares professional intent, user relationship, authority, stage behavior, craft obligations, and observable outcomes.

The audit must detect both:

1. **semantic loss** — an earlier valid principle has disappeared, weakened, or become unreachable; and
2. **semantic accretion** — a new rigid rule has entered Runtime without user authority or general professional necessity.

## Baselines

### Founding complete baseline

`fb6a694c99b64b2155c8c600eb125d5d3d08e200`

This is the first coherent one-skill ECD implementation. It protects the original operating intent: one Producer interface, infer-first behavior, shortest valid routing, adaptive complexity, Development / Editorial / Visual / Production ownership, deterministic typography, professional autonomy, and ECD authority.

### Mature V2 baseline

`cdc48e4eba107dd67a4920d2fd1101058759031b`

This is the final V2.1 state before department-architecture development. It protects later validated semantics: explicit decision objects, Producer review, artifact decision inheritance, stage-scoped inputs, mandatory Script Alignment, copy-aware composition, production-intent image classification, Type-Fit, first-failed-object rework, and final QA.

### Authorized change record

`audit/AUTHORIZED_CHANGE_LEDGER.md`

An earlier rule may differ in V3.1 without constituting loss only when the difference is recorded as an intentional supersession, extension, or structural translation.

## Audit artifacts

- `audit/SEMANTIC_CONSTITUTION.md` — stable clause-level meaning of ECD.
- `audit/AUTHORIZED_CHANGE_LEDGER.md` — changes explicitly authorized after the founding baseline.
- `audit/SEMANTIC_TRACEABILITY_MATRIX.md` — baseline → V3.1 implementation → behavior-test trace.
- `audit/LEGACY_METHOD_MIGRATION_MATRIX.md` — deleted V2 method files and their V3.1 destinations.
- `evals/semantic/SEMANTIC_REGRESSION.md` — behavior tests required for certification.

## Status vocabulary

- **Preserved** — current implementation retains the earlier professional consequence.
- **Strengthened** — current implementation retains and makes the principle more enforceable.
- **Intentionally Superseded** — a later authorized rule replaces an earlier rule.
- **Distributed / Preserved** — meaning survives across several V3.1 files rather than one replacement file.
- **Partially Preserved** — some consequence survives, but a meaningful part is absent or weak.
- **Missing** — no sufficient current implementation exists.
- **Conflict** — current rules pull in incompatible directions.
- **Pending Evidence** — source mapping appears plausible but behavior or method-level proof is incomplete.

## Wave 1 preliminary verdict

V3.1 has clearly preserved or strengthened its central governance model:

- the human remains ECD;
- Creative Producer remains the only formal interface;
- departments and Specialist Skills cannot self-authorize;
- formal decisions require complete bound objects;
- stage leakage and silent mutation are prohibited;
- Frame Script, Storyboard, design, and Production remain professionally distinct;
- copy-aware composition, deterministic typography, Type-Fit, target-width proof, and first-failed-object rework remain represented.

V3.1 is **not certified** because Wave 1 found material areas requiring remediation or behavior proof:

1. **Infer-first behavior is no longer a canonical, testable Runtime principle.** Conservative assumptions exist, but the founding rule governing when to ask the ECD is not fully restored.
2. **Shortest-valid-route semantics are only partially represented.** Continuation exists, but reuse of the latest valid artifact and avoidance of waterfall recreation require stronger explicit implementation and tests.
3. **Complexity / risk proportionality has regressed.** Founding and V2 used Compact / Standard / Extended depth. V3.1 has dynamic seat combination, while the default profile and minimum-chain eval can be read as requiring every professional task for every project.
4. **Evidence Obligation modes are missing as a project-level control.** Speculative / Conceptual, Evidence-based Editorial, and Product / Commercial Validation no longer govern research depth explicitly.
5. **Stage-Scoped Input Register semantics are only partial.** V3.1 records Active and Deferred inputs, but the earlier authority classes, multi-stage projections, activation log, source-faithful preservation, and no-repeat rule are not fully represented.
6. **Reference Policy is fragmented.** Rights, source use, and visual transfer exist in several Skills, but reference roles and the full observation → analysis → interpretation → controlled-transfer discipline are not a shared cross-stage contract.
7. **Language craft has regressed.** Detailed Chinese copy craft and English copy craft have only partial equivalents; Bilingual Transcreation is explicitly unimplemented.
8. **Several deleted Visual and Production methods have plausible distributed replacements but still need method-level equivalence proof**, especially Anchor Keyframe semantics, visual intent / metaphor records, reference canon, Art Direction handoff, Mobile QA severity and map compliance, and production workflow detail.
9. **The minimum professional chain may conflict with minimal sufficient process.** A method pass should exist only when its professional question is real; combining seats must not become a requirement to simulate every listed Skill for trivial work.

## Certification criteria

V3.1 may be marked `Semantically Certified` only when:

1. every Constitution clause is `Preserved`, `Strengthened`, or `Intentionally Superseded`;
2. `Missing` and `Conflict` counts are zero;
3. every `Partially Preserved` item has an accepted remediation or an explicit ECD-approved retirement;
4. every deleted V2 method file has a migration disposition;
5. every Constitution clause has at least one positive behavior test and a defined failure condition;
6. every new hard Runtime constraint traces to an authorized change or a general professional invariant;
7. simple, intermediate-entry, and complex projects demonstrate proportionate process depth;
8. V3.1 does not require the ECD to manage internal roles or perform first-line professional QA;
9. a semantic audit summary is reviewed before V3.1 is promoted to `main`.

## Runtime freeze during audit

Audit records may be added to the branch. Runtime rules should not be changed ad hoc while evidence collection is incomplete. Remediation changes must reference affected Constitution clause IDs and update both traceability and tests.