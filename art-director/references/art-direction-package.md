# Art Direction Package

## Purpose

The Art Direction Package is the formal Art Director handoff to Production Artist.

It converts the Accepted Creative Script, selected visual route, resolved Storyboard, accepted Anchor Keyframes, Representative Design Comp, Color Script, and Activated Visual inputs into a system that can be executed without Production Artist inventing or repairing creative direction.

## Required Input Gate

Before final Art Direction, confirm:

- Creative Script is Accepted for Handoff;
- required ECD Script Alignment is resolved;
- Stage-Scoped Input Register and Activated Visual inputs are identified;
- Visual Problem Statement is stable;
- material references have Reading / Transfer Records;
- Visual Metaphor Map exists when relevant;
- Concept Route is selected and any required Visual Direction Alignment is resolved;
- Storyboard / Visual Sequence Board stages the sequence;
- Anchor Keyframe Gate passed or a valid bypass is recorded;
- Representative Design Comp passed when typography / layout is material;
- required Anchor / Design Alignment is resolved;
- Color Script / sequence logic exists when material;
- Production inputs remain Deferred until this package is Accepted for Handoff.

## Required Output

```markdown
# Art Direction Package

## 0. Source and State

Greenlit Creative Treatment:
Accepted Creative Script:
Stage-Scoped Input Register:
Activated Visual input IDs:
Deferred Production input IDs:
Visual Problem Statement:
Reference Reading Records:
Visual Metaphor Map:
Selected Concept Route:
Visual Direction Alignment state:
Storyboard state:
Anchor Keyframe Gate state:
Representative Design Comp state:
Anchor / Design Alignment state:
Color Script state:
Locked editorial content:

## 1. Activated Visual Input Resolution

| Input ID | Original ECD source | Authority class | Art-direction resolution | State | Alignment consequence |
|---|---|---|---|---|---|
| | | | | Resolved / Superseded / Conflict / Open | |

Confirm:

- no visual Hard Constraint was silently dropped;
- User Preferences were interpreted rather than automatically made immutable;
- Aesthetic Judgments were diagnosed and translated;
- Assistant Inference was not presented as ECD authority;
- original reference intent was preserved;
- only authorized reference roles and qualities were used.

## 2. Governing Visual Direction

Visual thesis:
[one sentence]

Visual problem solved:
[what is now made perceptible]

World / scene logic:
[how the visual environment or system operates]

Subject–environment hierarchy:
[what leads and what supports]

Mood / atmosphere:
[what should be felt]

Aesthetic stance:
[what kind of visual world this is and is not]

Visual metaphor:
[target / source / relational invariant / literalization traps]

Reference principles applied:
[principles and source IDs]

Reference content intentionally rejected:
[scenes, objects, composition, branding, genre defaults]

## 3. Formal System

- dominant shape and silhouette logic;
- space and depth behavior;
- scale relationships;
- line / motion / path behavior;
- value structure;
- color relationships;
- light-source and atmosphere logic;
- material and surface behavior;
- density and negative-space behavior;
- salience and reading path;
- viewer position and psychological distance.

## 4. World / Continuity System

When relevant:

- regions or page classes;
- route / connection logic;
- entrances, thresholds, loops, overlooks, absence, or unfinished areas;
- recurring environmental grammar;
- how close views remain part of the establishing world;
- how characters function: protagonist, guide, evidence of use, scale marker, or background;
- what breaks world continuity;
- what must never appear.

## 5. Anchor System

World / Cover Anchor:
- accepted proof:
- decisions locked:
- permitted variation:

Representative Body Anchor:
- accepted proof:
- decisions locked:
- permitted variation:

Additional distinct page-class anchor:
- reason:
- accepted proof:

## 6. Typography and Page Design

- typography personality and hierarchy;
- title / deck / support relationships;
- semantic line breaks;
- grid and margin behavior;
- image–type overlap and masking;
- source / evidence / limitation treatment;
- cover and body-page grammar;
- mobile-first reading conditions;
- accepted Design Comp references;
- permitted layout tolerances.

## 7. Screen-by-Screen Direction

For each screen:

### Screen [number]

Creative Script source:
Activated Visual input IDs served:
Storyboard reference:
Anchor / Comp reference:

First glance:
Second glance:
Third glance:

Primary visual task:
World / scene role:
Subject–environment hierarchy:
Composition and value intent:
Depth / scale / movement intent:
Color / light state:
Typography–image relationship:
Asset direction:
Protected meaning:
Small-size rule:
Production tolerances:
Forbidden drift:

## 8. Sequence Rhythm and Color Script

- energy curve;
- scale progression;
- density variation;
- value progression;
- color / light progression;
- image-led / type-led / quiet-page rhythm;
- cover-to-body relationship;
- payoff behavior;
- how repetition is avoided without losing world identity.

## 9. Production Plan

- required assets;
- image-generation or image-processing tasks;
- which assets must derive from anchors rather than raw references;
- deterministic typography requirements;
- font requirements and fallbacks;
- masks, depth planes, and editable separation;
- crop / safe-area intent;
- output variants;
- quality proofs required;
- technical risks and accepted fallbacks;
- Activated Production input IDs after handoff.

## 10. ECD Visual Alignment Records

Visual Direction Alignment:
- object shown:
- ECD source response:
- professional translation:
- decisions aligned:

Anchor / Design Alignment:
- objects shown:
- ECD source response:
- professional translation:
- decisions aligned:

What remains open for Production:

## 11. Art Direction QA

Confirm:

- the package solves the accepted Visual Problem Statement;
- Art Direction preserves Treatment and Script meaning;
- every Activated Visual input has a resolution state;
- the ECD's source language and the Art Director's interpretation remain distinguishable;
- the visual metaphor transfers relations rather than decorative objects;
- references were read and transformed rather than copied;
- the selected Concept Route remains coherent across all pages;
- Storyboard and anchors prove sequence and image world;
- Representative Design Comp proves page design where material;
- Color Script creates progression rather than one repeated grade;
- every screen has one clear visual task;
- Production inputs have not been executed prematurely;
- Production Artist can execute without inventing visual logic.
```

## Boundary Rule

Art Direction may reinterpret *how* a Written Visual Beat is shown. It may not rewrite *what* the beat means.

It may interpret an Activated User Preference. It may not silently violate a Hard Constraint, turn an Aesthetic Judgment into a guessed requirement, or upgrade Assistant Inference into ECD authority.

If the only way to make the design work is to change sequence, copy meaning, evidence, the Greenlit premise, or a user Hard Constraint, return upstream through Creative Producer.

## Raw Reference Prohibition

Production Artist must not receive a raw reference image as the principal prompt or governing source when the Art Direction Package already exists.

The package must translate references into:

- accepted structural principles;
- formal rules;
- world logic;
- anchors;
- prohibited transfer;
- production tolerances.

## Production Activation Rule

The package does not activate Production merely by existing.

Creative Producer must:

1. confirm Visual Direction and Anchor / Design Alignment are resolved where required;
2. confirm Anchor Keyframe Gate passed or valid bypass is recorded;
3. mark this package `Accepted for Handoff`;
4. activate Deferred Production inputs;
5. route the package, anchors, Design Comps, Color Script, and Activated Production inputs to Production Artist.

Broad production before this transition is unauthorized.
