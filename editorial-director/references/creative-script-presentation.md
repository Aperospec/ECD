# ECD-Facing Creative Script Presentation

## Purpose

This protocol defines how Creative Producer presents a Producer Cleared Creative Script for ECD Script Alignment.

The internal Creative Script Package may contain professional terminology, decision contracts, input IDs, detailed QA, and handoff records.

The ECD-facing proposal converts that backstage complexity into a complete creative decision object.

## Preconditions

Before release:

- Editorial self-QA passed;
- the complete internal package exists;
- Artifact Decision Contract and dependencies are current;
- applicable feedback has closure states;
- Creative Producer independently reviewed the package;
- Producer disposition is `Producer Cleared`;
- Visual capabilities remain inactive.

A failed precondition returns internally.

## Core principle

> Backstage completeness; frontstage clarity; Producer-controlled release.

The ECD should be able to understand:

- how the whole piece communicates;
- what every page is meant to say;
- what every page is expected to visibly contain;
- what exact words the audience will read;
- what changed from the last authoritative version;
- whether prior feedback was resolved;
- what this decision accepts;
- what remains for Art Director;
- what Creative Producer recommends.

## Mandatory visible order

1. **Overall Communication Logic / 整体怎么讲**
2. **Complete Page-by-Page Proposal**
3. **Complete Companion / Body Copy**
4. **Relevant Delta and Feedback Closure**
5. **Alignment Scope and Deferred Visual Scope**
6. **Producer Recommendation**
7. **Decision Request**

## 1. Overall Communication Logic

Begin with a short, connected explanation of the complete progression.

Tell the ECD:

- where the audience begins;
- what sequence of discoveries, events, explanations, comparisons, demonstrations, or transformations follows;
- where the payoff occurs;
- why the proposed number of pages is sufficient;
- which communication mode governs the structure when this materially helps judgment.

Do not call every progression a narrative. Chronology is used only when the accepted meaning depends on time or event sequence.

## 2. Complete page-by-page proposal

Present every proposed page in order.

Each page normally contains three sections:

```markdown
### Page [number] — [plain working label]

What this page says / 这页讲什么
[One clear paragraph explaining the audience-facing purpose.]

Frame Script / 分镜脚本
[Concrete prose describing who or what appears, what visibly happens or changes, how the elements relate, and what the audience can infer.]

Page Copy / 页面文案
[All exact proposed audience-facing text.]
```

Add a fourth section only when needed:

```markdown
Decision note / 特别需要确认
[A decision, invention, claim, boundary, delta, or conflict requiring ECD authority.]
```

### What this page says

This is the plain-language page purpose. It should make sense without Function, Editorial Job, or Audience Change labels.

### Frame Script

The Frame Script is mandatory.

It must let the ECD picture the proposed visible content before Art Direction begins.

It describes:

- subjects or information objects;
- actions, changes, handoffs, comparisons, evidence, or relationships;
- the visible event or information state that makes meaning perceptible;
- continuity with a shared project, object, process, person, system, or world when required.

It remains open on composition, camera, palette, style, typography, and layout.

An abstract statement of intended understanding is not a Frame Script.

### Page Copy

Show the exact proposed wording and meaningful hierarchy.

Do not expose Copy Desk worksheets.

## Fields that stay backstage

Do not show these by default on every page:

- Function;
- Editorial Job;
- Audience Change;
- Communication Mode per beat;
- Internal Semantic Proposition;
- Written Visual Requirements;
- transition bookkeeping;
- input IDs and authority classes;
- Artifact Decision Contract;
- scoring worksheets;
- detailed QA;
- handoff metadata.

Surface one only when it creates a decision the ECD must understand, translated into ordinary language.

## 3. Companion / Body Copy

When required, show the complete proposed draft in the primary conversation.

The ECD should not need to open an archive to read publication text.

## 4. Relevant delta and feedback closure

For a first Script, disclose significant inventions, claims, examples, or boundaries that require acceptance.

For a revision, summarize only decision-relevant delta:

- added;
- refined;
- changed;
- removed;
- authority consequence.

State whether applicable prior ECD feedback is:

- Resolved;
- Partially Resolved;
- Conflict;
- Superseded;
- Open.

Do not resubmit a known unresolved defect as if it were closed.

## 5. Alignment scope

State what Script Alignment accepts:

- Overall Communication Logic and page count;
- page order and meanings;
- every Frame Script;
- exact on-screen copy;
- complete companion / body copy;
- disclosed inventions, claims, evidence, limitations, boundaries, and delta.

State what remains outside the decision:

- final composition and placement;
- camera, perspective, crop, and scale treatment;
- color, lighting, material, and visual style;
- typography, grid, spacing, and layout;
- Storyboard;
- Anchor Keyframes;
- Representative Design Comp;
- Art Direction Package;
- final image and asset production.

Explain the consequence: Creative Producer may record Script authority and activate Visual inputs only after explicit ECD alignment.

## 6. Producer recommendation

Creative Producer states:

- review result: Producer Cleared;
- recommended decision;
- main reason;
- known tradeoff or limitation;
- whether applicable prior feedback is closed.

The recommendation is not ECD approval.

## 7. Decision request

End with one explicit request:

- align the Script;
- revise a named page or section;
- pause;
- return to Development;
- reject.

Do not begin visual work in the same response.

## Script authority

Every new Creative Script requires explicit ECD Script Alignment.

A revision requires renewed alignment when it changes an ECD-approved decision.

A non-decision technical correction may retain authority only after Creative Producer verifies its delta and tolerance.

## Internal package synchronization

The internal package and ECD-facing proposal must agree on:

- authoritative upstream decisions;
- Overall Communication Logic;
- page count and order;
- page meaning;
- Frame Scripts;
- exact audience copy;
- body copy;
- material inventions, evidence, limitations, and boundaries;
- relevant delta;
- Alignment scope.

## Presentation QA

Before release, Creative Producer confirms:

- the underlying artifact is Producer Cleared;
- Overall Communication Logic is understandable without workflow terminology;
- every proposed page is visible;
- every page includes page purpose, concrete Frame Script, and exact copy;
- the ECD can picture each page before Art Direction;
- complete body copy is visible when required;
- relevant delta and feedback closure are explicit;
- Producer recommendation is explicit;
- Alignment and Deferred Visual scopes are exact;
- no attachment is required to understand the proposal;
- Visual capabilities remain inactive;
- the response ends at the decision request.

## Failure recovery

If a previous proposal was incomplete, abstract, internally cluttered, professionally weak, or released without Producer Review:

1. withdraw the Alignment request;
2. keep Visual capabilities inactive;
3. return the earliest failed object for correction;
4. preserve valid Editorial work;
5. rerun Editorial self-QA and Producer Review;
6. synthesize a new presentation version;
7. request Script Alignment again.
