# Wave 3 Behavior Findings

Audit ID: `ECD-SPA-001`

Status: `behavior execution active`

## F-006 — Valid gate approval acknowledged but not advanced

Affected Constitution clauses:

- `SEM-003` — No user-orchestrated internal workflow;
- `SEM-008` — Routine professional autonomy;
- `SEM-044` — Producer advances internal work autonomously.

Related regression tests:

- `SREG-06`;
- `SREG-10`;
- `SREG-12`.

### Observed behavior

A complete Creative Treatment had been presented and the ECD explicitly approved the pending Greenlight.

The assistant then responded only with an acknowledgement equivalent to:

```text
收到。当前文字稿已确认并锁定，确认记录已保存。正文没有改动；除非你提出新修改，否则不再调整这一版。
```

The runtime did not proceed into Editorial and did not produce the next Script Alignment Decision Object.

### Why this is a failure

The prior **Decision Request Turn** correctly stopped at the Greenlight request.

The later user approval was a **Decision Resolution Turn**. Once Greenlight was validly resolved, Editorial became authorized. The Producer should have autonomously run the proportionate Editorial chain, Department review, Producer integration, and returned the next complete Script Alignment Decision Object.

Requiring another user message such as `继续` would make the ECD orchestrate routine internal workflow.

### Root cause

Source rules contained two individually correct statements:

1. a Decision Object request turn must stop at the request;
2. after authorization, Producer should continue internal work autonomously.

The distinction between the request turn and the later resolution turn was not explicit enough. Runtime behavior overgeneralized the hard stop and treated approval recording itself as a terminal response.

### Remediation

Added:

- `core/DECISION_RESOLUTION_PROTOCOL.md`.

Strengthened:

- root `SKILL.md` invariant 9;
- `core/RUNTIME_STATE_MACHINE.md`;
- `core/AUTHORITY_AND_DECISION_OBJECTS.md`;
- `core/creative-producer/SKILL.md`.

New canonical rule:

```text
Decision Request Turn
→ show complete object
→ ask ECD
→ stop

Later ECD Decision Resolution Turn
→ resolve Pending Decision ID
→ if approved, record authority
→ activate next valid state
→ run internal work autonomously
→ return next complete ECD Decision Object or genuine blocker
```

An acknowledgement-only response after valid approval is now explicitly invalid when authorized internal work can proceed.

### Retest requirement

Run the same pattern against the updated runtime:

1. obtain a complete Greenlight Decision Object;
2. reply with an unambiguous approval such as `好的，就这个吧，Greenlight`;
3. verify that the next assistant response does not stop at acknowledgement;
4. verify that Editorial runs internally and the response ends at a complete Script Alignment Decision Object;
5. repeat for Script Alignment → Visual and Visual Alignment → Production;
6. verify Final Acceptance → Completion Record.

### Certification status

`F-006` remains **Open — source remediation implemented; runtime retest pending**.
