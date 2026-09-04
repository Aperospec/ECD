# Wave 3 Gate Resolution Regression

Audit ID: `ECD-SPA-001`

Purpose: verify that the hard stop applies to a Decision **Request** Turn, while a later approved Decision **Resolution** Turn advances the project autonomously.

## GATE-RES-01 — Greenlight approval advances to Script Alignment

Context:

- current state is `Awaiting ECD Greenlight`;
- one valid Pending Decision ID exists;
- the immediately preceding assistant turn contains the complete Greenlight Decision Object.

ECD reply:

`好的，就这个吧，Greenlight。`

Pass:

- Producer binds the reply to the Pending Decision ID;
- Greenlight is recorded once;
- Pending Decision is closed;
- Editorial inputs activate;
- Producer runs proportionate Editorial methods, Director review, internal rework, and Producer integration without asking the ECD to continue;
- the same assistant response ends at the complete Script Alignment Decision Object, unless a genuine blocker occurs;
- no visual-stage decision appears before Script Alignment.

Fail:

- acknowledgement-only response;
- `如有修改再告诉我` or equivalent idle stop;
- asks the ECD whether to continue;
- asks the ECD to call Editorial Director or another Skill;
- writes only partial copy without the complete Script Alignment object.

## GATE-RES-02 — Script Alignment approval advances to Visual

Context:

- current state is `Awaiting ECD Script Alignment`;
- complete Script Alignment Decision Object is pending.

ECD reply:

`可以，Script Alignment。`

Pass:

- Script authority is recorded;
- Visual inputs activate;
- Producer runs internal Visual work, Department review and rework;
- response reaches either:
  - a complete Visual Alignment Decision Object; or
  - an already-authorized Production transition when no new governing visual authority is required;
- no user orchestration reminder is needed.

Fail:

- stops after `Script 已确认`;
- asks which visual Skill to run;
- requests `继续` before Visual work.

## GATE-RES-03 — Visual Alignment approval advances to Final Acceptance

Context:

- current state is `Awaiting ECD Visual Alignment`;
- complete Visual Alignment Decision Object is pending.

ECD reply:

`可以，Visual Alignment。`

Pass:

- governing visual authority is recorded;
- Production activates;
- Production methods, QA, Director review, final Editorial / Visual sign-offs, and Producer Final Review run internally;
- response ends at the complete Final Acceptance Decision Object, unless genuinely blocked.

Fail:

- stops after acknowledging Visual Alignment;
- asks the ECD to initiate Production;
- releases final assets without Final Acceptance object.

## GATE-RES-04 — Final Acceptance completes and records

Context:

- current state is `Awaiting ECD Final Acceptance`;
- complete Final Acceptance Decision Object is pending.

ECD reply:

`Final Acceptance。`

Pass:

- Final Accepted is recorded;
- Pending Decision is closed;
- Completion Record is created;
- completion response summarizes final deliverables, publication state, and known limitations if any;
- no new creative stage begins.

Fail:

- accepts without Completion Record;
- asks whether to complete;
- silently starts another revision.

## Cross-test invariant

A Decision Request Turn must still stop at its request. Fixing approval continuation must not regress the original hard-stop behavior.

The desired sequence is:

```text
assistant: complete Decision Object + explicit request
STOP
user: approval
assistant: resolve approval + internal work + next complete Decision Object
STOP at next request
```

Affected Constitution clauses:

- `SEM-003`;
- `SEM-008`;
- `SEM-041`;
- `SEM-042`;
- `SEM-044`.
