# Legacy Method Migration Matrix

Audit ID: `ECD-SPA-001`

Wave: `1 — preliminary source mapping`

Source baseline: `v2.1-legacy @ cdc48e4eba107dd67a4920d2fd1101058759031b`

Target candidate: `v3-department-architecture @ b5b1d51453d70ae1afb6eb95284b6086bafb5f86`

## Interpretation

Deleting a V2 file is acceptable only when its professional consequence is:

- fully migrated into V3.1;
- deliberately distributed across named current files;
- intentionally superseded by an authorized rule; or
- explicitly retired by ECD authority.

A similar filename or topic is not proof of migration. `Pending Evidence` means that likely replacements exist, but method-level or behavioral equivalence has not yet been demonstrated.

## Core and studio governance

| V2 file | Durable semantic responsibility | V3.1 destination | Wave 1 disposition | Open issue |
|---|---|---|---|---|
| `ORGANIZATION.md` | one user-facing Skill; ECD authority; Producer interface; adaptive routing; professional boundaries | `SKILL.md`; `V3_ARCHITECTURE.md`; Director Skills | Strengthened | Infer-first, shortest-route, and proportional-depth clauses require explicit restoration elsewhere |
| `shared/ACCEPTANCE_RECORD.md` | separate professional readiness, Producer clearance, ECD authority, and stage activation | `core/AUTHORITY_AND_DECISION_OBJECTS.md`; `core/PROJECT_STATE.md`; profile Decision Objects | Distributed / Preserved | Run end-to-end authority-record test |
| `shared/ARTIFACT_DECISION_CONTRACT.md` | inherited decisions, added / refined / changed / removed delta, tolerances, dependency consequences | `core/HANDOFF_AND_REWORK.md`; `core/PROJECT_STATE.md` | Distributed / Preserved | Current structure is less explicit as a standalone per-artifact contract; test actual cross-stage trace |
| `shared/ARTIFACT_STATES.md` | independent quality and authority dimensions; Handoff Ready computation | `core/AUTHORITY_AND_DECISION_OBJECTS.md`; `core/RUNTIME_STATE_MACHINE.md`; `core/PROJECT_STATE.md` | Strengthened | Verify current packages do not collapse states in practice |
| `shared/CREATIVE_TREATMENT_PRESENTATION.md` | complete frontstage Treatment, Producer recommendation, scope, hard stop | `profiles/social-editorial/DECISION_OBJECTS.md`; Authority contract | Preserved | Behavior test required |
| `shared/CREATIVE_TREATMENT_TEMPLATE.md` | Compact and Standard / Extended Treatment structures; evidence obligation; reference roles; optional project-specific decisions; Deferred inputs | Development Director; Decision Objects; Project State | Partially Preserved | Complexity variants, evidence-obligation field, stage-projection detail, and optional project-specific decision structure are weakened |
| `shared/DELIVERABLE_CONTRACT.md` | intended use, audience, surface, outputs, dimensions, variants, rights and acceptance | `core/DELIVERABLE_CONTRACT.md` | Preserved | Add complexity / evidence fields only if routed through separate controls, not by overloading contract |
| `shared/DEVELOPMENT_FUNCTION.md` | project-worth question, premise diagnosis, Treatment, no downstream pre-emption | Development Director and Development Specialists | Strengthened | Preserve connected Treatment rather than Specialist worksheet dump |
| `shared/ECD_DECISION_PRESENTATION.md` | complete visible decision object, frontstage / backstage distinction, gate-specific minimums, failure recovery | Authority contract; profile Decision Objects; Producer Skill | Strengthened | Verify primary-conversation completeness in runtime |
| `shared/GREENLIGHT_RECORD.md` | identified Treatment, scope, exclusions, response, authority, activated next stage | Authority contract; Project State; Runtime | Distributed / Preserved | Test bound decision ID and ambiguous response handling |
| `shared/HANDOFF_CONTRACT.md` | formal owner-to-owner handoff, dependencies, evidence, locks and release | Department Control Loop; Handoff and Rework; Producer Skill | Strengthened | None at source level |
| `shared/LOCK_AND_REWORK_PROTOCOL.md` | first-failed-owner diagnosis, preserve unaffected work, targeted invalidation | Handoff and Rework; Project State stale dependency; Producer | Strengthened | Run delta and targeted-rework test |
| `shared/PRODUCER_CONTROL_LOOP.md` | Producer assignment, review, internal return, feedback closure, ECD release, stage activation | Producer Skill; Department Control Loop; Runtime | Strengthened | Ensure Producer does not absorb department craft |
| `shared/PRODUCTION_MODEL.md` | adaptive stage-gated model; complexity / risk profile; evidence obligation; stage inputs; copy-aware chain | root Skill; Runtime; Stage Matrix; profiles; departments | Partially Preserved | Compact / Standard / Extended, evidence-obligation modes, and full stage-scoped input model were not fully migrated |
| `shared/PROJECT_STATE.md` | contract, complexity, evidence mode, active / deferred inputs, artifacts, states, locks, feedback, next action | `core/PROJECT_STATE.md` | Partially Preserved | Current state is strong but omits explicit complexity profile and evidence-obligation mode |
| `shared/REFERENCE_POLICY.md` | cross-stage reference roles, source statement, rights, four-pass reading, controlled transfer | Claims Rights; Visual Concept; Image Direction; Project State | Partially Preserved | No single shared reference-role and activation contract |
| `shared/RESEARCH_FUNCTION.md` | evidence depth by promise; three evidence-obligation modes; concise production consequence | Research Verification; Claims Rights | Partially Preserved | Evidence-obligation mode and commercial-validation depth are not explicit project controls |
| `shared/STAGE_CAPABILITY_MATRIX.md` | allowed / forbidden capabilities and transition preconditions | `core/STAGE_CAPABILITY_MATRIX.md` | Strengthened | Proportionality conflict remains outside stage boundaries |
| `shared/STAGE_SCOPED_INPUT_REGISTER.md` | preserve source once; authority classes; per-stage projections; Deferred activation; no-repeat rule | Project State; Stage Matrix; Producer assignment | Partially Preserved | Authority classes, projection table, activation log, source-faithful dual record, and no-repeat rule are missing or weak |

## Editorial methods

| V2 file | Durable semantic responsibility | V3.1 destination | Wave 1 disposition | Open issue |
|---|---|---|---|---|
| `editorial-director/ROLE.md` | communication architecture, sequence, Frame Scripts, copy, copy quality, evidence language | Editorial Director + five registered Editorial Skills | Strengthened | Required-chain proportionality must be resolved |
| `references/bilingual-transcreation.md` | shared semantic invariant, native drafts, parity dimensions, language-specific briefs and layout consequences | none; Registry marks Localization / Transcreation unimplemented | Missing | Must be implemented or explicitly retired by ECD |
| `references/chinese-copy-craft.md` | Chinese grammar, collocation, reference, word order, register, metaphor, rhythm, read-aloud and cross-page audit | Copywriting; Copy Editing; Proofreading; Typography | Partially Preserved | Editorial language method is materially shallower than V2; Typography does not replace copy craft |
| `references/content-modes.md` | deliberate explanatory, narrative, procedural, comparative, evidentiary and other modes | Content Architecture | Preserved | Test against narrative default |
| `references/copy-desk-workflow.md` | drafting, independent edit, proofread, fact / claim and language checks | Copywriting; Copy Editing; Proofreading; Editorial Director | Strengthened | Small-task pass selection must remain proportional |
| `references/copy-quality-gate.md` | fidelity, clarity, truth position, native language, repetition and exactness | Editorial Director; Copy Editing; Proofreading | Distributed / Preserved | Add native-language depth |
| `references/creative-script-package.md` | internal package, page meanings, Frame Scripts, exact copy, evidence and handoff | Editorial Director; Content Architecture; Frame Script; Decision Objects | Preserved | Behavior test required |
| `references/creative-script-presentation.md` | ECD-facing Overall Communication Logic; every page; full copy; scope; stop | profile Decision Objects; Authority contract | Strengthened | None at source level |
| `references/editorial-architecture.md` | audience movement, page jobs, minimum sufficient sequence | Content Architecture | Strengthened | None at source level |
| `references/english-copy-craft.md` | idiomatic English syntax, voice, headline and editorial rhythm | general Copywriting / Copy Editing only | Partially Preserved | No dedicated English or locale-aware method |
| `references/frame-script.md` | concrete visible / experiential beat distinct from layout and Storyboard | Frame Script Skill; Editorial Director; Stage Matrix | Preserved | Run abstract-vs-concrete test |
| `references/sequence-development.md` | minimum sequence, difference test, transitions, payoff | Content Architecture; Storyboard / Sequence | Preserved | Verify editorial / visual ownership remains separate |
| `references/social-editorial-copy.md` | display copy roles, mobile brevity, caption relationship and CTA discipline | Copywriting; Copy Editing; profile | Partially Preserved | Detailed platform copy heuristics require source-level follow-up |
| `references/visual-beats.md` | written visual statement preceding actual Storyboard | replaced by concrete Frame Script / Written Visual Requirements distinction | Intentionally Superseded | Preserve the boundary, not the obsolete label |
| `references/writing-reference-canon.md` | how writing references are read and transferred without imitation | no direct replacement | Pending Evidence / likely Partial | Claims Rights and Copy Editing cover risk, but no dedicated writing-reference method |

## Visual methods

| V2 file | Durable semantic responsibility | V3.1 destination | Wave 1 disposition | Open issue |
|---|---|---|---|---|
| `art-director/ROLE.md` | visual problem, routes, Storyboard, design, typography, image direction, critique and sign-off | Art Director + six registered Visual Specialist Skills | Strengthened | Verify Art Director reviews actual work rather than aggregate labels |
| `references/anchor-keyframe-gate.md` | smallest representative proof; cover / world and body anchors; exploratory / Production-intent separation; proof burden by novelty | Visual Concept; Image Direction; Editorial Design; Decision Objects | Partially Preserved | Proof function survives, but explicit Anchor roles, gate record and novelty-based burden are less explicit |
| `references/art-direction-package.md` | executable visual system, page classes, locks, tolerances, asset / type / sequence instructions | Visual Department formal package; Editorial Design return; Typography and Image Direction returns | Distributed / Preserved | Run Production-without-guessing test |
| `references/copy-aware-composition.md` | exact-copy geometry before Production-intent imagery; image classes; map; Producer gate; Type-Fit | Editorial Design METHOD; Typography METHOD; Image Direction; Stage Matrix; Production Skills | Distributed / Preserved | Verify formal pre-image clearance and per-screen coverage in behavior |
| `references/ecd-friendly-visual-alignment.md` | understandable visual decision surface with actual proof and recommendation | profile Decision Objects; Authority contract | Preserved | Behavior test required |
| `references/reference-reading-and-transfer.md` | assigned visual reference roles and four-pass controlled transfer | Visual Concept; Claims Rights; Image Direction | Partially Preserved | Shared role activation, ECD source statement, and multi-reference conflict record weakened |
| `references/representative-design-comp.md` | exact copy and target geometry proving hierarchy, image–type, legibility and feasibility | Editorial Design METHOD; profile; Decision Objects | Preserved | Run representative-comp test |
| `references/social-editorial-design-system.md` | mobile-first hierarchy, dominant action, typography as structure, image–type, depth, grid, page archetypes, rhythm, evidence, mobile proof | profile; Editorial Design METHOD; Typography METHOD; Design Critique | Distributed / Preserved | Run cross-page and mobile suite; verify no design checklist becomes template |
| `references/storyboard-development.md` | low-cost sequence staging, visual difference and continuity before final design | Storyboard / Sequence Skill | Preserved | Method-level comparison still pending |
| `references/visual-concept-development.md` | visual problem, materially distinct routes, selected visual thesis and proof | Visual Concept Skill | Preserved | None at source level |
| `references/visual-critique-and-failure-diagnosis.md` | observation-based critique, earliest failure, actionable rework | Design Critique METHOD | Strengthened | Independence must be represented honestly in one-model runtime |
| `references/visual-intent-elicitation.md` | infer / surface intended aesthetic and viewer relation without over-questioning | Visual Concept; Art Director; Producer assumptions | Partially Preserved | No explicit visual-intent elicitation and clarification threshold method |
| `references/visual-metaphor-mapping.md` | map conceptual relations into visual relations without literal illustration | Visual Concept Skill | Partially Preserved | General route method exists; explicit metaphor relation record not verified |
| `references/visual-problem-framing.md` | state visual problem, first perception, later understanding, risk and open variables | Visual Concept; Art Director | Preserved | None at source level |
| `references/visual-reference-canon.md` | durable design-reference theory and quality standards | Visual Concept; Editorial Design; Design Critique | Pending Evidence / likely Partial | Source-level comparison required; no direct canon replacement |

## Production methods

| V2 file | Durable semantic responsibility | V3.1 destination | Wave 1 disposition | Open issue |
|---|---|---|---|---|
| `production-artist/ROLE.md` | faithful realization, deterministic type, variants, export and QA | Production Director + four Production Skills | Strengthened | None at organizational level |
| `production-artist/references/mobile-qa.md` | severity model; exact text; map fidelity; image class; Type-Fit; thumbnail; actual width; blur; overlays; masks; evidence; sequence; variants | Technical QA; Production Director; Design Critique; Editorial Design | Distributed / Pending Evidence | Some checks survive across files, but collective equivalence must be tested; explicit severity and map / image-class audit may be weaker |
| `production-artist/references/production-workflow.md` | preflight, asset realization, deterministic layout, Type-Fit, variants, opened-export QA and return upstream | Production Director; Image Production; Finished Art; Production Typesetting; Technical QA | Distributed / Pending Evidence | Run complete production trace and compare against V2 workflow obligations |

## Priority migration gaps

### P0

- `shared/PRODUCTION_MODEL.md` proportionality semantics;
- `shared/STAGE_SCOPED_INPUT_REGISTER.md`;
- `shared/RESEARCH_FUNCTION.md` Evidence Obligation modes;
- `editorial-director/references/bilingual-transcreation.md`.

### P1

- shared Reference Policy and writing-reference method;
- detailed Chinese and English copy craft;
- Anchor Keyframe equivalence;
- Mobile QA collective equivalence;
- Visual intent and reference-canon equivalence.

## Completion rule

No row may remain `Missing`, `Conflict`, `Partially Preserved`, or `Pending Evidence` at certification. It must become:

- Preserved;
- Strengthened;
- Distributed / Preserved with passed behavior evidence;
- Intentionally Superseded with Authorized Change Ledger reference; or
- Explicitly Retired by ECD decision.