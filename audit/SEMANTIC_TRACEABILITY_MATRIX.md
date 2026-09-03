# Semantic Traceability Matrix

Audit ID: `ECD-SPA-001`

Wave: `1 — source-level initial trace`

Candidate: `v3-department-architecture @ b5b1d51453d70ae1afb6eb95284b6086bafb5f86`

This matrix traces each Constitution clause from the founding complete baseline (`fb6a694c…`) and mature V2 baseline (`cdc48e4e…`) into current V3.1. Status is provisional until the listed semantic regression tests run.

## Status summary

- preserved / strengthened / intentionally superseded: substantial majority of core governance and stage semantics;
- conflict: proportional process and minimum-chain interpretation;
- missing: bilingual transcreation;
- partial: infer-first, shortest route, evidence-obligation modes, stage-scoped input semantics, shared reference policy, source / inference authority preservation, and native-language craft depth.

## Matrix

| Clause | Canonical intent | Baseline evidence | V3.1 implementation | Wave 1 status | Required evidence or remediation |
|---|---|---|---|---|---|
| SEM-001 | Human remains ECD with final consequential authority | `fb6a…/ORGANIZATION.md`; `cdc48…/SKILL.md` | `SKILL.md`; `V3_ARCHITECTURE.md`; `core/AUTHORITY_AND_DECISION_OBJECTS.md` | Strengthened | `SREG-01`, `SREG-10` |
| SEM-002 | One formal Producer interface | `fb6a…/ORGANIZATION.md`; `fb6a…/SKILL.md` | `SKILL.md`; `core/creative-producer/SKILL.md` | Strengthened | `SREG-01`, `SREG-12` |
| SEM-003 | User does not orchestrate roles or handoffs | founding `Infer first`; `cdc48…/SKILL.md` | root invariant 7; Producer autonomous method | Strengthened | `SREG-12` |
| SEM-004 | Infer first; ask only materially consequential questions | `fb6a…/SKILL.md` and `ORGANIZATION.md` | Producer records temporary assumptions and stops for genuine missing information, but no canonical material-question rule | Partially Preserved | Restore explicit inference / question policy; run `SREG-02` |
| SEM-005 | Enter at latest valid artifact and reuse sound work | founding `Use the shortest valid route`; mature V2 adaptive entry | Entry Router Continuation; Runtime `Continuation Validation`; stale-dependency rule | Partially Preserved | Make `shortest valid route` explicit and test reuse without waterfall recreation: `SREG-03` |
| SEM-006 | Process depth scales with risk and complexity | founding and V2 Compact / Standard / Extended models | `V3_ARCHITECTURE.md` dynamic scale; profile has fixed default chains but no project complexity record | Conflict | Restore a project-level complexity / risk router; revise minimum-chain interpretation; `SREG-04` |
| SEM-007 | Rigor is not maximum paperwork; combine when questions are resolved | founding Compact rule; V2 Minimal Sufficient Process | architecture permits combined seats, but profile and eval can imply every listed Skill pass is mandatory | Conflict | Distinguish mandatory professional question from mandatory named pass; `SREG-04`, `SREG-05` |
| SEM-008 | Routine professional decisions stay internal | founding `ECD Gates` and organization | Producer autonomy; Directors own craft; ECD gates limited to authority-bearing objects | Preserved | `SREG-06` |
| SEM-009 | Explicit Deliverable Contract | founding / V2 root and `shared/DELIVERABLE_CONTRACT.md` | `core/DELIVERABLE_CONTRACT.md`; Project State | Preserved | `SREG-01`, `SREG-18` |
| SEM-010 | Completion and publication chain is recoverable | V2 Acceptance Record and Project State | Runtime Completed state; Project Completion Record; final sign-offs | Strengthened | `SREG-18` |
| SEM-011 | Evidence depth matches promise | `v2.1-legacy/shared/RESEARCH_FUNCTION.md` evidence-obligation modes | Research Verification and Claims Rights exist; no project-level Speculative / Evidence-based / Commercial mode | Partially Preserved | Restore Evidence Obligation control and routing: `SREG-07` |
| SEM-012 | Fact, inference, concept, experience, simulation, and speculation remain distinct | V2 Research, Treatment, copy craft | Research Verification; Claims Rights; Copywriting; Copy Editing; profile | Strengthened | `SREG-08` |
| SEM-013 | Research constrains but does not choose creative premise | founding / V2 Research Function | Research Verification purpose and failure routing; Development Director separation | Preserved | `SREG-07` |
| SEM-014 | References have assigned roles and only those roles activate | `v2.1-legacy/shared/REFERENCE_POLICY.md` | source-use classification in Claims Rights; image roles in Image Direction; no shared cross-stage reference-role register | Partially Preserved | Re-establish shared Reference Role contract: `SREG-09` |
| SEM-015 | Observation → formal analysis → interpretation → controlled transfer | V2 Reference Policy and `reference-reading-and-transfer.md` | Visual Concept contains a condensed four-part reference analysis; rights split elsewhere | Partially Preserved | Prove full controlled-transfer behavior or restore a reusable method object: `SREG-09` |
| SEM-016 | Source wording, studio interpretation, and user authority stay separate | V2 Stage-Scoped Input Register and Reference Policy | Research classifications; Project State sources; no explicit authority-class / source-faithful register | Partially Preserved | Restore source / interpretation / authority fields and no-repeat behavior: `SREG-11` |
| SEM-017 | Rights, provenance, attribution, version and evidence context survive | V2 Research / Reference / Acceptance records | Claims Rights; Research Verification; Project State; Production Director | Preserved | `SREG-08`, `SREG-09`, `SREG-18` |
| SEM-018 | Development determines whether and what project exists | founding / V2 Development Function | Development Director + Creative Strategy + Concept Development | Strengthened | `SREG-01` |
| SEM-019 | Treatment is connected creative synthesis, not worksheet dump | V2 Treatment Template / Presentation | Development Director quality standard; Decision Object Treatment template | Preserved | `SREG-01` |
| SEM-020 | Development does not decide downstream craft | founding / V2 Development Function | root invariant 4; Stage Capability Matrix; Development Director | Strengthened | `SREG-10` |
| SEM-021 | Greenlight binds an identified Treatment | mature V2; later user directive | Authority contract; Runtime state 6; Entry Router | Intentionally Superseded / Strengthened | `SREG-01`, `SREG-10` |
| SEM-022 | Editorial owns architecture, Frame Scripts, exact and publication copy | founding / mature V2 | Editorial Director and five Editorial Skills | Strengthened | `SREG-13` |
| SEM-023 | Communication mode is chosen deliberately, not narrative by default | founding root; V2 content modes | Content Architecture communication-mode method | Preserved | `SREG-13` |
| SEM-024 | Semantic proposition, Frame Script, visual requirements, copy and Storyboard are distinct | V2 Editorial / Frame Script protocols | Content Architecture; Frame Script; Editorial Director; Stage Matrix | Preserved | `SREG-13`, `SREG-14` |
| SEM-025 | Every new Script requires explicit Alignment | mature V2 and explicit ECD authorization | Authority contract; Runtime state 10; Decision Objects | Intentionally Superseded / Strengthened | `SREG-10`, `SREG-13` |
| SEM-026 | Visual starts only from authority-complete Script and exact inputs | mature V2 Production Model | Runtime / Stage Matrix / Visual Director | Preserved | `SREG-10`, `SREG-15` |
| SEM-027 | Resolve visual concept before broad execution when needed | founding Art Direction; V2 concept development | Visual Concept Skill; Art Director chain | Preserved | `SREG-15` |
| SEM-028 | Storyboard gives low-cost full-sequence proof | founding; V2 Storyboard protocol | Storyboard / Sequence Skill; profile full-sequence requirement | Preserved | `SREG-15` |
| SEM-029 | Exact copy shapes Production-intent imagery before creation | mature V2 Copy-Aware Composition | Editorial Design METHOD; Image Direction; Stage Matrix; Production chain | Strengthened | `SREG-16` |
| SEM-030 | Exploratory and Production-intent imagery remain distinct | mature V2 Copy-Aware / Anchor protocols | Visual Concept; Image Direction; Stage Matrix | Preserved | `SREG-16` |
| SEM-031 | Full sequence and representative fidelity are both required | later authorized V3 change; V2 anchors / comps | profile; Visual Department; Decision Objects | Strengthened | `SREG-15` |
| SEM-032 | Required text remains deterministic and editable | founding / mature V2 | Production Typesetting; Finished Art; profile | Preserved | `SREG-16`, `SREG-17` |
| SEM-033 | Production faithfully realizes and does not redesign | founding / V2 Production Artist | Production Director and Production Skills; Stage Matrix | Preserved | `SREG-17` |
| SEM-034 | Test real target width, thumbnail, platform overlays, variants, opened exports | mature V2 Mobile QA | Editorial Design; Design Critique; Technical QA; Production Director | Distributed / Preserved | Need collective-behavior test including map, depth, sequence and actual file inspection: `SREG-17`, `SREG-18` |
| SEM-035 | No silent mutation | mature V2 Artifact Decision Contract | root invariant 5; Handoff and Rework; Project State | Preserved | `SREG-19` |
| SEM-036 | Artifacts record inheritance, new decisions, open decisions, tolerances and delta | mature V2 Artifact Decision Contract | Handoff delta; Project State locks / tolerances / dependencies | Distributed / Preserved | Verify an actual cross-stage artifact chain: `SREG-19` |
| SEM-037 | Early information is preserved and activated stage-by-stage | V2 Stage-Scoped Input Register | Project State Active / Deferred inputs; Stage Matrix authoritative inputs | Partially Preserved | Restore authority classes, multi-stage projections, activation log, and no-repeat rule: `SREG-11` |
| SEM-038 | Specialist, Department, Producer, and ECD states remain separate | mature V2 Artifact States; later department authorization | Authority contract; Runtime; Department Control Loop | Strengthened | `SREG-10`, `SREG-20` |
| SEM-039 | No phantom capability or review | explicit V3 authorization | Capability Registry; root invariants 1–2; Department Control Loop | Strengthened | `SREG-20` |
| SEM-040 | Department review precedes Producer integration | explicit department architecture | Department Control Loop; Producer Skill; Handoff | Strengthened | `SREG-20` |
| SEM-041 | Formal ECD decisions use complete visible objects | mature V2 decision presentation | Authority contract; profile Decision Objects | Strengthened | `SREG-10`, `SREG-13`, `SREG-15`, `SREG-18` |
| SEM-042 | Decision-request turn stops | mature V2 and explicit hardening | root invariant 9; Runtime stop states | Strengthened | `SREG-10` |
| SEM-043 | Rework returns to earliest failed object and preserves unaffected work | founding / mature V2 lock and rework | Handoff and Rework; Project State stale-dependency rule; Producer | Strengthened | `SREG-19` |
| SEM-044 | Producer autonomously reaches next ECD gate or real blocker | founding and explicit Producer authorization | root invariant 7; Producer method 9 | Strengthened | `SREG-12` |
| SEM-045 | Native-language craft is first-class | V2 Chinese Copy Craft and English Copy Craft | Copywriting / Copy Editing mention Chinese naturalness; Typography has deep CJK and mixed-script method | Partially Preserved | Restore dedicated audience-language craft or expand Editorial methods; `SREG-21` |
| SEM-046 | Bilingual transcreation uses shared semantic invariant and native drafts | V2 `bilingual-transcreation.md` | Registry explicitly marks Localization / Transcreation unimplemented | Missing | Implement or explicitly retire through ECD authority; `SREG-22` currently expected to fail |
| SEM-047 | Methods, references, modes, archetypes and ratios do not become templates | founding adaptive method; V2 design / writing canons | Visual Concept specificity test; Editorial Design METHOD; Typography; profile numeric caveat | Preserved | `SREG-23` |

## Immediate non-certification findings

### Finding F-001 — Process proportionality conflict

Affected clauses: `SEM-006`, `SEM-007`.

The current architecture says small work may combine seats, while the default Social Editorial profile declares most Editorial and Visual Skills required and `evals/MINIMUM_PROFESSIONAL_CHAIN.md` can be read as requiring a full named chain in every project. This risks replacing adaptive rigor with ceremonial method simulation.

Required resolution:

- define professional-question routing before Skill routing;
- preserve mandatory outcomes while making named method passes conditional by actual need;
- restore a recorded complexity / risk profile;
- test single-image, two-page, standard carousel, evidence-sensitive, and continuation projects.

### Finding F-002 — Evidence obligation loss

Affected clause: `SEM-011`.

V2 explicitly differentiated Speculative / Conceptual, Evidence-based Editorial, and Product / Commercial Validation. V3.1 has capable research and claims Skills but no project-level mode controlling required depth and public promise.

### Finding F-003 — Stage-scoped input semantics weakened

Affected clauses: `SEM-016`, `SEM-037`.

Current Project State retains Active and Deferred lists but not the full earlier mechanism for authority class, faithful source wording, multi-stage projections, activation conditions, receiving owner, no-repeat behavior, and activation history.

### Finding F-004 — Reference governance fragmented

Affected clauses: `SEM-014`, `SEM-015`, `SEM-016`.

Current source-use, visual reference, and image-role logic is spread across Claims Rights, Visual Concept, Image Direction, and Project State. The distributed system may work, but no shared contract guarantees that one reference's authorized role and prohibited transfer remain stable across departments.

### Finding F-005 — Language-method regression

Affected clauses: `SEM-045`, `SEM-046`.

V3.1 retains strong visual Typography methods and general Copywriting / Copy Editing, but the dedicated Chinese, English, and bilingual editorial-craft protocols were removed. Bilingual Transcreation is explicitly absent.

## Audit rule for remediation

A runtime change made to close a finding must cite:

- clause IDs;
- baseline file and semantic consequence;
- current failure or ambiguity;
- proposed current implementation;
- regression test IDs;
- whether the change is restoration, strengthening, or authorized supersession.