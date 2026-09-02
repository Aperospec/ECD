# Artifact States and Authority

## Purpose

Artifact status has separate dimensions for professional quality, Producer clearance, and ECD authority.

No single label may collapse these responsibilities.

## Quality state

### Working

The professional owner is developing the artifact.

### Specialist QA Passed

The professional owner considers the craft complete enough for Producer Review.

This is an internal claim, not release authority.

### Producer Review Pending

The formal artifact has returned to Creative Producer for independent project-level review.

### Returned for Rework

Creative Producer identified a defect or incomplete condition and returned the artifact to the responsible professional owner.

### Producer Cleared

Creative Producer confirmed authority fidelity, valid delta, stage validity, completeness, cross-artifact coherence, professional sufficiency, feedback closure, and decision readiness.

Producer clearance means the artifact is mature enough for its next valid use. It does not equal ECD approval.

## Authority state

### Unreviewed

No ECD authority has been requested or granted.

### Awaiting ECD Decision

A Producer Cleared, complete decision object has been released for a named ECD decision.

### Greenlit

The ECD accepted an identified Creative Treatment and authorized Editorial development from that premise.

### ECD-Aligned

The ECD accepted an identified intermediate decision-bearing artifact or decision scope.

### Final Accepted

The ECD accepted the final deliverable package for the stated use, subject to recorded conditions.

### Reopened

An authoritative artifact or decision returned to its professional owner for authorized revision.

### Superseded

A later authoritative version replaced the artifact or decision.

### Unauthorized / Invalid

The artifact was created or used outside the valid stage, Producer Review, or ECD authority sequence.

It is non-authoritative until the valid sequence is restored and any reusable material is accepted by the correct owner.

## Handoff readiness

`Handoff Ready` is a computed condition, not a substitute for quality or authority state.

A formal artifact is Handoff Ready only when:

```text
Quality state = Producer Cleared
+ required authority state for the artifact class is satisfied
+ authoritative dependencies are current
+ required Active inputs are resolved or explicitly open
+ no blocking feedback or conflict remains
```

Legacy use of `Accepted for Handoff` must be interpreted as this complete condition. Producer clearance alone is not sufficient when ECD authority is required.

## Authority by artifact class

| Artifact class | Quality requirement | ECD authority requirement |
|---|---|---|
| Internal research, validation, or studies | Producer Cleared when formally handed off | none unless the object itself asks the ECD to decide |
| Creative Treatment | Producer Cleared | Greenlit |
| New Creative Script | Producer Cleared | ECD-Aligned |
| Revision to an ECD-aligned Script | Producer Cleared | renewed alignment only when the Artifact Decision Contract changes an approved decision |
| Internal visual studies | Producer Cleared when formally used | none unless decision-bearing |
| New governing visual direction and representative proof | Producer Cleared | ECD-Aligned |
| Revision to an ECD-aligned visual direction | Producer Cleared | renewed alignment when an approved governing visual decision changes |
| Art Direction Package | Producer Cleared | all governing visual decisions must already have required authority |
| Final Assets | Producer Cleared final package | Final Accepted for publication / completion |

## Decision-bearing artifact rule

An artifact is decision-bearing when it establishes, selects, changes, or removes a decision that will constrain downstream work.

The authority requirement follows the artifact class and its delta, not a model's informal judgment that a choice “feels material.”

## State record

```markdown
Artifact:
Version:
Professional owner:

Quality state:
Specialist self-QA reference:
Producer Review Record:
Producer disposition:

Authority state:
Required ECD authority:
ECD-facing decision object:
ECD decision evidence:

Dependencies:
Artifact Decision Contract:
Active locks:
Open feedback:
Handoff Ready: [yes / no]
Blocking reason:
Next valid action:
```

## Decision evidence

An ECD decision record identifies:

- decision object and version;
- ECD-facing presentation reference;
- Producer Review Record and recommendation;
- decision scope and delta;
- items outside the decision;
- ECD response or authorization evidence;
- resulting authority state and locks.

An archive file alone is not decision evidence unless the ECD explicitly selected it as the review surface.

## Compact work

Compact work may combine records, but it must still distinguish:

- specialist self-QA;
- Producer clearance;
- ECD authority;
- dependencies and delta;
- Handoff Ready condition.

A proposal and its acceptance may never be merged into an inferred state.

## State QA

Reject or repair state when:

- Specialist QA is treated as Producer clearance;
- Producer clearance is treated as ECD approval;
- required ECD authority is missing;
- more than one version is treated as authoritative;
- a downstream artifact depends on a superseded version;
- an unauthorized delta is present;
- feedback closure is missing;
- a handoff or stage activation occurs before Handoff Ready.
