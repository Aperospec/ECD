# Authority and Decision Objects — V3.1

## Purpose

This contract prevents conversational approval from being confused with formal ECD authority.

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
- Awaiting Script Alignment
- Script Aligned
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

## Advisory acceptance is not project authority

Examples:

- `这个题目不错`
- `我认为可以`
- `就选这个`
- `继续`

After an Advisory Recommendation, these phrases may authorize Producer to develop a Treatment. They do not Greenlight a Treatment that has not been presented.

After a valid Greenlight Decision Object, the same phrases may constitute Greenlight because the pending object binds their meaning.

## Explicit waiver

The ECD may explicitly waive or combine a gate, but the waiver must name what is being waived.

Valid examples:

- `这次不需要 Treatment，直接把我提供的已确认脚本作为 Script Aligned 输入。`
- `视觉方向已经由我给定，跳过 Visual Alignment，只做忠实制作。`

Producer records:

- waived gate;
- authoritative substitute artifact;
- scope;
- risks;
- downstream consequence.

A generic request to `快一点`, `直接做`, or `继续` is not an explicit waiver.

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
- source, research, audience, platform, claims, rights, and factual boundaries as required;
- what the project is not;
- material alternatives considered when relevant;
- Development Director recommendation;
- Producer recommendation;
- exact scope becoming authoritative;
- Editorial stage consequence;
- explicit `ECD Greenlight` request.

## Script Alignment Decision Object

Required content:

- Overall Communication Logic;
- recommended format and number of pages / beats;
- every page or beat with:
  - `这页讲什么`;
  - `分镜脚本`;
  - `页面文案`;
- complete companion / publication copy;
- source, evidence, attribution, disclosure, and limitation language;
- Editorial Director recommendation;
- Producer recommendation;
- exact Script decisions becoming authoritative;
- visual decisions remaining Deferred;
- explicit `ECD Script Alignment` request.

The Script object must not contain binding palette, typeface, layout coordinates, camera, lighting, or image-style decisions. Semantic visual requirements are allowed when necessary to preserve meaning.

## Visual Alignment Decision Object

Required content:

- accepted Script conditions;
- visual problem and selected visual thesis;
- materially distinct routes considered when relevant;
- full-sequence coverage;
- representative high-fidelity page-class proofs;
- exact-copy typography and line behavior;
- image–type relationships;
- image direction and production-intent constraints;
- target-width / thumbnail / platform proof;
- Design Critique findings and closure;
- Art Director recommendation;
- Producer recommendation;
- proposed visual locks and tolerances;
- what remains for Production;
- explicit `ECD Visual Alignment` request.

## Final Acceptance Decision Object

Required content:

- directly accessible final assets or previews;
- deliverable and variant list;
- exact-copy verification;
- Editorial Director sign-off;
- Art Director sign-off;
- Production Director sign-off;
- technical and target-surface QA;
- provenance, attribution, claims, disclosure, and limitation state;
- authorized deviations;
- known limitations;
- Producer Final Review and recommendation;
- publication state;
- explicit `ECD Final Acceptance` request.

## Invalid decision request

A request is invalid when:

- the underlying artifact is incomplete;
- the complete proposal is hidden in an archive;
- Department or Producer clearance is merely asserted;
- the decision type is vague, such as `这版方向可以吗`;
- approval scope is absent;
- downstream work already occurred before the request;
- the response continues into the next phase after asking;
- multiple unrelated authority decisions are bundled without explicit ECD consent.

## Recovery

When an invalid request occurred:

1. withdraw the implied authority;
2. mark unauthorized downstream artifacts invalid for authority purposes;
3. return to the last valid state;
4. complete missing professional work and reviews;
5. issue a new named Decision Object;
6. wait for the ECD response.
