# Stage-Scoped Input Register — V3.1

Constitution clauses: `SEM-016`, `SEM-037`.

## Purpose

A natural brief can contain information for several professional stages at once.

This register preserves each material source statement once, separates source wording from studio interpretation, creates stage-specific projections, and activates only the projection owned by the current authorized stage.

Core principle:

> Information may arrive early; authority and execution remain stage-scoped.

## Authority classes

Every material input receives one class.

- **Hard Constraint** — explicit ECD requirement that remains binding until changed by ECD authority.
- **User Preference** — stated preference open to professional interpretation and tradeoff.
- **Creative Seed** — promising idea to be developed, not treated as a completed decision.
- **Reference Intent** — the role the user expects a source or reference to play.
- **Existing Artifact** — a prior professional object whose identity and authority must be validated.
- **Assistant Inference** — a studio interpretation or temporary assumption; never promoted to ECD authority without evidence.
- **Requires Alignment** — a consequential interpretation that needs an explicit ECD decision before becoming authoritative.
- **External Constraint** — platform, legal, technical, budget, time, or tool condition established from a reliable source.

## Projection stages

One source statement may create several projections.

### Global / Deliverable

- intended use;
- audience and platform;
- language and locale;
- deliverable type, count, dimensions, variants, file requirements;
- deadline, publication, and irreversible-action conditions.

### Development

- premise, angle, proposition, audience consequence;
- factual, conceptual, commercial, rights, and reference boundaries;
- Evidence Obligation;
- excluded meanings or directions.

### Editorial

- required or excluded content;
- sequence seeds;
- terminology, voice, speaker position, claim and disclosure constraints;
- copy preferences and language conditions.

### Visual

- visual hierarchy, mood, scale, spatial relation, color, light, material, typography, composition, reference role, evidence treatment, image behavior, and identity conditions.

### Production

- exact dimensions, formats, file naming, editable layers, masks, variants, asset-processing conditions, implementation tolerances, export, delivery, and technical QA requirements.

## Statuses

- **Active Now** — current authorized owner may use this projection.
- **Deferred** — preserved for a later authorized stage.
- **Activated** — its activation condition was met and it has been handed to the receiving owner.
- **Resolved / Consumed** — faithfully incorporated into an accepted artifact or contract.
- **Superseded** — replaced by a later authoritative decision.
- **Rejected** — explicitly excluded.
- **Conflict** — inconsistent with another active requirement and awaiting resolution.
- **Stale Pending Revalidation** — depended on an upstream decision that has reopened.

Deferred does not mean optional. A Deferred Hard Constraint becomes binding when its stage activates.

## Register structure

```markdown
# Stage-Scoped Input Register

Project:
Register version:
Last updated:

| ID | Original wording / faithful summary | Source | Authority class | Projection stage | Studio interpretation | Status | Activation condition | Receiving owner | Alignment required | Dependency / conflict |
|---|---|---|---|---|---|---|---|---|---|---|
| | | | | | | | | | | |

## Active Now
- ID / current consequence

## Deferred — Editorial
- ID / source-faithful summary / activation condition

## Deferred — Visual
- ID / source-faithful summary / activation condition

## Deferred — Production
- ID / source-faithful summary / activation condition

## Conflicts / Ambiguities
- ID / issue / affected decision / decision owner / blocking consequence

## Activation Log
- date or turn / triggering authority change / IDs activated / receiving owner / artifact consequence

## Supersession Log
- date or turn / old ID or interpretation / new authority / affected artifacts
```

## Source-fidelity rule

Preserve the user's original wording or a faithful summary separately from studio interpretation.

A downstream owner receives both.

Do not rewrite a preference into a hard constraint, a seed into a completed direction, or an Assistant Inference into user authority.

## Multi-stage projection rule

When one statement affects several stages:

1. record the source statement once;
2. create separate projection rows for each affected stage;
3. preserve the same source and authority class;
4. activate only the current-stage projection;
5. keep later projections Deferred;
6. do not treat acceptance of one projection as acceptance of another.

Example structure without project-specific content:

```text
One user statement
├─ Development projection: intended meaning
├─ Editorial projection: copy constraint
├─ Visual projection: aesthetic preference
└─ Production projection: output requirement
```

Greenlight may accept the Development meaning while the copy, visual, and Production projections remain Deferred.

## Activation protocol

### Intake to Development

Activate:

- Global / Deliverable projections needed for initialization;
- Development projections.

Keep Editorial, Visual, and Production projections Deferred.

### Greenlight to Editorial

- lock only accepted Treatment decisions;
- activate relevant Editorial projections;
- preserve original source wording and current authority class;
- keep Visual and Production projections Deferred.

### Script Alignment to Visual

- activate relevant Visual projections;
- transfer exact copy, Frame Scripts, reference roles, evidence and rights conditions, and the original source statement;
- do not treat a prior broad preference as a fixed design unless its authority class supports that consequence.

### Visual Alignment / Art Direction to Production

- activate Production projections;
- transfer target geometry, variants, exact assets, masks, file requirements, tolerances, and technical conditions.

### Rework or reopening

- mark only dependent projections stale;
- preserve unrelated projections;
- reactivate at the earliest affected stage after authority is restored.

## No-repeat rule

Creative Producer carries registered inputs forward.

The ECD is asked to restate an input only when:

- the source meaning remains materially ambiguous at activation;
- a later decision creates a conflict;
- scope, evidence, rights, or feasibility changes its consequence;
- the user explicitly reopens it.

Do not ask again merely because a different department is now active.

## Temporary assumptions

A temporary assumption is recorded as `Assistant Inference` and includes:

- evidence supporting the inference;
- reversibility;
- affected stage;
- what would change if wrong;
- expiry or confirmation condition.

A temporary assumption cannot authorize an irreversible action or change an ECD-approved decision.

## Compact projects

Compact work may embed the register inside Project State rather than maintain a separate file.

Compression is valid only when the embedded record still preserves:

- original wording or faithful summary;
- authority class;
- stage projection;
- Active / Deferred status;
- activation condition;
- receiving owner;
- conflict and supersession history where material.

## Producer transition check

Before every stage transition confirm:

- all material inputs are registered;
- source wording and studio interpretation remain separate;
- current-stage projections are active;
- later-stage projections remain Deferred;
- accepted artifacts resolve only decisions belonging to their stage;
- receiving owners have the original context and authority class;
- conflicts have an identified decision owner;
- activation is recorded;
- no known input is being requested from the ECD a second time without cause.

## Quality gate

The register passes when early information survives without premature authority, each stage receives only its authorized projection, and downstream work can trace every material constraint or preference back to its source.
