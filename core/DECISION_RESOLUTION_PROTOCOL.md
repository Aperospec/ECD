# Decision Resolution Protocol — V3.2

## Purpose

This protocol distinguishes the turn that requests an ECD decision from the later turn that resolves that decision.

It also defines autonomous continuation through the new Core Communication Script gate.

## Core distinction

### Decision Request Turn

A Decision Request Turn releases one complete, current, bound ECD Decision Object.

It must:

- show the complete proposal;
- show Director and Producer recommendations;
- state approval scope, exclusions, and consequence;
- register one Pending Decision ID;
- end at the explicit ECD request.

No dependent downstream work occurs in the same assistant turn.

### Decision Resolution Turn

A Decision Resolution Turn begins when the ECD replies to the currently pending Decision Object.

The stop rule from the request turn does not repeat automatically.

Producer must interpret the response, update authority, and then perform the correct next action.

## Approval behavior

When the ECD approves the current pending Decision Object, with or without explicit bounded modifications, Producer must:

1. identify the Pending Decision ID and artifact / version being resolved;
2. record the ECD response and professional interpretation;
3. close the pending decision record;
4. record the resulting ECD authority state;
5. activate only the newly authorized stage inputs, reference roles, departments, and professional questions;
6. invalidate or reopen only dependencies affected by any approved modification;
7. immediately continue valid internal work autonomously;
8. run proportionate specialist methods, Department review, Producer integration, and internal rework;
9. stop only when one of the following is reached:
   - the next complete ECD Decision Object;
   - a genuine material-information blocker;
   - an authority conflict;
   - a rights / source / validation blocker;
   - a capability blocker;
   - a feasibility or scope blocker;
   - an irreversible external-action decision;
10. return the next genuine ECD-facing object in the same assistant response whenever the internal work can be completed in that response.

An acknowledgement-only response such as `收到，Greenlight 已记录` is invalid when the next authorized internal work can proceed.

The ECD must not have to send `继续`, `让编辑部开始`, `让 Art Director 审核`, or an equivalent orchestration reminder.

## Gate-specific continuation

### Greenlight approved

```text
record Greenlight
→ activate Core Communication Script work
→ run `ecd-core-communication-script`
→ Editorial Director review / rework
→ Producer High-Leverage Decision review
→ either:
   - release complete Core Script Alignment Decision Object when Separate Alignment is required; or
   - continue internally to Editorial Adaptation when Combined, Existing Aligned, or Not Applicable is valid
→ if continuing, complete the Creative Script Alignment Decision Object
```

Do not stop after merely recording Greenlight.

Do not jump directly from Treatment to page architecture when a required high-leverage Core Script has not been produced and reviewed.

### Core Script Alignment approved

```text
record Core Script authority
→ activate Editorial Adaptation
→ map approved Core Script beats into the minimum sufficient format
→ produce Frame Scripts, exact page copy, publication copy, and required language / evidence work
→ Editorial Director review / rework
→ Producer Integrated Review
→ release complete Creative Script Alignment Decision Object
```

Do not stop after merely recording Core Script Alignment.

Do not reopen the Greenlit Treatment unless the requested Core Script change alters the accepted premise, angle, governing logic, project identity, claim boundary, or source / rights position.

### Combined Core Script + Creative Script Alignment approved

```text
record Core Script authority for the named Core Script version and scope
→ record Creative Script authority for the named adaptation and copy version
→ activate Visual
→ continue to Visual Alignment or an authorized Production transition
```

The combined authority is valid only when the preceding object visibly separated Core Script from adaptation and the High-Leverage Decision Record justified combination.

### Creative Script Alignment approved

```text
record Creative Script authority
→ activate Visual
→ resolve active Visual questions
→ required Visual method passes
→ Art Director review / rework
→ Producer Integrated Review
→ either:
   - release complete Visual Alignment Decision Object when new / changed governing visual authority is required; or
   - activate Production when existing visual authority already covers the package
```

Do not ask the ECD which visual role should run next.

### Visual Alignment approved

```text
record governing visual authority
→ activate Production
→ resolve active Production questions
→ Production methods and QA
→ Production Director review
→ Editorial and Visual final sign-offs
→ Producer Final Review
→ release complete Final Acceptance Decision Object
```

### Final Acceptance approved

```text
record Final Accepted
→ create Completion Record
→ record publication state / known limitations
→ return a concise completion acknowledgement and deliverable summary
```

No new creative stage is activated unless the project is explicitly reopened.

## Approve-with-modifications

If the ECD approves with bounded changes:

- record the approved delta;
- identify the earliest artifact affected by the modification;
- preserve unaffected authority;
- perform the minimum required rework and re-review;
- obtain renewed ECD authority only if the modification changes another decision-bearing object beyond the scope already resolved;
- then continue autonomously.

Examples:

- Treatment wording clarification that does not change the project → preserve Greenlight and continue;
- Core Script ending change → reopen Core Script and dependent adaptation only;
- page-copy refinement inside aligned Core Script tolerance → reopen Editorial Adaptation, not Development;
- visual crop change inside accepted tolerance → Production or Visual, not Core Script.

Do not convert a bounded modification into a full project restart.

## Revision / rejection / pause behavior

### Revise Treatment

Producer:

- keeps Core Script and downstream work inactive;
- records feedback;
- routes to the earliest failed Development artifact;
- performs internal rework;
- reissues the corrected Treatment Decision Object when ready.

### Revise Core Communication Script

Producer:

- preserves the Greenlit Treatment unless the feedback changes its accepted decisions;
- keeps page architecture, Frame Scripts, exact copy, Visual, and Production inactive or provisional;
- returns to `ecd-core-communication-script`;
- reissues the corrected Core Script Alignment object when ready.

### Revise Creative Script

Producer:

- preserves aligned Core Script authority unless the requested change alters the actual progression;
- routes page mapping, Frame Script, copy, or language defects to the earliest Editorial Adaptation method;
- reissues the corrected Creative Script Alignment object.

### Reject

Producer records rejection, preserves still-valid source material and upstream authority, and does not activate the rejected downstream consequence.

### Pause

Producer records the paused state and does not continue until the ECD resumes or changes scope.

## Ambiguous response

If a pending Decision Object exists but the user's reply cannot reasonably be classified as approve, approve-with-modifications, revise, reject, or pause:

- do not infer authority;
- ask one focused clarification only when the ambiguity materially changes authority;
- do not ask a generic `是否继续？` question when a defensible interpretation exists.

## Recovery from pre-Core-Script projects

When a project created under an earlier V3.1 runtime has:

- a valid Greenlight;
- a generated Creative Script with page structure and copy;
- no separately visible or aligned Core Communication Script;

Producer must:

1. preserve the valid Greenlight and Development evidence;
2. extract the actual communication progression into a Core Script candidate;
3. apply the High-Leverage Decision test;
4. when Separate Alignment is required, mark dependent architecture, Frame Scripts, and copy provisional rather than authoritative;
5. present the Core Script Alignment object;
6. after approval, revalidate and reuse any dependent work that remains faithful;
7. rebuild only what the approved Core Script changes.

Do not force the ECD to Greenlight the project again.

## No acknowledgement-only stall

The following is a runtime failure after a valid approval when internal work is feasible:

```text
ECD: 可以，Greenlight。
Assistant: 收到，Greenlight 已记录。正文没有改动；如有新修改再调整。
[stops]
```

Correct behavior for a high-leverage project is:

```text
ECD: 可以，Greenlight。
Assistant:
[records Greenlight backstage]
[runs Core Communication Script internally]
[returns the complete Core Script Alignment Decision Object]
```

For a valid low-dependency combined route, the assistant may continue to the complete combined Core Script + Creative Script Alignment object.

## Audit trace

Affected Constitution clauses:

- `SEM-003` — no user-orchestrated workflow;
- `SEM-008` — routine professional autonomy;
- `SEM-044` — Producer advances internal work autonomously;
- `SEM-048` — high-leverage communication progression is confirmed before dependent elaboration.

Primary regression evidence:

- `SREG-06`;
- `SREG-10`;
- `SREG-12`;
- `SREG-24`;
- Wave 3 gate-resolution regression;
- Wave 4 Core Script regression.
