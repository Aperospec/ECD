# Production Workflow

## Purpose

This workflow turns an accepted Art Direction Package into final Social Editorial assets without allowing technical convenience to redefine the work.

Production Artist owns exact realization, deterministic typography, variants, export, and technical finish. It does not own the premise, Script meaning, or visual direction.

## Stage 0 — Production Input Gate

Do not begin broad production until the following are identifiable:

- Deliverable Contract;
- accepted Creative Script;
- Storyboard / Visual Sequence Board when relevant;
- accepted Representative Design Comp or explicit reason it is unnecessary;
- Art Direction Package;
- exact audience-facing copy;
- source assets and provenance / transformation permissions;
- locked decisions, tolerances, and approved fallbacks;
- target dimensions, variants, language, and safe-area conditions.

Return to Creative Producer when execution would require inventing an unresolved visual premise.

## Stage 1 — Asset Inventory

Create an inventory at the depth required by complexity:

```markdown
| Asset | Source / owner | Role | Required transformation | Permission / attribution | Resolution | State | Risk |
|---|---|---|---|---|---|---|---|
```

Classify assets as:

- supplied and locked;
- supplied and transformable;
- evidence that must remain authentic;
- to be generated;
- to be edited or cleaned;
- to be sourced or captured;
- to be constructed deterministically;
- fallback only.

Do not reconstruct real evidence merely because a fictional version is visually easier.

## Stage 2 — Implementation Plan

For each screen define:

- final dimensions and safe areas;
- background / environment layer;
- typography / graphic-structure layer;
- hero / evidence layer;
- foreground detail layer when required;
- masks and overlap relationships;
- deterministic text blocks and semantic line breaks;
- reusable components;
- variants and crop behavior;
- production risk and fallback.

Preserve editable separation between imagery, typography, masks, and evidence whenever the toolchain permits.

## Stage 3 — Image and Asset Realization

### Original Imagery

When generating imagery:

- generate subjects, environments, lighting, texture, materiality, and visual effects without final publication text by default;
- leave intentional quiet zones or masking space defined by the Design Comp;
- preserve required depth planes;
- verify subject identity, count, pose, object state, action, and physical relationships;
- reject malformed geometry, impossible contact, inconsistent perspective, or accidental flatness;
- generate at sufficient resolution for final crop and export.

### Editing Supplied Images

When editing a supplied image:

- preserve the source elements the ECD intends to keep;
- avoid unnecessary global regeneration when a localized edit is sufficient;
- retain product, interface, face, object, or evidence fidelity as required;
- document material reconstruction or simulation;
- do not silently replace an actual screenshot with a fabricated interface.

### Evidence Assets

For screenshots, charts, documents, interfaces, or outputs:

- preserve the evidence itself;
- crop only what is irrelevant and safe to remove;
- retain source, date, version, region, labels, or limitations when required;
- annotate without covering critical evidence;
- distinguish observed output, source claim, simulation, and reconstruction.

### Masks, Edges, and Depth

Check:

- edge quality at final size;
- hair, transparent material, thin geometry, and soft boundaries;
- contact shadow and grounding;
- overlap order;
- realistic occlusion;
- consistent light direction;
- subject volume and perspective;
- no sticker-like halo unless intentionally designed.

## Stage 4 — Deterministic Typography

Final audience-facing copy should normally be composed with a deterministic renderer capable of exact text, line breaks, alignment, font selection, and export.

### Required Controls

- exact Unicode text and punctuation;
- correct language glyph coverage;
- approved font or permitted fallback;
- weight, width, size, tracking, leading, and alignment;
- semantic line breaks;
- text wrapping and overflow;
- masks or depth ordering for type–subject overlap;
- source, caption, and limitation hierarchy;
- repeatable output across variants.

### Font Fallback

When the preferred font is unavailable:

1. use the approved fallback in the Art Direction Package;
2. compare width, weight, x-height, CJK metrics, punctuation behavior, and hierarchy;
3. reflow inside permitted tolerances;
4. return to Art Director when the fallback changes the visual premise.

Do not substitute a materially different typography personality silently.

### Exact Copy Check

Compare every composed line against the accepted Creative Script. Verify:

- characters and punctuation;
- capitalization;
- names, numbers, dates, and versions;
- negation and qualification;
- source and attribution;
- required limitation;
- line breaks that carry meaning.

## Stage 5 — Layout Assembly

Assemble each screen against the accepted Design Comp and Art Direction Package.

Check:

- first-, second-, and third-glance hierarchy;
- center of gravity and reading path;
- title scale and confidence;
- image–type overlap and recognition;
- grid, margin, and negative-space behavior;
- body-page density;
- evidence visibility;
- subject volume and grounding;
- safe areas and platform overlays;
- cross-page shared grammar and intentional variation.

A layout is not complete merely because all elements fit inside the canvas.

## Stage 6 — Overflow and Fit Repair

Use the smallest authorized change.

Repair order:

1. apply accepted line breaks and text widths;
2. use approved alternate copy compression already supplied by Editorial Director;
3. adjust spacing or geometry inside Art Direction tolerances;
4. use an approved font fallback;
5. return to Art Director if hierarchy or composition must change;
6. return to Editorial Director if wording must change.

Forbidden repairs:

- hiding text outside crop;
- reducing required copy to decorative size;
- removing qualifications;
- covering evidence;
- adding generic text boxes without Art Direction support;
- flattening or shrinking the hero to avoid masking;
- changing the title to something easier to typeset.

## Stage 7 — Variants and Surface Adaptation

For each variant:

- begin from the accepted visual premise, not a blind crop;
- preserve dominant hierarchy and meaning;
- re-evaluate safe areas and UI overlays;
- adjust composition when aspect-ratio change materially alters relationships;
- route to Art Director when adaptation becomes a redesign;
- verify exact copy and evidence independently.

## Stage 8 — Mobile and Technical QA

Run `mobile-qa.md` on representative proofs and final exports.

Critical failures block delivery regardless of overall visual score:

- wrong or corrupted text;
- primary message unreadable at target size;
- required evidence or limitation hidden;
- invalid dimensions or broken files;
- unauthorized reference or asset use;
- material drift from accepted Design Comp;
- unapproved change to Script meaning.

## File and Export Rules

Unless the Deliverable Contract specifies otherwise:

- use clear, stable filenames;
- include screen order with zero-padded numbers for sequences;
- separate preview and final files;
- avoid accidental metadata or working-layer exposure when privacy matters;
- verify orientation, resolution, color behavior, alpha, and compression;
- open exported files after writing them;
- confirm every requested variant exists and is not duplicated or stale.

Example naming:

```text
project_cover_01_1080x1440_v03.png
project_body_02_1080x1440_v03.png
project_story_01_1080x1920_v03.png
```

## Completion Record

```markdown
# Production Completion Record

Project:
Art Direction Package version:
Representative Design Comp version:
Deliverable Contract reference:

Final assets:
- filename / dimensions / format / role

Variants:
- 

Asset provenance and attribution state:
Exact-copy verification: [pass / fail / note]
Mobile QA: [pass / fail / note]
Technical QA: [pass / fail / note]
Visual-comp fidelity: [pass / fail / note]
Authorized deviations:
Known limitations:
Upstream issue still open:
Ready for Creative Producer Final Review: [yes / no]
```

## Production Completion Standard

Production is complete only when:

- every requested asset and variant exists;
- exact copy is correct;
- accepted visual relationships survive;
- files pass mobile and technical QA;
- evidence, limitations, and attribution remain visible;
- unauthorized deviations are absent;
- known limitations are recorded;
- Creative Producer can review the package without reconstructing production history.
