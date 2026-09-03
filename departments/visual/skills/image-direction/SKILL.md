---
name: ecd-image-direction
description: Internal Visual specialist skill for planning production-intent imagery from approved page design and exact-copy geometry, including subject, scene, viewpoint, crop, gesture, light, material, continuity, protected zones, generation constraints, and proof.
version: 3.1-alpha
---

# Image Direction Skill

## Purpose

Image Direction defines what image assets must accomplish inside the approved design system.

It is not generic prompt writing, final image generation, or independent illustration detached from typography and layout.

## Inputs

- selected visual thesis;
- Storyboard / Sequence Return;
- Editorial Design layout and exact-copy geometry;
- Typography requirements;
- Frame Scripts and Written Visual Requirements;
- source images, references, rights, and evidence conditions;
- target dimensions and variants;
- Art Director assignment.

## Method

### 1. Classify image role

For each page, determine whether imagery is:

- documentary evidence;
- source artifact;
- product or object depiction;
- character / scene construction;
- conceptual metaphor;
- environmental atmosphere;
- diagrammatic or informational support;
- unnecessary because type or evidence should lead.

Do not generate imagery merely because the page has empty space.

### 2. Read the layout consequences

Record:

- exact copy footprint;
- subject and evidence protected zones;
- required quiet or low-detail zones;
- intended overlap or occlusion;
- crop and extension latitude;
- layer separation and mask needs;
- target variants.

An instruction such as `leave room for text` is insufficient.

### 3. Direct the image

Define:

- required subject, count, identity, state, and action;
- environment and spatial relationship;
- viewpoint, distance, and perspective;
- gesture and focal hierarchy;
- light direction, contrast, and local value behavior;
- material and surface response;
- background complexity;
- color relationship to typography and system;
- continuity across pages;
- realism, stylization, or conceptual status;
- source authenticity and evidence constraints.

### 4. Build production-intent constraints

Translate the direction into a brief usable by Image Production:

```markdown
Canvas / crop:
Subject position range:
Subject scale range:
Required visible features:
Forbidden content:
Quiet / low-detail zones:
Protected zones:
Light / dark behavior behind type:
Perspective / camera behavior:
Layer / mask requirements:
Continuity reference:
Variant latitude:
Acceptance evidence:
```

### 5. Create low-cost proof

When necessary, test one or more representative image routes. Mark whether each is:

- Exploratory;
- Production-intent representative proof;
- source evidence.

A visually strong exploratory image cannot be silently promoted into final use.

### 6. Evaluate proof in layout

Inspect the image with exact copy and target geometry. Reject an image that only works alone.

## Output

```markdown
# Image Direction Return

Project:
Pages / page classes:
Image role classification:
Authoritative Frame Scripts:
Layout and copy constraints:
Image direction:
Production-intent brief:
Continuity system:
Reference transfer limits:
Exploratory / production-intent status:
Representative proof:
In-layout evaluation:
Rejected image routes and reasons:
Open risks:
Self-check:
Recommended Art Director disposition:
```

## Self-check

- Does imagery serve the page rather than decorate it?
- Are exact-copy and layout consequences explicit?
- Are subject, action, evidence, and continuity correct?
- Can Image Production execute without inventing scene decisions?
- Is exploratory work clearly separated from production intent?
- Was the proof judged inside the actual layout?

## Failure routing

- layout cannot accommodate required image → Editorial Design;
- typography and image conflict → Typography + Editorial Design;
- Frame Script lacks concrete content → Editorial;
- source / evidence authenticity issue → Research / Claims Rights;
- production feasibility issue → Production consultation through Producer.
