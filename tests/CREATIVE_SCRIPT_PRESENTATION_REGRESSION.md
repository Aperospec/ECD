# Creative Script Presentation Regression

## Purpose

These tests verify that a Creative Script requiring ECD Script Alignment is presented as a complete decision object in the primary conversation.

The regression was created after a test in which the studio generated a detailed internal Creative Script file but showed the ECD only seven page titles and one sentence per page, then asked for `Script Alignment` and directed the ECD to the attachment for the complete Script and body copy.

That outcome is a failure even when the internal file is structurally complete.

Apply:

- `../shared/ECD_DECISION_PRESENTATION.md`;
- `../editorial-director/references/creative-script-presentation.md`.

## Hard Failures

A test fails immediately when:

- Script Alignment is requested before the complete Script is visible in the primary conversation;
- the response contains only a numbered sequence summary;
- Written Visual Beats exist only in an attachment;
- complete on-screen copy or companion copy exists only in an attachment;
- the ECD must open a file to understand page functions, transitions, material fictional additions, or Alignment scope;
- internal-file completeness is treated as ECD-facing presentation completeness;
- the response says “完整脚本见文件” and proceeds to request Alignment;
- Visual inputs are activated after an invalid summary-only Alignment request;
- the Script presentation hides what remains Deferred for Art Director;
- a defective internal Script is copied into the conversation without first passing treatment-fidelity and sequence QA.

## Required Visible Order

```text
Script Core
→ Communication Strategy
→ Complete Page / Beat Sequence
→ Complete Companion / Body Copy
→ Treatment Fidelity and Sequence QA
→ Script Alignment Scope
→ Decision Request
```

## S01 — Real-Failure Regression: Seven-Page Summary Plus Attachment

### Context

The ECD has Greenlit a Creative Treatment for a seven-page Social Editorial post. Editorial Director produces a complete internal Markdown file containing:

- Communication Strategy;
- seven detailed beats;
- Written Visual Beats;
- on-screen copy;
- companion copy;
- input-resolution state;
- Sequence QA;
- Script Alignment scope.

### Failing primary-conversation response

```text
Greenlight 已记录。Creative Script V1 收束为 7 页：

1. [标题]
   [一句文案]
2. [标题]
   [一句文案]
...
7. [标题]
   [一句文案]

完整脚本和配套正文在 09_CREATIVE_SCRIPT_V1.md。
如果这套顺序和文案成立，回复 Script Alignment。
```

### Expected result

Fail.

Reason:

- the response presents a Sequence Summary, not the Creative Script Proposal;
- the full decision object is hidden in the file;
- the ECD cannot judge Written Visual Beats, page functions, transitions, body copy, QA, or Alignment scope without opening the attachment;
- the decision request is invalid.

### Recovery

- keep the Script `Proposed`;
- withdraw the Alignment request;
- inspect and revise the internal Script if content fidelity or page progression is weak;
- present the complete ECD-facing Script in the primary conversation;
- ask for Alignment only after all decision-relevant content is visible;
- keep Visual inputs Deferred.

## S02 — Internal Completeness Does Not Cure Presentation Failure

Input condition:

- the attached Script file contains every required field;
- the primary conversation contains only an executive summary.

Expected:

- fail ECD Decision Presentation Gate;
- do not mark `ECD-Aligned`;
- do not mark `Accepted for Handoff` on the basis of the summary;
- archive-file completeness may be recorded separately but does not authorize the next stage.

## S03 — Valid Seven-Page Script Proposal

Expected primary-conversation content:

- one Script Core statement;
- dominant / supporting modes;
- opening promise, payoff, sequence logic, and rationale;
- all seven pages shown in order;
- each page includes its function, Editorial Job, Audience Change, Written Visual Beat, exact on-screen copy, material preservation / limitation, and transition when relevant;
- complete body copy;
- concise fidelity and sequence QA;
- new examples or fictional material disclosed;
- Alignment scope states what becomes accepted;
- visual composition, palette, typography, Storyboard, Design Comp, and production remain Deferred;
- explicit decision request followed by a hard stop.

Expected: pass presentation gate, subject to content-quality gate.

## S04 — Compact Does Not Mean Summary-Only

Input:

- a two-page Compact Script requiring ECD Alignment.

Expected:

- concise presentation permitted;
- both pages still show full decision-relevant content;
- complete body copy visible when required;
- no “see attachment for details” dependency;
- visual scope remains Deferred.

## S05 — No Material Script Alignment Required

Input:

- a narrow copy correction that does not change sequence, page role, meaning, fictional content, or public position.

Expected:

- Producer may accept the corrected Script for handoff without unnecessary ECD ceremony;
- Project State records why Alignment was not material;
- this exception must not be used for a new multi-page sequence or full copy deck.

## S06 — Content Fidelity and Presentation Are Separate Gates

Input condition:

- the full Script is visible in the conversation;
- the Script materially changes the Greenlit Treatment or repeats the same editorial job across multiple pages.

Expected:

- presentation gate may pass;
- professional Script-quality gate fails;
- Producer does not request Alignment until Editorial Director revises the Script;
- visual inputs remain Deferred.

## S07 — Alignment Scope Must Be Explicit

Expected Script Alignment section:

```text
Confirming in this decision:
- page count and order;
- communication progression;
- page roles and Written Visual Beats;
- all on-screen copy;
- complete body copy;
- disclosed new examples / fictional content;
- evidence and limitation placement.

Still not confirming:
- composition;
- camera and crop;
- palette and lighting;
- visual style;
- typography and layout;
- Storyboard / Visual Sequence Board;
- Representative Design Comp;
- Art Direction Package;
- final assets.
```

Fail when the request merely says “如果顺序和文案成立，回复 Script Alignment” without defining the full object and consequence.

## S08 — Attachment as Archive Only

Expected:

- an internal file may be linked after the full proposal is shown;
- the file may contain IDs, detailed QA, input-resolution tables, and handoff metadata;
- no unique material decision content is hidden there;
- the ECD-facing proposal and archive identify the same Script version.

## S09 — Decision Evidence Requires Presentation Reference

Project State should record:

- Script version;
- ECD-facing presentation turn / reference;
- archive-file reference;
- whether the complete proposal was visible;
- decision requested;
- ECD response;
- resulting state.

Fail when the only reference is an attachment path.

## S10 — No Visual Activation in the Alignment Turn

After presenting the complete Script and requesting Alignment:

- end the response;
- do not activate Visual inputs;
- do not create Storyboard panels;
- do not generate images;
- wait for the ECD decision.

## Evaluation Record

```markdown
Test ID:
Internal Script complete: [yes / no]
Primary-conversation proposal complete: [yes / no]
All pages visible: [yes / no]
Written Visual Beats visible: [yes / no]
Exact copy visible: [yes / no]
Body copy visible: [yes / no / not required]
Fidelity / sequence QA visible: [yes / no]
Alignment scope visible: [yes / no]
Deferred visual scope visible: [yes / no]
Attachment required to decide: [yes / no]
Content-quality gate: [pass / fail]
Presentation gate: [pass / fail]
Visual inputs remain Deferred: [yes / no]
Overall: [pass / fail]
```
