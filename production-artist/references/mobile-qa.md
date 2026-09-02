# Mobile and Technical QA

## Purpose

This protocol verifies that final Social Editorial assets work under actual feed, mobile, platform, copy-aware, and file conditions rather than only at full-resolution desktop zoom.

Run it on Representative Design Comps and again on final exports.

## QA levels

### Critical

Failure blocks delivery:

- corrupted or missing file;
- wrong dimensions or orientation;
- incorrect, missing, or garbled required text;
- primary meaning unreadable at target size;
- required evidence, limitation, attribution, or name hidden;
- material drift from accepted Design Comp or Copy-Aware Layout Map;
- Production-intent imagery without traceable Layout Map coverage;
- unauthorized asset or reference use.

### Major

Requires correction unless explicitly accepted:

- weak hierarchy;
- body copy difficult to read;
- platform UI collision;
- poor masks or sticker-like edges;
- sequence inconsistency;
- visible compression artifacts;
- incorrect crop or safe area;
- font fallback materially changing design;
- copy–image fit repaired through unreadable type or unplanned opaque boxes.

### Minor

May be repaired inside Production tolerance:

- small spacing inconsistency;
- non-semantic line-break refinement;
- minor edge cleanup;
- metadata or filename correction;
- negligible color or compression variation.

## 1. Contract, map, and file checks

For every final file verify:

- expected filename and screen order;
- format, pixel dimensions, aspect ratio, and orientation;
- alpha and color behavior where applicable;
- file opens successfully;
- no unintended guides, masks, placeholders, or stale variants;
- exact-copy source and version;
- Copy-Aware Layout Map reference;
- Production-intent image classification and provenance;
- Type-Fit Proof reference.

## 2. Exact text and glyph checks

Compare export against the ECD-aligned Creative Script:

- all characters present;
- no generated pseudo-text;
- punctuation and quotation marks correct;
- names, numbers, dates, versions, and units correct;
- negation and qualifications preserved;
- CJK and multilingual glyphs render correctly;
- no fallback tofu, missing glyph, clipping, or baseline defect;
- source and limitation copy remains legible;
- semantic line breaks preserved or changed only within accepted tolerance.

Read the exported file, not only the editable source.

## 3. Copy-Aware Layout Map fidelity

Compare the final screen with its Layout Map and Design Comp.

Confirm:

- copy hierarchy and footprint remain intact;
- intended line behavior is preserved;
- subject, face, product, action, interface, and evidence protection zones survive;
- quiet, overlap, occlusion, and layer-order decisions are intentional;
- local contrast remains sufficient;
- crop and extension behavior remain within tolerance;
- the image was not substituted with a visually attractive asset that breaks the map;
- no Exploratory image was silently promoted.

A map mismatch routes to Art Director when the accepted map is wrong, or Production Artist when implementation departs from a valid map.

## 4. Type-Fit test

Verify exact copy in final target geometry and at actual mobile width.

Confirm:

- primary copy is immediately readable;
- required supporting copy can be read without zooming;
- source and limitation text is not merely technically present;
- hierarchy and minimum readable scale match accepted criteria;
- line length and leading support comfortable reading;
- protected visual content remains visible;
- image–type relationship matches the accepted depth and masking model;
- no paragraph was reduced merely to fit;
- no unauthorized wording change, hierarchy collapse, or emergency opaque box was used to preserve the image.

A screen that fits only at full-resolution desktop zoom fails.

## 5. Thumbnail test

Reduce the screen to representative feed-preview size.

Confirm the viewer can still identify:

- the hero or dominant evidence object;
- the primary title or decisive statement;
- the basic meaning or promise;
- the intended visual center.

A cover that works only after opening the full image fails its feed function unless the Deliverable Contract explicitly removes that requirement.

## 6. Actual mobile-width test

Preview the exported asset at approximately the physical width at which it will appear on the target mobile device or a defensible equivalent.

Confirm:

- primary copy is immediately readable;
- required supporting copy can be read without zooming;
- body pages do not resemble shrunken print layouts;
- annotations are large enough to connect to evidence;
- platform chrome does not conceal essential content;
- the accepted Type-Fit result survives export.

When no exact device is specified, test a conservative mobile condition rather than a large desktop preview.

## 7. Blur / squint test

Blur, defocus, or visually suppress detail.

Confirm:

- first-glance hierarchy remains dominant;
- secondary information does not compete;
- multiple visual centers do not emerge accidentally;
- title, hero, and evidence relationships remain structurally clear.

If hierarchy disappears under blur, return to Art Director rather than sharpening decorative detail.

## 8. Safe area and UI overlay test

Check expected platform behavior:

- top and bottom interface overlays;
- side crop or rounded-corner behavior;
- carousel indicators;
- caption or profile overlays;
- share, like, or navigation controls;
- thumbnail crop;
- device notch or system areas where applicable.

No essential title, face, product feature, evidence, source, or limitation may depend on a vulnerable edge unless intentionally designed and tested.

## 9. Image, mask, and depth checks

At full size and target size verify:

- subject edges are clean and contextually natural;
- hair, glass, thin parts, and semi-transparent materials are handled correctly;
- no unintended halo;
- contact shadows ground the subject;
- lighting and shadow directions agree;
- perspective and scale are plausible;
- type–subject overlap matches accepted layer order;
- enough letter anatomy remains for recognition;
- dimensional subjects retain volume rather than becoming flat stickers;
- extension or inpainting has no visible seams or repetitions.

## 10. Evidence integrity check

For evidence-led screens verify:

- screenshot, chart, document, UI, result, or comparison is large enough to inspect;
- annotations point to the correct feature;
- critical labels and values remain visible;
- crop does not change meaning;
- before / after evidence is equivalent;
- reconstruction, simulation, or speculation is labeled when required;
- decorative elements do not imply evidence that does not exist;
- source, version, date, region, or limitation remains where material.

## 11. Cross-page sequence check

View the sequence in order and as thumbnails.

Confirm:

- shared visual grammar is evident;
- adjacent pages are not semantically or visually redundant;
- page order is correct;
- density and energy vary intentionally;
- cover establishes a promise the sequence fulfills;
- image–type behavior is coherent but not mechanically repeated;
- evidence appears before dependent conclusions;
- final page supplies consequence, payoff, action, or aftertaste;
- no page looks like an accidental template from another project.

Semantic repetition routes to Editorial Director. Visual repetition with distinct meaning routes to Art Director.

## 12. Variant check

For each aspect ratio, language, or platform variant:

- repeat exact-text validation;
- repeat Layout Map and Type-Fit validation;
- repeat safe-area validation;
- verify hierarchy rather than assuming crop equivalence;
- inspect line breaks and font fallback;
- verify required evidence and limitations;
- compare against the same accepted visual premise;
- ensure filename and dimensions identify the variant accurately.

## QA record

```markdown
# Mobile and Technical QA Record

Project:
Asset package:
Target platform / surface:
Target viewing condition:
Exact-copy source:
Copy-Aware Layout Map set:

| Check | Status | Severity | Evidence / note | Owner if failed |
|---|---|---|---|---|
| file integrity | | | | Production Artist |
| dimensions / format | | | | Production Artist |
| exact text / glyphs | | | | Production Artist or Editorial Director |
| Layout Map fidelity | | | | Art Director / Production Artist |
| image-class compliance | | | | Art Director / Production Artist |
| Type-Fit | | | | Art Director / Production Artist / Editorial Director |
| thumbnail | | | | Art Director / Production Artist |
| actual mobile width | | | | Art Director / Production Artist |
| blur hierarchy | | | | Art Director |
| safe areas / UI overlays | | | | Production Artist / Art Director |
| masks / depth / image quality | | | | Production Artist / Art Director |
| evidence integrity | | | | Research / Editorial / Art / Production |
| cross-page rhythm | | | | Editorial Director / Art Director |
| variants | | | | Production Artist |

Critical failures:
Major failures:
Authorized exceptions:
Overall state: [pass / fail / pass with recorded limitation]
Ready for Creative Producer Final Review: [yes / no]
```

## Ownership decision

When a check fails, identify the first professional object where the defect became true:

- wrong words in accepted Script → Editorial Director;
- correct copy but wrong hierarchy or Layout Map → Art Director;
- valid Layout Map but noncompliant image or composition → Production Artist;
- unreadable hierarchy already present in Design Comp → Art Director;
- readable Comp degraded in export → Production Artist;
- evidence requirement absent from Script → Editorial Director or Development;
- platform geometry absent from Deliverable Contract → Creative Producer.
