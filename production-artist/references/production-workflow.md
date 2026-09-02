# Production Workflow

## Purpose

This workflow turns Producer Cleared Art Direction, required ECD visual authority, valid Copy-Aware Layout Maps, and Activated Production inputs into final Social Editorial assets without redefining upstream decisions or treating copy as an afterthought.

## Stage 0 — Production gate

Require:

- Deliverable Contract;
- Stage-Scoped Input Register;
- Activated Production inputs and capabilities;
- Greenlit Treatment;
- ECD-aligned Creative Script;
- accepted Frame Scripts and exact copy;
- governing visual authority records;
- accepted visual route, Storyboard, Production-intent Anchor Keyframes, and Design Comp as applicable;
- Copy-Aware Layout Maps for every Production-intent screen or valid page class;
- representative Type-Fit evidence and acceptance criteria;
- Producer Cleared Art Direction Package;
- current Artifact Decision Contracts and dependencies;
- source assets, provenance, rights, and transformation permissions;
- target dimensions, variants, safe areas, locks, tolerances, and fallbacks;
- Creative Producer assignment and acceptance criteria.

Production does not begin from specialist confidence alone.

No Production-intent image may be generated, selected, cropped, extended, or committed without valid Layout Map coverage.

Apply `../../art-director/references/copy-aware-composition.md`.

## Stage 1 — Input and asset review

Record consequences and risks for each active input.

Create an asset inventory:

```markdown
| Asset | Source / owner | Role | Image class | Layout Map | Transformation | Rights / attribution | Resolution | State | Risk |
|---|---|---|---|---|---|---|---|---|---|
```

Distinguish supplied, transformable, evidentiary, generated, edited, sourced, constructed, and fallback assets.

Classify visual assets as:

- `Exploratory` — may inform visual language but is not eligible for direct final use;
- `Production-intent` — eligible for final use and governed by an identified Layout Map.

An exploratory asset is not silently promoted because it is visually attractive.

## Stage 2 — Copy-aware preflight

For every final text-bearing screen verify:

- exact ECD-aligned copy and permitted compression;
- copy hierarchy;
- target geometry and safe areas;
- provisional or intended font metric;
- provisional line breaks;
- copy footprint and minimum readable scale;
- primary and secondary text zones;
- primary image–type relationship;
- protected subject, face, product, action, interface, and evidence zones;
- high-detail, low-detail, quiet, overlap, and occlusion zones;
- local contrast and layer-order requirements;
- crop, extension, variant, and mask requirements;
- Type-Fit acceptance criteria.

If this information is missing or contradictory, stop and return through Creative Producer to Art Director or the earliest affected owner.

A placeholder may be used only when metrically faithful to the exact copy. The actual copy must be tested before Production-intent imagery is committed.

## Stage 3 — Implementation and image brief

For each screen define:

- final dimensions and safe areas;
- source Script beat, Frame Script, and Art Direction reference;
- Copy-Aware Layout Map reference;
- exact copy blocks and hierarchy;
- background / environment layer;
- subject or evidence layer;
- typography and graphic layer;
- foreground layer when required;
- protected visual zones and required quiet regions;
- masks, depth, overlap, occlusion, and layer order;
- local contrast requirement;
- reusable components;
- variants and crop behavior;
- inherited decisions and tolerances;
- technical risk and accepted fallback.

Translate the Layout Map into a Production-intent image brief specifying:

- subject position, scale, orientation, and focal detail;
- background complexity and value behavior;
- regions that must remain quiet, dark, light, low-detail, extensible, or empty;
- regions that must not contain essential visual content;
- intended subject–type interaction;
- crop and extension latitude;
- required masks or editable separation;
- generation, sourcing, editing, and evidence constraints.

A generic instruction such as `leave room for text` is insufficient when the actual copy footprint or interaction is consequential.

## Stage 4 — Asset realization

Generate, edit, source, capture, or construct Production-intent assets from accepted Art Direction and Layout Maps.

Verify:

- required subject, action, state, relationship, and count;
- geometry, perspective, contact, scale, material, and light;
- consistency with accepted Anchors;
- fidelity to copy zones, protected zones, local contrast, and crop requirements;
- reference and rights boundaries;
- sufficient resolution and adaptation latitude;
- evidence authenticity and context where applicable.

Image assets normally exclude final publication text.

Generated pseudo-text or baked-in required audience copy cannot satisfy the Script. Required language remains separate, editable, reproducible, and exactly verifiable by default.

## Stage 5 — Deterministic typography and Type-Fit Proof

Compose exact copy in a controllable layout system.

Control:

- Unicode text and punctuation;
- language glyph coverage;
- accepted font or fallback;
- weight, width, size, tracking, leading, and alignment;
- semantic line breaks;
- wrapping and overflow;
- depth, masking, and occlusion;
- source, caption, and limitation hierarchy;
- repeatability across variants.

Compare every line against the ECD-aligned Script.

Then run Type-Fit Proof at target geometry and actual viewing width.

Confirm:

- exact wording and hierarchy;
- intended line behavior;
- copy footprint and minimum readable scale;
- image–type relationship and depth order;
- protected subject and evidence zones;
- local contrast without emergency repair;
- safe areas, crop, and representative variants;
- fidelity to the Layout Map and Design Comp.

The following fail the gate:

- shrinking required copy below the accepted readable threshold;
- changing copy or qualification without authority;
- abandoning hierarchy to preserve an image;
- obscuring essential visual content;
- adding opaque repair boxes outside the accepted visual system;
- approving only at full-resolution desktop zoom.

When Type-Fit fails, identify and reopen the earliest failed object rather than forcing the final layout.

## Stage 6 — Assembly and fit

Assemble each screen against Art Direction, Layout Map, Design Comp, and Type-Fit Proof.

Check:

- perceptual hierarchy;
- center of gravity and reading path;
- title and support relationship;
- subject–environment or evidence hierarchy;
- image–type depth;
- grid, margin, and negative space;
- body-page density;
- cross-page grammar and purposeful variation;
- safe areas and platform overlays.

Use the smallest adjustment allowed by recorded tolerances.

When fit requires a change to meaning, exact copy, hierarchy, Layout Map, visual route, or representative proof, stop and return through Creative Producer to the earliest affected owner.

## Stage 7 — Variants

Adapt each surface from the accepted visual premise and Copy-Aware Layout Map rather than relying on blind cropping.

For every variant, re-evaluate:

- exact copy and line breaks;
- copy footprint and minimum readable scale;
- protected visual zones;
- hierarchy and image–type relationship;
- evidence, crop, safe areas, and visual balance;
- Type-Fit result.

A material redesign returns through Creative Producer to Art Director.

## Stage 8 — Production self-QA

Run:

- Copy-Aware Layout Map presence and fidelity;
- Production-intent image-class verification;
- exact-copy and glyph verification;
- Type-Fit Proof;
- dimensions, orientation, and safe-area checks;
- feed-preview and actual-width readability;
- hierarchy and copy–image checks;
- geometry, perspective, contact, material, mask, edge, and light checks;
- protected-zone and local-contrast checks;
- evidence, rights, and attribution checks;
- cross-page consistency and differentiation;
- variant completeness;
- export-open and file-integrity checks;
- Artifact Decision Contract and implementation-delta check;
- applicable feedback check.

## Completion record

```markdown
# Production Completion Record

Project:
Art Direction Package:
Deliverable Contract:
Stage-Scoped Input Register:
Activated Production inputs:
Artifact Decision Contract:
Copy-Aware Layout Maps:

Final assets:
- filename / dimensions / format / role / image class / Layout Map

Variants:
- 

Production input resolution:
Asset provenance / attribution:
Production-intent image compliance:
Exact-copy verification:
Type-Fit Proof:
Mobile QA:
Technical QA:
Visual-proof fidelity:
Implementation delta:
Authorized deviations:
Known limitations:
Applicable feedback closure:
Open upstream issue:
Production self-QA:
Recommended Producer disposition:
Ready for Creative Producer Final Review: [yes / no]
```

## Specialist return

Production Artist returns the full package to Creative Producer.

It does not release final assets directly to the ECD or declare Final Acceptance.

## Producer Final Review

Creative Producer independently verifies:

- authoritative upstream decisions survived;
- exact copy and visual direction are preserved;
- every Production-intent screen has valid Layout Map coverage;
- image assets were developed or selected under copy-aware constraints;
- Type-Fit passed at target conditions without emergency repair;
- implementation delta is authorized;
- applicable ECD feedback is closed;
- assets, variants, rights, evidence, mobile QA, and technical QA are complete;
- limitations are disclosed;
- the final decision object is ready.

Defects return internally.

## Completion standard

Production self-QA passes when:

- every requested asset and variant exists;
- every Production-intent asset has traceable Layout Map coverage;
- exact copy is correct;
- Type-Fit passes at target viewing conditions;
- accepted visual relationships survive;
- active Production inputs are resolved;
- files pass mobile and technical QA;
- evidence, rights, attribution, and limitations remain correct;
- decision contract and deviations are recorded;
- the next action is Specialist Return to Creative Producer.

Final completion requires Producer clearance and explicit ECD Final Acceptance.
