# ECD

ECD is the working repository for an AI-native **Social Editorial Creative Studio**.

The studio is organized around professional creative-industry roles rather than legacy pipeline names. The human user is the **Executive Creative Director (ECD)** and retains final creative authority. The AI team is coordinated by a **Creative Producer** and staffed by specialist Skills for research, editorial strategy, editorial direction, art direction, and production.

## Studio Model

```text
Executive Creative Director (Human)
        ↓
Creative Producer
        ↓
Research Editor
        ↓
Editorial Strategist
        ↓
Editorial Director
        ↓
Art Director
        ↓
Production Artist
```

This is not a mandatory linear pipeline. The Creative Producer routes each project only through the professional roles actually required.

## Roles

- `creative-producer` — owns intake, routing, briefs, decisions, gates, rework, and final review coordination.
- `research-editor` — owns source intake, research, verification, evidence, rights, attribution, and material classification.
- `editorial-strategist` — owns editorial framing, insight, angle, proposition, audience relevance, and the Creative Treatment.
- `editorial-director` — owns content architecture, sequence, creative script, storyboard logic, on-screen copy, and companion copy.
- `art-director` — owns Social Editorial art direction, visual hierarchy, typography, composition, image–type relationships, cover/body-page design, and visual QA.
- `production-artist` — owns deterministic production, asset realization, layout assembly, crop, sizing, export, variants, and technical QA.

The **Executive Creative Director is not a Skill**. It is the human authority above the system.

## Shared Studio Protocols

Shared operating rules live under `shared/` and define the production model, handoffs, locks, and targeted rework. These documents are intentionally minimal at this stage and will be refined as each professional Skill is developed.

## Development Principle

Build the studio role by role. Preserve clear professional ownership. Do not let downstream execution silently rewrite upstream creative decisions, and do not force every project through every role.
