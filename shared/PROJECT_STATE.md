# Project State

## Purpose

Project State is Creative Producer's authoritative record of current phase, valid artifacts, active inputs, locks, open issues, and next valid action.

## State template

```markdown
# Project State

## Identity
Project ID:
Working title:
ECD / owner:
Created:
Last updated:
Complexity profile:

## Intake and contract
Original request / source:
Intended use:
Deliverable Contract:
Target language / locale:
Evidence obligation:
Entry point:
Material assumptions:
Material unknowns:

## Phase and owner
Phase: [Development / Awaiting Greenlight / Editorial / Awaiting Script Alignment / Visual Development / Awaiting Visual Alignment / Art Direction / Production / Final Review / Accepted]
Current professional owner:
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
| Artifact | Version / reference | Owner | State | Authority / dependency notes |
|---|---|---|---|---|
| Creative Treatment | | | | |
| Greenlight Record | | | | |
| Creative Script | | | | |
| Visual Problem Statement | | | | |
| Reference Reading / Transfer | | | | |
| Visual Metaphor Map | | | | |
| Concept Route | | | | |
| Storyboard / Visual Sequence Board | | | | |
| Anchor Keyframes | | | | |
| Representative Design Comp | | | | |
| Art Direction Package | | | | |
| Final Assets | | | | |
| Acceptance Record | | | | |

## Active locks
- Development:
- Editorial / copy:
- Visual:
- Production:

## ECD gate state
Pending decision:
Decision object and version:
ECD-facing presentation reference:
Decision scope:
Items outside this decision:
Decision evidence:
Resulting state:

## Open issues
- issue / first affected owner / consequence / blocking / recommended action

## Rework scope
Triggering feedback:
Earliest failed object:
Artifacts invalidated:
Artifacts still valid:
Next proof:

## Change log
- date / change / authority / consequence
```

## Compact state

Compact work may use a shorter record containing:

- project and deliverable;
- current phase and owner;
- authoritative artifact and version;
- active and Deferred inputs;
- current locks;
- open issue;
- next action;
- pending ECD gate.

## Transition requirements

### Development to Awaiting Greenlight

Requires a coherent Creative Treatment, sufficient evidence / rights resolution for the intended promise, complete ECD-facing presentation, and a clear decision request.

### Awaiting Greenlight to Editorial

Requires a valid Greenlight Record tied to the identified Treatment. Activate Editorial inputs only.

### Editorial to Visual Development

Requires a Creative Script Accepted for Handoff, Alignment-ready copy, resolved material Script Alignment, and explicit activation of Visual inputs.

### Visual Development to Art Direction

Requires a selected visual route, resolved sequence-level questions, representative anchor proof, and required visual alignment.

### Art Direction to Production

Requires an Art Direction Package Accepted for Handoff, resolved material visual decisions, and explicit activation of Production inputs.

### Production to Final Review

Requires all requested assets, variants, exact-copy checks, and QA records.

### Final Review to Accepted

Requires complete ECD-facing final presentation and ECD Final Acceptance when applicable.

## State QA

Reject or repair state when:

- more than one version of an artifact is treated as authoritative;
- a downstream artifact depends on a superseded upstream version;
- active and Deferred inputs are unclear;
- an ECD decision lacks an identifiable presentation object;
- a lock has no protected dimension or authority;
- broad production is active before representative visual proof;
- a rework request is assigned to the latest role rather than the earliest failed object.
