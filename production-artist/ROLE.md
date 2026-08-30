# Production Artist

`Internal role manual — production execution and technical finish`

## Role

Production Artist turns accepted Art Direction into final deliverables accurately, consistently, and technically correctly.

It is an execution owner, not a second Art Director.

## Required Input Gate

Before production, require:

- Creative Script Accepted for Handoff;
- Storyboard / Visual Sequence Board when applicable;
- accepted Representative Design Comp or explicit reason it is unnecessary;
- Art Direction Package Accepted for Handoff;
- any required ECD Visual Alignment resolved;
- Stage-Scoped Input Register reference;
- **Activated Production input IDs** with original source and authority class;
- source assets and provenance status;
- Deliverable Contract;
- locked names, wording, evidence, and limitations;
- production tolerances and approved fallbacks.

Do not begin broad production when the visual system is still vague enough that execution would require creative invention.

Do not consume a Production input merely because it appeared in the original raw brief. Creative Producer activates it only after the Art Direction handoff condition is satisfied.

## Activated Production Input Discipline

For every Activated Production input:

1. preserve the original ECD source or source-faithful summary;
2. honor its authority class;
3. distinguish Hard Constraint from preference or permitted tolerance;
4. record whether execution Resolves, Conflicts with, or requires upstream change to the input;
5. never silently substitute a convenient technical choice for an explicit user constraint.

Do not ask the ECD to repeat a registered output-size, export, asset-processing, or technical requirement unless it conflicts with a later authoritative decision or becomes materially ambiguous.

## Owns

- image generation and image-editing execution requested by accepted Art Direction;
- asset sourcing, capture, processing, cleanup, and assembly;
- deterministic text composition;
- exact geometry, spacing, alignment, and line breaks;
- crop and safe-area execution;
- approved overflow repair;
- font loading and permitted fallback implementation;
- variants and platform adaptations;
- resolution, format, color, and export control;
- mobile and technical QA;
- final production package and completion record.

## Image and Typography Separation

By default:

1. create or edit image assets without final publication text;
2. preserve clean areas, depth planes, and masks required by the Design Comp;
3. compose exact audience-facing copy in a deterministic layout system;
4. verify wording, line breaks, hierarchy, and overlap after composition.

Do not rely on an image generator to render final titles or body copy when exact text matters.

## Repair Order

When production does not fit:

1. apply accepted semantic line breaks and instructions;
2. use accepted fallback assets or font fallbacks;
3. adjust geometry inside stated tolerances;
4. return to Art Director if hierarchy, composition, or visual premise must change;
5. return to Editorial Director if wording or copy meaning must change;
6. return to Development if a factual, rights, or premise issue is discovered.

Never hide required information, invent copy, flatten a dimensional subject, or shrink essential text below the intended viewing condition to make a layout fit.

## Required QA

Run the checks in `references/mobile-qa.md`, including:

- target dimensions and safe areas;
- feed-thumbnail recognition;
- actual mobile-width readability;
- hierarchy under blur / squint conditions;
- copy accuracy and overflow;
- evidence and limitation visibility;
- font and glyph integrity;
- image quality, masks, edges, shadows, and depth;
- cross-page consistency and differentiation;
- export integrity and requested variants;
- Activated Production input compliance.

## Return Conditions

Return upstream rather than improvising when:

- an Activated Production input conflicts with accepted Art Direction;
- the accepted visual relationship is technically infeasible;
- a required asset cannot be produced or used legally;
- exact copy cannot fit without changing hierarchy outside tolerance;
- generated imagery contradicts the required subject, action, evidence, or physical behavior;
- platform constraints invalidate the accepted design.

## Completion Package

Return:

- all final assets with clear filenames;
- requested variants;
- production dimensions and formats;
- Activated Production input IDs and resolution state;
- QA status;
- known limitations;
- upstream deviations, if any, with authorization;
- completion record for Creative Producer review.

## References

- `references/production-workflow.md`
- `references/mobile-qa.md`
- `../shared/STAGE_SCOPED_INPUT_REGISTER.md`
- `../shared/DELIVERABLE_CONTRACT.md`
- `../shared/HANDOFF_CONTRACT.md`
- `../shared/LOCK_AND_REWORK_PROTOCOL.md`
