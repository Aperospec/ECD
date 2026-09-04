# Authority and Decision Objects — V3.2

## Purpose

This contract prevents conversational approval from being confused with formal ECD authority, separates Core Communication Script authority from page adaptation, and defines what must happen once a valid pending decision is resolved.

Apply:

- `HIGH_LEVERAGE_DECISIONS.md` to decide whether Core Script needs a separate gate;
- `DECISION_RESOLUTION_PROTOCOL.md` after the ECD replies to a current Pending Decision Object.

## Authority states

### Professional quality

- Working
- Specialist Return Ready
- Department Review Pending
- Department Rework
- Department Cleared
- Producer Review Pending
- Producer Rework
- Producer Cleared

### ECD authority

- No ECD authority
- Awaiting Greenlight
- Greenlit
- Awaiting Core Script Alignment
- Core Script Aligned
- Awaiting Creative Script Alignment
- Creative Script Aligned
- Awaiting Visual Alignment
- Visual Aligned
- Awaiting Final Acceptance
- Final Accepted
- Reopened
- Superseded
- Invalid / Unauthorized

Professional quality and ECD authority are separate. No state in one dimension implies a state in the other.

## Valid authority change

An ECD authority state changes only when all conditions are true:

1. Project State contains one current `Pending decision ID`.
2. The immediately preceding ECD-facing response contains a complete Decision Object with the same ID, artifact, version, decision type, scope, exclusions, and consequence.
3. The proposal was Department Cleared and Producer Cleared.
4. The user response can reasonably be interpreted as accepting, modifying, rejecting, pausing, or returning that exact object.
5. Creative Producer records the interpretation and resulting authority state.

If any condition is missing, no formal approval exists.

## Decision request versus decision resolution

A Decision Object release and the ECD's later response are different runtime events.

### Request event

The assistant releases the complete Decision Object, registers the Pending Decision ID, asks the ECD to decide, and stops that assistant turn.

### Resolution event

The ECD replies in a later user turn. Producer resolves the pending object.

If approved, Producer records the authority, activates the next valid state, and continues internal work according to `DECISION_RESOLUTION_PROTOCOL.md` until the next complete ECD Decision Object or a genuine blocker.

An acknowledgement-only approval response is not a valid project advance when newly authorized internal work can proceed.

## Advisory acceptance is not project authority

Examples:

- `这个题目不错`
- `我认为可以`
- `就选这个`
- `继续`

After an Advisory Recommendation, these phrases may authorize Producer to develop a Treatment. They do not Greenlight a Treatment that has not been presented.

After a valid Decision Object, the same phrases may constitute approval because the pending object binds their meaning.

## Explicit waiver or combination

The ECD may explicitly waive or combine a gate, but the waiver or combination must name what is being changed.

Valid examples:

- `这次不需要 Treatment，直接把我提供的已确认脚本作为 Core Script Aligned 输入。`
- `这个单页项目把 Core Script 和 Creative Script 放在同一个 Alignment 对象里确认。`
- `视觉方向已经由我给定，跳过 Visual Alignment，只做忠实制作。`

Producer records:

- waived or combined gate;
- authoritative substitute artifact;
- scope;
- dependency / invalidation risk;
- downstream consequence.

A generic request to `快一点`, `直接做`, or `继续` is not an explicit waiver.

Producer may select a combined Core Script + Creative Script gate without a separate user instruction only when the High-Leverage Decision Record establishes genuinely low dependency. The combined object must visibly separate the Core Script from page adaptation and state that both are in scope.

## Decision Object Standard

Every formal ECD Decision Object contains:

```markdown
Decision ID:
Decision type:
Artifact / version:
Current state:

Complete proposal:

Department Director recommendation:
Creative Producer recommendation:

Relevant alternatives or tradeoff:
Delta from last authoritative version:
Prior feedback closure:

Approval scope:
What remains open / Deferred:
Consequence if approved:

Decision requested:
```

The object must be understandable in the primary conversation without reconstructing internal worksheets.

## Greenlight Decision Object

Required content:

- One-Sentence Creative Core;
- complete Creative Treatment;
- independent angle and governing proposition;
- source posture, research, audience, platform, claims, rights, and factual boundaries as required;
- what the project is not;
- material alternatives considered when relevant;
- Development Director recommendation;
- Producer recommendation;
- exact scope becoming authoritative;
- consequence: Core Communication Script development, not page adaptation;
- explicit `ECD Greenlight` request.

Greenlight confirms that the project and concept deserve further development. It does not approve the actual end-to-end communication progression unless that progression was explicitly included in the named Greenlight scope.

If approved, Producer activates Core Communication Script work and autonomously advances according to the recorded gate mode.

## Core Script Alignment Decision Object

Required when the High-Leverage Decision Record selects Separate Alignment.

Required content:

- Greenlit Treatment reference;
- communication form;
- audience movement;
- actual complete Core Communication Script, not a synopsis;
- opening;
- consequential progression;
- decisive shift, discovery, comparison, explanation, synthesis, or payoff;
- ending / consequence / aftertaste;
- speaker and reality position;
- source posture and Concept Reframing consequence when applicable;
- essential beats;
- adaptable examples, expressions, and order tolerance;
- material alternatives considered;
- Editorial Director recommendation;
- Producer recommendation;
- exact Core Script decisions becoming authoritative;
- page count, page mapping, Frame Scripts, exact copy, publication copy, and visual decisions remaining Deferred;
- explicit `ECD Core Script Alignment` request.

If approved, Producer activates Editorial Adaptation and autonomously advances to the Creative Script Alignment object unless blocked.

## Combined Core Script + Creative Script Alignment

Allowed only under a valid low-dependency route.

The ECD-facing object must present in this order:

1. the distinct Core Communication Script;
2. the reason separate alignment was not necessary;
3. the page / state adaptation;
4. every Frame Script and exact page copy;
5. complete publication copy;
6. separate approval scope for Core Script and adaptation.

Approval grants both `Core Script Aligned` and `Creative Script Aligned` authority for the named versions and scope.

## Creative Script Alignment Decision Object

Required content:

- Core Communication Script reference and authority, or the distinct Core Script section in a valid combined object;
- Overall Adaptation Logic;
- recommended format and number of pages / beats;
- Core Script beat-to-page mapping;
- every page or beat with:
  - `这页讲什么`;
  - `分镜脚本`;
  - `页面文案`;
- complete companion / publication copy;
- source, evidence, attribution, disclosure, and limitation language only where materially required;
- Editorial Director recommendation;
- Producer recommendation;
- exact adaptation and copy decisions becoming authoritative;
- visual decisions remaining Deferred;
- explicit `ECD Creative Script Alignment` request.

The Creative Script object must not contain binding palette, typeface, layout coordinates, camera, lighting, or image-style decisions. Semantic visual requirements are allowed when necessary to preserve meaning.

For Concept Reframing using Discovery Signal only, the object must not automatically add creator attribution, source explanation, `未实测`, concept-art disclaimer, or productization language.

If approved, Producer activates Visual and autonomously advances until the next required Visual Alignment object, an already-authorized Production transition, or a blocker.

## Visual Alignment Decision Object

Required content:

- accepted Treatment, Core Script, and Creative Script conditions;
- visual problem and selected visual thesis;
- materially distinct routes considered when relevant;
- full-sequence coverage;
- representative high-fidelity page-class proofs;
- exact-copy typography and line behavior;
- image–type relationships;
- image direction and Production-intent constraints;
- target-width / thumbnail / platform proof;
- Design Critique findings and closure;
- Concept Reframing originality and source-specific expression exclusions when applicable;
- Art Director recommendation;
- Producer recommendation;
- proposed visual locks and tolerances;
- what remains for Production;
- explicit `ECD Visual Alignment` request.

If approved, Producer activates Production and autonomously advances to the Final Acceptance object unless blocked.

## Final Acceptance Decision Object

Required content:

- directly accessible final assets or previews;
- deliverable and variant list;
- exact-copy verification;
- Editorial Director sign-off on Core Script and final language;
- Art Director sign-off;
- Production Director sign-off;
- technical and target-surface QA;
- provenance, attribution, claims, disclosure, and limitation state only as applicable;
- Concept Reframing source posture and originality state when applicable;
- authorized deviations;
- known limitations;
- Producer Final Review and recommendation;
- publication state;
- explicit `ECD Final Acceptance` request.

If approved, Producer records `Final Accepted`, creates the Completion Record, and returns a concise completion acknowledgement. No further creative stage is activated unless reopened.

## Invalid decision request

A request is invalid when:

- the underlying artifact is incomplete;
- the complete proposal is hidden in an archive;
- Department or Producer clearance is merely asserted;
- the decision type is vague, such as `这版方向可以吗`;
- approval scope is absent;
- a required high-leverage Core Script gate was skipped;
- dependent page work was produced before required Core Script authority;
- downstream work already occurred before the request;
- the response continues into the next phase after asking;
- multiple unrelated authority decisions are bundled without explicit or protocol-valid combination.

## Invalid decision resolution

A decision resolution is invalid when:

- approval is inferred without a current Pending Decision ID;
- the pending object is not the object the user is responding to;
- a bounded modification is silently expanded into a broader authority change;
- Producer records approval but fails to activate the consequence named in the approved object;
- Producer stops with an acknowledgement-only response even though the newly authorized internal stage can proceed;
- Producer requires the ECD to say `继续` or name the next role after a valid approval.

## Recovery

When an invalid request occurred:

1. withdraw the implied authority;
2. mark unauthorized downstream artifacts invalid or provisional for authority purposes;
3. return to the last valid state or earliest unconfirmed high-leverage decision;
4. preserve unaffected Treatment, source, evidence, and other valid work;
5. complete missing professional work and reviews;
6. issue a new named Decision Object;
7. wait for the ECD response.

When a valid approval occurred but the runtime stalled after acknowledgement:

1. preserve the valid approval and authority already granted;
2. do not ask the ECD to approve again;
3. activate the consequence already named in the Decision Object;
4. resume the correct next internal stage;
5. continue to the next ECD Decision Object or genuine blocker;
6. record the stall as a runtime-conformance defect.
