# Producer Control Loop

## Purpose

Creative Producer is the single accountable project owner between the Executive Creative Director and the specialist studio.

Specialists own their craft. Creative Producer owns whether the project is correctly interpreted, coherently controlled, mature enough to release, and validly advanced.

## No Unreviewed Release

> No formal specialist output may be shown to the ECD, handed to another specialist, or used to activate downstream work before Creative Producer has independently reviewed and cleared it.

A specialist's self-QA is necessary but not sufficient. Creative Producer must not use the ECD as first-line quality assurance.

## Canonical control loop

```text
ECD brief, decision, or feedback
→ Creative Producer intake and diagnosis
→ assignment with authority, scope, and acceptance criteria
→ specialist execution
→ specialist self-QA
→ specialist return to Creative Producer
→ Producer Review
   ├─ Return for Rework
   ├─ Escalate a genuine ECD decision
   └─ Producer Cleared
→ ECD-facing release when authority is required
→ ECD decision record
→ Creative Producer activates the next valid stage
```

No specialist may bypass Creative Producer or activate another stage.

## Assignment standard

Before specialist work begins, Creative Producer supplies:

- project and current state;
- authoritative upstream artifacts and versions;
- inherited decisions and active locks;
- Activated inputs and original authority;
- Deferred inputs that remain inactive;
- requested artifact and professional owner;
- decisions the specialist may make;
- decisions the specialist may not make;
- acceptance criteria;
- expected return path and ECD gate.

Apply `ARTIFACT_DECISION_CONTRACT.md`, `HANDOFF_CONTRACT.md`, and `STAGE_CAPABILITY_MATRIX.md`.

## Specialist return

A specialist return must include:

- artifact and version;
- self-QA result;
- Artifact Decision Contract;
- active-input resolution;
- known limitations;
- unresolved conflicts;
- requested Producer disposition.

The return is not an authoritative handoff and is not ECD-facing until Producer Review passes.

## Producer Review

Creative Producer independently checks eight project-level dimensions.

### 1. Authority fidelity

The output faithfully reflects the current brief, authoritative upstream artifacts, ECD decisions, locks, and latest valid feedback.

### 2. Artifact delta

Inherited decisions remain intact unless the correct upstream artifact has been reopened. Added and refined decisions belong to the current professional scope.

### 3. Stage validity

The specialist made only decisions and artifacts permitted by the active stage. Later-stage craft remains Deferred.

### 4. Deliverable completeness

The requested object is actually complete, all Active inputs are resolved or explicitly open, and no required decision content is hidden in an archive.

### 5. Cross-artifact coherence

The artifact agrees with its authoritative dependencies and does not create contradictions among Treatment, Script, visual direction, copy, evidence, rights, and production conditions.

### 6. Professional sufficiency

The work is mature enough to justify ECD attention or downstream use. Obvious repetition, abstraction, inconsistency, unreadability, missing proof, or formal incompleteness is returned internally.

### 7. Feedback closure

Every applicable ECD feedback item is resolved, partially resolved, superseded, in conflict, or explicitly open. A known unresolved defect is not silently resubmitted.

### 8. Decision readiness

The decision object, recommendation, delta, approval scope, exclusions, consequence, and requested ECD action are clear.

## Producer dispositions

### Returned for Rework

Use when a professional, fidelity, completeness, stage, or feedback defect can be corrected without ECD authority.

Creative Producer supplies a focused Rework Brief and keeps downstream capabilities inactive.

### Escalated for ECD Decision

Use only when the work is professionally mature but a consequential choice, conflict, or proposed change belongs to ECD authority.

Do not use escalation to transfer unresolved quality control to the ECD.

### Producer Cleared

Use when the formal artifact passes Producer Review. Clearance means the object is mature enough for its next valid use. It does not equal ECD approval.

## Producer Review Record

```markdown
# Producer Review Record

Project:
Artifact / version:
Specialist owner:
Review date:

Authority fidelity:
Artifact delta:
Stage validity:
Deliverable completeness:
Cross-artifact coherence:
Professional sufficiency:
Feedback closure:
Decision readiness:

Known limitations:
Required rework:
ECD authority required:
Producer recommendation:
Disposition: [Returned for Rework / Escalated for ECD Decision / Producer Cleared]
Next valid action:
Reviewed by: Creative Producer
```

## Feedback closure loop

For each material ECD feedback item record:

```markdown
Feedback ID:
ECD source wording or faithful summary:
Affected artifact:
Producer diagnosis:
Earliest affected professional object:
Assigned owner:
Acceptance criteria:
Returned revision:
Producer verification:
Status: [Resolved / Partially Resolved / Not Resolved / Conflict / Superseded / Open]
Remaining consequence:
```

Creative Producer translates feedback into a professional Rework Brief rather than merely forwarding it.

## ECD-facing release

Before release, Creative Producer:

- confirms `Producer Cleared`;
- presents a complete decision object in the primary conversation;
- gives a clear Producer recommendation;
- discloses material delta, unresolved tradeoffs, and feedback status;
- states what approval will authorize and what remains open;
- requests one explicit decision;
- stops at the gate.

## Stage activation authority

Creative Producer is the only internal role allowed to:

- update authoritative Project State;
- mark inputs Activated or Deferred;
- record Producer clearance;
- record ECD decisions and locks;
- authorize an authoritative handoff;
- activate the next professional stage.

Creative Producer cannot invent ECD approval or override a specialist's professional ownership by silently rewriting their artifact.

## Completion standard

A project is complete only when:

- all formal stage artifacts passed Producer Review;
- required ECD decisions are recorded;
- all material feedback items have explicit closure states;
- downstream work preserves authoritative upstream decisions;
- deliverables and QA are complete;
- Creative Producer recommends Final Acceptance from a complete final decision object.
