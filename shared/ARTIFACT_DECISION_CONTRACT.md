# Artifact Decision Contract

## Purpose

Every formal artifact must preserve the authority of its upstream artifacts while making only the new decisions owned by its current professional stage.

This contract is a backstage control object. It prevents semantic drift, hidden scope changes, and downstream convenience from becoming unauthorized creative authority.

## Core invariant

> A downstream artifact may elaborate inherited decisions within its professional scope. It may not silently change or remove an authoritative upstream decision.

Shared vocabulary or topic similarity is not sufficient evidence of fidelity. The actual accepted decisions and their relationships must remain traceable.

## Contract structure

For each formal artifact, record:

```markdown
# Artifact Decision Contract

Artifact:
Version:
Professional owner:
Project State reference:

## Authoritative upstream artifacts
- artifact / version / authority state

## Inherited authoritative decisions
- decision / source artifact / tolerance

## Decisions introduced by this artifact
- decision / professional owner / rationale

## Open or Deferred decisions
- decision / future owner / activation condition

## Constraints and tolerances
- protected decision / permitted interpretation range

## Dependencies
- artifact / version / dependency consequence

## Delta from prior authoritative version
| Decision | Delta class | Previous state | Proposed state | Authority consequence |
|---|---|---|---|---|

## Conflicts or unresolved authority
- issue / earliest affected artifact / decision owner / blocking consequence
```

## Delta classes

### Added

A new decision that belongs to the current professional owner's scope and does not conflict with an inherited decision.

### Refined

A more specific interpretation that preserves the substance, authority, and protected consequence of an inherited decision.

### Changed

A proposed alteration to the substance or consequence of an existing decision.

### Removed

A proposed deletion or abandonment of an existing decision.

## Delta rules

- `Added` is allowed when it belongs to the active stage and does not pre-empt a Deferred stage.
- `Refined` is allowed when the inherited meaning and authority remain intact.
- `Changed` or `Removed` requires reopening the earliest authoritative artifact where that decision was accepted.
- A current-stage owner may recommend an upstream change but may not implement it silently.
- An ECD-approved decision can be changed only through a new complete ECD decision object.
- An artifact with unresolved unauthorized delta cannot pass Producer Review.

## Decision extraction

Upstream decisions may appear in connected prose rather than fixed fields. Preserve the original artifact as authoritative and extract only the minimum decision set needed for inheritance, QA, and handoff.

Do not replace a coherent creative artifact with a rigid worksheet. The contract supports the artifact; it does not become the audience-facing creative proposition.

## Producer verification

Creative Producer verifies before release:

- authoritative upstream versions are correct;
- inherited decisions are represented faithfully;
- new decisions belong to the current stage;
- every change or removal has the correct authority path;
- open and Deferred decisions remain visibly open;
- dependencies and tolerances are current;
- no topic-level similarity is being used to conceal decision-level drift.

## Rework

When a delta is unauthorized:

1. identify the earliest artifact whose accepted decision would change;
2. return the work to that artifact's professional owner through Creative Producer;
3. preserve unaffected decisions and work;
4. invalidate only actual dependents;
5. obtain renewed ECD authority when the changed decision was ECD-approved;
6. resume downstream work only after the corrected artifact is Producer Cleared and authority-complete.
