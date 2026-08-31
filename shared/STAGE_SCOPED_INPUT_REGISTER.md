# Stage-Scoped Input Register

## Purpose

A natural brief can contain information for several professional stages. This register preserves each material source statement once, keeps its authority visible, and activates only the projection relevant to the current stage.

Core principle:

> Information may arrive early; authority and execution remain stage-scoped.

## Authority classes

- **Hard Constraint** — explicit user requirement that remains binding until changed by the ECD.
- **User Preference** — stated preference open to professional interpretation.
- **Creative Seed** — promising idea to be developed rather than treated as a finished decision.
- **Reference Intent** — the role a supplied source or image is expected to play.
- **Existing Artifact** — prior professional object whose authority must be validated.
- **Assistant Inference** — studio interpretation; never promoted to user authority without evidence.
- **Requires Alignment** — consequential interpretation requiring ECD confirmation.

## Projection stages

### Global / Deliverable

Platform, surface, language, output count, format, publication context, supplied assets, and external-action constraints.

### Development

Premise, angle, proposition, audience consequence, factual or speculative boundaries, rights, and semantic guardrails.

### Editorial

Content units, sequence seeds, required or excluded information, copy constraints, evidence placement, and protagonist or claim boundaries.

### Visual / Art Direction

Visual hierarchy, spatial relationships, scale, mood, style, color, light, material, typography, composition, reference roles, and required visual behavior.

### Production

Exact dimensions, variants, file formats, asset-processing requirements, implementation tolerances, and delivery conditions.

## Statuses

- **Active Now** — current professional owner may use the projection.
- **Deferred** — preserved for a later stage.
- **Activated** — activation condition has been met and the projection has been handed off.
- **Resolved / Consumed** — faithfully incorporated into an accepted artifact.
- **Superseded** — replaced by a later authoritative decision.
- **Rejected** — explicitly excluded.
- **Conflict** — inconsistent with another active requirement and awaiting resolution.

Deferred does not mean optional. A Deferred Hard Constraint becomes binding when its stage activates.

## Register template

```markdown
# Stage-Scoped Input Register

Project:
Source brief / reference:
Last updated:

| ID | Source statement / artifact | Stage | Authority class | Professional interpretation | Status | Activation condition | Receiving owner | Alignment required |
|---|---|---|---|---|---|---|---|---|
| | | | | | | | | |

## Active Now
- ID / consequence

## Deferred — Editorial
- ID / source-faithful summary

## Deferred — Visual / Art Direction
- ID / source-faithful summary

## Deferred — Production
- ID / source-faithful summary

## Conflicts / Ambiguities
- ID / issue / consequence / decision owner

## Activation Log
- date / triggering artifact-state change / IDs / receiving owner / consequence
```

## Source-fidelity rule

Preserve the user's original wording or a faithful summary separately from the studio's interpretation. A downstream owner receives both.

When one source statement affects several stages:

1. record the source once;
2. create separate stage projections;
3. activate only the current-stage projection;
4. retain the original authority class;
5. avoid treating acceptance of one projection as acceptance of another.

## Activation protocol

### Intake to Development

Activate Global / Deliverable and Development projections. Keep Editorial, Visual, and Production projections Deferred.

### Greenlight to Editorial

Lock only the accepted Treatment decisions. Activate Editorial projections. Keep Visual and Production projections Deferred.

### Script handoff to Art Director

After the Creative Script is Accepted for Handoff and required Script Alignment is resolved, activate Visual projections. Transfer original reference assets, source wording, authority classes, and transfer boundaries.

### Art Direction handoff to Production Artist

After the Art Direction Package is Accepted for Handoff and required Visual Alignment is resolved, activate Production projections.

## No-repeat rule

Creative Producer carries registered inputs forward. The ECD is asked again only when:

- a later decision creates a conflict;
- the source meaning is materially ambiguous at activation;
- changed scope or evidence alters the consequence;
- the ECD explicitly reopens the matter.

## QA

Before every stage transition confirm:

- all material inputs are registered;
- source and inference remain distinguishable;
- current-stage projections are active;
- later-stage projections remain Deferred;
- the receiving owner has original context and authority class;
- every accepted artifact resolves only decisions belonging to its stage;
- unresolved conflicts have an identified decision owner.
