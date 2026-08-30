# Art Direction Package

## Purpose

The Art Direction Package is the formal Art Director handoff to Production Artist.

It converts an accepted Creative Script, resolved Storyboard direction, Representative Design Comp, and **Activated Visual / Art Direction inputs** into a visual system that can be executed without Production Artist inventing creative decisions.

## Required Input Gate

Before final Art Direction, confirm:

- Creative Script is Accepted for Handoff;
- required ECD Script Alignment is resolved;
- Stage-Scoped Input Register is identified;
- Activated Visual / Art Direction input IDs are identified with original source and authority class;
- Visual Beats and final / accepted copy are identified;
- original reference assets and intended-use boundaries are known;
- Storyboard / Visual Sequence Board has resolved the sequence-level visual questions;
- Representative Design Comp has resolved high-risk hierarchy / typography / reference-interpretation questions when required;
- any required ECD Visual Alignment is complete or explicitly pending;
- target surface / viewing condition is known to the degree required for design;
- Production inputs remain Deferred until this package is Accepted for Handoff.

## Required Output

```markdown
# Art Direction Package

## 0. Input Fidelity and Stage State

Greenlit Creative Treatment:
Accepted Creative Script:
Stage-Scoped Input Register:
Activated Visual input IDs:
Deferred Production input IDs:
Storyboard / Visual Board state:
Representative Design Comp state:
Reference intent and boundaries:
Locked editorial content:

## 1. Activated Visual Input Resolution

For every Activated Visual / Art Direction input:

| Input ID | Original ECD source | Authority class | Art-direction resolution | State after package | Alignment consequence |
|---|---|---|---|---|---|
| | | Hard Constraint / User Preference / Creative Seed / Reference Intent / Assistant Inference | | Resolved / Superseded / Conflict / Open | |

Confirm:

- no user Hard Constraint was silently dropped;
- User Preferences were professionally interpreted rather than automatically locked;
- Assistant Inference was not presented as user authority;
- original reference intent was preserved;
- only authorized reference attributes were extracted.

## 2. Visual Direction

Visual thesis:
[one sentence]

Mood / atmosphere:
[what should be felt]

Aesthetic stance:
[what kind of visual world this is and is not]

Reference attributes applied:
[attributes only, with source input IDs]

Reference attributes intentionally not used:
[when relevant]

Prohibited reference transfer:
[subjects / scenes / branded devices / exact composition etc.]

## 3. Shared Visual System

- typography personality and hierarchy;
- color relationships;
- lighting / atmosphere behavior when relevant;
- grid / margin behavior;
- image treatment;
- surface / texture behavior;
- source / evidence treatment;
- recurring identifiers when accepted;
- variables that must remain flexible.

## 4. Screen-by-Screen Direction

For each screen:

### Screen [number]

Creative Script source:
[beat / Visual Beat]

Activated Visual input IDs served:

Accepted Storyboard direction:
[reference or none]

Representative Design Comp reference:
[when applicable]

First glance:
[primary perception]

Second glance:
[title / decisive explanation]

Third glance:
[support / evidence / limitation when relevant]

Primary visual task:
[image-led / evidence-led / diagram-led / type-led / quiet / other]

Composition intent:
[center of gravity, reading path, depth, negative space]

Typography–image relationship:
[overlap / separation / depth / contour / quiet-zone relationship]

Asset direction:
[what needs to be generated, sourced, captured, or constructed]

Protected meaning:
[what must not be visually lost]

Small-size / viewing-condition rule:
[what must survive]

Production tolerances:
[what Production Artist may adjust]

Forbidden drift:
[what Production Artist may not change]

## 5. Sequence Rhythm

- energy curve;
- density variation;
- image / type variation;
- cover-to-body relationship;
- evidence distribution;
- how repetition is avoided without losing identity.

## 6. Production Plan

- required assets;
- image-generation or image-processing tasks;
- deterministic text-composition requirements;
- font requirements / fallbacks;
- crop / safe-area intent;
- output variants;
- quality proofs required;
- technical risks and accepted fallbacks;
- Production input IDs ready for activation after handoff.

## 7. ECD Visual Alignment Record

- alignment required: [yes / no]
- why the visual interpretation is or is not material:
- representative proof used:
- ECD direction / correction:
- accepted visual premise:
- activated visual input IDs affected:
- what became locked:

## 8. Art Direction QA

Confirm:

- Art Direction expresses the Greenlit premise and Accepted Creative Script;
- every Activated Visual input has a resolution state;
- the original ECD visual source and authority class were preserved;
- Storyboard content came from our Visual Beats rather than copied reference scenes;
- detailed reference extraction happened only after visual activation;
- every screen has one clear visual task;
- typography supports rather than rewrites editorial meaning;
- body pages are designed for the actual viewing condition, not as reduced print-magazine pages;
- cover promise and sequence visual language are coherent;
- evidence / limitation remains visible where required;
- Production inputs have not been executed prematurely;
- Production Artist can execute without inventing creative logic.
```

## Boundary Rule

Art Direction may reinterpret *how* a Visual Beat is shown. It may not rewrite *what* the beat means.

It may professionally interpret an Activated User Preference. It may not silently violate an Activated Hard Constraint or upgrade an Assistant Inference into ECD authority.

If the only way to make the design work is to change sequence, copy meaning, evidence, the Greenlit premise, or a user Hard Constraint, return the problem upstream through Creative Producer.

## Production Activation Rule

The Art Direction Package itself does not activate Production merely by existing.

Creative Producer must:

1. resolve required ECD Visual Alignment;
2. mark this package `Accepted for Handoff`;
3. activate Deferred Production inputs in the Stage-Scoped Input Register;
4. then route the package and Activated Production inputs to Production Artist.
