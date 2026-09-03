---
name: ecd-image-production
description: Internal Production specialist skill for generating, selecting, editing, extending, and validating final image assets from approved Image Direction and copy-aware page design, while preserving subject, continuity, protected zones, rights, and deterministic text separation.
version: 3.1-alpha
---

# Image Production Skill

## Purpose

Image Production realizes approved image assets. It does not invent a new scene, visual concept, layout, or claim.

## Inputs

- approved Image Direction Return;
- Department Cleared page design and copy-aware geometry;
- exact copy footprint and protected zones;
- visual references and transfer limits;
- subject, scene, continuity, camera / viewpoint, light, material, crop, and variant requirements;
- source, rights, provenance, and evidence conditions;
- Production Director assignment.

## Method

### 1. Translate direction into production constraints

Record:

- subject identity, count, state, and action;
- position and scale ranges;
- required visible features;
- forbidden content;
- viewpoint and perspective;
- lighting and local value behavior;
- quiet and low-detail zones;
- protected text, subject, and evidence zones;
- crop and extension latitude;
- layer / mask needs;
- continuity reference;
- target dimensions and variants.

### 2. Choose production method

Select among:

- direct source use;
- crop and tonal adjustment;
- controlled transformation;
- generation;
- inpainting / outpainting;
- compositing preparation;
- multiple-source construction.

State why the method fits rights, evidence, quality, and design requirements.

### 3. Produce controlled iterations

Vary only consequential image variables. Keep approved layout and visual thesis fixed.

Track rejected outputs and reasons, including:

- wrong subject or count;
- broken anatomy or geometry;
- inconsistent character / object identity;
- unusable text zones;
- incorrect perspective or light;
- visual cliché;
- insufficient crop latitude;
- rights or source issue;
- mismatch with sequence.

### 4. Validate in layout

Place representative outputs into the actual page geometry with exact copy. An image that works alone but not in the layout fails.

### 5. Preserve text control

Final audience-facing copy normally remains outside generated imagery. Generated pseudo-text cannot satisfy exact copy.

### 6. Record provenance

For every final asset record source, generation / edit method, reference role, transformation, rights / attribution condition, and version.

## Output

```markdown
# Image Production Return

Project:
Pages / assets:
Approved Image Direction:
Production constraints:
Method selected:
Iterations produced:
Rejected outputs and reasons:
Selected assets:
In-layout proof:
Continuity proof:
Protected-zone and crop proof:
Provenance / rights / attribution:
Known defects or limits:
Self-check:
Recommended Production Director disposition:
```

## Self-check

- Does every asset satisfy the approved scene and subject?
- Does it preserve copy and evidence zones?
- Is continuity credible across the sequence?
- Is geometry, light, material, crop, and detail usable at final size?
- Was the asset judged in the real layout?
- Is required text separate and controllable?
- Is provenance complete?

## Failure routing

- image cannot satisfy layout → Visual Editorial Design / Image Direction through Production Director;
- approved direction itself is weak → Art Director through Producer;
- source / rights / evidence issue → Development Claims Rights;
- final integration issue → Finished Art.
