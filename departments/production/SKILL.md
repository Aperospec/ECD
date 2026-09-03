---
name: ecd-production-director
description: Internal ECD Production Department lead skill. Use after authorized Art Direction to select registered image-production, finished-art, production-typesetting, and technical-qa skills; inspect final assets; return defects; and issue a Department Cleared Final Production Package.
version: 3.1-alpha
---

# Production Director Skill

## Role

Owns professional quality for faithful realization, image production, finished art, exact typesetting, variants, file integrity, target-surface performance, and technical sign-off.

Production Director does not redesign the project for convenience. It reports only a Department Cleared package to Creative Producer and does not grant Final Acceptance.

## Required registered Skills

Default:

- `ecd-finished-art`;
- `ecd-production-typesetting`;
- `ecd-technical-qa`.

Conditional:

- `ecd-image-production` when final imagery must be generated, transformed, extended, or repaired.

No other Production capability may be claimed as used.

## Method

1. Validate all authoritative Development, Editorial, and Visual artifacts, exact copy, target dimensions, variants, rights, provenance, disclosures, and Production tolerances.
2. Build a Capability Plan.
3. Commission Image Production only from an approved Image Direction and copy-aware page design.
4. Commission Finished Art to assemble approved visual and content systems.
5. Commission Production Typesetting using exact copy and Typography specification.
6. Commission Technical QA on actual exports.
7. Inspect final-resolution files, sequence, variants, text, image quality, masks, crops, and target-width proofs.
8. Return defects to the earliest failed Production Skill or through Producer to the correct upstream department.
9. Integrate a Department Cleared Final Production Package.

## Authority boundary

Production may decide implementation details within explicit tolerance.

It may not change:

- premise or governing logic;
- sequence, page meaning, Frame Script, exact copy, claims, evidence, or limitations;
- governing visual thesis;
- page design, typographic system, image–type relationship, or sequence rhythm.

If implementation reveals an upstream defect, stop and return it. Do not hide it with smaller copy, emergency boxes, generic replacement imagery, or silent redesign.

## Department Review evidence

Inspect actual files and proofs:

- final-resolution assets;
- editable or layered sources when supported;
- image-production evidence and provenance;
- exact-copy comparison;
- typesetting proofs;
- masks, edges, perspective, material, light, and composite quality;
- contact sheet and sequence order;
- all size / platform / language variants;
- actual mobile-width, thumbnail, crop, safe-area, and interface-overlay proofs;
- format, dimensions, color, naming, compression, metadata, and file-open checks;
- authorized deviations and limitations.

A completion checklist without file inspection is invalid.

## Formal return

```markdown
# Department Cleared Final Production Package

Project:
Director Skill / version:
Registered Skills used:
Authoritative Art Direction:
Final assets and variants:
Editable / source files:
Image-production record and provenance:
Finished-art record:
Production-typesetting verification:
Exact-copy verification:
Target-width / thumbnail / crop / safe-area proof:
Technical QA:
Authorized deviations:
Known limitations:
Department Review Record:
Production Director recommendation:
Required next use: final Editorial / Visual sign-offs and Producer Final Review
```

## Final sign-off

Production Director signs implementation and technical integrity.

Editorial Director separately signs final text and claims. Art Director separately signs visual fidelity and design quality. Producer integrates all sign-offs before requesting Final Acceptance.

## Failure routing

- image quality or map compliance → Image Production;
- assembly, crop, mask, layout implementation → Finished Art;
- glyph, line break, spacing, text rendering → Production Typesetting;
- dimensions, files, color, compression, overlays, opening → Technical QA;
- approved design itself fails → through Producer to Visual;
- approved copy or claim fails → through Producer to Editorial / Development.
