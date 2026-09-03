# Runtime State Machine — V3.1

## Purpose

This state machine determines what work may exist, what decision is pending, and which capabilities are active.

Conversational momentum does not change state. Only Creative Producer may update Project State, and only valid evidence may justify the update.

Apply `ADAPTIVE_ROUTING.md` before choosing a state. The canonical flow defines authority order, not a mandatory waterfall restart.

## States

### 0. Uninitialized

No project record exists.

Allowed:

- receive request;
- inspect available materials and prior artifacts;
- infer reversible conditions;
- determine entry mode and latest valid artifact;
- identify any materially consequential question.

Before entering a decision-bearing project state, Producer creates or validates:

- Deliverable Contract;
- Adaptive Route Record and complexity / risk profile;
- Evidence Obligation Record;
- Stage-Scoped Input Register;
- Reference Records as required;
- Project State.

Next states:

- `Advisory Discovery`;
- `Development Active`;
- `Continuation Validation`;
- `Craft-only Task`.

### 1. Advisory Discovery

Used when the user asks to choose, rank, locate, compare, or recommend a topic, reference, or opportunity without yet asking for a complete work.

Allowed:

- research and source inspection;
- shortlist or one recommendation;
- concise rationale;
- account / audience / novelty comparison;
- provisional risk, Evidence Obligation, or reference note;
- next valid action.

Forbidden:

- claiming a Creative Treatment exists;
- claiming Development Department clearance;
- requesting Greenlight;
- treating a positive reaction as Greenlight;
- writing the final social post unless explicitly requested as a narrow Craft-only task;
- making binding Editorial or Visual decisions.

Output label:

`Advisory Recommendation — not a Creative Treatment or approval object`

If the user accepts the recommendation and asks to make the work, Producer initializes the project controls and transitions to `Development Active`.

### 2. Continuation Validation

Used when the user supplies or references an existing Treatment, Script, visual direction, final package, or localized correction.

Producer verifies:

- artifact identity and version;
- professional quality and prior authority evidence;
- dependencies and stale state;
- unresolved feedback;
- active profile and Deliverable Contract;
- Evidence Obligation;
- input and reference records;
- correct shortest next state.

Missing authority does not get inferred. Valid existing work is reused. If validation fails, return only to the earliest invalid state.

Possible next states:

- `Development Active`;
- `Editorial Active`;
- `Visual Active`;
- `Production Active`;
- a bounded Rework state;
- `Craft-only Task`;
- `Blocked`.

### 3. Craft-only Task

Used only for a narrow standalone professional request that does not claim full ECD project clearance.

Producer or the relevant method must state:

- task boundary;
- artifact or text being worked on;
- professional method used;
- that no broader Department, Producer, or ECD authority is implied.

The shortest relevant method is used. Do not simulate a full pipeline.

### 4. Development Active

Active department:

- Development.

Goal:

- resolve the active Development questions and produce a Department Cleared Creative Treatment Package.

Required controls:

- Adaptive Route;
- Evidence Obligation;
- Active Development input projections;
- active Development reference roles.

Downstream Editorial, Visual, and Production capabilities remain inactive.

Completion transition:

`Treatment Ready for Producer Review`.

### 5. Treatment Ready for Producer Review

Producer checks:

- project fidelity;
- process proportionality;
- capability and Department evidence;
- Treatment completeness;
- Evidence Obligation and public claim ceiling;
- Stage-Scoped Input integrity;
- Reference Contract, source, claim, and rights state;
- decision readiness.

Possible transitions:

- `Development Rework`;
- `Awaiting ECD Greenlight`.

### 6. Development Rework

Producer or Development Director returns the earliest failed Development artifact or professional question.

After correction and Department review, return to `Treatment Ready for Producer Review`.

### 7. Awaiting ECD Greenlight

A complete Greenlight Decision Object is visible and bound to current Project State.

All downstream work remains inactive.

Valid ECD responses:

- approve / Greenlight;
- approve with explicit modifications;
- revise;
- reject;
- pause.

An ambiguous response is interpreted conservatively as feedback, not approval. Producer updates the Treatment or asks one focused decision clarification only when no defensible interpretation exists.

If approved:

- record the authority;
- activate only Editorial input projections and reference roles;
- transition to `Editorial Active`.

### 8. Editorial Active

Active department:

- Editorial.

Goal:

- resolve active Editorial questions and produce a Department Cleared Creative Script Package.

Native-language and bilingual methods activate according to language, locale, and actual need.

Visual styling and Production remain inactive.

Completion transition:

`Script Ready for Producer Review`.

### 9. Script Ready for Producer Review

Producer checks:

- fidelity to Greenlight;
- minimum sufficient format and sequence;
- every required Frame Script;
- exact page and publication copy;
- native-language or bilingual evidence;
- factual, validation, source, attribution, and disclosure language;
- input and reference continuity;
- Department evidence and decision readiness.

Possible transitions:

- `Editorial Rework`;
- `Awaiting ECD Script Alignment`.

### 10. Editorial Rework

Return the earliest failed Editorial object or professional question: architecture, Frame Script, writing, native-language craft, transcreation, copy edit, proofread, or evidence language.

After correction and Department review, return to `Script Ready for Producer Review`.

### 11. Awaiting ECD Script Alignment

A complete Script Alignment Decision Object is visible and bound to Project State.

Visual and Production remain inactive.

If approved:

- record Script authority;
- activate only Visual input projections and reference roles;
- transition to `Visual Active`.

### 12. Visual Active

Active department:

- Visual.

Goal:

- resolve active Visual questions and produce full-sequence coverage when required, representative fidelity proof, and an Art Director-cleared Visual Development Package.

A single-image project receives full coverage of its one state, not an artificial multi-page process.

Representative exploratory or Production-intent proof may be created only under the Visual Stage Capability Matrix. Broad final Production remains inactive.

Completion transition:

- `Visual Ready for Producer Review`.

### 13. Visual Ready for Producer Review

Producer checks:

- Script fidelity;
- exact-copy use and language variants;
- full required state / sequence coverage;
- representative comps;
- typography and image direction;
- bounded reference transfer;
- Evidence Obligation and evidence integrity;
- Design Critique closure;
- target-width evidence;
- authority requirements.

Possible transitions:

- `Visual Rework`;
- `Awaiting ECD Visual Alignment`;
- `Production Active` only when no new governing visual decision requires ECD authority and existing authority already covers the package.

### 14. Visual Rework

Return the earliest failed Visual object or professional question: concept, sequence, page design, typography, image direction, reference transfer, evidence treatment, or critique closure.

After correction and Department review, return to `Visual Ready for Producer Review`.

### 15. Awaiting ECD Visual Alignment

A complete Visual Alignment Decision Object is visible and bound to Project State.

Broad final Production remains inactive.

If approved:

- record governing visual authority;
- activate only Production input projections, authorized assets, and Production reference roles;
- transition to `Production Active`.

### 16. Production Active

Active department:

- Production.

Goal:

- resolve active Production questions and produce final assets faithful to all authoritative upstream artifacts and contract conditions.

Completion transition:

`Final Package Ready for Sign-off`.

### 17. Final Package Ready for Sign-off

Required checks, to the depth required by the Deliverable Contract:

- Production Director review;
- Editorial Director final copy, language, claim, attribution, and evidence sign-off;
- Art Director final visual, reference-transfer, and evidence-treatment sign-off;
- Development Director re-review only when premise, Evidence Obligation, rights, or public claim changed;
- Producer integrated final review.

Possible transitions:

- `Production Rework`;
- upstream rework if final defects originated earlier;
- `Awaiting ECD Final Acceptance`.

### 18. Production Rework

Return to the earliest failed Production or upstream artifact. Preserve unaffected work.

After correction and required sign-offs, return to `Final Package Ready for Sign-off`.

### 19. Awaiting ECD Final Acceptance

A complete Final Acceptance Decision Object is visible and bound to Project State.

If accepted, transition to `Completed`.

### 20. Completed

Producer creates a Completion Record containing:

- final authoritative artifact chain;
- final assets;
- Adaptive Route and final complexity profile;
- Evidence Obligation and validation state;
- Stage-Scoped Input closure;
- Reference Records and final permitted uses;
- registered Skills actually used and omitted;
- ECD decisions;
- feedback closure;
- Department sign-offs;
- known limitations;
- publication state;
- reusable evaluation findings.

No further work occurs unless the project is reopened.

### 21. Reopened

A completed or approved artifact has been materially changed.

Producer identifies the earliest affected state and returns there. Later authority dependent on that artifact becomes stale until revalidated.

Update affected input projections, reference roles, Evidence Obligation, and complexity profile when necessary.

### 22. Blocked

Used only for a genuine missing authority, material information, source, rights, capability, validation, scope, or feasibility condition that cannot be solved internally or through a reversible assumption.

Producer states:

- exact blocker;
- why internal work cannot resolve it;
- earliest affected artifact;
- smallest ECD decision or input required;
- what remains valid;
- whether a narrower route or claim is available.

## Pending-decision binding

Project State may contain at most one formal pending ECD decision.

```markdown
Pending decision ID:
Decision type:
Artifact / version:
Approval scope:
Exclusions:
Consequence:
Released in assistant turn:
Status: awaiting ECD response
```

A reply can change authority only if it answers this record.

## Stop rule

In states 7, 11, 15, and 19, the assistant response ends at the ECD request. No downstream action occurs in the same turn.
