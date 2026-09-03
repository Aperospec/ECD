---
name: ecd-image-direction
description: Internal Visual specialist skill for planning Production-intent imagery from approved page design, exact-copy geometry, Evidence Obligation, and bounded reference roles, including subject, scene, viewpoint, crop, gesture, light, material, continuity, protected zones, generation constraints, and proof.
version: 3.1-alpha
---

# Image Direction Skill

## Purpose

Image Direction defines what image assets must accomplish inside the approved design system.

It is not generic prompt writing, final image generation, or independent illustration detached from typography, evidence, reference permissions, and layout.

Apply `core/REFERENCE_CONTRACT.md`, `core/EVIDENCE_OBLIGATION.md`, and the Active Visual projections in the Stage-Scoped Input Register.

## Inputs

- selected visual thesis;
- Storyboard / Sequence Return when required;
- Editorial Design layout and exact-copy geometry;
- Typography requirements;
- Frame Scripts and Written Visual Requirements;
- Evidence Obligation, reality position, and public claim ceiling;
- source images, Reference Records, assigned roles, rights, attribution, evidence context, and prohibited transfer;
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
- reconstruction or simulation;
- unnecessary because type or evidence should lead.

Do not generate imagery merely because the page has empty space.

The image role must match the assigned reference role and Evidence Obligation.

### 2. Read the layout consequences

Record:

- exact copy footprint for every language variant;
- subject and evidence protected zones;
- required quiet or low-detail zones;
- intended overlap or occlusion;
- crop and extension latitude;
- layer separation and mask needs;
- target variants.

An instruction such as `leave room for text` is insufficient.

### 3. Read reference and rights consequences

For each material reference record:

- assigned active role;
- transferable principles;
- authorized direct-use content;
- source-specific expression excluded;
- rights, attribution, watermark, likeness, brand, and evidence conditions;
- version, date, region, and context that must survive;
- prohibited use.

Do not treat a Quality Benchmark or mood reference as permission to reproduce its subject, composition, identity, or branded expression.

### 4. Direct the image

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
- realism, stylization, reconstruction, simulation, or conceptual status;
- source authenticity and evidence constraints;
- visual cues required to avoid misleading documentary or product-result implications.

### 5. Build Production-intent constraints

Translate the direction into a brief usable by Image Production:

```markdown
Canvas / crop:
Image role and reality status:
Evidence Obligation:
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
Reference principles permitted:
Source-specific expression prohibited:
Rights / attribution / evidence conditions:
Variant latitude:
Acceptance evidence:
```

### 6. Create low-cost proof

When necessary, test one or more representative image routes. Mark each as:

- Exploratory;
- Production-intent representative proof;
- Source evidence;
- Reconstruction / simulation.

A visually strong exploratory image cannot be silently promoted into final use.

A reconstruction or simulation cannot be presented as documentary evidence.

### 7. Evaluate proof in layout and context

Inspect the image with exact copy, language variants, target geometry, source labels, and required disclosure.

Reject an image that:

- works only alone;
- violates the Copy-Aware Layout Map;
- removes evidence context;
- implies a stronger capability or reality status than approved;
- copies source-specific expression outside authorization;
- fails required continuity or variants.

## Output

```markdown
# Image Direction Return

Project:
Pages / page classes:
Image role classification:
Evidence Obligation / reality position:
Authoritative Frame Scripts:
Layout and copy constraints:
Reference Records and assigned roles:
Transferable principles:
Authorized direct-use content:
Source-specific expression excluded:
Rights / attribution / evidence context:
Image direction:
Production-intent brief:
Continuity system:
Exploratory / Production-intent / evidence / simulation status:
Representative proof:
In-layout evaluation:
Rejected image routes and reasons:
Open risks:
Self-check:
Recommended Art Director disposition:
```

## Self-check

- Does imagery serve the page rather than decorate it?
- Are exact-copy and layout consequences explicit for every required variant?
- Are subject, action, evidence, and continuity correct?
- Are reference roles, permissions, and prohibited transfer respected?
- Does visual realism match the approved reality and validation position?
- Can Image Production execute without inventing scene or rights decisions?
- Is exploratory work clearly separated from Production intent?
- Was the proof judged inside the actual layout and publication context?

## Failure routing

- layout cannot accommodate required image → Editorial Design;
- typography and image conflict → Typography + Editorial Design;
- Frame Script lacks concrete content → Editorial;
- reference role or source intent is ambiguous → Art Director / Producer;
- source, evidence, reality, attribution, or rights issue → Research / Claims Rights;
- Production feasibility issue → Production consultation through Producer.
