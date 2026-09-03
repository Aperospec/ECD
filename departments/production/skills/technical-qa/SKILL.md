---
name: ecd-technical-qa
description: Internal Production specialist skill for inspecting actual exported files and variants for dimensions, format, color, compression, naming, file integrity, exact text, safe areas, platform overlays, thumbnail and mobile performance, and delivery completeness.
version: 3.1-alpha
---

# Technical QA Skill

## Purpose

Technical QA verifies that final deliverables actually work in their required files, dimensions, variants, and viewing conditions.

It does not replace Editorial or Art Direction judgment, but it must report visible failures discovered during technical inspection.

## Inputs

- Deliverable Contract;
- final exported assets;
- expected file list and order;
- exact text reference;
- target dimensions, formats, color behavior, compression, and naming;
- safe areas, crop, and interface-overlay requirements;
- language and platform variants;
- Production Director assignment.

## Method

### 1. Inventory delivery

Compare expected and actual:

- file count;
- filenames;
- order;
- dimensions and orientation;
- format and extension;
- language / size / platform variants;
- source or editable files when required.

### 2. Open every file

Verify that each file:

- opens successfully;
- is not corrupted;
- displays the expected content;
- has no missing glyph, font substitution, transparency, clipping, or export artifact;
- uses the intended color profile or behavior.

### 3. Verify exact text in exports

Compare visible final text with the approved exact copy, including punctuation, numbers, names, qualifiers, disclosures, and page order.

### 4. Verify geometry and platform conditions

Inspect:

- pixel dimensions;
- aspect ratio;
- safe areas;
- platform crop;
- interface overlays;
- thumbnail recognisability;
- actual mobile-width readability;
- compression and edge quality;
- evidence legibility.

### 5. Verify variants

Check that each variant preserves communication, not only file dimensions.

### 6. Record defects with evidence

For each defect record file, location, observed result, expected result, severity, and responsible upstream Skill.

### 7. Recheck corrected exports

A correction is closed only after the new file is opened and reinspected.

## Output

```markdown
# Technical QA Return

Project:
Deliverable Contract:
Expected inventory:
Actual inventory:
File-open results:
Dimensions / orientation:
Format / color / compression:
Exact-text comparison:
Safe-area / crop / overlay proof:
Thumbnail / actual-width proof:
Variant integrity:
Defects found:
Correction evidence:
Known limitations:
Final QA disposition:
Recommended Production Director disposition:
```

## Severity

- Blocker — file missing, corrupt, wrong content, unusable text, or invalid required format;
- Major — crop, safe area, readability, wrong copy, visible artifact, or variant failure;
- Minor — non-consequential naming or finish issue that still requires correction before release when in contract.

## Self-check

- Was every actual file opened?
- Was every variant inspected?
- Were exact text and page order compared?
- Were target-width, thumbnail, safe area, crop, and overlay tested?
- Were corrected files reinspected rather than assumed fixed?

## Failure routing

- image or composite artifact → Image Production / Finished Art;
- typesetting or glyph defect → Production Typesetting;
- approved design fails actual platform → Visual through Producer;
- copy or claim error → Editorial through Producer;
- missing contract condition → Creative Producer.
