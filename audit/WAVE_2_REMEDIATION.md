# Wave 2 Semantic Remediation Record

Audit ID: `ECD-SPA-001`

Status: `source-level remediation complete; runtime installation and behavioral verification pending`

## Scope

Wave 2 addressed the five material gaps identified in Wave 1 without adding project-specific rules:

- F-001 — infer-first, shortest route, and process proportionality;
- F-002 — project-level Evidence Obligation;
- F-003 — Stage-Scoped Input authority and no-repeat behavior;
- F-004 — shared Reference Contract and controlled transfer;
- F-005 — native-language and bilingual craft.

## Runtime candidate

The substantive Wave 2 Runtime implementation is complete through:

`7bfa0a2219aa792f510e635bd7270f2c0e18895a`

Later Wave 2 commits update Eval and Audit records only.

## F-001 — Adaptive routing and proportional process

Affected clauses:

- `SEM-004`;
- `SEM-005`;
- `SEM-006`;
- `SEM-007`;
- `SEM-008`.

Implemented:

- `core/ADAPTIVE_ROUTING.md`;
- Compact / Standard / Extended complexity and risk profiles;
- infer-first material-question threshold;
- latest-valid-artifact entry and reuse;
- professional-question routing before named Skills;
- combined execution seats with distinct method evidence;
- routine ECD interruption threshold;
- Adaptive Route Record in Project State and Producer review.

Integrated into:

- root `SKILL.md`;
- `core/creative-producer/SKILL.md`;
- `core/RUNTIME_STATE_MACHINE.md`;
- `core/PROJECT_STATE.md`;
- `core/DEPARTMENT_CONTROL_LOOP.md`;
- Development, Editorial, Visual, and Production Directors;
- Social Editorial Profile;
- question-based minimum professional eval.

Tests:

- `SREG-02`–`SREG-06`;
- `SREG-12`.

## F-002 — Evidence Obligation

Affected clauses:

- `SEM-011`;
- `SEM-012`;
- `SEM-013`;
- `SEM-017`.

Implemented:

- `core/EVIDENCE_OBLIGATION.md`;
- Speculative / Conceptual mode;
- Evidence-based Editorial mode;
- Product / Commercial Validation mode;
- stricter claim-level overrides;
- public claim ceiling;
- practical validation protocol;
- reproducibility, failure-boundary, dependency, cost, operational, rights, and commercial-use checks;
- narrower-claim or blocker behavior when validation is unavailable.

Integrated into:

- Project State;
- Deliverable Contract;
- Producer Skill;
- Development Director;
- Research Verification;
- Claims and Rights Review;
- Editorial, Visual, and Production Directors;
- Stage Matrix;
- Social Editorial Profile and Decision Objects.

Tests:

- `SREG-07`;
- `SREG-08`;
- `SREG-17`;
- `SREG-18`.

## F-003 — Stage-Scoped Input Register

Affected clauses:

- `SEM-016`;
- `SEM-037`.

Implemented:

- `core/STAGE_SCOPED_INPUT_REGISTER.md`;
- Hard Constraint, User Preference, Creative Seed, Reference Intent, Existing Artifact, Assistant Inference, Requires Alignment, and External Constraint classes;
- Global / Deliverable, Development, Editorial, Visual, and Production projections;
- original wording separate from studio interpretation;
- Active, Deferred, Activated, Resolved, Superseded, Rejected, Conflict, and stale states;
- activation and supersession logs;
- no-repeat rule;
- temporary-assumption record;
- Compact embedded-register option.

Integrated into:

- Project State;
- Producer assignments and reviews;
- Stage Matrix;
- Department Control;
- Handoff and Rework;
- all Department Directors;
- Social Editorial Profile and Decision Objects.

Test:

- `SREG-11`.

## F-004 — Reference Contract

Affected clauses:

- `SEM-014`;
- `SEM-015`;
- `SEM-016`;
- `SEM-017`;
- `SEM-047`.

Implemented:

- `core/REFERENCE_CONTRACT.md`;
- explicit source, evidence, asset, concept, world, mood, style, color, composition, typography, workflow, benchmark, and negative-reference roles;
- original ECD intent and authority class;
- direct-use, transformation, attribution, evidence, rights, and prohibited-use conditions;
- Description → Formal Analysis → Interpretation → Controlled Transfer;
- source-specific expression exclusion;
- stage-scoped role activation;
- multi-reference conflict handling;
- similarity and originality tests.

Integrated into:

- Claims and Rights Review;
- Visual Concept;
- Image Direction;
- Art Director;
- Production Director;
- Producer Skill;
- Project State;
- Handoff and Rework;
- Social Editorial Profile and Decision Objects.

Tests:

- `SREG-09`;
- `SREG-15`–`SREG-18`;
- `SREG-23`.

## F-005 — Native-language and bilingual craft

Affected clauses:

- `SEM-045`;
- `SEM-046`.

Implemented and registered:

- `ecd-chinese-copy-craft`;
- `ecd-english-copy-craft`;
- `ecd-bilingual-transcreation`.

Chinese Copy Craft restores:

- sentence integrity;
- semantic compatibility;
- collocation;
- omitted subject and reference;
- information focus;
- voice and register;
- metaphor discipline;
- read-aloud rhythm;
- cross-page language audit;
- mixed-script language mechanics.

English Copy Craft restores:

- locale and house style;
- syntax and grammatical spine;
- agency and action;
- idiom, collocation, articles, prepositions, and countability;
- pronoun and modifier clarity;
- parallelism;
- voice and rhythm;
- translation-smell detection;
- cross-page mechanics and terminology.

Bilingual Transcreation restores:

- shared semantic invariant;
- language-specific briefs;
- native drafting and native craft review;
- functional and semantic parity;
- deliberate differences in syntax, rhetoric, and line length;
- terminology control;
- language-specific layout consequences.

Integrated into:

- Capability Registry;
- Editorial Director;
- Social Editorial Profile;
- Stage Matrix;
- Decision Objects;
- Project State;
- Producer Final Review;
- Production Director sign-off.

Tests:

- `SREG-21`;
- `SREG-22`.

## Static source checks completed

- the four restored Core contracts exist;
- root `SKILL.md` includes them in mandatory startup load;
- Chinese, English, and Bilingual Skills have unique `name`, usable `description`, and `version` frontmatter;
- Capability Registry lists all three as Implemented;
- Social Editorial Profile routes professional questions rather than making every registered Skill universally mandatory;
- Department Control and minimum professional eval use question-based routing;
- V3 top-level remains clean and does not contain the deleted V2 Runtime directories.

## Current source-level audit state

- Constitution clauses: 47;
- source-level Missing: 0;
- source-level Conflict: 0;
- Wave 1 findings source-level resolved: 5 of 5;
- semantic certification: not granted;
- remaining status: runtime registration, behavior execution, and distributed Visual / Production equivalence evidence pending.

## Next verification sequence

1. resync the branch and verify all 28 `SKILL.md` entries are registered or readable;
2. execute `SREG-01`–`SREG-12` before another full creative production test;
3. execute `SREG-21` and `SREG-22` with controlled Chinese, English, and bilingual fixtures;
4. execute `SREG-13`–`SREG-18` on one controlled Social Editorial project;
5. execute `SREG-19`–`SREG-20` with injected failures;
6. execute `SREG-23` across unrelated content subjects;
7. close pending Anchor, visual-metaphor, Art Direction, Mobile QA, and Production-workflow equivalence rows;
8. update the audit matrices and decide whether V3.1 may be marked Semantically Certified.
