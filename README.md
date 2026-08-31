# ECD

ECD is a single-entry, AI-native **Social Editorial Creative Studio**.

The human user is the Executive Creative Director and retains final authority. One root `SKILL.md` acts as the user-facing entrance. Internally, four professional modes collaborate:

- Creative Producer — intent, state, stage activation, ECD-facing proposals, gates, handoffs, and rework;
- Editorial Director — content architecture, Written Visual Beats, bilingual Copy Desk, and Creative Script;
- Art Director — visual problem framing, intent elicitation, reference analysis, metaphor mapping, concept routes, Storyboard, anchors, Design Comp, color script, and Art Direction;
- Production Artist — accepted asset realization, deterministic typography, layout, variants, export, and QA.

## Canonical Workflow

```text
ECD Input
↓
Stage-Scoped Intake
↓
Creative Treatment
↓
ECD Greenlight
↓
Editorial Architecture + Copy Desk
↓
Complete ECD-facing Creative Script Proposal
↓
ECD Script Alignment when material
↓
Visual Problem + Intent + Reference Reading
↓
Visual Metaphor Map when relevant
↓
Concept Routes
↓
ECD Visual Direction Alignment when material
↓
Formal Studies + Storyboard
↓
World / Cover Anchor + Representative Body Anchor
↓
Representative Design Comp
↓
ECD Anchor / Design Alignment when material
↓
Color Script + Art Direction Package
↓
Production
↓
Final Assets
↓
ECD Final Acceptance
```

## Visual Development Principle

A user's natural-language visual judgment and supplied reference are **visual research inputs**, not a final image-generation prompt.

The user may say:

- “这张图很对”;
- “我喜欢这个感觉”;
- “人生档案馆就是人生游乐场”;
- “这些图很难看”.

Art Director must translate that input professionally:

1. reconstruct the visual problem;
2. state what it believes the user values and why;
3. classify the reference role;
4. separate description, formal structure, interpretation, and transferable qualities;
5. map any visual metaphor at the level of relationships rather than surface objects;
6. develop materially different concept routes;
7. ask only a few plain-language, high-consequence alignment questions;
8. prove the selected system through low-cost studies and representative anchors;
9. permit broad production only after the Anchor Gate passes.

The ECD does not need to know art terminology or write prompts.

## Anchor-before-Batch Rule

For a new reference-led, metaphor-led, world-led, or multi-image visual system, Art Director normally proves:

- one World / Cover Anchor;
- one Representative Body Anchor;
- optionally one additional distinct page class with recorded reason.

Do not generate four to eight final-looking images before these proofs and any required ECD alignment.

## Decision-Object Rule

Every ECD decision must be attached to a complete, visible, identifiable object in the primary conversation.

Files may preserve internal state and detailed QA, but cannot contain the only material needed for:

- Greenlight;
- Script Alignment;
- Visual Direction Alignment;
- Anchor / Design Alignment;
- Final Acceptance.

## Core Boundaries

- A Written Visual Beat is not a Storyboard.
- A reference is not a style token.
- A metaphor is not a list of literal source-domain objects.
- A polished batch is not evidence that the visual direction was solved.
- Image generation does not replace problem framing, concept design, formal study, or art direction.
- Final typography is normally composed deterministically.

## Repository Structure

```text
SKILL.md
creative-producer/ROLE.md
editorial-director/ROLE.md
art-director/ROLE.md
production-artist/ROLE.md
shared/
editorial-director/references/
art-director/references/
production-artist/references/
tests/
```

Key visual-development references:

```text
art-director/references/visual-reference-canon.md
art-director/references/visual-problem-framing.md
art-director/references/visual-intent-elicitation.md
art-director/references/reference-reading-and-transfer.md
art-director/references/visual-metaphor-mapping.md
art-director/references/visual-concept-development.md
art-director/references/anchor-keyframe-gate.md
art-director/references/ecd-friendly-visual-alignment.md
art-director/references/visual-critique-and-failure-diagnosis.md
```

## Feedback Routing

- wrong premise → Development;
- wrong sequence / copy → Editorial Director / Copy Desk;
- misunderstood visual goal → Visual Problem Framing;
- misunderstood user intuition → Visual Intent Elicitation;
- wrong reference transfer → Reference Reading;
- superficial metaphor → Visual Metaphor Map;
- wrong world / route → Concept Development;
- bad composition / value / scale → Formal Studies;
- wrong page staging → Storyboard;
- failed representative image language → Anchor Keyframe;
- failed typography / page hierarchy → Design Comp;
- correct direction executed badly → Production Artist.

When a result is described as ugly, do not rerender blindly. Diagnose the first failed visual object and return there.
