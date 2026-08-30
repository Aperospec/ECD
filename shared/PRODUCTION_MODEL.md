# Social Editorial Production Model

## Purpose

ECD is one user-facing Skill operating an adaptive Social Editorial studio. The human ECD communicates through Creative Producer; Editorial Director, Art Director, and Production Artist are internal professional modes.

The studio uses two phases separated by **Greenlight**, with stage-local input activation inside Production:

- Development decides whether there is a project worth making and what it actually is.
- Greenlight accepts the Development premise and opens Editorial Production.
- Editorial, Visual, and Production stages activate only the inputs that belong to them when their upstream handoff condition is satisfied.

The model is not a compulsory waterfall. It protects professional ownership while choosing the shortest valid route and preserving early user instructions without executing them prematurely.

## Project Initialization

Before substantive work, Creative Producer establishes at the appropriate depth:

```text
Entry Point
+ Deliverable Contract
+ Stage-Scoped Input Register
+ Complexity Profile
+ Evidence Obligation
+ Project State
→ Valid Route
```

Use:

- `DELIVERABLE_CONTRACT.md`
- `STAGE_SCOPED_INPUT_REGISTER.md`
- `PROJECT_STATE.md`
- `ARTIFACT_STATES.md`

## Cross-Stage Brief Model

A single user brief may contain information for several professional stages.

Do not force the ECD to separate the brief into multiple messages.

Instead:

```text
Raw source statement
↓
Preserve original source and authority
↓
Project into one or more stages
├─ Global / Deliverable
├─ Development
├─ Editorial
├─ Visual / Art Direction
└─ Production
↓
Activate only current-stage projection
↓
Keep later projections Deferred until their activation condition
```

One statement may produce different projections.

Example:

```text
“建筑非常宏大，人很小。”

Development projection:
communicate the scale and breadth of a person's life.

Visual projection:
monumental architecture with a small human figure.
```

The first may enter the Treatment. The second remains Deferred until Art Director is activated.

### Authority classes

Preserve whether an input is:

- Hard Constraint;
- User Preference;
- Creative Seed;
- Reference Intent;
- Existing Artifact;
- Assistant Inference;
- Requires Alignment.

An Assistant Inference must never silently become a user Hard Constraint.

### Complexity Profiles

- **Compact** — one to three screens, one key visual, simple cover-plus-body work, or a narrow correction. Combine artifacts when one object can resolve adjacent professional questions.
- **Standard** — ordinary multi-screen Social Editorial work with normal handoff objects.
- **Extended** — evidence-sensitive, commercial, multi-format, campaign, research-heavy, or high-consequence work requiring detailed records.

Artifact compression is allowed. Ungranted Greenlight, unresolved professional questions, and premature stage activation are not.

## Phase I — Development

Canonical Development logic:

```text
Raw or unresolved ECD input
↓
Creative Producer intake
↓
Stage-Scoped Input Register
├─ Active: Deliverable + Development projections
├─ Deferred: Editorial projections
├─ Deferred: Visual projections
└─ Deferred: Production projections
↓
Development work as required
├─ Research / Verification / Validation
├─ Reference boundary / rights intelligence
└─ Editorial Development
   ├─ premise diagnosis
   ├─ insight
   ├─ angle
   ├─ proposition
   ├─ audience relevance
   └─ Creative Treatment
↓
Creative Producer presents Treatment
+ optional source-faithful Deferred Input Notice
↓
ECD Greenlight decision in a later turn
↺ revise, deepen, reframe, pause, or reject as needed
↓
Greenlit Creative Treatment
```

### Evidence Obligations

Creative Producer selects the appropriate obligation:

1. **Speculative / Conceptual** — preserve the distinction between imagination and present fact; do not demand unnecessary feasibility proof.
2. **Evidence-based Editorial** — verify the public facts and claims on which the publication relies.
3. **Product / Commercial Validation** — test reproducibility, dependencies, limits, rights, and failure conditions to the depth required by the promise.

Research depth must match the promise being made.

## Creative Treatment

The Creative Treatment is Development's authoritative proposal for what the project is.

It establishes, at the required depth:

- premise;
- core creative / editorial idea;
- selected angle;
- core proposition;
- why the project deserves to exist;
- audience relevance and intended takeaway;
- reality, imagination, evidence, and claim boundaries;
- reference-use, rights, attribution, and asset boundaries at Development level;
- what the project must preserve semantically and must not falsely imply or become.

The Treatment may use the Development projection of a cross-stage input. It does not consume its Deferred Editorial / Visual / Production projections.

It does not contain the final page sequence, final audience-facing copy, Storyboard, detailed palette / lighting / composition extraction, layout, typography system, or Art Direction.

Use `CREATIVE_TREATMENT_TEMPLATE.md`.

## Greenlight

Greenlight is owned by the Executive Creative Director and governed by `GREENLIGHT_RECORD.md`.

A Greenlit project has:

- an identified Creative Treatment or explicitly supplied professional equivalent;
- sufficient evidence, validation, rights, and reference resolution for the intended premise;
- material Development boundaries recorded;
- traceable ECD authorization.

For raw or unresolved input, the Treatment must be presented to the ECD before Production. The response that presents it is a hard stop.

A request to make, start, design, or directly produce a post is Development authorization only when no Treatment has yet been presented or explicitly identified. This remains true for Compact projects and detailed briefs.

Before Greenlight, no formal Creative Script, final sequence, Storyboard, Design Comp, Art Direction Package, deliverable image generation, image editing, rendering, layout production, or export may begin.

### Greenlight activation consequence

After Greenlight:

```text
Treatment decisions → authoritative
Deferred Editorial projections → Activated
Deferred Visual projections → remain Deferred
Deferred Production projections → remain Deferred
Next authorized stage → Editorial Director / Creative Script
```

Greenlight does not authorize immediate visual production.

A later change to premise, angle, proposition, public promise, audience takeaway, or essential rights foundation reopens Development and may require re-projection of affected inputs.

## Phase II — Production

Production uses stage-local authorization.

Canonical logic:

```text
Greenlit Creative Treatment
+ Activated Editorial Inputs
↓
Editorial Director
↓
Creative Script
↓
Script Accepted for Handoff
+ ECD Script Alignment when material
↓
Activate Visual / Art Direction Inputs
↓
Art Director
├─ Storyboard / Visual Sequence Board
├─ Representative Design Comp
└─ Art Direction Package
↓
Art Direction Package Accepted for Handoff
+ ECD Visual Alignment when material
↓
Activate Production Inputs
↓
Production Artist
├─ image and asset realization
├─ deterministic text composition
├─ layout, crop, variants, and export
└─ mobile and technical QA
↓
Creative Producer Final Review
↓
ECD Final Acceptance
```

## Editorial Stage

Editorial Director receives:

- Greenlit Treatment;
- Activated Editorial input IDs with original source and authority class;
- Deliverable Contract;
- Development locks and evidence boundaries;
- Visual / Production inputs still Deferred.

The Creative Script defines how the Greenlit project communicates:

- dominant and supporting communication modes;
- page / card / beat sequence;
- one primary editorial job per beat;
- written Visual Beats defining semantic visual requirements;
- on-screen copy and functional hierarchy;
- companion / body copy;
- evidence, attribution, and limitation placement;
- transitions, payoff, and ending logic.

Editorial Director records how each Activated Editorial input was resolved.

It must not use Deferred Visual references to pre-decide palette, camera, lighting, typography, or composition.

### Script Alignment

If the Script introduces a material communication decision not already authorized by the Treatment or explicit ECD instruction, Creative Producer uses ECD Script Alignment before visual activation.

Examples:

- significant sequence architecture;
- invented protagonist biography or life events;
- a headline or public position that changes interpretation;
- material reinterpretation or omission of a user Creative Seed / Hard Constraint.

Routine editorial craft does not require ceremonial alignment.

## Visual Activation

Only after the Script is Accepted for Handoff and required Script Alignment is resolved:

```text
Deferred Visual / Art Direction inputs → Activated
Production inputs → remain Deferred
```

Creative Producer transfers original ECD visual instructions and reference assets with authority class and prohibited-transfer boundaries.

Do not rely on Development paraphrases when original visual source is available.

## Storyboard / Visual Sequence Board

The Board is Art Director's low-cost visual translation of the complete Script and Activated Visual inputs.

It tests:

- fidelity to each Visual Beat;
- fidelity to user visual Hard Constraints / preferences;
- visual distinction between adjacent screens;
- sequence coherence;
- subject, evidence, scale, depth, and image–type relationships;
- reference-DNA abstraction rather than scene copying;
- whether a representative high-fidelity proof is needed.

## Representative Design Comp

The Design Comp uses real or accepted copy, target geometry, credible imagery, and intended hierarchy to prove:

- actual title and body-copy scale;
- typography personality and line breaks;
- image–type depth and overlap;
- grid, negative space, and reading path;
- cover and body-page grammar;
- reference interpretation;
- mobile readability;
- overall aesthetic direction.

A typical multi-page project should prove at least one cover and one representative body page. A Compact project may combine Board and Comp after the Script handoff.

When the visual interpretation materially affects mood, aesthetic stance, visual world, reference extraction, durable identity, or the audience's subjective relationship to the work, use ECD Visual Alignment before locking it.

## Art Direction Package

The Art Direction Package translates the accepted Board and Design Comp into an executable visual system:

- visual thesis, mood, atmosphere, and aesthetic stance;
- hierarchy and visual grammar;
- typography direction;
- image direction and asset roles;
- composition and image–type relationships;
- screen-by-screen intent;
- cross-page rhythm;
- surface and small-size behavior;
- production tolerances and forbidden drift;
- asset plan and technical risks;
- resolution state of Activated Visual inputs.

## Production Activation

Only after the Art Direction Package is Accepted for Handoff and required Visual Alignment is resolved:

```text
Deferred Production inputs → Activated
```

Production Artist receives original technical constraints and authority classes in addition to accepted Art Direction.

## Production Execution

Production Artist realizes accepted Art Direction faithfully.

Final imagery and final typography are separated by default:

```text
Generated / edited image assets
+
Deterministic text composition and layout
→ Final deliverables
```

Production handles exact geometry, crop, safe areas, fonts, variants, export, and QA without becoming a new creative authority.

## Artifact and Input Ownership

- Deliverable Contract, Stage-Scoped Input Register, Project State, Greenlight Record, lock state, Acceptance Record — Creative Producer;
- Creative Treatment — Development, coordinated by Creative Producer and Greenlit by ECD;
- Creative Script — Editorial Director;
- Storyboard / Visual Sequence Board — Art Director;
- Representative Design Comp — Art Director;
- Art Direction Package — Art Director;
- Final Assets and technical completion record — Production Artist;
- final subjective acceptance — ECD.

The ECD owns the authority of original user instructions. Internal roles own only their professional interpretation at the active stage.

## Adaptive Entry

Examples:

- raw idea → Development;
- real public post → Development plus proportionate verification;
- visual reference in raw brief → register intended use now, activate detailed visual interpretation later;
- identified Greenlit Treatment → Editorial Director plus activation of stored Editorial inputs;
- Creative Script Accepted for Handoff → Art Director plus activation of stored Visual inputs;
- accepted Design Comp and Art Direction Package → Production Artist plus activation of stored Production inputs;
- copy correction → Editorial Director;
- visual correction → Art Director;
- technical correction → Production Artist.

Creative Producer records the entry point and reconstructs relevant stage-input state rather than losing previously supplied constraints.

## No Re-Ask Principle

The studio should not ask the ECD to repeat an input already preserved in the Stage-Scoped Input Register.

Ask again only for conflict, material ambiguity, changed consequence, or an explicitly reopened decision.

## Final Review

Before ECD Final Acceptance, confirm:

- the Deliverable Contract is complete;
- Greenlit meaning survived all downstream interpretation;
- every material ECD input is resolved, consciously superseded, rejected, or explicitly open;
- no Deferred Hard Constraint was lost;
- no Assistant Inference became user authority silently;
- required evidence, limitations, names, and wording remain visible;
- the accepted visual premise survived production;
- all variants exist;
- mobile and technical QA passed or limitations are explicit;
- deviations were authorized by the correct owner.
