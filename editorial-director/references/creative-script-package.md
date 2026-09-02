# Creative Script Package

## Purpose

The Creative Script converts a Greenlit Treatment and Activated Editorial inputs into a complete communication blueprint for Art Director.

It resolves Editorial meaning, concrete Frame content, semantic visual requirements, and audience language while leaving final visual craft open.

The studio maintains two representations:

1. **Internal Creative Script Package** — technically complete for professional control, self-QA, Producer Review, and handoff.
2. **ECD-facing Creative Script Proposal** — Producer Cleared, decision-complete, concrete, and easy to judge.

The two representations must agree on all material decisions and exact audience copy.

## Input gate

Require:

- Greenlit Treatment and Greenlight Record;
- Accepted Development Decisions;
- Deliverable Contract;
- Stage-Scoped Input Register;
- Activated Editorial inputs with source and authority;
- authoritative dependencies and Artifact Decision Contracts;
- target language and locale;
- Development locks and boundaries;
- Visual and Production inputs and capabilities still Deferred;
- valid existing Editorial work and feedback;
- Creative Producer assignment and acceptance criteria.

## Internal object model

For each page distinguish:

- **Function / Editorial Job** — why the page exists;
- **Audience Change** — what becomes newly understood or felt;
- **Internal Semantic Proposition** — exact meaning to preserve;
- **Frame Script** — what the audience will visibly encounter;
- **Written Visual Requirements** — semantic acceptance criteria for visual work;
- **Page Copy** — exact audience-facing language;
- **Transition** — why the next page is needed;
- **Input and Feedback Resolution** — control records.

These fields are not automatically exposed to the ECD.

## Artifact decision inheritance

The package records:

- authoritative upstream artifacts and versions;
- inherited Development decisions;
- new Editorial decisions;
- open or Deferred visual and production decisions;
- relevant delta from any prior authoritative Script;
- proposed changes that require upstream reopening;
- dependencies and tolerances.

Apply `../../shared/ARTIFACT_DECISION_CONTRACT.md`.

A Script cannot pass self-QA when it silently changes an inherited authoritative decision.

## Compact package

```markdown
# Creative Script — [version]

Project:
Greenlit Treatment:
Accepted Development Decisions:
Deliverable:
Language / locale:
Overall Communication Logic:
Sequence logic:

## Artifact Decision Contract
Inherited decisions:
New Editorial decisions:
Open / Deferred decisions:
Delta from prior Script:
Dependencies:
Authority consequence:

## Screen [number]
Function:
Editorial job:
Audience change:
Internal Semantic Proposition:
Frame Script:
Written Visual Requirements:
On-screen copy:
- title:
- Core Line:
- support / evidence / limitation:
Transition:
Activated Editorial inputs resolved:
Applicable feedback resolved:

## Companion Copy
Purpose:
Final draft:
Attribution / limitation:

## Editorial Self-QA
Upstream decision fidelity:
Sequence QA:
Frame Script QA:
Copy QA:
Evidence and limitation:
Deferred-stage integrity:
Known limitations:

## Specialist Return
Requested Producer disposition:
Required ECD authority:
```

## Standard / Extended package

```markdown
# Creative Script — [version]

## Source and State
Project:
Complexity / risk profile:
Treatment / Greenlight:
Accepted Development Decisions:
Deliverable Contract:
Stage-Scoped Input Register:
Artifact state:
Language / locale:
Activated Editorial inputs:
Deferred Visual inputs and capabilities:
Deferred Production inputs and capabilities:
Active boundaries:
Creative Producer assignment:

## Artifact Decision Contract
Authoritative upstream artifacts:
Inherited decisions:
Decisions introduced by this Script:
Open or Deferred decisions:
Dependencies:
Delta from prior authoritative Script:
Proposed upstream change:
Authority consequence:

## Script Core
[One concise statement describing the governing Editorial movement.]

## Overall Communication Logic
Dominant mode:
Supporting modes:
Opening promise:
Payoff:
Sequence logic:
Minimum sufficient beat count:
Why this structure:

## Language and Copy Direction
Copy Brief summary:
Voice and reader relationship:
Governing vocabulary / metaphor:
Exact terms:
Compression rules:
Copy Quality Gate status:

## Editorial Architecture
For each beat:
- number and role;
- primary Editorial job;
- audience change;
- relationship to previous and next beat;
- density intention;
- required evidence / limitation;
- Activated inputs served;
- applicable feedback served.

## Beat-by-Beat Script

### Beat [number]
Function:
Editorial job:
Audience change:
Communication mode:
Internal Semantic Proposition:

Frame Script:
[Concrete prose describing who or what appears, what visibly happens or changes, how the visible elements relate, and what the viewer can understand.]

Written Visual Requirements:
- required subject / action / state / evidence / relationship;
- semantic condition that must survive;
- continuity or limitation requirement;
- variables left to Art Director.

On-screen copy:
- display / page title:
- optional deck:
- Core Line / Beat Statement:
- supporting copy:
- evidence / source / limitation:

Approved meaning-preserving compression:
Transition:
Forbidden Editorial drift:
Activated inputs resolved:
Feedback items resolved:

## Companion / Body Copy
Purpose:
Complete final draft:
Required attribution / limitation:
Relationship to sequence:

## Input and Feedback Resolution
| Item | Source / authority | Script resolution | State | Consequence |
|---|---|---|---|---|

## Editorial Self-QA
Treatment and Development-decision fidelity:
Artifact delta:
Sequence progression:
Frame Script picture test:
Frame Script difference / continuity test:
Frame Script multiplicity test:
Written Visual Requirement quality:
Copy Quality Gate:
Evidence and limitation:
Deferred-stage integrity:
Known limitations:
Unresolved authority:

## Specialist Return to Creative Producer
Artifact / version:
Self-QA result:
Recommended Producer disposition:
Required ECD authority:
Open visual questions:
```

## ECD-facing rendering

The Editorial Director does not release directly to the ECD.

After Editorial self-QA, the internal package returns to Creative Producer. Creative Producer independently reviews and either returns it or renders a Producer Cleared proposal:

```markdown
# Creative Script — [version]

## Overall Communication Logic
[Plain-language explanation of how the complete piece communicates from opening to payoff.]

### Page [number] — [plain working label]

What this page says:
[Clear audience-facing purpose.]

Frame Script:
[Concrete visible scene, action, transformation, comparison, evidence state, or information relationship.]

Page Copy:
[Exact proposed audience-facing wording.]

Decision note:
[Only when a decision, delta, invention, evidence boundary, or conflict requires ECD authority.]

## Complete Companion / Body Copy
[Full draft]

## Relevant Delta and Feedback
[Only decision-relevant changes and applicable prior-feedback closure.]

## Alignment Scope
Confirming:
- Overall Communication Logic and page count;
- page meanings and order;
- Frame Scripts;
- exact page and body copy;
- disclosed inventions, claims, boundaries, and delta.

Still Deferred:
- final composition, camera, palette, lighting, style, typography, and layout;
- Storyboard, Anchors, Design Comp, Art Direction, and Production.

## Producer Recommendation
[Recommendation and known tradeoff.]

Decision requested:
```

## Script authority

Every new Creative Script requires explicit ECD Script Alignment.

A revision requires renewed alignment when its Artifact Decision Contract changes an ECD-approved decision.

A purely technical correction may retain prior authority only when Creative Producer verifies the delta is within an existing tolerance.

## Stage boundary

The Script decides proposed visible content through Frame Scripts and protects meaning through Written Visual Requirements.

It does not decide:

- final composition or placement;
- camera, lens, or crop;
- palette, light, material, or rendering style;
- typography, grid, spacing, or layout;
- final visual metaphor implementation;
- Storyboard panels;
- image-generation prompts;
- production rendering.

## Validation

Editorial self-QA passes when:

- the Greenlit project and Accepted Development Decisions remain intact;
- Activated Editorial inputs are resolved;
- each beat advances;
- every page has a concrete Frame Script;
- Written Visual Requirements preserve meaning without performing Art Direction;
- exact audience copy is Alignment-ready;
- body copy is complete when required;
- evidence and limitations have explicit locations;
- Artifact Decision Contract and delta are current;
- applicable feedback is resolved or reported;
- later-stage capabilities remain inactive;
- internal and ECD-facing representations can agree;
- the next action is Specialist Return to Creative Producer.

Producer Review and ECD authority remain separate required steps after Editorial self-QA.
