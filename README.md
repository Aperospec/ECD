# ECD

ECD is a single-entry, AI-native **Social Editorial Creative Studio**.

The human user is the **Executive Creative Director (ECD)** and retains final creative authority. One root `SKILL.md` acts as the user-facing studio entrance. Internally, the Skill uses four professional role manuals rather than exposing four independent Skills:

- Creative Producer — intent, routing, staged input activation, state, Greenlight, handoffs, rework, and acceptance;
- Editorial Director — content architecture, sequence, written Visual Beats, on-screen copy, and companion copy;
- Art Director — Storyboard / Visual Sequence Board, Representative Design Comp, and Art Direction Package;
- Production Artist — asset realization, deterministic typography, layout, export, and technical QA.

## Cross-Stage Brief Principle

A real user brief may contain Development, editorial, visual, reference, and production information in one message.

The user does **not** need to separate that information according to the studio workflow.

Creative Producer creates a `Stage-Scoped Input Register` that:

- preserves the original user instruction;
- projects it into every professional stage it materially affects;
- records whether it is a Hard Constraint, User Preference, Creative Seed, Reference Intent, Existing Artifact, Assistant Inference, or Requires Alignment;
- activates only the current-stage projection;
- keeps later-stage projections Deferred;
- automatically carries Deferred inputs forward when their stage activates;
- does not ask the user to repeat an already stored instruction unless it becomes materially ambiguous or contradictory.

Information may arrive early. Execution remains stage-scoped.

## Canonical Workflow

```text
ECD Input
↓
Creative Producer
├─ Deliverable Contract
├─ Stage-Scoped Input Register
├─ Project State
├─ complexity and evidence routing
└─ shortest valid entry point
↓
Development
├─ Active: Development inputs
├─ Deferred: Editorial inputs
├─ Deferred: Visual inputs
└─ Deferred: Production inputs
↓
Creative Treatment presented to ECD
↓
ECD Greenlight in a later turn
↓
Activate Editorial inputs only
↓
Editorial Director
↓
Creative Script
├─ Content Architecture
├─ Sequence
├─ written Visual Beats
└─ audience-facing copy
↓
Script Accepted for Handoff
+ ECD Script Alignment when material
↓
Activate Visual / Art Direction inputs
↓
Art Director
├─ Storyboard / Visual Sequence Board
├─ Representative Design Comp
└─ Art Direction Package
↓
Art Direction Package Accepted for Handoff
+ ECD Visual Alignment when material
↓
Activate Production inputs
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

The model is adaptive rather than a compulsory waterfall. Valid intermediate artifacts enter at the latest legitimate stage. Compact projects may combine documents or visual proofs, but may not leave material professional questions unresolved, infer Greenlight from project size, or activate later-stage inputs early.

## Greenlight Boundary

For raw or unresolved input, “做一个帖子”, “开始吧”, “直接做”, and equivalent production requests authorize Development only.

Creative Producer must first present an identifiable Creative Treatment, state what acceptance will authorize, request Greenlight, and stop.

For a raw project, Greenlight accepts the Treatment and authorizes **Creative Script development next**. It does not automatically authorize Storyboard, Design Comp, image generation, or visual production.

A prior or same-message Greenlight is valid only when the authoritative Treatment and ECD authorization are explicitly identifiable.

See:

- `shared/GREENLIGHT_RECORD.md`
- `shared/STAGE_SCOPED_INPUT_REGISTER.md`

## Example of Cross-Stage Projection

User says:

> “建筑非常宏大，人很小。”

The same statement may be recorded as:

```text
Development projection — Active:
The work should make the scale and breadth of a person's life perceptible.

Art Direction projection — Deferred:
Monumental architecture with a small human figure.
```

Greenlighting the Development meaning does not mean the future exact composition has already been accepted.

Likewise, if the user says a reference image is liked for its “色调、画风”, Development records that reference intent and boundary. Detailed palette / lighting / material / composition extraction is deferred to Art Director after the Creative Script is Accepted for Handoff.

## Repository Structure

```text
SKILL.md                                  # only user-facing Skill entry
ORGANIZATION.md                           # authority and role model
creative-producer/ROLE.md                 # internal role manual
editorial-director/ROLE.md                # internal role manual
art-director/ROLE.md                      # internal role manual
production-artist/ROLE.md                 # internal role manual
shared/STAGE_SCOPED_INPUT_REGISTER.md     # cross-stage input authority and activation
shared/                                   # state, evidence, handoff, Greenlight, approval, and rework protocols
*/references/                             # craft methods and formal artifact contracts
TESTS.md                                  # core trigger / workflow regression tests
tests/STAGE_SCOPED_INPUT_REGRESSION.md    # cross-stage brief regression suite
```

## Core Boundaries

### Visual Beat is not Storyboard

- Editorial Director defines what each screen must communicate in words.
- Art Director creates the first true visual translation after visual activation.
- Production Artist realizes the accepted visual direction technically.

### Early information is not early approval

- a Deferred user Hard Constraint remains binding when its stage later activates;
- a Deferred User Preference guides that stage but is not an already accepted artifact;
- an Assistant Inference never becomes user authority silently;
- Greenlight of Treatment does not approve later-stage projections from the same raw statement.

### Generated imagery and final typography are separate

Image generation produces visual assets; exact audience-facing text is composed deterministically so wording, hierarchy, line breaks, and mobile readability remain controllable.

## Artifact and Activation Chain

```text
Raw Brief
→ Stage-Scoped Input Register
→ Creative Treatment
→ ECD Greenlight
→ Activate Editorial Inputs
→ Creative Script
→ Activate Visual Inputs
→ Storyboard / Visual Sequence Board
→ Representative Design Comp
→ Art Direction Package
→ Activate Production Inputs
→ Final Assets
→ ECD Final Acceptance
```

## Default Behavior

The user may provide only a sentence, link, screenshot, photograph, product asset, rough copy, visual preference, reference, or partial professional artifact. ECD should infer routine decisions, choose the shortest valid route, preserve all material user inputs, and ask only when missing information materially affects the premise, factual promise, deliverable, rights, scope, or irreversible action.

The Greenlight request is not routine clarification. It is the mandatory executive decision on a proposed Treatment when the project begins from raw or unresolved material.

Previously supplied downstream information should be carried forward automatically instead of requested again.

User direction overrides automatic routing only when it is explicit about the professional stage or authoritative artifact being accepted.
