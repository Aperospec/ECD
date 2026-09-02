# Copy-Aware Composition

## Purpose

Copy-Aware Composition is the required bridge between an ECD-aligned Creative Script and any image asset intended for direct use in a final Social Editorial screen.

The image is not developed as an independent illustration and decorated with text afterward. Exact copy, target geometry, hierarchy, line behavior, protected content, and image–type relationship must shape the composition before Production-intent image generation or selection begins.

## Core invariant

> Exact authoritative copy must influence composition before any image asset intended for direct final use is generated, selected, cropped, extended, or committed.

Text avoidance is only one possible result. The purpose is a coherent image–type system, not a default empty column beside an image.

## Ownership

- **Editorial Director** owns exact audience copy and any meaning-preserving compression authorized in the Script.
- **Art Director** owns copy hierarchy, provisional line behavior, spatial allocation, image–type relationship, protected zones, visual interaction, and the Copy-Aware Layout Map.
- **Production Artist** owns exact typography, geometry, masking, assembly, variant adaptation, and the Type-Fit Proof within accepted Art Direction.
- **Creative Producer** independently reviews the Layout Map, clears or returns it, and verifies all later copy-aware gates.

No role may change exact copy merely to rescue an image or layout.

## Image classes

### Exploratory Image-World Study

Used to investigate atmosphere, world logic, material, light, subject language, or reference transfer.

It may be created before exact copy geometry is resolved when the current question genuinely does not concern final composition.

It must be clearly marked `Exploratory` and may not be silently promoted into:

- a final screen image;
- a Production-intent Anchor;
- a final crop;
- an authoritative page composition.

Before reuse in a final screen, it must pass through a Producer Cleared Copy-Aware Layout Map and be re-evaluated, adapted, regenerated, or rejected.

### Production-intent Image Asset

An image generated, selected, extended, cropped, or edited with a reasonable expectation that it may appear in a final screen.

It requires a Producer Cleared Copy-Aware Layout Map before creation or commitment.

## Copy-Aware Layout Map

A Copy-Aware Layout Map is required for every Production-intent screen.

Several screens may inherit one page-class map only when their geometry, hierarchy, interaction model, and copy-fit behavior are genuinely equivalent. Exact copy fit must still be verified per screen.

The map may be embedded in a Storyboard, Representative Design Comp, or Art Direction Package, but it must remain identifiable and reviewable.

```markdown
# Copy-Aware Layout Map

Project:
Screen / page class:
Version:
Target geometry:
Source Script / Frame Script:

## Exact Copy
H1:
H2 / deck:
Support:
Evidence / source / limitation:
Microcopy:
Permitted compression:

## Copy Geometry
Hierarchy:
Provisional font class or metric proxy:
Provisional line breaks:
Copy footprint:
Primary text zone:
Secondary text zone:
Minimum readable scale:
Variant-safe behavior:

## Image–Type Relationship
Primary relationship:
Layer order:
Permitted overlap / occlusion:
Forbidden overlap:
Mask or separation requirement:

## Protected Visual Content
Subject focal zone:
Face / product / evidence protection:
Required visible action or relationship:
High-detail zones:
Low-detail / quiet zones:
Local contrast requirement:

## Image Asset Consequence
Subject position and scale:
Background complexity:
Lighting / value requirement:
Negative-space requirement:
Crop latitude:
Extension / inpainting latitude:
Required editable layers or masks:
Generation / sourcing constraints:

## Gate State
Art Director self-QA:
Producer Review Record:
Producer disposition:
Cleared for Production-intent image work: [yes / no]
Required ECD visual authority:
```

## Layout Map clearance gate

The Layout Map is a formal Art Director return.

Before Production-intent image work begins:

```text
Art Director creates Layout Map
→ Art Director self-QA
→ return to Creative Producer
→ Producer Review
   ├─ Returned for Rework
   └─ Producer Cleared for Production-intent proof
→ Production-intent image generation / selection / editing may begin
```

Producer clearance of the map is project-level release authority. It is not ECD approval of the governing visual system. Required ECD Visual Alignment still occurs from representative proof before broad Production.

No specialist may create the map and immediately bypass Creative Producer to generate a Production-intent image.

## Image–type relationship modes

Select one primary relationship for each screen or page class. Supporting relationships may be used only when they do not create competing logic.

- **Separated / quiet-zone** — copy occupies deliberately low-detail space.
- **Contained in negative space** — image composition creates a stable text field.
- **Controlled overlap** — copy crosses low-risk image areas with managed contrast.
- **Occlusion / interlock** — subject and typography occupy different depth planes.
- **Silhouette wrap** — copy follows or responds to subject geometry.
- **Typographic frame** — type structures or bounds the image.
- **Type-led composition** — typography is the dominant visual mass and imagery supports it.
- **Evidence-led composition** — proof remains inspectable and copy is organized around it.

Do not treat `leave blank space` as the universal solution. The chosen relationship must serve the Script, hierarchy, and visual route.

## Workflow

```text
ECD-aligned exact copy
→ copy hierarchy
→ provisional line breaks at target geometry
→ Copy-Aware Layout Map
→ Art Director self-QA
→ Producer Review and clearance of the map
→ low-cost layout scaffold / Production-intent image brief
→ text-free image generation, selection, or editing
→ deterministic typography and masking
→ Type-Fit Proof
→ Producer Review
→ mobile and variant verification
```

The workflow may be compressed, but neither Producer Review nor the dependency order may be reversed.

## Production-intent image brief

After the Layout Map is Producer Cleared, translate it into explicit image consequences:

- where the subject and focal detail must sit;
- which regions must remain quiet, dark, light, extensible, or low-detail;
- which regions must not contain faces, hands, products, evidence, or essential action;
- where overlap or occlusion is intended;
- what crop latitude and aspect-ratio adaptation are required;
- what layers, masks, or separation will be needed for deterministic typography;
- which visual details must survive at target size.

A generic prompt such as `subject on the right with space for text` is insufficient when the real copy footprint, line behavior, or interaction is consequential.

## Generated-text policy

Final audience-facing text remains separate and deterministic by default.

Production-intent image generation must not be relied upon to render exact required copy. Generated pseudo-text, misspelled text, or baked-in copy cannot satisfy the Script.

Non-semantic texture, illegible environmental marks, or explicitly decorative lettering may exist when permitted by Art Direction. Required audience language must remain reproducible, editable, and exactly verifiable.

## Type-Fit Proof

After the image asset exists, place the exact copy back into the target geometry using the intended or defensible typography system.

The proof must verify:

- exact wording and punctuation;
- intended hierarchy and line breaks;
- copy footprint and local contrast;
- image–type relationship and depth order;
- protected subject and evidence zones;
- minimum readable scale at actual viewing width;
- crop and safe-area behavior;
- representative variant behavior;
- absence of emergency repair.

The following do not count as a pass:

- shrinking required copy below the established readable threshold;
- changing words without Editorial authority;
- placing opaque boxes behind text solely because the image ignored the map;
- covering essential subject, action, interface, or evidence;
- abandoning the accepted hierarchy to preserve an attractive image;
- accepting a layout only at full-resolution desktop zoom.

## Failure routing

When Type-Fit fails, identify the earliest failed object:

- incorrect or excessive approved copy → Editorial Director through Creative Producer;
- wrong hierarchy, zones, relationship, or map → Art Director;
- image asset violates an otherwise valid map → Production Artist regenerates, edits, extends, or replaces the asset;
- exact implementation departs from the map or Design Comp → Production Artist;
- target geometry or platform condition was missing → Creative Producer / Deliverable Contract.

Changing approved copy is not the default repair for a copy-blind image.

## Producer Review gates

### Before Production-intent image work

Creative Producer verifies:

- exact Script copy was used rather than placeholder copy;
- provisional line behavior and copy footprint were tested at target geometry;
- protected visual content and quiet / overlap zones are explicit;
- the image–type relationship and asset consequences are actionable;
- the map is mature enough to guide a representative image without hidden composition decisions.

Only a Producer Cleared map may release Production-intent image work.

### Before visual release or Production activation

Creative Producer verifies:

- Production-intent imagery inherited the cleared map;
- Exploratory studies were not silently promoted;
- required audience text remains controlled and separate;
- representative Type-Fit Proof exists before scale-out;
- failures were returned to the earliest affected owner rather than repaired by unreadable text or ad hoc boxes.

An artifact that fails either gate is not `Producer Cleared` for its next use.

## Compact work

Compact work may combine the Layout Map, Storyboard, Anchor, and Design Comp into one proof when that proof uses exact copy and genuinely resolves the required questions.

The combined artifact still requires Art Director self-QA and Producer clearance before Production-intent image work.

It may not omit copy geometry or Producer Review.

## Quality gate

Copy-Aware Composition passes when:

- exact copy visibly shaped the image composition before Production-intent generation or selection;
- the Layout Map was Producer Cleared before Production-intent image work;
- the selected image–type relationship is deliberate and appropriate;
- image assets preserve copy zones and essential visual content;
- exact deterministic typography fits without unauthorized semantic or hierarchy change;
- the result passes target-width and variant checks;
- the map, proof, review, and authority state are traceable;
- Creative Producer independently cleared the result.
