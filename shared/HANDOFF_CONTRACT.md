# Handoff Contract

## Principle

Creative Producer coordinates every formal transfer.

A specialist return, Producer clearance, ECD decision, and authoritative handoff are distinct events. No specialist may release formal work directly to the ECD, another specialist, or a downstream stage.

## Transfer types

### Assignment

Creative Producer activates a specialist with authoritative inputs, scope, permissions, acceptance criteria, and return conditions.

### Specialist Return

The specialist submits a formal artifact, self-QA, decision contract, limitations, and unresolved questions to Creative Producer.

It is not yet an authoritative handoff.

### Producer Review

Creative Producer independently verifies the artifact and records `Returned for Rework`, `Escalated for ECD Decision`, or `Producer Cleared`.

### ECD-facing release

When ECD authority is required, Creative Producer releases a complete decision object and recommendation after Producer clearance.

### Authoritative Handoff

Creative Producer transfers an artifact downstream only after its quality, authority, dependencies, feedback, and activation conditions are satisfied.

## Common assignment envelope

```markdown
From: Creative Producer
To:
Project / Project State:
Active phase:
Authoritative upstream artifacts and versions:
Artifact Decision Contracts:
Inherited decisions and locks:
Requested output:
Decisions owned by receiver:
Decisions outside receiver authority:
Deliverable Contract fields:
Activated input IDs with original source and authority:
Deferred inputs and capabilities:
Evidence / rights / attribution conditions:
Reference roles and transfer boundaries:
Assets and provenance:
Acceptance criteria:
Known risks or blockers:
Expected specialist self-QA:
Expected Producer Review:
Expected ECD gate:
Return conditions:
```

## Common specialist-return envelope

```markdown
From:
To: Creative Producer
Artifact / version:
Specialist self-QA:
Artifact Decision Contract:
Activated-input resolution:
Dependencies:
Known limitations:
Unresolved conflicts or authority request:
Recommended Producer disposition:
```

## Common authoritative-handoff envelope

```markdown
From: Creative Producer
To:
Project / state reference:
Authoritative artifact and version:
Quality state:
Authority state:
Producer Review Record:
ECD decision record, when required:
Artifact Decision Contract:
Active locks and tolerances:
Activated inputs and capabilities:
Deferred inputs and capabilities:
Applicable feedback closure:
Evidence / rights / reference / asset conditions:
Requested downstream output:
Return conditions:
Next expected ECD gate:
```

A handoff is invalid when the receiver must guess whether a statement is binding, optional, inferred, approved, or still Deferred.

## Development flow

```text
Creative Producer assignment
→ Development work and self-QA
→ Development return to Creative Producer
→ Producer Review
→ Producer Cleared Treatment
→ complete ECD Greenlight object
→ ECD Greenlight
→ Creative Producer activates Editorial
```

The Greenlight release turn ends at the decision request.

## Editorial flow

### Producer assignment to Editorial Director

Transfer:

- Greenlit Treatment and Greenlight Record;
- Accepted Development Decisions;
- Deliverable Contract and target language / locale;
- Activated Editorial inputs with original source and authority;
- Development locks and boundaries;
- exact names, claims, evidence, and limitations;
- current Artifact Decision Contracts;
- Visual and Production inputs and capabilities still Deferred;
- acceptance criteria and expected Script Alignment.

### Editorial Director return to Creative Producer

Return:

- Creative Script version;
- Editorial self-QA;
- Overall Communication Logic and complete sequence;
- Internal Semantic Propositions;
- Frame Script for every page;
- Written Visual Requirements;
- exact on-screen and companion copy;
- evidence and limitation placement;
- Editorial input resolution;
- Artifact Decision Contract and delta;
- known limitations and open visual questions.

### Producer release for Script Alignment

Creative Producer independently reviews the full package and returns defects internally.

After Producer clearance, present:

1. Overall Communication Logic;
2. every page using `What this page says`, `Frame Script`, and `Page Copy`;
3. complete Companion / Body Copy;
4. relevant delta and feedback closure;
5. Alignment scope and Deferred Visual scope;
6. Producer recommendation;
7. explicit decision request.

Every new Creative Script requires ECD Script Alignment. Visual capabilities remain inactive until Creative Producer records the decision.

## Visual flow

### Producer assignment to Art Director

Transfer:

- ECD-aligned Script;
- Greenlit Treatment;
- accepted Frame Scripts;
- Written Visual Requirements and semantic locks;
- exact copy and permitted compression;
- Deliverable Contract and viewing conditions;
- Activated Visual inputs;
- original references, roles, rights, and transfer boundaries;
- current Artifact Decision Contracts;
- Production inputs and capabilities still Deferred;
- expected representative proof and visual authority.

### Art Director return to Creative Producer

Return:

- visual artifact and version;
- visual self-QA;
- Frame Script and Written Visual Requirement fidelity;
- Artifact Decision Contract and delta;
- active-input and reference-resolution state;
- representative proof;
- professional recommendation;
- known risks, tolerances, and unresolved authority questions.

### Producer release for Visual Alignment

Creative Producer reviews the actual proof and returns weak, incomplete, or misaligned work internally.

When a new or changed governing visual decision requires ECD authority, present the representative evidence, Producer recommendation, delta, tradeoff, decision scope, and next consequence.

### Authoritative handoff to Production

Creative Producer activates Production only when:

```text
Art Director self-QA
+ Producer Cleared Art Direction
+ required ECD visual authority
+ current dependencies and closed blocking feedback
```

## Production flow

### Producer assignment to Production Artist

Transfer:

- ECD-aligned Script, Frame Scripts, and exact copy;
- governing visual decisions and authority records;
- Storyboard, anchors, Design Comp, and Producer Cleared Art Direction Package;
- Deliverable Contract;
- Activated Production inputs;
- assets, provenance, rights, and transformation permissions;
- exact technical specifications, locks, tolerances, and fallbacks;
- acceptance criteria and final QA requirements.

### Production Artist return to Creative Producer

Return:

- final files and variants;
- Production self-QA;
- Artifact Decision Contract and implementation delta;
- input resolution and provenance;
- exact-copy verification;
- mobile and technical QA;
- authorized deviations;
- known limitations.

### Producer Final Review and ECD release

Creative Producer independently reviews the complete final package, verifies feedback closure and upstream fidelity, returns defects internally, and releases only a Producer Cleared final decision object for ECD Final Acceptance.

## Return path

Creative Producer routes rework to the earliest affected object:

- premise, governing logic, claim, evidence, rights, or Greenlight basis → Development;
- sequence, page meaning, Frame Script, Written Visual Requirement, or copy → Editorial Director / Copy Desk;
- visual problem, intent, reference, metaphor, route, Storyboard, anchor, or design → Art Director;
- exact implementation, asset defect, typography, crop, variant, or export → Production Artist;
- state, activation, decision presentation, assignment, review, or feedback closure → Creative Producer.

## Handoff QA

An authoritative handoff passes when:

- artifact, version, quality state, and authority state are identifiable;
- Producer Review passed;
- required ECD authority is recorded;
- Artifact Decision Contract and dependencies are current;
- active and Deferred capabilities are explicit;
- original source and professional interpretation remain distinguishable;
- applicable ECD feedback is closed or disclosed;
- the receiver can work without inventing upstream decisions;
- return conditions and next gate are clear.
