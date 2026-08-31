# ECD

ECD is a single-entry, AI-native **Social Editorial Creative Studio**.

The human user is the **Executive Creative Director (ECD)** and retains final creative authority. One root `SKILL.md` acts as the user-facing studio entrance. Internally, the Skill uses four professional role manuals rather than exposing four independent Skills:

- Creative Producer — intent, routing, state, staged input activation, ECD-facing proposals, Greenlight, handoffs, rework, and acceptance;
- Editorial Director — content architecture, sequence, written Visual Beats, bilingual Copy Desk, on-screen copy, companion copy, and Creative Script;
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
├─ Editorial Architecture
├─ Treatment Fidelity Gate
├─ Chinese / English / Bilingual Copy Desk
└─ Copy Quality Gate
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

A page-title list plus one sentence per page is a sequence summary, not a complete Creative Script Proposal. Before Script Alignment, the primary conversation must show the Communication Strategy, complete page-by-page structure, Written Visual Beats, exact on-screen copy, complete body copy, fidelity, sequence and copy QA, Alignment scope, and what remains Deferred for Art Director.

See:

- `shared/ECD_DECISION_PRESENTATION.md`;
- `editorial-director/references/creative-script-presentation.md`.

## Bilingual Copy Desk

Editorial Director contains an internal Copy Desk rather than treating copy as a one-pass fill-in task.

The normal method is:

```text
Greenlit Treatment
→ Editorial Architecture
→ Treatment Fidelity Gate
→ Copy Brief / Voice Contract
→ Internal Semantic Proposition per page
→ Candidate Development
→ Native Chinese or English Drafting
→ Native-Language Copy Edit
→ Cross-Page Voice / Metaphor Audit
→ Bilingual Transcreation when required
→ Copy Quality Gate
→ Alignment-ready Copy
```

The reference canon includes Chinese writing, grammar and rhetoric sources; English clarity, sentence craft and copyediting sources; advertising-copy sources; and the Simplified Chinese punctuation standard. Books are used as method sources, not copied text or author-style imitation.

Chinese and English are written and edited as independent native-language versions from a shared semantic brief. One language is not mechanically translated into the other.

A structurally complete Script still fails when its copy is grammatically incomplete, non-idiomatic, generic, translated, metaphorically confused, or unfaithful to the Greenlit Treatment.

See:

- `editorial-director/references/writing-reference-canon.md`;
- `editorial-director/references/copy-desk-workflow.md`;
- `editorial-director/references/chinese-copy-craft.md`;
- `editorial-director/references/english-copy-craft.md`;
- `editorial-director/references/bilingual-transcreation.md`;
- `editorial-director/references/copy-quality-gate.md`.

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
editorial-director/references/social-editorial-copy.md
editorial-director/references/writing-reference-canon.md
editorial-director/references/copy-desk-workflow.md
editorial-director/references/chinese-copy-craft.md
editorial-director/references/english-copy-craft.md
editorial-director/references/bilingual-transcreation.md
editorial-director/references/copy-quality-gate.md
art-director/ROLE.md
production-artist/ROLE.md
shared/ECD_DECISION_PRESENTATION.md
shared/STAGE_SCOPED_INPUT_REGISTER.md
shared/CREATIVE_TREATMENT_PRESENTATION.md
shared/GREENLIGHT_RECORD.md
shared/HANDOFF_CONTRACT.md
shared/ARTIFACT_STATES.md
tests/CREATIVE_SCRIPT_PRESENTATION_REGRESSION.md
tests/BILINGUAL_COPY_QUALITY_REGRESSION.md
```

## Artifact Chain

```text
Creative Treatment
→ ECD Greenlight
→ Creative Script with Alignment-ready Copy
→ ECD Script Alignment when material
→ Storyboard / Visual Sequence Board
→ Representative Design Comp
→ ECD Visual Alignment when material
→ Art Direction Package
→ Final Assets
→ ECD Final Acceptance
```

The studio is adaptive rather than a compulsory waterfall. Valid existing professional artifacts enter at the latest legitimate stage, but no ECD gate may be replaced by an incomplete summary, attachment-only handoff, first-draft copy, or unedited translation.
