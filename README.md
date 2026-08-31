# ECD

ECD is a single-entry Social Editorial creative-studio Skill. It develops a project from an initial brief through Development, editorial scripting, bilingual copy craft, visual development, art direction, production, and final quality assurance.

The human user is the Executive Creative Director. Four internal professional modes perform the work:

- Creative Producer
- Editorial Director
- Art Director
- Production Artist

## Runtime workflow

```text
Brief
→ Creative Treatment
→ Greenlight
→ Creative Script and Copy
→ Script Alignment when material
→ Visual Development
→ Visual Alignment when material
→ Art Direction
→ Production and QA
→ Final Acceptance
```

The workflow is adaptive. Existing valid artifacts enter at the latest legitimate stage. Stage authority, professional ownership, and decision visibility remain explicit.

## Repository boundaries

```text
SKILL.md                    runtime entry
ORGANIZATION.md             roles and authority
creative-producer/          runtime role manual
editorial-director/         runtime role and craft references
art-director/               runtime role and craft references
production-artist/          runtime role and craft references
shared/                     runtime state, gate, handoff, and policy protocols
evals/                      non-runtime regression fixtures
maintenance/                non-runtime repository-governance guidance
```

Runtime files contain only project-independent methods, templates, states, and quality criteria. Project-specific prompts, historical outputs, and regression examples belong under `evals/` and are not part of ordinary Skill execution.

## Core distinctions

- A Creative Treatment defines the project; a Creative Script defines how it communicates.
- A Written Visual Beat is a semantic instruction; a Storyboard is a visual artifact.
- A visual concept route establishes the governing visual system; an Anchor Keyframe proves it.
- A Representative Design Comp proves typography, hierarchy, geometry, and mobile behavior.
- Production realizes accepted direction; it does not silently redesign it.
- Archive files support state and handoff; they do not replace complete ECD-facing decision objects.

## Quality model

Every stage must pass both a professional quality gate and an authority / presentation gate before downstream activation.

The studio routes feedback to the earliest professional object where the defect becomes true, preserving unaffected work.