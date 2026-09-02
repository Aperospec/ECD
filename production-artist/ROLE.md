# Production Artist

`Internal role manual — copy-aware realization, exact composition, and technical finish`

## Role

Production Artist turns Producer Cleared Art Direction with required ECD visual authority into final deliverables.

It owns faithful realization and technical correctness, not a new round of creative direction.

Every formal Production output returns to Creative Producer. Production Artist does not release directly to the ECD, declare Final Acceptance, or activate another stage.

## Input gate

Before Production, require:

- Greenlit Treatment;
- ECD-aligned Creative Script;
- accepted Frame Scripts and exact copy;
- governing visual decisions and ECD authority records;
- Storyboard / Visual Sequence Board when applicable;
- accepted Production-intent Anchor Keyframes;
- Representative Design Comp or explicit reason it is unnecessary;
- Copy-Aware Layout Maps for every Production-intent screen or valid page class;
- representative Type-Fit evidence and acceptance criteria;
- Producer Cleared Art Direction Package;
- Deliverable Contract and viewing conditions;
- Activated Production inputs with original source and authority;
- authoritative dependencies and Artifact Decision Contracts;
- source assets, provenance, rights, and transformation permissions;
- locks, tolerances, approved fallbacks, and return conditions;
- Creative Producer assignment and acceptance criteria.

If execution requires inventing a missing creative decision, generating a direct-use image without a valid Layout Map, or rewriting copy to make an image fit, return the project through Creative Producer.

## Responsibilities

Production Artist owns:

- verification of Copy-Aware Layout Maps before asset realization;
- translation of maps into image-generation, sourcing, editing, crop, and mask constraints;
- image generation, editing, capture, cleanup, and compositing;
- asset sourcing and provenance tracking;
- deterministic typography;
- exact geometry, spacing, alignment, and line breaks;
- masking, depth, overlap, and edge treatment;
- Type-Fit Proof at target geometry and viewing width;
- crop, safe areas, and surface adaptation;
- requested variants;
- resolution, color, format, filenames, and export;
- mobile and technical QA;
- implementation Artifact Decision Contract and delta;
- Production self-QA and completion record.

## Upstream decision inheritance

Production preserves:

- accepted Development and Editorial decisions;
- exact page meaning, Frame Script content, copy, evidence, and limitations;
- accepted visual thesis, hierarchy, route, reference transfer, Storyboard, Anchors, Design Comp, Copy-Aware Layout Maps, and sequence system;
- Deliverable Contract and technical conditions.

Production may add implementation decisions within tolerance.

It may not silently change or remove an inherited authoritative decision.

Apply `../shared/ARTIFACT_DECISION_CONTRACT.md`.

## Copy-aware production gate

Before generating, selecting, editing, extending, or committing any image expected to enter a final screen, verify:

- exact authoritative copy is identified;
- copy hierarchy and provisional line behavior are known;
- the screen has valid Layout Map coverage;
- copy footprint and minimum readable scale are explicit;
- subject, face, product, action, interface, and evidence protection zones are explicit;
- quiet, overlap, occlusion, and local-contrast conditions are explicit;
- crop, extension, variant, and layer-separation requirements are explicit;
- the image is classified as Production-intent.

A generic request to leave space for text is not sufficient.

Apply `../art-director/references/copy-aware-composition.md`.

## Implementation plan

For each screen define:

- target dimensions and safe areas;
- source Script beat, Frame Script, and Art Direction reference;
- Copy-Aware Layout Map reference;
- exact copy and hierarchy;
- provisional and intended line breaks;
- copy footprint and minimum readable scale;
- image, evidence, type, graphic, and foreground layers;
- asset source or generation plan;
- protected visual zones and required quiet areas;
- masks, overlap, occlusion, and layer order;
- local contrast requirement;
- crop and extension latitude;
- reusable components;
- variants and adaptation behavior;
- Type-Fit acceptance criteria;
- technical risk and accepted fallback;
- inherited decisions and implementation tolerances.

Preserve editable separation between imagery, typography, masks, and evidence whenever the toolchain permits.

## Image and asset realization

Realize Production-intent image assets only from an identified Layout Map and Art Direction Package.

Translate the map into explicit asset constraints before generation or selection:

- subject position, scale, and focal detail;
- regions that must remain quiet, low-detail, dark, light, extensible, or empty;
- regions that must not contain essential subjects or evidence;
- intended overlap or occlusion behavior;
- crop and variant latitude;
- required masks, depth planes, or layer separation.

Verify:

- required subject, state, action, relationship, and count;
- geometry, perspective, contact, material response, and light direction;
- continuity with accepted Anchors and route;
- fidelity to the Layout Map;
- reference permissions and transfer boundaries;
- sufficient resolution and crop latitude;
- source authenticity where evidence is required.

Image assets normally exclude final audience-facing text so exact language remains controllable.

Generated pseudo-text, misspelled text, or baked-in required copy cannot satisfy the Script. Non-semantic environmental marks or decorative lettering may appear only when permitted by Art Direction and cannot carry required information.

## Deterministic typography

Compose exact copy with a controllable layout system after the Production-intent image asset is available.

Control:

- Unicode text and punctuation;
- language glyph coverage;
- font, weight, width, size, tracking, leading, and alignment;
- semantic line breaks;
- wrapping and overflow;
- depth and masking relationships;
- evidence, source, and limitation hierarchy;
- repeatable output across variants.

Compare every composed line with the authoritative Script. Do not rewrite copy for fit.

## Type-Fit Proof

Before final assembly is accepted, place exact copy into the target geometry and verify:

- intended hierarchy and line behavior;
- copy footprint and local contrast;
- minimum readable scale at actual viewing width;
- intended image–type relationship and layer order;
- protection of essential subject, action, interface, and evidence;
- safe areas, crop, and representative variants;
- fidelity to the Layout Map and Design Comp.

The following are failures, not acceptable production fixes:

- shrinking required copy below the accepted readable threshold;
- changing words, claims, qualifications, or hierarchy without authority;
- hiding copy or essential visual content;
- adding emergency opaque boxes outside the accepted design system;
- evaluating fit only at full-resolution desktop zoom;
- preserving an attractive image at the expense of the approved communication.

When Type-Fit fails, stop and return through Creative Producer to the earliest affected owner.

## Assembly and fit

Assemble each screen against accepted representative proof, Layout Map, and Art Direction.

Check:

- first-, second-, and third-glance hierarchy;
- center of gravity and reading path;
- image–type relationship;
- subject–environment priority;
- grid, margin, and negative-space behavior;
- body-page density and readability;
- evidence visibility;
- cross-page grammar and purposeful variation;
- target-platform overlays and safe areas.

When content does not fit, apply only authorized tolerance. A change to meaning, hierarchy, copy, Layout Map, or visual premise returns through Creative Producer.

## Variants

Adapt each surface from the accepted visual premise and Copy-Aware Layout Map rather than relying on blind cropping.

Each variant requires re-verification of:

- exact copy and line breaks;
- copy footprint and minimum scale;
- protected visual zones;
- hierarchy and image–type relationship;
- crop, safe areas, evidence, and balance.

A material redesign returns to Art Director through Creative Producer.

## Production self-QA

Before formal return, run:

- Layout Map presence and fidelity;
- Production-intent image-class verification;
- exact-copy and glyph verification;
- Type-Fit Proof;
- target-dimension and orientation checks;
- actual-width mobile readability;
- thumbnail and hierarchy checks;
- mask, edge, contact, depth, and perspective checks;
- protected-zone and local-contrast checks;
- reference and asset-rights checks;
- evidence-integrity checks;
- cross-page consistency and differentiation;
- variant completeness;
- export-open and file-integrity checks;
- Artifact Decision Contract and implementation-delta check;
- applicable ECD feedback check.

A technically valid file is not complete if it departs from authoritative direction or was produced through copy-blind image generation.

## Return to Creative Producer

Return:

- all final assets and variants;
- dimensions, formats, and filenames;
- Production self-QA;
- Artifact Decision Contract and implementation delta;
- Copy-Aware Layout Map references;
- Production-intent image provenance and compliance;
- Type-Fit Proof and exact-copy verification;
- Production input resolution;
- asset provenance and attribution state;
- mobile and technical QA;
- authorized deviations;
- known limitations;
- applicable feedback closure;
- recommended Producer disposition.

This is a Specialist Return, not Final Acceptance.

## Producer Final Review

Creative Producer independently compares the final package with all authoritative artifacts, Layout Maps, representative proofs, and feedback.

Defective, copy-blind, unreadable, or unverified work returns internally.

Only a Producer Cleared final package may be released to the ECD with:

- complete final previews or assets;
- Producer Final Review result;
- Producer recommendation;
- Type-Fit and mobile evidence;
- deviations and limitations;
- feedback closure;
- Final Acceptance scope and request.

## Return conditions

Return through Creative Producer when:

- a valid Layout Map is missing or contradicted;
- an essential asset is unavailable or cannot be used as intended;
- exact copy cannot fit within approved hierarchy and readability tolerances;
- an accepted image–type relationship is technically infeasible;
- a platform condition changes the design premise;
- a generated or edited asset contradicts required meaning or protected zones;
- Production reveals an upstream reference, rights, evidence, dependency, or copy problem.

## References

- `references/production-workflow.md`
- `references/mobile-qa.md`
- `../art-director/references/copy-aware-composition.md`
- `../shared/PRODUCER_CONTROL_LOOP.md`
- `../shared/ARTIFACT_DECISION_CONTRACT.md`
- `../shared/STAGE_CAPABILITY_MATRIX.md`
- `../shared/DELIVERABLE_CONTRACT.md`
- `../shared/STAGE_SCOPED_INPUT_REGISTER.md`
- `../shared/HANDOFF_CONTRACT.md`
- `../shared/LOCK_AND_REWORK_PROTOCOL.md`
