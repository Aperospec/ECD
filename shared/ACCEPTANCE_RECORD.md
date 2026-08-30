# Acceptance Record

## Purpose

The Acceptance Record distinguishes professional handoff review, representative visual alignment, staged input resolution, and final ECD acceptance.

It prevents a preliminary proof from being mistaken for final delivery, prevents technical completion from being mistaken for subjective acceptance, and prevents early ECD instructions from silently disappearing across stages.

## Script Alignment Record

Use when a Creative Script introduces a material communication choice requiring ECD alignment before Visual inputs activate.

```markdown
# ECD Script Alignment

Project:
Creative Script and version:
Stage-Scoped Input Register reference:
Material communication question:
Activated Editorial input IDs affected:
Editorial Director recommendation:
Main tradeoff / consequence:
ECD direction or correction:
Accepted communication premise:
Decision-level locks:
Visual inputs may activate after this decision: [yes / no]
State: [ECD-Aligned / revise / rejected]
Recorded by Creative Producer:
```

## Representative Visual Alignment Record

Use when a Storyboard or Representative Design Comp requires ECD alignment.

```markdown
# Representative Visual Alignment

Project:
Artifact and version:
Artifact type: [Storyboard / Visual Sequence Board / Representative Design Comp]
Stage-Scoped Input Register reference:
Activated Visual input IDs affected:
Original ECD visual instructions / reference intent:
Material question being aligned:
Art Director recommendation:
Representative screens reviewed:
Main tradeoff / risk:
ECD direction or correction:
Accepted visual premise:
Decision-level locks:
What remains open for Art Direction / Production:
Production inputs may activate after Art Direction handoff: [yes / no]
State: [ECD-Aligned / revise / rejected]
Recorded by Creative Producer:
```

## Final Acceptance Record

```markdown
# ECD Final Acceptance

Project:
Date:
Final asset package / version:
Deliverable Contract reference:
Stage-Scoped Input Register reference:
Greenlight and Creative Script references:
Accepted visual premise / Design Comp reference:
Art Direction Package reference:

## Stage-Scoped Input Resolution Audit

For every material registered ECD input:

| Input ID | Source authority | Final state | Artifact / decision that resolved it | Open limitation |
|---|---|---|---|---|
| | | Resolved / Consumed / Superseded / Rejected / Conflict / Open | | |

Audit:

- all Development inputs accounted for: [pass / fail / note]
- all Activated Editorial inputs accounted for: [pass / fail / note]
- all Activated Visual inputs accounted for: [pass / fail / note]
- all Activated Production inputs accounted for: [pass / fail / note]
- no Deferred Hard Constraint was silently dropped: [pass / fail / note]
- no Assistant Inference became ECD authority silently: [pass / fail / note]
- no previously supplied instruction was needlessly re-requested: [pass / fail / note]

## Creative Producer Final Review

- Greenlit premise preserved: [pass / fail / note]
- Creative Script meaning preserved: [pass / fail / note]
- accepted visual premise preserved: [pass / fail / note]
- exact names / wording preserved: [pass / fail / note]
- evidence / limitations visible: [pass / fail / note]
- requested outputs and variants complete: [pass / fail / note]
- mobile QA: [pass / fail / note]
- technical QA: [pass / fail / note]
- unauthorized deviation: [none / describe]

Known limitations:
Open registered input, if any:
External action still pending:

## ECD Decision

Final state: [Final Accepted / accepted with recorded limitation / revise / rejected]
ECD correction or condition:
Publication authorization: [granted / not requested / pending]
Locked final package:
Recorded by Creative Producer:
```

## Compact Acceptance

For a narrow project:

```markdown
Final package:
Stage Input Register:
All material input IDs accounted for:
Contract complete:
Creative fidelity:
Visual-input fidelity:
Production-input fidelity:
Mobile / technical QA:
Known limitation:
ECD state:
Publication state:
```

## Acceptance Rules

- Creative Producer may mark a final package ready for ECD review, but may not mark it Final Accepted on the ECD's behalf.
- ECD Greenlight accepts the Treatment only; it is not proof that later Editorial / Visual / Production inputs were resolved correctly.
- ECD Script Alignment does not automatically accept later visual interpretation.
- ECD Visual Alignment on a Design Comp does not automatically accept later execution.
- Technical QA passing does not resolve a subjective creative rejection.
- Final acceptance should not be recommended while a material registered user input is missing, silently dropped, or unresolved without disclosure.
- A material `Conflict` in the Stage-Scoped Input Register must be resolved or explicitly accepted as a limitation before Final Acceptance.
- Final acceptance does not authorize publication unless publication authority is explicitly included or already implied by the user's instruction.
- A requested revision must be routed to the first failed owner or state transition rather than automatically assigned to Production Artist.
