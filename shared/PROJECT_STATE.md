# Project State

## Purpose

Project State is Creative Producer's authoritative record of where the work is, what is valid, what is locked, what inputs are active, and what may happen next.

It prevents role drift, instruction loss, premature production, forgotten approvals, and contradictory artifact versions.

Maintain only the detail required by the project's complexity, but never omit the current gate or authoritative object.

## Single-Source Principle

At any moment, identify one authoritative version of each active professional artifact.

Drafts and alternatives may exist, but are not downstream inputs until their state changes explicitly.

Do not infer authority from detail, recency, polish, image count, or production cost.

## State Template

```markdown
# Project State

## 0. Identity

Project ID:
Working title:
ECD / owner:
Created:
Last updated:
Complexity: [Compact / Standard / Extended]

## 1. Intake and Route

Original request:
Intended use:
Entry point:
Shortest valid route:
Consequential assumptions:
Material unknowns:

## 2. Deliverable Contract

Contract reference:
Platform / surface:
Outputs:
Count / duration / size:
Language / locale:
Publication context:

## 3. Stage-Scoped Inputs

Register reference:
Active input IDs:
Needs-Interpretation input IDs:
Deferred Editorial / Copy inputs:
Deferred Visual Research / Intent inputs:
Deferred Visual Direction inputs:
Deferred Production inputs:
Conflicts:

## 4. Evidence and Reference State

Evidence obligation:
Research state:
Reference assets:
Reference roles established:
Rights / attribution:
Material claim limits:

## 5. Phase and Current Owner

Phase:
[Development / Awaiting Greenlight / Editorial Architecture / Copy Desk / Awaiting Script Alignment / Visual Problem / Visual Intent / Reference Reading / Metaphor Mapping / Concept Routes / Awaiting Visual Direction Alignment / Formal Studies / Storyboard / Anchor Keyframes / Representative Design Comp / Awaiting Anchor-Design Alignment / Color Script / Art Direction Package / Production / Final Review / Accepted]

Current professional owner:
Current objective:
Current decision object:
Next valid action:

## 6. Artifact Register

| Artifact | Version / reference | Owner | State | Authority / notes |
|---|---|---|---|---|
| Creative Treatment | | Development | | |
| Greenlight Record | | Producer / ECD | | |
| Creative Script | | Editorial Director | | |
| Copy Brief / Voice Contract | | Copy Desk | | |
| Visual Problem Statement | | Art Director | | |
| Visual Intent Record | | Art Director | | |
| Reference Reading Record | | Art Director | | |
| Visual Metaphor Map | | Art Director | | |
| Concept Routes / Boards | | Art Director | | |
| Visual Direction Alignment | | Producer / ECD | | |
| Formal Studies | | Art Director | | |
| Storyboard / Visual Sequence Board | | Art Director | | |
| World / Cover Anchor | | Art Director | | |
| Representative Body Anchor | | Art Director | | |
| Representative Design Comp | | Art Director | | |
| Anchor / Design Alignment | | Producer / ECD | | |
| Color Script / Sequence System | | Art Director | | |
| Art Direction Package | | Art Director | | |
| Final Assets | | Production Artist | | |
| Acceptance Record | | Producer / ECD | | |

## 7. Active Locks

- Treatment / premise:
- Script / copy:
- visual problem:
- concept route / world logic:
- reference-transfer boundary:
- visual metaphor:
- anchor image language:
- Design Comp / typography / layout:
- Color Script / sequence:
- production specification:

## 8. Unresolved Issues

For each:
- issue:
- first affected object:
- owner:
- consequence:
- ECD involvement required:
- blocking:
- recommended action:

## 9. ECD Gate State

Creative Treatment presented:
Greenlight evidence:
Script Proposal presented:
Script Alignment evidence:
Visual Direction Proposal presented:
Visual Direction Alignment evidence:
Anchor / Design Proposal presented:
Anchor / Design Alignment evidence:
Final package presented:
Final Acceptance evidence:

## 10. Production Authorization

Visual Direction accepted: [yes / no / not required]
Storyboard sufficient: [yes / no]
Anchor Keyframe Gate: [not started / working / passed / failed / bypassed with reason]
Representative Design Comp: [not required / working / passed / failed]
Art Direction Package Accepted for Handoff: [yes / no]
Production inputs activated: [yes / no]
Broad production authorized: [yes / no]

## 11. Rework Scope

Triggering feedback:
First failed object:
Artifact reopened:
Downstream invalidated:
Artifacts still valid:
Next diagnostic proof:

## 12. Change Log

- date / version / change / authority / consequence
```

## Compact State

```markdown
Project:
Deliverable:
Phase / owner:
Current authoritative object:
Active / Deferred inputs:
Current ECD gate:
Treatment / Script state:
Visual route state:
Anchor Gate state:
Production authorization:
Locks:
Open issue:
Next action:
```

A compact record may be short. It must still distinguish visual research from direction, direction from anchors, and anchors from broad production authorization.

## Transition Rules

### Development → Awaiting Greenlight

Requires a coherent, visible Creative Treatment and sufficient evidence / rights resolution.

### Awaiting Greenlight → Editorial Architecture

Requires valid ECD Greenlight tied to the Treatment.

### Editorial / Copy → Awaiting Script Alignment

Requires Treatment fidelity, coherent sequence, Alignment-ready copy, and complete ECD-facing Script Proposal when alignment is material.

### Script Alignment / Handoff → Visual Problem

Requires Script Accepted for Handoff and activation of Visual Research / Intent inputs.

Do not activate Production.

### Visual Problem → Visual Intent / Reference / Metaphor

Requires a clear account of what must become perceptible and which material inputs need interpretation.

### Visual Intent / Reference / Metaphor → Concept Routes

Requires source / inference separation, controlled reference transfer, and metaphor mapping when relevant.

### Concept Routes → Awaiting Visual Direction Alignment

Requires materially distinct routes or a justified single route, low-cost proof, recommendation, and complete ECD-facing proposal when alignment is material.

### Visual Direction Alignment → Formal Studies / Storyboard

Requires selected route and translated ECD decision.

### Storyboard → Anchor Keyframes

Requires coherent full-sequence staging and identified representative risks.

### Anchor Keyframes / Design Comp → Awaiting Anchor-Design Alignment

Requires actual representative proofs visible in the primary conversation when alignment is material.

### Anchor-Design Alignment → Color Script / Art Direction Package

Requires accepted representative image and page-design relationships.

### Art Direction Package → Production

Requires:

- package Accepted for Handoff;
- Anchor Gate passed or valid bypass;
- Design Comp passed when material;
- required visual alignment resolved;
- Production inputs activated.

### Production → Final Review

Requires all requested assets, variants, and QA.

### Final Review → Accepted

Requires complete visible final package and ECD Final Acceptance when material.

## Unauthorized / Non-Authoritative Work

Mark work non-authoritative when it was produced outside the valid sequence, including:

- Production artifacts before Greenlight;
- final-looking images before Visual Problem / route alignment;
- broad image batch before Anchor Gate;
- Production work before Art Direction handoff.

Recovery:

1. stop downstream work;
2. preserve as failure evidence or exploratory material only;
3. restore the first missing gate;
4. do not manufacture retrospective approval;
5. determine whether any fragment remains reusable after the correct direction is accepted.

## Invalid State Examples

- two authoritative Scripts;
- Greenlight without identified Treatment;
- visual reference recorded as a production prompt;
- ECD Aesthetic Judgment converted directly into palette / camera / batch instructions;
- Concept Route absent but Storyboard or anchors exist;
- Visual Direction Alignment recorded without a visible proposal;
- six final-looking images exist while Anchor Gate is `not started`;
- Production authorized because the model can generate quickly;
- raw reference is the governing Production input;
- final assets accepted without matching anchors, Design Comp, contract, and QA;
- rework assigned to latest role rather than first failed object.
