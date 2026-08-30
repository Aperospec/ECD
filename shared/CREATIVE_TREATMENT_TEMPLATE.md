# Creative Treatment Template

## Purpose

The Creative Treatment is the authoritative Development proposal that defines what the project is and why it deserves to enter Production.

It establishes the creative and editorial premise without prematurely deciding the final page sequence, audience-facing copy, Storyboard, layout, or Art Direction.

For raw or unresolved input, the Treatment must be presented to the ECD and accepted before Production. The response presenting it ends at the Greenlight request.

When the original brief spans multiple stages, use `STAGE_SCOPED_INPUT_REGISTER.md`. The Treatment contains only the **Development projection** of that material. Editorial, visual, and production projections remain Deferred.

## Cross-Stage Boundary

A source statement may matter to Development and a later craft stage at the same time.

Example:

```text
ECD: “建筑非常宏大，人很小。”

Development meaning allowed in Treatment:
The work should make the scale and breadth of a person's life perceptible.

Deferred Art Direction input:
Monumental architecture with a small human figure.
```

Do not place the exact visual technique in `Must preserve` unless the ECD explicitly made that technique a Development-level semantic condition. If it is a user-supplied downstream Hard Constraint, preserve it in the Stage-Scoped Input Register and activate it later without pretending Greenlight approved the entire visual solution.

Likewise, a reference supplied for “色调、画风” may be registered during Development as reference intent, but Art Director should perform the detailed palette / lighting / material / style extraction after visual activation.

## Deferred Input Notice

When useful, Creative Producer may show a concise notice immediately before the Greenlight request:

```markdown
## Deferred Inputs Recorded — Not Part of This Greenlight

Editorial:
- [source-faithful user direction; no final sequence interpretation]

Visual / Art Direction:
- [source-faithful visual preference or reference intent; no premature palette / composition extraction]

Production:
- [when relevant]
```

This notice reassures the ECD that downstream information was captured. It is **outside the authoritative Treatment body** and is not locked by Greenlight.

Do not populate the notice with assistant-invented downstream decisions.

## Compact Treatment

Use for a clear one-to-three-screen project or a user instruction that already contains much of the essential premise.

A concise Treatment is still a proposed object. It is not automatically Greenlit by the request to make the deliverable.

```markdown
# Creative Treatment

Project:
What is happening / what we are making:
Core creative or editorial premise:
Selected angle:
Core proposition:
Why it matters to the audience:
Audience should ultimately understand / feel / notice / reconsider:
Reality / imagination / evidence boundary:
Reference-use and rights boundary at Development level:
Must preserve semantically:
Must not imply or become:
Recommended communication direction at principle level:

## Deferred Inputs Recorded — Not Part of This Greenlight

Editorial:
Visual / Art Direction:
Production:

## Greenlight Request

Treatment version:
Recommendation: [Greenlight / revise / validate further / pause / reject]
What Greenlight will make authoritative:
What Greenlight will authorize next: Creative Script development
What remains unaccepted / Deferred after Greenlight:
Material condition, if any:
Decision requested from ECD: [Greenlight / revision / pause / rejection]
```

After presenting this request, stop. Do not append the Creative Script, final page sequence, Storyboard, visual proposal, image prompt, or generated asset.

## Standard / Extended Treatment

```markdown
# Creative Treatment

## 0. Project Definition

Working title:
Intended use:
Audience:
Publication context:

## 1. What the Project Is

Premise:
[Describe what is actually happening and what the work is about in complete, concrete language.]

Creative / editorial idea:
[The governing idea that gives the project identity.]

Selected angle:
[The specific lens through which the topic will be treated.]

Core proposition:
[The central statement the work will establish or invite the audience to imagine.]

## 2. Why It Deserves to Exist

What is genuinely interesting:
Why now / why this audience:
What is non-generic about this treatment:
What value, tension, transformation, evidence, or possibility carries the project:

## 3. Intended Audience Experience

The audience begins with:
The work should make them notice / understand / feel / compare / imagine / reconsider:
The audience should leave with:
Desired aftertaste or consequence:

## 4. Reality, Evidence, and Claim Boundary

Evidence obligation:
Verified facts relied upon:
Unresolved uncertainty:
Demonstration versus independently observed result:
Speculative or reconstructed elements:
Material public-claim limit:
Required limitation or disclosure:

## 5. Reference, Rights, and Asset Boundary — Development Level

Reference intent as supplied by ECD:
Rights / direct-use status:
Prohibited transfer:
Required attribution:
Asset ownership / license constraints:

Do not perform detailed Art Direction extraction here unless the detail itself is explicitly supplied and Development-relevant.

## 6. Creative Guardrails

The work must preserve semantically:
The work must not falsely imply:
The work must not become:
Clichés, generic framings, or misleading shortcuts to avoid:

Do not use this section to lock page count, exact scenes, palette, camera, typography, or composition merely because such ideas appeared in the raw brief. Register those under their later stage.

## 7. Production Consequence at Principle Level

Likely communication behavior:
[Do not write the final sequence. Indicate only the likely dominant behavior when useful.]

Material deliverable consequences:
Known production risks:
Questions that still require ECD authority before Greenlight:

## 8. Greenlight Recommendation

Recommendation: [Greenlight / revise / validate further / pause / reject]
Rationale:
Material conditions of Greenlight:

## 9. Deferred Inputs Recorded — Not Part of This Greenlight

Editorial inputs preserved:
- [source-faithful summary / input IDs]

Visual / Art Direction inputs preserved:
- [source-faithful summary / input IDs]

Production inputs preserved:
- [source-faithful summary / input IDs]

## 10. ECD Greenlight Request

Treatment version / reference:
What acceptance will make authoritative:
Authorized next stage if accepted: Editorial Director / Creative Script
Editorial input IDs that will activate after Greenlight:
Visual / Production input IDs that will remain Deferred:
What remains unaccepted after Greenlight:
Decision requested: [Greenlight / revision / pause / rejection]
```

## Presentation Rule

For raw or unresolved input:

1. decompose the full brief in the Stage-Scoped Input Register;
2. activate only Development projections;
3. present the complete Treatment at the appropriate depth;
4. optionally show a concise, source-faithful Deferred Input Notice;
5. state the recommendation and exact Greenlight consequence;
6. ask one concise decision question;
7. end the response.

Do not continue into formal scripting or visual production in the same response.

A later ECD reply may be concise when it clearly refers to this Treatment. Record the authorization under `GREENLIGHT_RECORD.md`.

The only exceptions to a new presentation turn are:

- an identifiable prior Greenlight;
- a stage-aware ECD instruction explicitly identifying supplied material as the final / approved Treatment and authorizing Production from it.

Generic requests to make, start, design, or directly produce the deliverable are not exceptions.

## Treatment QA

Before Greenlight, confirm:

- the topic has become a specific project premise;
- the angle and proposition are distinguishable;
- audience relevance is concrete rather than generic;
- reality, speculation, evidence, and claim limits are clear;
- reference intent is recorded without premature Art Direction interpretation;
- cross-stage statements were projected rather than flattened into the Treatment;
- later-stage user instructions are preserved as Deferred;
- Assistant Inference is distinguishable from user-supplied constraints;
- `Must preserve` contains Development-level meaning rather than unactivated visual technique;
- the Treatment states what the work must not imply or become;
- no unresolved issue would fundamentally change the project;
- the document has not drifted into final sequence, copy deck, Storyboard, palette, camera, typography, composition, or layout;
- the Treatment has a version or reference that can receive Greenlight;
- the Greenlight request authorizes Creative Script development next rather than immediate visual production;
- the response ends at the ECD decision rather than silently crossing into Production.
