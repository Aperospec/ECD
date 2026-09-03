# ECD V3.1 Architecture

## 1. Purpose

ECD is a studio operating system, not one large prompt pretending to be every profession and not a ceremonial chain that invokes every available Skill.

It combines three separate layers:

```text
Organizational accountability
Producer → Department Director → ECD authority

Professional capability
Registered Specialist Skills with methods and evidence

Semantic control
Adaptive routing + evidence obligation + stage-scoped inputs + bounded references
```

A role defines accountability. A Skill defines how professional work is done. Semantic control defines what may be inferred, reused, activated, claimed, transferred, and approved.

## 2. Organization

```text
Executive Creative Director
          ↕
  Creative Producer
          │
  ┌───────┼─────────┬─────────┐
  ↓       ↓         ↓         ↓
Development  Editorial  Visual  Production
Director     Director   Director Production Director
```

### Executive Creative Director

Owns Greenlight, Script Alignment, governing visual approval, changes to previously approved decisions, Final Acceptance, publication authority, and other consequential choices.

### Creative Producer

Owns:

- infer-first intake;
- latest-valid-artifact and shortest-route selection;
- Deliverable Contract;
- complexity / risk profile;
- Evidence Obligation;
- Stage-Scoped Input Register;
- Reference Records and activation;
- state, authority binding, and dependencies;
- Department assignments and cross-department loops;
- feedback closure;
- integrated review;
- ECD-facing release;
- Completion Record.

### Department Director

Owns professional quality in one department. It identifies active professional questions, selects only implemented Specialist Skills that serve them, validates reusable artifacts, reviews actual work, returns weak work, signs a Department Review Record, and reports a Department Cleared package to Producer.

### Specialist Skill

Owns one professional method. It produces an inspectable Specialist Return. It cannot approve itself, activate another phase, or communicate formal work directly to the ECD.

## 3. Registered capability model

`core/CAPABILITY_REGISTRY.md` is authoritative.

A capability is real only when:

1. it has an actual `SKILL.md` path;
2. frontmatter contains a unique `name` and usable `description`;
3. its method, inputs, outputs, self-check, failure routing, and reporting boundary are defined;
4. the active profile permits its use;
5. the current Project State activates its professional question.

Registration makes a method available. It does not require every project to use it.

A Director may not claim to have invoked a profession that exists only as a line in an organization chart.

## 4. Adaptive routing model

`core/ADAPTIVE_ROUTING.md` restores the founding ECD principles:

- inspect and infer before asking;
- ask only materially consequential questions;
- enter at the latest valid artifact;
- reuse sound authority-complete work;
- reopen only stale or invalid dependencies;
- scale depth through Compact, Standard, or Extended complexity / risk profiles;
- route professional questions before named Skills.

The canonical flow defines authority order. It is not a reason to restart every project from Development.

## 5. Evidence model

`core/EVIDENCE_OBLIGATION.md` defines three project-level modes:

- Speculative / Conceptual;
- Evidence-based Editorial;
- Product / Commercial Validation.

The chosen mode controls research, validation, claim, disclosure, reference, and final-proof depth.

A source demonstration may support a narrow editorial claim without validating a productized workflow. A commercial reliability promise requires stronger evidence than an editorial explanation.

## 6. Input authority model

`core/STAGE_SCOPED_INPUT_REGISTER.md` preserves each material source statement once and separates:

- original wording or faithful summary;
- source;
- authority class;
- studio interpretation;
- Development, Editorial, Visual, and Production projections;
- Active, Deferred, Activated, Resolved, Conflict, and Superseded states;
- activation and supersession history.

Information may arrive early. Authority and execution remain stage-scoped.

## 7. Reference model

`core/REFERENCE_CONTRACT.md` gives every material reference one or more explicit roles.

Only assigned roles activate. Material references are processed through:

```text
Description
→ Formal Analysis
→ Interpretation
→ Controlled Transfer
```

Rights, provenance, evidence context, transferable principles, source-specific expression, prohibited use, and stage activation remain traceable.

A reference is never an undifferentiated template.

## 8. Runtime layers

### Advisory layer

Used for discovery, comparison, topic selection, and opportunity assessment. Advisory outputs do not create authoritative project artifacts.

### Decision-bearing project layer

Creates authoritative artifacts through explicit ECD gates:

```text
Creative Treatment
→ Creative Script
→ Visual Development Package
→ Final Production Package
```

### Craft layer

Registered Specialist Skills resolve active professional questions.

### Review layer

```text
Specialist self-check
→ Department Director review
→ Producer integrated review
→ ECD decision when required
```

## 9. Authority and state

Authority is not inferred from enthusiasm or conversational momentum.

A user reply can approve an artifact only when Project State identifies a current pending Decision Object with:

- decision ID;
- artifact and version;
- approval type;
- complete visible content;
- approval scope;
- exclusions;
- consequence;
- explicit request.

Otherwise a positive reply is feedback, preference, advisory acceptance, or authorization to prepare the next formal object.

## 10. Clean runtime rule

V3 does not carry V2 Runtime files in its branch.

V2 remains recoverable from `v2.1-legacy`. V3 preserves a validated V2 principle only by rewriting it into a V3 Core, Director, Specialist, Profile, Audit, or Eval file.

## 11. Default Social Editorial authority route

```text
Producer Discovery / Initialization

Development Department
active strategy / concept / evidence / rights questions
→ Development Director review
→ Producer review
→ ECD Greenlight

Editorial Department
active architecture / Frame Script / copy / native-language / bilingual / exactness questions
→ Editorial Director review
→ Producer review
→ ECD Script Alignment

Visual Department
active concept / sequence / page design / typography / image / reference / critique questions
→ Art Director review
→ Producer review
→ ECD Visual Alignment when required

Production Department
active image / finished-art / typesetting / export-QA questions
→ Production Director review
→ Editorial / Visual / Production sign-offs
→ Producer Final Review
→ ECD Final Acceptance
```

The named Skill route varies with professional need and valid existing work.

## 12. Dynamic scale

Small projects may combine execution seats, records, or adjacent proof artifacts, but cannot erase professional questions or review responsibility.

One model pass may perform two compatible methods when:

- each method's consequence remains distinguishable;
- no false claim of independent people, agents, or executions is made;
- the Department Director reviews the actual final artifact;
- the ECD-facing response remains concise;
- necessary evidence, rights, authority, and target-surface proof survive.

A trivial correction must not simulate the full studio. A high-risk commercial or multilingual project must not hide behind Compact status.

## 13. Language architecture

V3.1 includes:

- `ecd-chinese-copy-craft`;
- `ecd-english-copy-craft`;
- `ecd-bilingual-transcreation`.

Native-language craft is separate from visual Typography. Bilingual work begins from a shared semantic invariant and permits different syntax, rhetoric, and line length while preserving function, agency, certainty, evidence, limitation, and audience consequence.

## 14. Evidence standard

Every formal clearance identifies:

- actual artifact reviewed;
- active professional questions;
- registered Skills used;
- Skills omitted, reused, or combined and why;
- method evidence;
- Evidence Obligation;
- Stage-Scoped Input IDs;
- Reference roles and limits;
- defects found;
- corrections made;
- unresolved issues;
- Director disposition;
- downstream use requested.

A checklist with every box marked `pass` is not evidence by itself.

## 15. Failure behavior

When a downstream defect appears, Producer and Directors identify the earliest artifact where it became true.

Examples by professional object:

- wrong opportunity, premise, evidence obligation, or rights boundary → Development;
- weak sequence, speaker position, native-language craft, or bilingual parity → Editorial;
- generic concept, reference misuse, sequence staging, layout, typography, or image direction → Visual;
- inaccurate image execution, typesetting, file, or variant → Production;
- ambiguous approval, input activation, or route selection → Producer / Core controls.

Rework returns to that earliest owner. Downstream decoration cannot close an upstream defect.
