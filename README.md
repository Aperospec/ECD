# ECD

ECD is the working repository for an AI-native **Social Editorial Creative Studio**.

The human user is the **Executive Creative Director (ECD)** and retains final creative authority. The studio is coordinated through a **Creative Producer**, which remains the ECD-facing lead from the first spark of an idea through final delivery.

## Two-Phase Studio Model

```text
Executive Creative Director (Human)
        ↕
Creative Producer
        │
        ├── DEVELOPMENT / 立项前
        │   ├── Intent & Use Alignment
        │   ├── Research / Verification / Validation (when needed)
        │   ├── Reference Intelligence
        │   ├── Editorial Development
        │   ├── Insight / Angle / Proposition Development
        │   └── Creative Treatment
        │
        ├── GREENLIGHT / 正式立项
        │
        └── PRODUCTION / 立项后
            ├── Editorial Director → Creative Script
            │   ├── Content Architecture
            │   ├── Sequence
            │   ├── Visual Beats (written)
            │   └── On-screen / Body Copy
            │
            ├── Art Director
            │   ├── Storyboard / Visual Board
            │   ├── ECD Visual Alignment when needed
            │   └── Art Direction Package
            │
            └── Production Artist → Final Assets
```

The central boundary is **Greenlight**.

Before Greenlight, the studio is deciding whether there is a project worth making and what that project actually is. The final Development artifact is the **Creative Treatment**.

After the ECD approves the Creative Treatment, the project is Greenlit and enters Production.

## Core Roles

- `creative-producer` — the continuous ECD-facing studio lead across Development and Production; owns alignment, state, orchestration, research commissioning, Greenlight, handoffs, locks, rework, and final review coordination.
- `editorial-director` — post-Greenlight owner of content architecture, sequence, written Visual Beats, Creative Script, on-screen copy, and companion / body copy. It does **not** own the actual Storyboard.
- `art-director` — post-Greenlight visual owner; translates Visual Beats into Storyboards / Visual Boards, manages ECD visual alignment when materially required, and owns Social Editorial Art Direction and editorial design.
- `production-artist` — execution role for asset realization, layout assembly, crop, sizing, variants, export, and technical QA.

The **Executive Creative Director is not a Skill**. It is the human authority above the system.

## Development Functions

Development is not represented as a separate ECD-facing personality. It is a backstage professional capability coordinated by Creative Producer.

It may use research, verification, product validation, reference analysis, editorial insight development, angle exploration, proposition development, and Creative Treatment drafting. Producer repeatedly translates this work into ECD-ready alignment until the project is ready for Greenlight.

See:

- `shared/DEVELOPMENT_FUNCTION.md`
- `shared/RESEARCH_FUNCTION.md`

## Shared Studio Protocols

Shared operating rules live under `shared/` and define the two-phase production model, development behavior, research behavior, handoffs, Greenlight, locks, and targeted rework.

## Current Production Artifacts

```text
Creative Treatment
→ Greenlight
→ Creative Script
→ Storyboard / Visual Board
→ Art Direction Package
→ Final Assets
```

Each artifact has one professional owner and downstream work may not silently rewrite upstream meaning.

## Development Principle

Build and test the studio through real downstream collaboration rather than attempting to perfect one role in isolation. Preserve clear professional ownership, keep Creative Producer as the coherent ECD interface, and do not let downstream production silently redefine a Greenlit Creative Treatment or approved Creative Script.