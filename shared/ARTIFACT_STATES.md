# Artifact States and Authority

## Purpose

This document defines what artifact-state terms mean, who may assign them, and what downstream work is allowed to assume.

Use these terms consistently. Do not use the generic word `approved` without identifying the actual state or authority.

## Canonical States

### Working

The responsible professional owner is actively developing the artifact. It may change without formal rework.

### Proposed

The professional owner considers the artifact ready for review. It is not yet an authoritative downstream input.

A proposed Creative Treatment remains in Development / Awaiting Greenlight until the ECD authorizes that identified version.

### Accepted for Handoff

Creative Producer has confirmed that the artifact is sufficiently complete, coherent, and within scope to move to the next professional owner.

This is a production-management decision, not a substitute for ECD authority over material creative choices or Greenlight.

Creative Producer may recommend a Treatment for Greenlight but may not mark it accepted for Production on the ECD's behalf.

### ECD-Aligned

The ECD has confirmed a material interpretation or direction that requires subjective or executive authority.

Typical examples:

- a material Script communication choice not resolved by the Treatment;
- a Representative Design Comp that defines the visual world;
- a rights, attribution, brand, or public-position decision.

For the Creative Treatment, the relevant executive state is specifically **ECD Greenlight**, recorded under `GREENLIGHT_RECORD.md`.

### Locked

Creative Producer has recorded that downstream work must preserve the identified version and dimensions of the artifact unless explicitly reopened.

A lock must state what is locked. An entire artifact should not be treated as immutable when only selected decisions require protection.

### Final Accepted

The ECD has accepted the final deliverable for the intended use, subject to any recorded limitation or external action still pending.

### Superseded

The artifact is no longer authoritative because a later accepted version replaced it. Downstream work must not continue from it.

### Reopened

A previously accepted or locked artifact has returned to its professional owner because the first-failed-owner rule identified a material defect or authorized change.

### Unauthorized / Invalid

An artifact was produced outside the valid state sequence, such as a Creative Script, Storyboard, Design Comp, generated image, or final asset created before Greenlight.

It is not an authoritative input merely because it exists. Preserve it only as failure evidence or explicitly non-authoritative exploration, then return the project to the first missing gate.

## Authority Matrix

| Object | Professional owner | Accepted for Handoff | ECD alignment normally required when | Final authority |
|---|---|---|---|---|
| Deliverable Contract | Creative Producer | Creative Producer | scope, publication, cost, rights, or output changes materially | ECD for material scope / external action |
| Creative Treatment | Development via Creative Producer | Creative Producer may recommend for Greenlight | premise, angle, promise, or public position is accepted | ECD Greenlight tied to identified Treatment |
| Greenlight Record | Creative Producer records | not applicable | always for raw or unresolved input | ECD authorization evidence controls |
| Creative Script | Editorial Director | Creative Producer | Script introduces a material communication choice not resolved by Treatment | ECD when material; otherwise Creative Producer handoff |
| Storyboard / Visual Sequence Board | Art Director | Creative Producer | visual interpretation materially changes mood, world, or audience relationship | ECD when material |
| Representative Design Comp | Art Director | Creative Producer | it defines a subjective visual premise or durable identity | ECD when material |
| Art Direction Package | Art Director | Creative Producer | it contains a material unresolved visual direction | ECD when material; otherwise Creative Producer handoff |
| Final Assets | Production Artist | Creative Producer review | subjective final quality or publication acceptance is required | ECD Final Acceptance |

## Greenlight Is Not Generic Approval

Greenlight means the ECD authorizes Production on the basis of a specified Creative Treatment. It does not automatically accept:

- final page sequence;
- final copy;
- Storyboard;
- visual identity;
- final assets.

Those decisions follow their own professional and ECD gates.

A generic request to make, start, design, or directly produce something is not Greenlight before a Treatment has been presented or explicitly identified. Apply `GREENLIGHT_RECORD.md`.

## ECD Alignment Is Not Final Acceptance

ECD Alignment confirms a material direction so work may continue. It does not mean the final execution has been accepted.

Use **ECD Final Acceptance** only for the completed deliverable or an explicitly named final object.

## Compact Project Rule

Compact work may combine adjacent post-Greenlight states in one concise record when authority is unambiguous. For example:

```text
Creative Treatment v1 — Proposed and presented to ECD
Greenlight Record — explicit ECD acceptance of Treatment v1
Creative Script — Accepted for Handoff by Creative Producer
Combined Board + Design Comp — ECD-Aligned when materially required
Final Assets — pending ECD Final Acceptance
```

Compact status may shorten the Treatment and Greenlight Record. It may not merge “Treatment proposed” and “Treatment accepted” into one inferred state.

Do not create ceremonial approval steps merely to populate every state, but do not remove the actual ECD decision.

## Lock Granularity

Prefer decision-level locks:

- core proposition locked;
- exact product name locked;
- page 1 title locked;
- comparison evidence locked;
- cover subject–title depth relationship locked;
- body-page minimum reading condition locked.

Avoid blanket locks that prevent legitimate professional refinement.

## State QA

Reject ambiguous records such as:

- `approved` with no authority;
- `Greenlit` with no Treatment version and authorization evidence;
- `Greenlit by direct production instruction` when no Treatment had yet been presented or identified;
- `final` before technical QA;
- `locked` with no version or protected dimensions;
- `ECD accepted` when only Creative Producer reviewed it;
- `handoff complete` while required copy remains placeholder text;
- `production ready` without a sufficiently resolved visual proof;
- a pre-Greenlight Production artifact promoted from `Unauthorized / Invalid` merely to avoid rework.
