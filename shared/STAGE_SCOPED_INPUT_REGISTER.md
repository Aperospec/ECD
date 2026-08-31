# Stage-Scoped Input Register

## Purpose

A real ECD brief may contain Development, deliverable, editorial, visual, reference, language, and production information in one message.

The studio must capture that information once, preserve original authority, and activate only the projection belonging to the current professional stage.

The user is not responsible for translating natural-language intent into internal workflow language.

This register prevents:

1. premature execution;
2. instruction loss;
3. authority drift;
4. reference over-transfer;
5. forcing the ECD to repeat or professionalize an already useful intuition.

## Core Principle

> Information may arrive early. Interpretation, authority, and execution remain stage-scoped.

One source statement may create multiple projections.

Example:

```text
ECD source:
“建筑非常宏大，人很小。”

Development projection:
The work should communicate the breadth and scale of a person's life.
Status: Active Now

Visual-intent projection:
The ECD values a world-to-human scale contrast.
Status: Deferred until Visual activation

Art-direction projection:
Explore monumental environmental scale with a comparatively small human figure.
Status: Needs interpretation / alignment; not yet a locked composition.
```

Acceptance of one projection does not accept the others.

## Input Authority Classes

- **Hard Constraint** — explicit requirement that the responsible stage must preserve unless the ECD changes it;
- **User Preference** — stated preference that should guide professional interpretation;
- **Creative Seed** — idea to develop, not a finished decision;
- **Reference Intent** — why a reference was supplied and which role it may serve;
- **Aesthetic Judgment** — approval or rejection such as “this feels right” or “this is ugly”; valid evidence whose cause must be diagnosed;
- **Existing Artifact** — prior professional object whose authority must be validated;
- **Assistant Inference** — studio interpretation; never user authority;
- **Requires Alignment** — consequential ambiguity or alternative requiring ECD confirmation.

Always preserve the original ECD source separately from the professional translation.

## Stage Projections

### Global / Deliverable

- platform, surface, aspect ratio, count limit;
- language and locale;
- publication context;
- supplied assets;
- output / external-action constraints.

These may activate immediately.

### Development

- premise, angle, proposition;
- audience relevance and takeaway;
- semantic guardrails;
- reality / imagination / claim boundaries;
- rights and reference-use boundaries;
- what the project must preserve or not imply.

### Editorial / Copy

- possible content units and sequence seeds;
- required or forbidden content;
- title / wording constraints;
- protagonist and fictional-content boundaries;
- body-copy requirements;
- target voice, language, and locale.

Activate after Greenlight.

### Visual Research / Intent

Use for early or newly introduced visual material that requires professional interpretation:

- natural-language visual intuitions;
- “this image feels right” statements;
- metaphor seeds;
- aesthetic approval or rejection;
- reference-role ambiguity;
- world-versus-character priorities;
- qualities the ECD cannot or need not express technically.

Activate after Creative Script handoff, or immediately inside an already active Art Direction stage.

These are not production prompts.

### Visual Direction

- scale, spatial, camera, lighting, color, material, mood, style, typography, or composition preferences;
- world / scene rules;
- reference-image attribute intent;
- visual motifs and image–type relationships;
- visual elements explicitly required or forbidden.

These become executable only after Visual Problem Framing and reference / metaphor interpretation. Some remain `Needs Alignment` until a Concept Route is accepted.

### Production

- exact dimensions not already global;
- export variants;
- asset-processing restrictions;
- deterministic typography requirements;
- file-format and delivery rules;
- implementation tolerances.

Activate only after valid Art Direction handoff.

## Projection Status

- **Active Now** — current owner may use the input;
- **Deferred** — preserved but not current-stage executable;
- **Needs Interpretation** — active as research but not yet an execution decision;
- **Proposed Translation** — professional interpretation awaiting acceptance or internal validation;
- **Activated** — handed to the responsible owner as executable input;
- **Resolved / Consumed** — faithfully incorporated into an accepted artifact;
- **Superseded** — replaced by later authority;
- **Rejected** — explicitly excluded;
- **Conflict** — contradicts another active condition.

A Deferred or Needs-Interpretation Hard Constraint remains material. These states do not mean optional.

## Register Template

```markdown
# Stage-Scoped Input Register

Project:
Source brief / turn:
Last updated:

| ID | Original input / source | Projection stage | Authority class | Professional interpretation | Status | Activation / interpretation condition | Receiving owner | Alignment needed |
|---|---|---|---|---|---|---|---|---|
| I-01-D | | Development | | | Active Now | immediate | Development | |
| I-01-VI | | Visual Research | Aesthetic Judgment | | Deferred | Script Accepted for Handoff | Art Director | yes / maybe |
| I-01-VD | | Visual Direction | Assistant Inference | | Needs Interpretation | Visual Problem Statement | Art Director | |

## Active Now

- IDs and consequence

## Deferred — Editorial / Copy

- 

## Deferred — Visual Research / Intent

- 

## Deferred — Visual Direction

- 

## Deferred — Production

- 

## Conflicts / Ambiguities

- ID / issue / consequence / ECD gate

## Interpretation Log

- date / source input / hypothesis / evidence / ECD response / professional translation

## Activation Log

- date / triggering artifact-state change / IDs activated / receiving owner / consequence
```

## Source-Fidelity Rule

Preserve wording close to what the ECD actually supplied.

User says:

> “这张图画面内容很棒，人生档案馆恰恰是一个人生游乐场。”

Correct record:

```text
Reference Intent / Creative Seed:
The ECD sees the supplied amusement-world image as conceptually compatible with a life archive and values the idea of a life that can be entered and explored.

Status:
Needs Interpretation.

Next professional work:
Visual Problem Framing, reference-role reading, metaphor mapping, and ECD-friendly alignment.
```

Incorrect record:

```text
Production instruction:
Generate six mountain amusement-park scenes in blue-orange sunset lighting.
```

The incorrect record invents content, style, quantity, and execution authority.

## Cross-Stage Statement Rule

When one statement matters to multiple stages:

1. preserve one source statement;
2. create separate stage projections;
3. activate only the current-stage projection;
4. distinguish research interpretation from executable direction;
5. never treat acceptance of one projection as acceptance of the others.

## Stage Activation Protocol

### Intake → Development

Activate global and Development projections. Keep Editorial, Visual, and Production projections Deferred.

### Greenlight → Editorial / Copy

- lock only accepted Treatment decisions;
- activate Editorial / Copy projections;
- keep Visual and Production Deferred;
- no Storyboard or deliverable imagery.

### Creative Script Accepted for Handoff → Visual Research / Intent

1. confirm Script and any required Script Alignment;
2. activate Visual Research / Intent inputs first;
3. preserve original references, source wording, and authority classes;
4. create Visual Problem Statement;
5. perform intent elicitation, reference reading, and metaphor mapping;
6. translate accepted interpretations into Visual Direction inputs;
7. keep Production Deferred.

Visual activation is not permission for broad image production.

### Visual Direction Alignment → Formal Development

After a Concept Route is accepted:

- mark route-level visual inputs Activated / Resolved as appropriate;
- permit thumbnails, value, spatial, scale, motion, and Storyboard studies;
- do not activate broad Production.

### Anchor / Design Alignment → Art Direction Completion

After representative anchors and Design Comp are accepted:

- lock only proven visual relationships;
- complete Color Script and Art Direction Package;
- keep Production Deferred until handoff acceptance.

### Art Direction Package Accepted for Handoff → Production

Activate Production projections and transfer accepted route, anchors, Design Comp, Color Script, exact copy, technical constraints, variants, and tolerances.

## New Visual Input During Art Direction

When the ECD introduces a new reference or statement after Visual activation:

1. register it as new source input;
2. classify whether it is Reference Intent, Preference, Creative Seed, Aesthetic Judgment, Hard Constraint, or Requires Alignment;
3. identify which existing visual object it affects;
4. reopen the earliest affected object when material;
5. preserve unaffected work;
6. do not feed the new reference directly into batch generation.

Examples:

- new color-only reference may reopen Style Board or Color Script;
- new world-structure reference may reopen Visual Problem, Reference Reading, Concept Route, and anchors;
- “this whole direction is ugly” requires critique and first-failed-object diagnosis;
- a small texture preference may remain a routine Art Direction adjustment.

## No Re-Ask Rule

Do not ask the ECD to repeat a stored instruction or translate it into specialist language.

Ask again only when:

- stored instructions conflict;
- interpretation remains materially ambiguous after professional analysis;
- the target surface or evidence changes the consequence;
- the ECD explicitly reopens the decision.

Art Director should present a hypothesis and discriminating question rather than an empty request for specification.

## Failure Conditions

- flattening the full brief into one stage;
- losing a Deferred instruction;
- converting an Aesthetic Judgment into guessed execution details;
- treating a raw reference as a production prompt;
- activating Visual Direction before intent / reference interpretation;
- treating Script Alignment as approval of palette, composition, or world;
- beginning a full image batch immediately after Visual activation;
- asking the ECD to write prompt syntax or choose professional jargon;
- upgrading Assistant Inference into user authority;
- failing to preserve the original source wording.

## QA

Before every transition confirm:

- all material source inputs are registered;
- original source and professional interpretation remain distinct;
- current-stage projections are active;
- later-stage projections remain Deferred;
- visual research inputs have not been mistaken for production direction;
- no already supplied input is being needlessly requested again;
- receiving owners get source context and authority class;
- current artifacts resolve only their own stage decisions;
- ECD alignment is requested only where material and with a complete decision object.
