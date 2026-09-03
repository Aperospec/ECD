---
name: ecd-production-typesetting
description: Internal Production specialist skill for deterministically implementing approved exact copy and Typography specifications in final layouts, including glyphs, line breaks, spacing, optical alignment, mixed scripts, masks, variants, and exported proof.
version: 3.1-alpha
---

# Production Typesetting Skill

## Purpose

Production Typesetting implements the approved typographic system exactly and repeatably.

It does not rewrite copy, select a new visual direction, or change hierarchy to make the layout easier.

## Inputs

- authoritative exact copy;
- Typography Specialist Return and specification;
- Department Cleared Editorial Design;
- target dimensions and variants;
- font files or available licensed families and fallbacks;
- mask, depth, image–type, contrast, and safe-area requirements;
- Production Director assignment.

## Method

### 1. Verify text and font readiness

Check:

- exact text version;
- Unicode characters and punctuation;
- simplified / traditional requirement;
- Chinese, Latin, numeral, symbol, and code coverage;
- font availability, rights, and fallback;
- target rendering environment.

### 2. Implement type roles

For each role apply:

- family and fallback;
- weight / width;
- size or responsive range;
- leading;
- tracking / character spacing;
- alignment;
- line length;
- line-break rule;
- color / value;
- depth / overlap;
- minimum readable condition;
- variant behavior.

### 3. Preserve semantic line integrity

Do not split names, phrases, numbers, qualifiers, or rhetorical units in ways that change meaning or rhythm.

When exact copy cannot fit within approved hierarchy and minimum legibility, stop and return the conflict. Do not silently rewrite or shrink.

### 4. Apply optical correction

Inspect perception rather than relying only on software metrics:

- punctuation and hanging alignment;
- CJK / Latin apparent size;
- baseline and cap-height relationships;
- asymmetric word shapes;
- optical centering;
- crop and occlusion recognition;
- repeated role consistency.

### 5. Test against imagery

Verify local contrast, protected zones, overlap, masks, and image–type depth in the actual final page.

### 6. Render every variant

Each size / language / platform variant requires a separate text-fit and hierarchy check.

### 7. Compare exported output

Inspect the rasterized or rendered final file, not only source settings.

## Output

```markdown
# Production Typesetting Return

Project:
Text version:
Typography specification:
Fonts / fallbacks:
Role implementation:
Line breaks:
Chinese / mixed-script checks:
Optical corrections:
Image–type / mask checks:
Variant checks:
Exported proofs:
Exact-text comparison:
Fit conflicts returned:
Self-check:
Recommended Production Director disposition:
```

## Self-check

- Is every character and punctuation mark exact?
- Do line breaks preserve meaning and rhythm?
- Are Chinese / Latin / numerals optically coherent?
- Does hierarchy match the approved proof?
- Is required text readable at actual viewing width?
- Do masks and overlaps preserve both type and image?
- Were all variants inspected after export?

## Failure routing

- exact copy too long or structurally unsuitable → Editorial through Production Director;
- approved type system fails target conditions → Visual Typography through Producer;
- image blocks approved type placement → Finished Art / Image Production;
- font or rendering availability issue → Production Director / Producer blocker.
