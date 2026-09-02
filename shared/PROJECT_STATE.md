# Project State

## Purpose

Project State is Creative Producer's authoritative record of current phase, active capabilities, valid artifacts, quality state, authority state, Producer Review, feedback closure, copy-aware readiness, locks, open issues, and next valid action.

## State template

```markdown
# Project State

## Identity
Project ID:
Working title:
Executive Creative Director:
Created:
Last updated:
Complexity / risk profile:

## Intake and contract
Original request / source:
Intended use:
Deliverable Contract:
Target language / locale:
Evidence obligation:
Entry point:
Consequential assumptions:
Material unknowns:

## Phase and capability state
Active phase:
Current specialist owner:
Current assignment:
Active capabilities:
Forbidden / Deferred capabilities:
Current objective:
Next valid action:

## Stage-scoped inputs
Register reference:
Active input IDs:
Deferred Editorial IDs:
Deferred Visual IDs:
Deferred Production IDs:
Conflicts:

## Artifact register
| Artifact | Version | Professional owner | Quality state | Authority state | Producer Review | Decision Contract / dependencies | Handoff Ready |
|---|---|---|---|---|---|---|---|
| Creative Treatment | | | | | | | |
| Greenlight Record | | | | | | | |
| Creative Script | | | | | | | |
| Visual Problem Statement | | | | | | | |
| Reference Reading / Transfer | | | | | | | |
| Visual Metaphor Map | | | | | | | |
| Concept Route | | | | | | | |
| Storyboard / Visual Sequence Board | | | | | | | |
| Copy-Aware Layout Maps | | Art Director | | | | | |
| Anchor Keyframes | | | | | | | |
| Representative Design Comp | | | | | | | |
| Representative Type-Fit Proof | | Art Director | | | | | |
| Art Direction Package | | | | | | | |
| Production-intent Image Assets | | Production Artist | | | | | |
| Final Type-Fit Proof | | Production Artist | | | | | |
| Final Assets | | | | | | | |
| Acceptance Record | | | | | | | |

## Copy-aware composition state
Exact-copy source and version:
Target geometry:
Required page classes / screens:
Layout Map coverage:
Exploratory image assets:
Production-intent image assets:
Representative Type-Fit state:
Final Type-Fit state:
Minimum readable thresholds:
Open copy–image conflict:
Earliest affected owner:
Production activation blocker:

## Current Producer Review
Artifact / version:
Specialist self-QA:
Review status:
Authority fidelity:
Artifact delta:
Stage validity:
Deliverable completeness:
Cross-artifact coherence:
Professional sufficiency:
Feedback closure:
Decision readiness:
Copy-aware production readiness:
Producer disposition:
Producer recommendation:
Required rework:
Next review action:

## ECD gate state
Pending decision:
Decision object and version:
Producer Review Record:
Producer recommendation:
ECD-facing presentation reference:
Decision delta:
Decision scope:
Items outside this decision:
Decision evidence:
Resulting authority state:
Resulting stage activation:

## Feedback resolution
| Feedback ID | Source | Affected artifact | Producer diagnosis | Assigned owner | Acceptance criteria | Status | Remaining consequence |
|---|---|---|---|---|---|---|---|

## Active locks
- Development:
- Editorial / copy:
- Visual:
- Copy-aware composition:
- Production:

## Open issues
- issue / earliest affected owner / authority owner / consequence / blocking / recommended action

## Rework scope
Triggering feedback:
Earliest failed object:
Artifacts reopened:
Artifacts invalidated:
Artifacts still valid:
Lowest-cost next proof:
Required authority:
Return owner:
Producer re-review condition:

## Change log
- date / change / authority / consequence
```

## Compact state

Compact work may use a shorter record containing:

- project and deliverable;
- current phase, assignment, and active capabilities;
- authoritative artifacts and versions;
- quality and authority state;
- Producer Review status and recommendation;
- active and Deferred inputs;
- exact-copy source and Layout Map / Type-Fit state when applicable;
- open feedback and issues;
- current locks;
- pending ECD gate;
- next valid action.

## Transition requirements

### Initialization to Development

Requires a valid route, Deliverable Contract, Stage-Scoped Input Register, Project State, assignment, and explicit active / Deferred capabilities.

### Development to Awaiting Greenlight

Requires:

- Development self-QA;
- Producer Cleared Treatment;
- complete ECD-facing Treatment;
- Producer recommendation;
- explicit Greenlight request.

### Awaiting Greenlight to Editorial

Requires explicit ECD Greenlight tied to the identified Treatment, recorded by Creative Producer. Activate Editorial capabilities only.

### Editorial to Awaiting Script Alignment

Requires:

- Editorial self-QA;
- Producer Cleared Creative Script;
- current Artifact Decision Contract;
- complete ECD-facing Script;
- Producer recommendation;
- explicit Script Alignment request.

### Awaiting Script Alignment to Visual Development

Requires explicit ECD alignment of the new Creative Script, recorded by Creative Producer. Activate Visual capabilities only.

A revision may retain prior authority only when Creative Producer verifies that its delta does not change an ECD-approved decision.

### Visual Development to visual proof readiness

Requires:

- Art Director self-QA;
- exact copy and target geometry;
- valid Copy-Aware Layout Maps for all Production-intent proof screens;
- explicit exploratory / Production-intent image classification;
- representative Anchor / Design Comp as needed;
- representative Type-Fit evidence;
- Producer Review.

### Visual Development to Production readiness

Requires:

- Producer Cleared visual direction and representative proof;
- required ECD visual authority for new or changed governing visual decisions;
- Producer Cleared Art Direction Package;
- valid Layout Map coverage for every Production-intent screen or applicable page class;
- representative Type-Fit pass;
- no blocking visual or copy–image feedback;
- explicit Production activation by Creative Producer.

### Production to Final Review

Requires:

- all requested assets and variants;
- Production self-QA;
- traceable Production-intent image compliance;
- exact-copy checks;
- final Type-Fit Proof at target conditions;
- mobile QA and technical QA;
- current dependencies;
- return to Creative Producer.

### Final Review to Awaiting Final Acceptance

Requires Producer Cleared final package, complete feedback closure, valid Layout Map and Type-Fit evidence, complete ECD-facing final presentation, and Producer recommendation.

### Awaiting Final Acceptance to Accepted

Requires explicit ECD Final Acceptance recorded by Creative Producer.

## State QA

Reject or repair state when:

- active capabilities are not explicit;
- more than one artifact version is authoritative;
- a downstream artifact depends on a superseded upstream version;
- a formal artifact lacks an Artifact Decision Contract;
- Specialist QA, Producer clearance, and ECD authority are conflated;
- a Producer Review disposition is missing;
- applicable ECD feedback lacks closure state;
- an ECD decision lacks a complete presentation or recommendation;
- a Production-intent image lacks Layout Map coverage;
- an Exploratory image is treated as final-use without reclassification and proof;
- exact-copy Type-Fit evidence is missing;
- broad Production is active before required visual authority and copy-aware readiness;
- a rework request is assigned to the latest role rather than the earliest failed object;
- anyone other than Creative Producer activates the next stage.
