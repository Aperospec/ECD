# Stage-Scoped Input Register

## Purpose

A real ECD brief may contain Development, deliverable, editorial, visual, reference, and production information in the same user message.

The studio must capture that information once, preserve its original authority, and activate only the projection that belongs to the current professional stage.

The user is not responsible for separating a natural-language brief into internal workflow phases, and the studio must not ask the user to repeat information that has already been supplied.

This register prevents two opposite failures:

1. **premature execution** — downstream visual or editorial instructions are interpreted and locked during Development;
2. **instruction loss** — downstream information supplied early is forgotten and requested again after Greenlight.

## Core Principle

> Information may arrive early. Authority and execution remain stage-scoped.

A single source statement may create multiple professional projections.

Example:

```text
ECD source statement:
“建筑非常宏大，人很小。”

Development projection:
The work should communicate the scale and breadth of a person's life without positioning AI as the dominant observer.
Status: Active Now

Art Direction projection:
Monumental architectural scale with a comparatively small human figure.
Status: Deferred
Activation condition: Creative Script Accepted for Handoff
```

The Development projection may enter the Creative Treatment because it expresses meaning. The Art Direction projection is preserved but must not become an accepted composition decision merely because the Treatment is Greenlit.

## Input Authority Classes

Classify every material input projection as one of:

- **Hard Constraint** — an explicit user requirement that the responsible later stage must preserve unless the ECD changes it;
- **User Preference** — a stated preference that should guide the responsible stage but may be professionally interpreted;
- **Creative Seed** — an idea supplied by the ECD that the responsible stage should develop rather than treat as a finished decision;
- **Reference Intent** — what a supplied reference is intended to contribute;
- **Existing Artifact** — an already-created professional object whose authority must be separately validated;
- **Assistant Inference** — a professional interpretation derived from supplied material; never silently upgrade this to a user constraint;
- **Requires Alignment** — a materially ambiguous or consequential interpretation that requires ECD confirmation before it becomes authoritative.

Always preserve the distinction between what the ECD actually said and what the studio inferred.

## Stage Projections

Use only the projections that apply.

### Global / Deliverable Projection

Examples:

- target platform or surface;
- output format and count limit;
- language;
- publication context;
- supplied assets;
- irreversible external action constraints.

These may become active immediately because they define the Deliverable Contract rather than creative stage output.

### Development Projection

Use for:

- project premise;
- selected angle;
- core proposition;
- audience relevance and intended takeaway;
- semantic guardrails;
- reality / imagination / claim boundaries;
- rights and reference-use boundaries;
- what the project must preserve or must not imply.

Development should abstract downstream input only to the degree necessary to explain project meaning.

### Editorial Projection

Use for:

- possible content units;
- sequence or progression seeds;
- user-supplied scene, evidence, comparison, or chapter intentions;
- title or copy constraints supplied in advance;
- content that must or must not appear;
- protagonist or factual-content boundaries;
- body-copy requirements.

Editorial projections remain Deferred until a valid Greenlight activates Editorial Director.

### Visual / Art Direction Projection

Use for:

- scale, spatial, camera, lighting, color, material, mood, style, typography, or composition preferences;
- visual motifs and desired image–type relationships;
- reference-image attribute intent;
- visual elements the ECD explicitly requires or forbids;
- cover/body visual preferences.

Visual projections remain Deferred until the Creative Script is Accepted for Handoff and Creative Producer activates Art Director.

### Production Projection

Use for:

- exact technical dimensions not already in the Deliverable Contract;
- export variants;
- deterministic typography requirements;
- asset-processing restrictions;
- file-format and delivery requirements;
- implementation tolerances explicitly supplied by the ECD.

Production projections remain Deferred until the Art Direction Package is Accepted for Handoff.

## Projection Status

Each projection has one status:

- **Active Now** — the current professional owner may use it;
- **Deferred** — preserved but not available as a current-stage execution decision;
- **Activated** — its activation condition was met and it has been handed to the responsible owner;
- **Resolved / Consumed** — it has been faithfully incorporated into an accepted professional artifact;
- **Superseded** — replaced by a later ECD decision or authoritative artifact;
- **Rejected** — explicitly excluded from the project;
- **Conflict** — contradicts another active constraint and requires resolution.

`Deferred` does not mean optional or forgotten. A Deferred Hard Constraint remains binding when its stage activates.

## Register Template

```markdown
# Stage-Scoped Input Register

Project:
Source brief / turn:
Last updated:

| ID | Original input / source | Projection stage | Authority class | Professional interpretation | Status | Activation condition | Receiving owner | Alignment needed |
|---|---|---|---|---|---|---|---|---|
| I-01-D | | Development | | | Active Now | immediate | Development | |
| I-01-A | | Art Direction | | | Deferred | Creative Script Accepted for Handoff | Art Director | |

## Active Now

- IDs and concise consequence

## Deferred — Editorial

- IDs and source-faithful summary

## Deferred — Visual / Art Direction

- IDs and source-faithful summary

## Deferred — Production

- IDs and source-faithful summary

## Conflicts / Ambiguities

- ID / conflict / consequence / ECD gate if required

## Activation Log

- date / triggering artifact-state change / IDs activated / receiving owner / consequence
```

## Source-Fidelity Rule

For Deferred projections, preserve wording close to the ECD's actual instruction.

Do not perform downstream craft work merely to make the register sound sophisticated.

Example:

User says:

> “第二张图我喜欢它的色调、画风。”

Correct Deferred Visual record:

> Reference B: color palette and visual style preference. Detailed palette/style extraction is deferred to Art Director.

Incorrect Development record:

> “Use blue-gray, warm ivory, high cool skylight, and hand-painted concept-art grain.”

The incorrect version has already performed Art Direction during Development unless those exact qualities were explicitly supplied by the ECD.

## Cross-Stage Statement Rule

When one statement matters to multiple stages:

1. preserve one source statement;
2. create separate stage projections;
3. activate only the current-stage projection;
4. never treat acceptance of one projection as acceptance of the others.

A Greenlight can lock the Development meaning while the associated visual technique remains Deferred.

## Stage Activation Protocol

### Intake → Development

Activate:

- Deliverable Contract inputs;
- Development projections;
- evidence and reference-boundary questions required to form the Treatment.

Keep Editorial, Visual, and Production projections Deferred.

### Greenlight → Editorial

When the ECD Greenlights the identified Treatment:

1. lock only the accepted Treatment decisions and relevant Greenlight boundaries;
2. activate Deferred Editorial projections;
3. preserve Visual and Production projections as Deferred;
4. hand the activated Editorial projections, their original source, and authority class to Editorial Director;
5. do not generate Storyboard, Design Comp, or deliverable imagery merely because Greenlight exists.

Greenlight authorizes the **next stage: Creative Script development**. It does not approve or activate visual execution.

### Creative Script Accepted for Handoff → Art Director

Before Art Director starts:

1. confirm the Script faithfully resolved all Activated Editorial projections;
2. resolve any material Script Alignment required by the ECD;
3. activate Deferred Visual / Art Direction projections;
4. transfer the original references, source wording, authority class, and prohibited transfer boundaries;
5. keep Production-only projections Deferred.

Art Director must work from the original visual inputs plus the accepted Script, not from prematurely invented visual interpretations inside the Treatment.

### Art Direction Package Accepted for Handoff → Production Artist

Activate Production projections and transfer:

- accepted visual system;
- exact copy and asset requirements;
- technical constraints;
- export / variant requirements;
- implementation tolerances.

## Stage-Local Alignment

Activation is not the same as approval of the receiving stage's output.

When a stage produces a materially consequential interpretation, use the normal ECD alignment rules before locking it.

Examples:

- Treatment Greenlight does not approve page count or headlines;
- Script acceptance does not approve visual palette or composition;
- visual-reference preference does not approve Art Director's extraction until the representative visual direction is aligned when material;
- an early user-supplied hard constraint remains binding without being mistaken for approval of the whole downstream artifact.

## No Re-Ask Rule

Do not ask the ECD to repeat a downstream instruction already stored in this register.

Ask again only when:

- the stored instruction conflicts with a later decision;
- its meaning is materially ambiguous when activation occurs;
- the target surface or evidence changes its consequence;
- the ECD explicitly reopened the decision.

Otherwise Creative Producer must carry the input forward automatically.

## Treatment Boundary

The Creative Treatment may contain only the Development projection of a cross-stage input.

A Treatment may also include a concise **Deferred Input Notice** outside the authoritative Treatment body to reassure the ECD that later-stage instructions were captured. This notice is not part of the Greenlight lock and must not contain premature downstream interpretation.

Recommended format:

```markdown
Deferred inputs recorded, not part of this Greenlight:
- Editorial: [source-faithful user directions]
- Visual: [source-faithful user preferences / reference intents]
- Production: [when relevant]
```

## Failure Conditions

Hard failures include:

- copying all raw-brief information into the Creative Treatment regardless of stage;
- converting a Deferred visual preference into an Art Direction decision during Development;
- treating Greenlight as approval of Deferred Editorial or Visual projections;
- starting Storyboard or image generation immediately after Greenlight before Script handoff;
- losing a Deferred instruction and asking the user to repeat it later;
- upgrading an Assistant Inference into a Hard Constraint;
- failing to preserve the original source wording or reference intent;
- handing a downstream role a paraphrase that materially changes what the ECD supplied.

## QA

Before every stage transition confirm:

- all material source inputs are registered;
- current-stage projections are active;
- later-stage projections remain deferred;
- no Deferred input has been silently executed;
- no already-supplied input is being needlessly requested again;
- the receiving owner gets the original source context and authority class;
- the artifact being accepted resolves only the decisions that belong to its stage;
- stage-local ECD alignment is requested only where material.