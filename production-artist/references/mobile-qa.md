# Mobile and Technical QA

## Purpose

This protocol verifies that final Social Editorial assets work under actual feed, mobile, platform, and file conditions rather than only at full-resolution desktop zoom.

Run it on Representative Design Comps and again on final exports.

## QA Levels

### Critical

Failure blocks delivery:

- corrupted or missing file;
- wrong dimensions or orientation;
- incorrect, missing, or garbled required text;
- primary meaning unreadable at target size;
- required evidence, limitation, attribution, or name hidden;
- material drift from accepted Design Comp;
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
- font fallback materially changing design.

### Minor

May be repaired inside production tolerance:

- small spacing inconsistency;
- non-semantic line-break refinement;
- minor edge cleanup;
- metadata or filename correction;
- negligible color or compression variation.

## 1. Contract and File Checks

For every final file verify:

- expected filename;
- expected screen order;
- format;
- pixel dimensions;
- aspect ratio;
- orientation;
- alpha behavior when applicable;
- color rendering appropriate to destination;
- file opens successfully;
- no unintended working marks, guides, masks, or placeholders;
- no stale or duplicated variant.

## 2. Exact Text and Glyph Checks

Compare export against the accepted Creative Script:

- all characters present;
- no generated pseudo-text;
- punctuation and quotation marks correct;
- names, numbers, dates, versions, and units correct;
- negation and qualifications preserved;
- CJK and multilingual glyphs render correctly;
- no fallback tofu, missing glyph, clipping, or baseline defect;
- source and limitation copy remains legible;
- semantic line breaks preserved.

Read the exported file, not only the editable source.

## 3. Thumbnail Test

Reduce the screen to representative feed-preview size.

Confirm the viewer can still identify:

- the hero or dominant evidence object;
- the primary title or decisive statement;
- the basic meaning or promise;
- the intended visual center.

A cover that works only after opening the full image fails its feed function unless the Deliverable Contract explicitly removes that requirement.

## 4. Actual Mobile-Width Test

Preview the exported asset at approximately the physical width at which it will appear on the target mobile device or a defensible equivalent.

Confirm:

- primary copy is immediately readable;
- required supporting copy can be read without zooming;
- source and limitation text is not merely technically present;
- line length and leading support comfortable reading;
- body pages do not resemble shrunken A4 layouts;
- annotations are large enough to connect to evidence;
- tap, crop, or platform chrome does not conceal essential content.

When no exact device is specified, test a conservative mobile condition rather than a large desktop preview.

## 5. Blur / Squint Test

Blur, defocus, or visually suppress detail.

Confirm:

- first-glance hierarchy remains dominant;
- secondary information does not compete;
- multiple visual centers do not emerge accidentally;
- title, hero, and evidence relationships remain structurally clear.

If hierarchy disappears under blur, return to Art Director rather than sharpening decorative detail.

## 6. Safe Area and UI Overlay Test

Check expected platform behavior:

- top and bottom interface overlays;
- side crop or rounded-corner behavior;
- carousel indicators;
- caption or profile overlays;
- share, like, or navigation controls;
- thumbnail crop;
- device notch or system areas when applicable.

No essential title, face, product feature, evidence, source, or limitation may depend on a vulnerable edge unless intentionally designed and tested.

## 7. Image, Mask, and Depth Checks

At full size and target size verify:

- subject edges are clean and contextually natural;
- hair, glass, thin parts, and semi-transparent materials are handled correctly;
- no unintended halo;
- contact shadows ground the subject;
- lighting and shadow directions agree;
- perspective and scale are plausible;
- type–subject overlap matches accepted depth order;
- enough letter anatomy remains for recognition;
- dimensional subjects retain volume rather than becoming flat stickers;
- background extension or inpainting has no visible seams or repetitions.

## 8. Evidence Integrity Check

For evidence-led screens verify:

- screenshot, chart, document, UI, result, or comparison is large enough to inspect;
- annotations point to the correct feature;
- critical labels and values remain visible;
- crop does not change meaning;
- before / after evidence is equivalent;
- reconstruction, simulation, or speculation is labeled when required;
- decorative elements do not imply evidence that does not exist;
- source, version, date, region, or limitation remains where material.

## 9. Copy–Image Interaction Check

Confirm:

- text does not accidentally cover essential product, face, UI, or evidence content;
- subject does not destroy title recognition;
- overlap is deliberate and consistent with the Design Comp;
- contrast is sufficient without emergency opaque boxes;
- support copy has a stable quiet zone;
- no paragraph was shrunk merely to fit;
- visual reading order matches editorial priority.

## 10. Cross-Page Sequence Check

View the sequence in order and as thumbnails.

Confirm:

- shared visual grammar is evident;
- adjacent pages are not semantically or visually redundant;
- page order is correct;
- density and energy vary intentionally;
- cover establishes a promise the sequence fulfills;
- evidence appears before dependent conclusions;
- final page supplies consequence, payoff, action, or aftertaste;
- no page looks like an accidental template from another project.

Semantic repetition routes to Editorial Director. Visual repetition with distinct meaning routes to Art Director.

## 11. Variant Check

For each aspect ratio, language, or platform variant:

- repeat exact-text validation;
- repeat safe-area validation;
- verify hierarchy rather than assuming crop equivalence;
- inspect line breaks and font fallback;
- verify required evidence and limitations;
- compare against the same accepted visual premise;
- ensure filename and dimensions identify the variant accurately.

## QA Record

```markdown
# Mobile and Technical QA Record

Project:
Asset package:
Target platform / surface:
Target viewing condition:

| Check | Status | Severity | Evidence / note | Owner if failed |
|---|---|---|---|---|
| file integrity | | | | Production Artist |
| dimensions / format | | | | Production Artist |
| exact text / glyphs | | | | Production Artist or Editorial Director |
| thumbnail | | | | Art Director / Production Artist |
| actual mobile width | | | | Art Director / Production Artist |
| blur hierarchy | | | | Art Director |
| safe areas / UI overlays | | | | Production Artist / Art Director |
| masks / depth / image quality | | | | Production Artist / Art Director |
| evidence integrity | | | | Research / Editorial / Art / Production |
| copy–image interaction | | | | Art Director / Production Artist |
| cross-page rhythm | | | | Editorial Director / Art Director |
| variants | | | | Production Artist |

Critical failures:
Major failures:
Authorized exceptions:
Overall state: [pass / fail / pass with recorded limitation]
Ready for Creative Producer Final Review: [yes / no]
```

## Ownership Decision

When a check fails, identify the first professional object where the defect became true:

- wrong words in accepted Script → Editorial Director;
- correct Script but wrong composed text → Production Artist;
- unreadable hierarchy already present in Design Comp → Art Director;
- readable Comp degraded in export → Production Artist;
- evidence requirement absent from Script → Editorial Director or Development;
- evidence specified but covered in final layout → Art Director or Production Artist according to the accepted Comp;
- platform geometry absent from Deliverable Contract → Creative Producer.
