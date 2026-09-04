# Runtime State Machine — V3.2

## Purpose

This state machine determines what work may exist, what decision is pending, and which capabilities are active.

Conversational momentum does not change state. Only Creative Producer may update Project State, and only valid evidence may justify the update.

Apply:

- `ADAPTIVE_ROUTING.md` before choosing a route;
- `HIGH_LEVERAGE_DECISIONS.md` before dependent elaboration;
- `DECISION_RESOLUTION_PROTOCOL.md` whenever the ECD replies to a current Pending Decision Object.

A decision-request turn stops; an approved decision-resolution turn advances.

## States

### 0. Uninitialized

No project record exists.

Allowed:

- receive request;
- inspect available materials and prior artifacts;
- infer reversible conditions;
- determine entry mode and latest valid artifact;
- identify materially consequential questions;
- classify social sources as Discovery Signal, Factual Dependency, or Direct-use Material when applicable.

Before entering a decision-bearing project state, Producer creates or validates:

- Deliverable Contract;
- Adaptive Route Record and complexity / risk profile;
- preliminary High-Leverage Decision Record;
- Evidence Obligation Record;
- Stage-Scoped Input Register;
- Source / Reference Records;
- Concept Reframing Record when applicable;
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
- engagement-signal reading;
- concise rationale;
- account / audience / novelty comparison;
- provisional source posture, Evidence Obligation, or reference note;
- next valid action.

Forbidden:

- claiming a Creative Treatment exists;
- claiming Development Department clearance;
- requesting Greenlight;
- treating a positive reaction as Greenlight;
- writing the final social post unless explicitly requested as a narrow Craft-only task;
- writing a formal Core Communication Script;
- making binding Editorial or Visual decisions.

Output label:

`Advisory Recommendation — not a Creative Treatment or approval object`

If the user accepts the recommendation and asks to make the work, Producer initializes the project controls and transitions to `Development Active`.

### 2. Continuation Validation

Used when the user supplies or references an existing Treatment, Core Communication Script, Creative Script, visual direction, final package, or localized correction.

Producer verifies:

- artifact identity and version;
- professional quality and prior authority evidence;
- dependencies and stale state;
- unresolved feedback;
- active profile and Deliverable Contract;
- High-Leverage Decision Record and Core Script gate mode;
- Evidence Obligation;
- source posture, input, and reference records;
- correct shortest next state.

Missing authority does not get inferred. Valid existing work is reused. If validation fails, return only to the earliest invalid state.

Possible next states:

- `Development Active`;
- `Core Communication Script Active`;
- `Editorial Adaptation Active`;
- `Visual Active`;
- `Production Active`;
- a bounded Rework state;
- `Craft-only Task`;
- `Blocked`.

#### V3.1-to-V3.2 recovery

When a Greenlit project already has a page-level Creative Script but no Core Script authority:

- preserve the Greenlit Treatment and source / evidence work;
- extract the actual proposed progression into a Core Communication Script candidate;
- assess dependency and leverage;
- if Separate Alignment is required, mark page architecture, Frame Scripts, and copy `provisional / dependent on unaligned Core Script`;
- present the Core Script Alignment object before Visual work;
- reuse any downstream material that remains valid after Core Script approval rather than discarding it automatically.

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

- resolve active Development questions and produce a Department Cleared Creative Treatment Package.

Required controls:

- Adaptive Route;
- preliminary High-Leverage assessment;
- Evidence Obligation;
- Concept Reframing source posture when applicable;
- Active Development input projections;
- active Development reference roles.

Downstream Core Script, Editorial Adaptation, Visual, and Production capabilities remain inactive.

Completion transition:

`Treatment Ready for Producer Review`.

### 5. Treatment Ready for Producer Review

Producer checks:

- project fidelity;
- process proportionality;
- capability and Department evidence;
- Treatment completeness;
- source posture and independent concept position;
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

A complete Treatment Greenlight Decision Object is visible and bound to current Project State.

All downstream work remains inactive until the ECD resolves this pending object.

Valid ECD responses:

- approve / Greenlight;
- approve with explicit modifications;
- revise;
- reject;
- pause.

An ambiguous response is interpreted conservatively as feedback, not approval.

If approved:

- record Greenlight;
- close the Pending Decision ID;
- activate Core Script input projections and relevant Editorial reference roles;
- transition to `Core Communication Script Active`;
- continue internal Core Script work immediately until a required Core Script Alignment object, a valid low-dependency continuation to Editorial Adaptation, or a genuine blocker.

An acknowledgement-only stop after Greenlight is invalid when Core Script work can proceed.

### 8. Core Communication Script Active

Active department:

- Editorial, limited to the Core Communication Script question.

Goal:

- produce the actual end-to-end communication progression;
- determine and justify the Core Script gate mode;
- keep dependent page adaptation inactive when Separate Alignment is required.

Allowed Skills, proportionately:

- Editorial Director;
- Core Communication Script;
- Copy Editing or native-language craft only when needed to assess the script itself.

Completion transition:

`Core Script Ready for Producer Review`.

### 9. Core Script Ready for Producer Review

Producer checks:

- fidelity to the Greenlit Treatment;
- whether the actual progression is directly judgeable;
- opening, progression, decisive shift, and payoff;
- speaker / reality / source position;
- essential versus adaptable beats;
- source independence in Concept Reframing;
- dependency fan-out and invalidation risk;
- gate mode validity;
- Department evidence.

Possible transitions:

- `Core Script Rework`;
- `Awaiting ECD Core Script Alignment` when Separate Alignment is required;
- `Editorial Adaptation Active` when gate mode is Combined, Existing Aligned, or Not Applicable and the route is valid.

### 10. Core Script Rework

Return the actual progression to `ecd-core-communication-script` or another earliest affected Editorial method.

Dependent page architecture, Frame Scripts, exact copy, and Visual work remain inactive when Separate Alignment is required.

After correction and Department review, return to `Core Script Ready for Producer Review`.

### 11. Awaiting ECD Core Script Alignment

A complete Core Script Alignment Decision Object is visible and bound to Project State.

Page architecture, Frame Scripts, exact copy, publication copy, Visual, and Production remain inactive until the ECD resolves the object.

If approved:

- record Core Script authority;
- close the Pending Decision ID;
- activate Editorial Adaptation inputs;
- transition to `Editorial Adaptation Active`;
- continue immediately to the complete Creative Script Alignment object or a genuine blocker.

An acknowledgement-only stop after Core Script Alignment is invalid when Editorial Adaptation can proceed.

### 12. Editorial Adaptation Active

Active department:

- Editorial.

Entry requires:

- Core Script Aligned;
- or valid Combined with Creative Script Alignment mode;
- or Existing Aligned;
- or Not Applicable for the bounded task.

Goal:

- map approved Core Script beats into the minimum sufficient format;
- produce Frame Scripts, exact page copy, publication copy, and a Department Cleared Creative Script Package.

Native-language and bilingual methods activate according to language, locale, and actual need.

Visual styling and Production remain inactive.

Completion transition:

`Creative Script Ready for Producer Review`.

### 13. Creative Script Ready for Producer Review

Producer checks:

- fidelity to Greenlight and Core Script;
- gate mode validity;
- Core Script beat-to-page mapping;
- minimum sufficient format and sequence;
- every required Frame Script;
- exact page and publication copy;
- native-language or bilingual evidence;
- factual, validation, source, attribution, and disclosure language actually required;
- absence of unnecessary source / testing / concept disclaimers;
- input and reference continuity;
- Department evidence and decision readiness.

Possible transitions:

- `Editorial Adaptation Rework`;
- `Awaiting ECD Creative Script Alignment`.

### 14. Editorial Adaptation Rework

Return the earliest failed Editorial object or professional question:

- Core Script, if the actual progression changed;
- Content Architecture;
- Frame Script;
- writing;
- native-language craft;
- transcreation;
- copy edit;
- proofread;
- evidence or source language.

After correction and Department review, return to the appropriate Core Script or Creative Script review state.

### 15. Awaiting ECD Creative Script Alignment

A complete Creative Script Alignment Decision Object is visible and bound to Project State.

Visual and Production remain inactive until the ECD resolves this pending object.

The object must show:

- separately aligned Core Script reference, or the distinct Core Script section included in the combined decision scope;
- adaptation logic;
- every page / beat with `这页讲什么 / 分镜脚本 / 页面文案`;
- complete publication copy.

If approved:

- record Creative Script authority and, for a valid combined route, Core Script authority within the named combined scope;
- close the Pending Decision ID;
- activate only Visual input projections and reference roles;
- transition to `Visual Active`;
- continue Visual work immediately until the next complete ECD Decision Object, an already-authorized Production transition, or a genuine blocker.

An acknowledgement-only stop after Creative Script Alignment is invalid when Visual work can proceed.

### 16. Visual Active

Active department:

- Visual.

Goal:

- resolve active Visual questions and produce full-sequence coverage when required, representative fidelity proof, and an Art Director-cleared Visual Development Package.

A single-image project receives full coverage of its one state, not an artificial multi-page process.

Representative exploratory or Production-intent proof may be created only under the Visual Stage Capability Matrix. Broad final Production remains inactive.

Completion transition:

`Visual Ready for Producer Review`.

### 17. Visual Ready for Producer Review

Producer checks:

- Treatment, Core Script, and Creative Script fidelity;
- exact-copy use and language variants;
- full required state / sequence coverage;
- representative comps;
- typography and image direction;
- bounded reference transfer and Concept Reframing independence;
- Evidence Obligation and evidence integrity;
- Design Critique closure;
- target-width evidence;
- authority requirements.

Possible transitions:

- `Visual Rework`;
- `Awaiting ECD Visual Alignment`;
- `Production Active` only when no new governing visual decision requires ECD authority and existing authority already covers the package.

### 18. Visual Rework

Return the earliest failed Visual object or professional question: concept, sequence, page design, typography, image direction, reference transfer, source-specific imitation, evidence treatment, or critique closure.

After correction and Department review, return to `Visual Ready for Producer Review`.

### 19. Awaiting ECD Visual Alignment

A complete Visual Alignment Decision Object is visible and bound to Project State.

Broad final Production remains inactive until the ECD resolves this pending object.

If approved:

- record governing visual authority;
- close the Pending Decision ID;
- activate only Production input projections, authorized assets, and Production reference roles;
- transition to `Production Active`;
- continue Production work immediately until the complete Final Acceptance Decision Object or a genuine blocker.

An acknowledgement-only stop after Visual Alignment is invalid when Production can proceed.

### 20. Production Active

Active department:

- Production.

Goal:

- resolve active Production questions and produce final assets faithful to all authoritative upstream artifacts and contract conditions.

Completion transition:

`Final Package Ready for Sign-off`.

### 21. Final Package Ready for Sign-off

Required checks, to the depth required by the Deliverable Contract:

- Production Director review;
- Editorial Director final Core Script, page copy, language, claim, attribution, and evidence sign-off;
- Art Director final visual, reference-transfer, originality, and evidence-treatment sign-off;
- Development Director re-review only when premise, Evidence Obligation, rights, source posture, or public claim changed;
- Producer integrated final review.

Possible transitions:

- `Production Rework`;
- upstream rework if final defects originated earlier;
- `Awaiting ECD Final Acceptance`.

### 22. Production Rework

Return to the earliest failed Production or upstream artifact. Preserve unaffected work.

After correction and required sign-offs, return to `Final Package Ready for Sign-off`.

### 23. Awaiting ECD Final Acceptance

A complete Final Acceptance Decision Object is visible and bound to Project State.

If accepted:

- record Final Accepted;
- close the Pending Decision ID;
- transition to `Completed`;
- create the Completion Record in the same assistant response;
- return a concise completion acknowledgement and deliverable summary.

### 24. Completed

Producer creates a Completion Record containing:

- final authoritative artifact chain;
- final assets;
- Adaptive Route and final complexity profile;
- High-Leverage Decision Record and Core Script authority;
- Evidence Obligation and validation state;
- Concept Reframing / source posture;
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

### 25. Reopened

A completed or approved artifact has been materially changed.

Producer identifies the earliest affected state and returns there. Later authority dependent on that artifact becomes stale until revalidated.

Examples:

- premise / angle changes → Development;
- actual communication progression changes → Core Communication Script;
- page mapping, Frame Script, or exact copy changes → Editorial Adaptation;
- visual design changes → Visual;
- implementation-only change → Production.

Update affected input projections, source posture, reference roles, Evidence Obligation, and complexity profile when necessary.

### 26. Blocked

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

## Decision request stop rule

In states 7, 11, 15, 19, and 23, the assistant response that releases the Decision Object and asks the ECD to decide ends at the request. No dependent downstream action occurs in that request turn.

This rule does not authorize a second stop after the ECD resolves the object.

## Decision resolution continuation rule

When the ECD later resolves the current Pending Decision Object:

- approval or approval-with-bounded-modifications triggers the state transition and autonomous internal continuation defined in `DECISION_RESOLUTION_PROTOCOL.md`;
- revise triggers targeted rework and re-release of the corrected object;
- reject prevents the rejected consequence from activating;
- pause records a paused state;
- ambiguous authority-changing replies receive at most one focused clarification.

Except for Final Acceptance, an approved resolution should normally produce the next genuine ECD Decision Object in the same assistant response, not an acknowledgement-only message.
