# ECD

ECD is the working repository for an AI-native **Social Editorial Creative Studio**.

The human user is the **Executive Creative Director (ECD)** and retains final creative authority. The studio is coordinated through a **Creative Producer**, which is the ECD-facing production lead and the main interface to all specialist work.

## Studio Model

```text
Executive Creative Director (Human)
        ↕
Creative Producer
        │
        ├── Research / Verification / Validation (backstage function)
        ├── Editorial Strategist
        ├── Editorial Director
        ├── Art Director
        └── Production Artist
```

This is not a mandatory linear pipeline. Creative Producer first aligns with the ECD on what the input means for the project and how it is intended to be used, then invokes only the professional capabilities required.

## Core Roles

- `creative-producer` — owns ECD-facing intake and alignment, production state, routing, briefs, research commissioning, handoffs, decisions, locks, feedback, rework, and final review coordination.
- `editorial-strategist` — owns editorial framing, insight, angle, proposition, audience relevance, and the Creative Treatment.
- `editorial-director` — owns content architecture, sequence, Creative Script, storyboard logic, on-screen copy, and companion copy.
- `art-director` — owns Social Editorial art direction, visual hierarchy, typography, composition, image–type relationships, cover/body-page design, visual rhythm, and visual QA.
- `production-artist` — owns production execution, asset realization, layout assembly, crop, sizing, variants, export, and technical QA.

The **Executive Creative Director is not a Skill**. It is the human authority above the system.

## Backstage Functions

Research, verification, evidence assessment, rights / attribution review, reference-boundary analysis, and product / commercial validation are backstage functions invoked by Creative Producer when the intended use requires them.

They are not independent ECD-facing roles and do not choose the editorial or visual direction.

See `shared/RESEARCH_FUNCTION.md`.

## Shared Studio Protocols

Shared operating rules live under `shared/` and define the production model, backstage research behavior, handoffs, locks, and targeted rework.

## Development Principle

Build and test the studio through real downstream collaboration rather than attempting to perfect one role in isolation. Preserve clear professional ownership, keep the Producer as the coherent ECD interface, and do not let downstream execution silently rewrite upstream creative decisions.
