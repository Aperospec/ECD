# Lock and Rework Protocol

## Purpose

Locks protect accepted decisions from silent downstream drift while preserving targeted revision.

Use the canonical artifact states in `ARTIFACT_STATES.md` and the staged input rules in `STAGE_SCOPED_INPUT_REGISTER.md`. Do not use `approved` as an undefined state.

## Lock Principle

Lock only the decisions that downstream work must preserve. Record:

- artifact and version;
- authority;
- protected dimensions;
- related Stage-Scoped Input IDs when relevant;
- tolerances;
- reason for the lock;
- downstream artifacts depending on it.

Prefer decision-level locks over blanket artifact immobility.

A Deferred input is not locked as a downstream artifact merely because its source appeared before Greenlight. Preserve its authority class and activate it later.

## Normal Locks

### Greenlight Lock

A Greenlight Lock exists only when `GREENLIGHT_RECORD.md` identifies the Treatment and ECD authorization evidence.

It may protect:

- premise;
- selected angle;
- core proposition;
- audience takeaway;
- material public position or promise;
- reality / imagination boundary;
- claim, evidence, rights, and reference-use limits;
- what the project must not imply or become.

A material change reopens Development and requires ECD re-alignment.

Do not create a Greenlight Lock from generic project-initiation language or merely because Production has already started.

Greenlight does not create a Visual Lock or Production Lock from Deferred inputs in the original brief.

### Creative Script Lock

May protect:

- sequence and beat purpose;
- written Visual Beat meaning;
- exact names and required wording;
- evidence and limitation placement;
- opening promise and payoff;
- companion-copy position;
- resolution of Activated Editorial input IDs.

### Visual Lock

The most reliable visual lock is the accepted **Representative Design Comp**, supported by the Board and Art Direction Package.

May protect:

- visual thesis and world;
- hierarchy and reading path;
- title scale and typography personality;
- image–type depth relationship;
- cover and body-page grammar;
- evidence treatment;
- small-size behavior;
- accepted assets and visual identity;
- resolution of Activated Visual input IDs.

### Production Lock

May protect:

- exact dimensions and formats;
- crop and safe areas;
- final text composition;
- export variants;
- accepted final files;
- resolution of Activated Production input IDs.

## First-Failed-Owner Rule

When quality fails, identify the earliest professional object or state transition where the defect becomes true.

- source, fact, evidence, validation, rights, or reference-boundary failure → Research / Development;
- premise, insight, angle, proposition, Treatment, or public-promise failure → Development;
- absent, invalid, or falsely inferred Greenlight → Creative Producer;
- missing, misclassified, prematurely activated, or lost Stage-Scoped input → Creative Producer / Project State;
- sequence, written Visual Beat, copy, evidence placement, or content-progression failure → Editorial Director;
- Storyboard, Design Comp, visual concept, mood, hierarchy, typography direction, reference extraction, or composition failure → Art Director;
- crop, overflow, dimensions, font implementation, file format, export, or production defect → Production Artist;
- other state, authority, routing, or lock failure → Creative Producer.

Reopen only that object, affected input projections, and downstream artifacts actually invalidated by the change.

## Rework Record

```markdown
Triggering feedback:
Observed defect:
First professional object / state transition where the defect appears:
Responsible owner:
Artifact / decision reopened:
Stage-Scoped Input IDs affected:
Input projection state changes:
Reason:
Downstream artifacts invalidated:
Downstream artifacts still valid:
Deferred inputs still valid:
ECD involvement required:
Recommended smallest valid change:
New state after correction:
```

## Stage-Activation Failures

These are Project State / Creative Producer failures unless the source input itself was wrong.

Examples:

- the entire raw brief was flattened into the Treatment;
- a Deferred visual preference was interpreted into final palette / lighting / composition during Development;
- Greenlight activated visual production instead of Editorial only;
- Visual inputs activated before the Script was Accepted for Handoff;
- Production inputs activated before Art Direction was Accepted for Handoff;
- a Deferred Hard Constraint disappeared before its stage;
- the ECD was asked to repeat a stored input without a material reason;
- an Assistant Inference was reclassified as a user Hard Constraint.

Recovery procedure:

1. stop the incorrectly activated stage;
2. identify the affected source input and projections;
3. restore the original source and authority class;
4. return the premature projection to `Deferred` when appropriate;
5. invalidate only professional artifacts that depended on the premature activation;
6. restore the correct current stage;
7. continue from the next valid activation condition.

Do not force the ECD to restate unaffected inputs during recovery.

## Pre-Greenlight Production Violation

This is a state and authority failure owned by Creative Producer.

A violation has occurred when the studio creates or commissions any of the following before valid Greenlight:

- formal Creative Script;
- final page sequence or audience-facing production copy;
- Storyboard / Visual Sequence Board;
- Representative Design Comp;
- Art Direction Package;
- deliverable image generation or editing;
- layout, render, export, or final asset.

Recovery procedure:

1. stop further Production immediately;
2. mark the premature artifacts `Unauthorized / Invalid — pre-Greenlight`;
3. preserve them only as failure evidence or non-authoritative exploration when useful;
4. do not ask the ECD to accept them merely to repair the state retroactively;
5. return Project State to Development or Awaiting Greenlight;
6. restore the Stage-Scoped Input Register so downstream projections are Deferred;
7. present the Creative Treatment and request the missing decision;
8. after valid Greenlight, activate Editorial inputs only and determine whether any premature work can be reused without biasing or bypassing the proper downstream owner.

The existence, quality, or cost of premature work does not create authorization.

## Reopening Development

Development must reopen when the proposed correction changes what the project fundamentally is or says.

Examples:

- a central claim is disproven;
- commercial validation makes the promised proposition untenable;
- ECD changes the core premise or angle;
- an essential rights or reference foundation becomes unusable;
- scripting reveals there is no coherent content without changing the Treatment;
- audience takeaway materially changes.

Creative Producer records which Production artifacts are superseded and obtains a new Greenlight when required.

### Re-project inputs rather than discard them all

When Treatment changes:

- re-evaluate only source inputs whose Development meaning is affected;
- preserve unrelated Deferred Editorial / Visual / Production inputs;
- mark a Deferred input `Conflict` only when the new Treatment actually contradicts it;
- do not make the ECD re-provide visual or production preferences that remain valid.

Example:

A revised premise may supersede the Development interpretation of a reference while its original user-stated color preference remains a valid Deferred Visual input.

## Visual Rework Examples

- “Page 2 and Page 3 communicate the same thing.” → Editorial Director, even if their artwork differs.
- “The written Visual Beat is right, but the depicted scene is wrong.” → Art Director.
- “The visual world is too cold or commercial, while the premise remains correct.” → Art Director.
- “The accepted cover relationship was lost during assembly.” → Production Artist if the Comp was correct; Art Director if the Comp itself established the wrong hierarchy.
- “The body copy was already unreadably small in the Design Comp.” → Art Director.
- “The Design Comp was readable, but the export reduced it.” → Production Artist.
- “The studio started generating images immediately after my raw brief.” → Creative Producer; invalidate premature Production and restore the Greenlight gate.
- “I told you at the beginning that the second reference was only for color/style, but you asked me again after the Script.” → Creative Producer / Stage-Scoped Input Register; restore the stored visual input and continue without re-asking unless a real ambiguity now exists.
- “You turned my early visual preference into a mandatory Treatment rule.” → Creative Producer / Development; restore the correct authority and Deferred projection, then assess whether the Treatment lock itself needs correction.

## No Downstream Repair by Distortion

A downstream role must not solve its difficulty by:

- weakening or rewriting the Greenlit premise;
- hiding a required limitation;
- changing locked names, facts, or copy;
- replacing evidence with decoration;
- changing reference boundaries;
- violating an Activated user Hard Constraint for convenience;
- flattening a dimensional subject because masking is difficult;
- removing an accepted image–type relationship;
- shrinking essential information below the intended viewing condition;
- using text boxes or generic cards to avoid solving composition;
- regenerating the entire concept when a localized correction is sufficient;
- inventing or backdating Greenlight to legitimize premature work;
- consuming a Deferred future-stage input before activation.

## Propagation Rule

A changed upstream artifact does not automatically invalidate every later artifact or every Deferred input. Determine actual dependency.

Examples:

- punctuation correction may require only text recomposition;
- changed page title may affect one Design Comp and its final asset;
- changed beat purpose invalidates that beat's Board, Comp, Art Direction, and production;
- changed core proposition normally invalidates the entire Script and downstream visual work;
- changed core proposition does **not** automatically erase unrelated Deferred visual preferences;
- changed output dimensions may require Art Director review if hierarchy changes, otherwise Production Artist only;
- invalid Greenlight makes every artifact depending on that alleged authorization non-authoritative until the gate is restored;
- corrected input authority may require updating later-stage locks even when the source statement itself remains unchanged.

## ECD Gates

Return to the ECD when rework materially changes:

- what the project says or whether it should exist;
- the Creative Treatment requiring Greenlight;
- a public claim, promise, or position;
- material rights or attribution;
- a material Script interpretation not previously aligned;
- durable brand or visual identity;
- material mood, aesthetic, visual world, reference interpretation, or representative visual premise;
- material scope, cost, or external action;
- final subjective acceptance.

Routine craft corrections and restoration of previously supplied non-conflicting inputs remain with the responsible owner. Restoring a missing Greenlight is not routine craft correction.
