# ECD

ECD is a single-entry, AI-native **Social Editorial Creative Studio**.

The human user is the **Executive Creative Director (ECD)** and retains final creative authority. One root `SKILL.md` acts as the user-facing studio entrance. Internally, the Skill uses four professional role manuals rather than exposing four independent Skills:

- Creative Producer — intent, routing, state, staged input activation, ECD-facing proposals, Greenlight, handoffs, rework, and acceptance;
- Editorial Director — content architecture, sequence, written Visual Beats, on-screen copy, companion copy, and Creative Script;
- Art Director — Storyboard / Visual Sequence Board, Representative Design Comp, and Art Direction Package;
- Production Artist — asset realization, deterministic typography, layout, export, and technical QA.

## Canonical Workflow

```text
ECD Input
↓
Creative Producer
├─ Deliverable Contract
├─ Stage-Scoped Input Register
├─ Project State
└─ shortest valid route
↓
Development when required
↓
ECD-facing Creative Treatment
↓
ECD Greenlight
↓
Editorial Director
↓
Internal Creative Script Package
↓
Complete ECD-facing Creative Script Proposal
↓
ECD Script Alignment when material
↓
Art Director
├─ Storyboard / Visual Sequence Board
├─ Representative Design Comp
└─ Art Direction Package
↓
ECD Visual Alignment when material
↓
Production Artist
↓
Final Assets and QA
↓
ECD Final Acceptance
```

## Decision-Object Rule

Every ECD decision must be attached to a complete, visible, identifiable decision object in the primary conversation.

A file or attachment may preserve the internal record, state tables, input IDs, detailed QA, or downstream handoff metadata. It may not be the only place containing information the ECD needs to decide.

This applies to:

- Creative Treatment / Greenlight;
- Creative Script / Script Alignment;
- Storyboard or Representative Design Comp / Visual Alignment;
- Final Assets / Final Acceptance.

A page-title list plus one sentence per page is a sequence summary, not a complete Creative Script Proposal. Before Script Alignment, the primary conversation must show the Communication Strategy, complete page-by-page structure, Written Visual Beats, exact on-screen copy, complete body copy, fidelity and sequence QA, Alignment scope, and what remains Deferred for Art Director.

See:

- `shared/ECD_DECISION_PRESENTATION.md`;
- `editorial-director/references/creative-script-presentation.md`.

## Core Boundaries

A written **Visual Beat** is not a Storyboard.

- Editorial Director defines what each screen must communicate in words.
- Art Director creates the first true visual translation.
- Production Artist realizes the accepted visual direction technically.

Generated imagery and final typography are separated by default. Image generation produces visual assets; exact audience-facing text is composed deterministically so wording, hierarchy, line breaks, and mobile readability remain controllable.

A natural brief may span multiple stages. The Stage-Scoped Input Register preserves all material instructions while activating only the inputs belonging to the current professional stage.

## Repository Structure

```text
SKILL.md
ORGANIZATION.md
creative-producer/ROLE.md
editorial-director/ROLE.md
editorial-director/references/creative-script-package.md
editorial-director/references/creative-script-presentation.md
art-director/ROLE.md
production-artist/ROLE.md
shared/ECD_DECISION_PRESENTATION.md
shared/STAGE_SCOPED_INPUT_REGISTER.md
shared/CREATIVE_TREATMENT_PRESENTATION.md
shared/GREENLIGHT_RECORD.md
shared/HANDOFF_CONTRACT.md
shared/ARTIFACT_STATES.md
tests/CREATIVE_SCRIPT_PRESENTATION_REGRESSION.md
```

## Artifact Chain

```text
Creative Treatment
→ ECD Greenlight
→ Creative Script
→ ECD Script Alignment when material
→ Storyboard / Visual Sequence Board
→ Representative Design Comp
→ ECD Visual Alignment when material
→ Art Direction Package
→ Final Assets
→ ECD Final Acceptance
```

The studio is adaptive rather than a compulsory waterfall. Valid existing professional artifacts enter at the latest legitimate stage, but no ECD gate may be replaced by an incomplete summary or attachment-only handoff.
