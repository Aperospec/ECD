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
            ├── Art Director → Art Direction
            └── Production Artist → Final Assets
```

The central boundary is **Greenlight**.

Before Greenlight, the studio is deciding whether there is a project worth making and what that project actually is. The final development artifact is the **Creative Treatment**.

After the ECD approves the Creative Treatment, the project is Greenlit and enters Production.

## Core Roles

- `creative-producer` — the continuous ECD-facing studio lead across Development and Production; owns alignment, state, orchestration, research commissioning, Greenlight, handoffs, locks, rework, and final review coordination.
- `editorial-director` — post-Greenlight owner of content architecture, sequence, Creative Script, storyboard logic, on-screen copy, and companion copy.
- `art-director` — post-Greenlight owner of Social Editorial art direction, visual hierarchy, typography, composition, image–type relationships, cover/body-page design, visual rhythm, and visual QA.
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

## Development Principle

Build and test the studio through real downstream collaboration rather than attempting to perfect one role in isolation. Preserve clear professional ownership, keep Creative Producer as the coherent ECD interface, and do not let downstream production silently redefine a Greenlit Creative Treatment.