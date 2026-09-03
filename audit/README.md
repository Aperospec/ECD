# Semantic Preservation Audit

Audit ID: `ECD-SPA-001`

Status: **active — Wave 2 source-level remediation complete; installation and behavioral verification pending; V3.1 is not yet semantically certified**

## Audited baselines

### Founding complete baseline

`fb6a694c99b64b2155c8c600eb125d5d3d08e200`

Protects the original ECD operating intent:

- one formal Creative Producer interface;
- infer-first behavior;
- shortest valid routing and reuse of valid artifacts;
- proportionate Compact / Standard / Extended process depth;
- Development, Editorial, Visual, and Production ownership;
- routine professional autonomy;
- deterministic typography and target-surface delivery;
- ECD final authority.

### Mature V2 baseline

`v2.1-legacy @ cdc48e4eba107dd67a4920d2fd1101058759031b`

Protects later validated semantics:

- explicit decision objects and hard stops;
- Producer review;
- artifact decision inheritance;
- stage-scoped inputs;
- mandatory Script Alignment;
- copy-aware composition and image-class separation;
- Type-Fit and mobile QA;
- earliest-failed-object rework;
- final acceptance traceability.

### Authorized changes

`audit/AUTHORIZED_CHANGE_LEDGER.md`

A difference from an earlier version is not semantic loss when it is recorded as an ECD-authorized supersession, strengthening, or structural translation.

## Wave 2 Runtime candidate

The source-level remediation was completed across the V3 branch through:

`7bfa0a2219aa792f510e635bd7270f2c0e18895a`

Later commits update audit and eval records without changing the substantive Runtime candidate under review.

## Audit artifacts

- `audit/SEMANTIC_CONSTITUTION.md` — 47 stable semantic clauses.
- `audit/AUTHORIZED_CHANGE_LEDGER.md` — authorized changes and supersessions.
- `audit/SEMANTIC_TRACEABILITY_MATRIX.md` — baseline → current implementation → test trace.
- `audit/LEGACY_METHOD_MIGRATION_MATRIX.md` — deleted V2 methods and their V3 destinations.
- `evals/semantic/SEMANTIC_REGRESSION.md` — behavior tests required for certification.

## Status vocabulary

- **Preserved** — current implementation retains the earlier professional consequence.
- **Strengthened** — current implementation retains and makes the principle more enforceable.
- **Intentionally Superseded** — a later authorized rule replaces an earlier rule.
- **Distributed / Preserved** — meaning survives across several current files.
- **Restored** — Wave 2 reintroduced a valid earlier semantic obligation that was weak or absent.
- **Partially Preserved** — some consequence survives, but a meaningful part is weak or absent.
- **Missing** — no sufficient current implementation exists.
- **Conflict** — current rules pull in incompatible directions.
- **Pending behavioral equivalence** — source mapping is sufficient, but actual runtime behavior or artifact proof has not yet established equivalence.

## Wave 1 findings

Wave 1 identified five material deficiencies:

1. infer-first, shortest-valid-route, and proportional process semantics were weak or conflicting;
2. project-level Evidence Obligation modes were absent;
3. Stage-Scoped Input semantics had been reduced to simple Active / Deferred lists;
4. shared reference governance and controlled transfer were fragmented;
5. native Chinese / English craft was shallow and Bilingual Transcreation was missing.

## Wave 2 remediation completed

### 1. Adaptive routing restored

Added `core/ADAPTIVE_ROUTING.md` and integrated it into root, Producer, Runtime, Project State, Department Control, Directors, Profile, and Evals.

Restored:

- infer first and ask only materially consequential questions;
- latest-valid-artifact entry;
- valid-artifact reuse;
- Compact / Standard / Extended complexity and risk profiles;
- professional-question routing before named Skills;
- combined execution seats without false independence;
- routine professional autonomy.

### 2. Evidence Obligation restored

Added `core/EVIDENCE_OBLIGATION.md` and integrated it across Development, Editorial, Visual, Production, Project State, and final decision objects.

Restored:

- Speculative / Conceptual;
- Evidence-based Editorial;
- Product / Commercial Validation;
- claim-level stricter overrides;
- public claim ceilings;
- practical validation, reproducibility, failure-boundary, dependency, cost, rights, and operational checks when commercial promises require them.

### 3. Stage-Scoped Input Register restored

Added `core/STAGE_SCOPED_INPUT_REGISTER.md`.

Restored:

- authority classes;
- original wording separate from studio interpretation;
- Global, Development, Editorial, Visual, and Production projections;
- Active, Deferred, Activated, Resolved, Superseded, Conflict, and stale states;
- activation and supersession logs;
- no-repeat behavior;
- Compact embedded-register option.

### 4. Reference governance restored

Added `core/REFERENCE_CONTRACT.md` and integrated it into Claims Rights, Visual Concept, Image Direction, Art Director, Production, Handoff, Project State, and Decision Objects.

Restored:

- explicit reference roles;
- rights, direct-use, attribution, evidence, and prohibited-transfer conditions;
- Description → Formal Analysis → Interpretation → Controlled Transfer;
- stage-scoped activation;
- multi-reference conflict handling;
- source-specific expression and project-specific originality boundaries.

### 5. Native-language and bilingual craft restored

Added and registered:

- `ecd-chinese-copy-craft`;
- `ecd-english-copy-craft`;
- `ecd-bilingual-transcreation`.

Integrated them into Editorial routing, Social Editorial Profile, Decision Objects, Project State, and Production sign-off.

## Wave 2 source-level verdict

At source level:

- `Missing`: 0;
- `Conflict`: 0;
- Wave 1 findings F-001 through F-005: source-level resolved;
- several Visual and Production legacy methods: still pending behavioral equivalence.

This does **not** constitute semantic certification.

## Remaining verification work

### Phase A — Static installation verification

- resync the branch;
- verify every implemented Skill is registered and readable;
- verify the four restored Core contracts are in mandatory startup load;
- verify the new native-language and transcreation Skills are discoverable;
- verify no V2 Runtime directory has re-entered the branch.

### Phase B — Orchestration and semantic control tests

Execute `SREG-01`–`SREG-12`, including:

- Advisory → Treatment authority;
- infer-first threshold;
- shortest valid route;
- process proportionality;
- Evidence Obligation;
- Reference Contract;
- Stage-Scoped Input no-repeat behavior;
- Producer autonomy.

### Phase C — Craft and end-to-end tests

Execute `SREG-13`–`SREG-18` on a controlled Social Editorial project, including at least one language variant.

### Phase D — Failure injection and language tests

Execute:

- `SREG-19`–`SREG-20` for rework and capability / review integrity;
- `SREG-21` for Chinese and English native craft;
- `SREG-22` for bilingual transcreation;
- `SREG-23` across unrelated subjects for anti-template behavior.

### Phase E — Distributed method equivalence

Close pending behavioral equivalence for:

- Anchor / smallest representative proof;
- visual metaphor and reference-canon behavior;
- executable Art Direction handoff;
- Mobile QA collective coverage;
- complete Production trace and opened-export inspection.

## Certification criteria

V3.1 may be marked `Semantically Certified` only when:

1. every Constitution clause is Preserved, Strengthened, Restored, or Intentionally Superseded;
2. Missing and Conflict counts remain zero;
3. every pending behavioral equivalence item has passing evidence or an ECD-authorized disposition;
4. every Constitution clause has a positive test and defined failure condition;
5. every new hard Runtime constraint traces to an authorized change or general professional invariant;
6. simple, continuation, multilingual, evidence-based, and commercial-validation projects demonstrate proportionate depth;
7. the ECD is not required to manage roles, repeat registered inputs, or perform first-line QA;
8. final assets and project records prove semantic, professional, evidence, rights, reference, language, visual, and technical continuity;
9. an audit summary is reviewed before V3.1 is promoted to `main`.

## Runtime change rule during audit

Further Runtime remediation must cite:

- affected Constitution clauses;
- baseline semantic consequence;
- current failure or ambiguity;
- current implementation;
- regression test IDs;
- whether the change is restoration, strengthening, or authorized supersession.

Do not add case-specific rules from individual projects to the Runtime. Cases remain test fixtures in the Eval layer.
