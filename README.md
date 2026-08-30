# ECD

ECD is a single-entry, AI-native **Social Editorial Creative Studio**.

The human user is the **Executive Creative Director (ECD)** and retains final creative authority. One root `SKILL.md` acts as the user-facing studio entrance. Internally, the Skill uses four professional role manuals rather than exposing four independent Skills:

- Creative Producer — intent, routing, state, Greenlight, handoffs, rework, and acceptance;
- Editorial Director — content architecture, sequence, written Visual Beats, on-screen copy, and companion copy;
- Art Director — Storyboard / Visual Sequence Board, Representative Design Comp, and Art Direction Package;
- Production Artist — asset realization, deterministic typography, layout, export, and technical QA.

## Canonical Workflow

```text
ECD Input
↓
Creative Producer
├─ Deliverable Contract
├─ Project State
├─ complexity and evidence routing
└─ shortest valid entry point
↓
Development when required
├─ Research / Verification / Validation
├─ Reference Intelligence
└─ Editorial Development
↓
Creative Treatment
↓
ECD Greenlight
↓
Editorial Director
↓
Creative Script
├─ Content Architecture
├─ Sequence
├─ written Visual Beats
└─ audience-facing copy
↓
Art Director
├─ Storyboard / Visual Sequence Board
├─ Representative Design Comp
└─ Art Direction Package
↓
Production Artist
├─ image and asset production
├─ deterministic text composition
├─ layout, crop, variants, and export
└─ mobile and technical QA
↓
Creative Producer Final Review
↓
ECD Final Acceptance
```

The model is adaptive rather than a compulsory waterfall. Approved intermediate artifacts enter at the latest valid stage. Compact projects may combine documents or visual proofs, but may not leave material professional questions unresolved.

## Repository Structure

```text
SKILL.md                         # only user-facing Skill entry
ORGANIZATION.md                  # authority and role model
creative-producer/ROLE.md        # internal role manual
editorial-director/ROLE.md       # internal role manual
art-director/ROLE.md             # internal role manual
production-artist/ROLE.md        # internal role manual
shared/                          # state, evidence, handoff, approval, and rework protocols
*/references/                    # craft methods and formal artifact contracts
TESTS.md                         # trigger, routing, artifact, visual, and regression tests
```

## Core Boundary

A written **Visual Beat** is not a Storyboard.

- Editorial Director defines what each screen must communicate in words.
- Art Director creates the first true visual translation.
- Production Artist realizes the approved visual direction technically.

Generated imagery and final typography are also separated by default. Image generation produces visual assets; exact audience-facing text is composed deterministically so wording, hierarchy, line breaks, and mobile readability remain controllable.

## Artifact Chain

```text
Creative Treatment
→ Greenlight
→ Creative Script
→ Storyboard / Visual Sequence Board
→ Representative Design Comp
→ Art Direction Package
→ Final Assets
→ ECD Final Acceptance
```

## Default Behavior

The user may provide only a sentence, link, screenshot, photograph, product asset, rough copy, or partial professional artifact. ECD should infer routine decisions, choose the shortest valid route, and ask only when missing information materially affects the premise, factual promise, deliverable, rights, scope, or irreversible action.

User direction overrides automatic routing.