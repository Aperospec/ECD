# ECD

ECD is a single-entry, stage-gated Social Editorial studio Skill.

The human user is the Executive Creative Director. Creative Producer is the single accountable project owner and the only user-facing interface. Three specialist roles perform the craft:

- Editorial Director
- Art Director
- Production Artist

## Operating model

```text
ECD brief or feedback
→ Creative Producer assignment
→ specialist execution and self-QA
→ Producer Review
→ ECD decision when required
→ Creative Producer stage activation
```

No formal specialist output may reach the ECD, another specialist, or a downstream stage before Producer Review passes.

## Core invariants

1. **No Silent Mutation** — downstream work may elaborate but cannot silently change authoritative upstream decisions.
2. **No Implicit Authority** — specialist QA, Producer clearance, and ECD approval are distinct.
3. **No Hidden Decision Object** — every ECD decision is based on a complete visible object and a Producer recommendation.
4. **No Stage Leakage** — only capabilities belonging to the active stage may operate.
5. **Minimal Sufficient Process** — complexity changes depth, not authority or fidelity.
6. **No Unreviewed Release** — Creative Producer independently reviews every formal output and closes feedback before release.
7. **No Copy-Blind Image Production** — exact copy shapes composition before any image intended for direct final use is generated or committed.

## Workflow

```text
Brief
→ Creative Treatment
→ Producer Review
→ ECD Greenlight
→ Creative Script, Frame Scripts, and Exact Copy
→ Producer Review
→ ECD Script Alignment
→ Visual Development and Storyboard
→ Copy-Aware Layout Maps
→ Production-intent Anchors and Design Comp
→ Type-Fit Proof
→ Producer Review
→ required ECD Visual Alignment
→ Art Direction
→ Production-intent image realization
→ Deterministic Typography
→ Final Type-Fit and QA
→ Producer Final Review
→ ECD Final Acceptance
```

Every new Creative Script requires ECD Script Alignment. A new visual system requires ECD Visual Alignment from representative proof before broad Production. Revisions require renewed authority when their decision delta changes an ECD-approved decision.

## Copy-aware composition

For each text-bearing Production-intent screen, exact copy is preflighted at target geometry before image generation or selection.

The Copy-Aware Layout Map records:

- hierarchy and provisional line behavior;
- copy footprint and minimum readable scale;
- image–type relationship and layer order;
- protected subject, action, interface, and evidence zones;
- quiet, overlap, occlusion, and local-contrast conditions;
- crop, variant, mask, and image-generation consequences.

Exploratory image-world studies may test atmosphere or visual language, but they cannot be silently promoted into final-page assets. Required audience text remains separate, editable, and deterministic by default.

After imagery exists, exact copy is recomposed and must pass Type-Fit at target viewing width. A failed fit returns to the earliest affected object rather than being concealed through unreadable text, unauthorized copy changes, hierarchy collapse, or emergency layout repair.

See `art-director/references/copy-aware-composition.md`.

## Responsibility

- **Specialists** own professional craft quality.
- **Creative Producer** owns project interpretation, assignments, state, cross-artifact coherence, independent review, feedback closure, recommendation, release, and stage activation.
- **Executive Creative Director** owns Greenlight, Script Alignment, governing visual decisions, changes to approved decisions, Final Acceptance, and publication authority.

## Core control documents

```text
shared/PRODUCER_CONTROL_LOOP.md
shared/ARTIFACT_DECISION_CONTRACT.md
shared/STAGE_CAPABILITY_MATRIX.md
shared/ARTIFACT_STATES.md
shared/PROJECT_STATE.md
shared/ECD_DECISION_PRESENTATION.md
shared/HANDOFF_CONTRACT.md
shared/LOCK_AND_REWORK_PROTOCOL.md
art-director/references/copy-aware-composition.md
```

## Social Editorial profile

The profile retains the professional distinction among:

- Creative Treatment — what the project is and why it matters;
- Creative Script — how it communicates;
- Internal Semantic Proposition — what a page means;
- Frame Script — what the audience will visibly encounter;
- Written Visual Requirements — what visual interpretation must preserve;
- Storyboard — the first actual visual staging;
- Copy-Aware Layout Map — how exact copy constrains image and layout geometry;
- Anchor Keyframe / Design Comp — representative visual and Type-Fit proof;
- Art Direction Package — the authoritative visual Production system;
- Final Assets — faithful image realization plus deterministic typography.

Internal records may be detailed. ECD-facing proposals remain complete, concrete, and easy to judge without opening an archive or decoding workflow terminology.
