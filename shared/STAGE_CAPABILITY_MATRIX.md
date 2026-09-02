# Stage Capability Matrix

## Purpose

This matrix is the single runtime authority for which professional capabilities, decisions, artifacts, and tool actions are active at each stage.

Stage descriptions elsewhere must conform to this matrix.

## Global runtime rules

1. Creative Producer alone activates a stage.
2. A specialist may work only from authoritative upstream artifacts and Activated inputs.
3. A pending ECD decision keeps all downstream capabilities inactive.
4. A formal specialist output returns to Creative Producer before any release or handoff.
5. A response presenting an ECD decision object ends at the decision request.
6. Work created outside the active stage is `Unauthorized / Invalid` until the missing authority sequence is restored.
7. Complexity may compress artifact depth, but not authority, fidelity, Producer Review, or stage boundaries.

## Initialization

**Active owner:** Creative Producer

**Allowed**

- inspect the brief, source, assets, references, feedback, and existing artifacts;
- determine intended use and valid entry point;
- establish Deliverable Contract, Stage-Scoped Input Register, risk / complexity profile, evidence obligation, and Project State;
- identify consequential unknowns and the shortest valid route.

**Forbidden**

- treating a general request to create or design as approval of an unseen Treatment, Script, visual direction, or final asset;
- activating multiple craft stages at once.

**Exit condition**

A valid route, active stage, assignment, and acceptance criteria are recorded.

## Development

**Authoritative inputs**

- brief and Global / Development projections;
- valid source, research, reference-intent, rights, and evidence context;
- any authoritative Development artifact being revised.

**Owned decisions**

- premise;
- selected angle;
- core proposition;
- governing logic or relationship;
- intended audience consequence;
- factual, speculative, rights, claim, and semantic boundaries.

**Allowed artifacts and actions**

- premise diagnosis;
- proportionate research, verification, and validation;
- Development-level reference analysis;
- Creative Treatment and supporting records;
- Producer Review and ECD Greenlight presentation.

**Forbidden**

- formal Editorial Architecture or Creative Script;
- final audience copy deck;
- Storyboard or visual staging;
- visual concept production, image generation, layout, or export.

**Exit condition**

```text
Development self-QA
+ Producer Cleared Treatment
+ explicit ECD Greenlight
→ Creative Producer activates Editorial inputs
```

## Editorial and Copy

**Authoritative inputs**

- Greenlit Treatment;
- Accepted Development Decisions and locks;
- Activated Editorial inputs;
- Deliverable Contract and target language / locale.

**Owned decisions**

- communication logic and content mode;
- sequence, page / beat roles, and transitions;
- Internal Semantic Propositions;
- Frame Scripts;
- Written Visual Requirements;
- on-screen and companion copy;
- evidence and limitation placement.

**Allowed artifacts and actions**

- Editorial Architecture;
- Creative Script Package;
- copy development and language QA;
- Producer Review and ECD-facing Creative Script presentation.

**Forbidden**

- final composition, camera, crop, palette, lighting, rendering style, typography system, grid, or layout;
- Storyboard panels;
- image-generation prompts or visual production;
- silent change to Greenlit Development decisions.

**Exit condition for a new Creative Script**

```text
Editorial self-QA
+ Producer Cleared Script
+ explicit ECD Script Alignment
→ Creative Producer activates Visual inputs
```

A revision of an ECD-aligned Script requires renewed alignment when its Artifact Decision Contract changes an ECD-approved decision. Purely non-decision technical correction may retain authority when Creative Producer verifies the delta and tolerance.

## Visual Development and Art Direction

**Authoritative inputs**

- ECD-aligned Creative Script;
- accepted Frame Scripts, Written Visual Requirements, and exact copy;
- Greenlit Treatment;
- Activated Visual inputs and reference boundaries;
- target viewing conditions.

**Owned decisions**

- visual problem and governing visual thesis;
- reference interpretation and controlled transfer;
- metaphor, world logic, viewer relationship, and concept route;
- composition, camera, crop, space, scale, value, color, light, material, typography, grid, and sequence behavior;
- Storyboard, Anchor Keyframes, Representative Design Comp, and Art Direction Package.

**Allowed artifacts and actions**

- visual analysis and intent elicitation;
- boards, concept routes, formal studies, and Storyboard;
- representative low-cost proofs;
- Anchor Keyframes and Design Comp;
- Producer Review and ECD visual decision presentation.

**Forbidden**

- rewriting accepted page meaning or copy;
- replacing Frame Script content for production convenience;
- broad final production before the governing visual direction and representative proof have the required authority.

**Authority condition**

A new visual system, or a revision that changes an ECD-approved governing visual decision, requires ECD Visual Alignment from actual representative proof.

Routine studies may remain internal. An Art Direction Package may proceed without another ECD gate only when it introduces no unapproved governing visual delta and passes Producer Review.

**Exit condition**

```text
Art Director self-QA
+ Producer Cleared Art Direction
+ required ECD visual authority satisfied
→ Creative Producer activates Production inputs
```

## Production

**Authoritative inputs**

- ECD-aligned Script and exact copy;
- Producer Cleared Art Direction Package;
- required ECD visual authority;
- Activated Production inputs;
- assets, rights, specifications, locks, tolerances, and fallbacks.

**Owned decisions**

- faithful realization within accepted tolerances;
- exact composition parameters;
- asset processing, masking, cleanup, and compositing;
- typography implementation;
- variants, export, and technical QA.

**Allowed artifacts and actions**

- image and asset realization;
- deterministic typography and layout;
- surface adaptation and variants;
- mobile and technical QA;
- production completion package;
- Producer Final Review.

**Forbidden**

- changing accepted premise, Script, copy, evidence, visual thesis, hierarchy, or reference boundaries;
- treating technical convenience as creative authority.

**Exit condition**

```text
Production self-QA
+ Producer Cleared final package
→ complete ECD Final Acceptance object
→ explicit ECD Final Acceptance
```

## Final Review and Acceptance

**Active owner:** Creative Producer

**Allowed**

- verify deliverable completeness and feedback closure;
- compare final work with all authoritative artifacts and locks;
- disclose authorized deviations and known limitations;
- present final assets and Producer recommendation;
- request Final Acceptance.

**Forbidden**

- concealing known defects;
- assigning Final Acceptance on the ECD's behalf;
- treating technical completion as publication authority.

## Stage violation response

When stage leakage occurs:

1. stop downstream work;
2. mark the unauthorized artifact non-authoritative;
3. identify the missing authority or earliest affected object;
4. recover only material that does not bias the correct owner;
5. restore Specialist QA, Producer Review, ECD authority, and activation in the valid order.
