# ECD V3.1 Architecture

## 1. Purpose

ECD is a studio operating system, not one large prompt pretending to be every profession.

It combines two separate layers:

```text
Organizational accountability
Producer → Department Director → ECD authority

Professional capability
Registered Specialist Skills with methods and evidence
```

A role defines accountability. A Skill defines how professional work is actually done.

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

Owns Greenlight, Script Alignment, governing visual approval, changes to previously approved decisions, Final Acceptance, and publication authority.

### Creative Producer

Owns project diagnosis, entry routing, plan, dependencies, state, authority binding, department assignments, cross-department loops, feedback closure, integrated review, ECD-facing release, and completion record.

### Department Director

Owns professional quality in one department. Selects only implemented specialist Skills, reviews actual artifacts, returns weak work, signs a Department Review Record, and reports a Department Cleared package to Producer.

### Specialist Skill

Owns one professional method. Produces an inspectable Specialist Return. It cannot approve itself, activate another phase, or communicate formal work directly to the ECD.

## 3. Registered capability model

`core/CAPABILITY_REGISTRY.md` is authoritative.

A capability is real only when:

1. it has an actual `SKILL.md` path;
2. frontmatter contains a unique `name` and usable `description`;
3. its method, inputs, outputs, self-check, failure routing, and reporting boundary are defined;
4. the active profile permits its use;
5. the current Project State activates it.

A Director may not claim to have invoked a profession that exists only as a line in an organization chart.

## 4. Runtime layers

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

Registered Specialist Skills produce department artifacts.

### Review layer

```text
Specialist self-check
→ Department Director review
→ Producer integrated review
→ ECD decision when required
```

## 5. Authority and state

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

## 6. Clean runtime rule

V3 does not carry V2 runtime files in its branch.

V2 remains recoverable from `v2.1-legacy`. V3 may preserve a validated V2 principle only by rewriting it into a V3 Core, Director, Specialist, or Profile file.

## 7. Default Social Editorial chain

```text
Producer Discovery / Initialization

Development Department
Creative Strategy
→ Concept Development
→ Research Verification / Claims Rights when required
→ Development Director review
→ Producer review
→ ECD Greenlight

Editorial Department
Content Architecture
→ Frame Script
→ Copywriting
→ Copy Editing
→ Proofreading
→ Editorial Director review
→ Producer review
→ ECD Script Alignment

Visual Department
Visual Concept
→ Storyboard / Sequence
→ Editorial Design
↔ Typography
↔ Image Direction when required
→ Design Critique
→ Art Director review
→ Producer review
→ ECD Visual Alignment when required

Production Department
Image Production when required
→ Finished Art
↔ Production Typesetting
→ Technical QA
→ Production Director review
→ Editorial / Visual / Production sign-offs
→ Producer Final Review
→ ECD Final Acceptance
```

## 8. Dynamic scale

Small projects may combine execution seats, but cannot erase professional tasks or review responsibility.

For example, one model pass may perform both Copywriting and Copy Editing methods, but:

- the two Skill methods remain distinct;
- the Copy Editing pass must inspect a completed draft rather than merely restate writer intent;
- Editorial Director must still review the actual result;
- no false claim of a separate person or agent may be made.

## 9. Evidence standard

Every formal clearance must identify:

- actual artifact reviewed;
- registered Skills used;
- method evidence;
- defects found;
- corrections made;
- unresolved issues;
- Director disposition;
- downstream use requested.

A checklist with every box marked `pass` is not evidence by itself.

## 10. Failure behavior

When a downstream defect appears, Producer and Directors identify the earliest artifact where it became true.

Examples:

- wrong premise → Development;
- weak sequence or misleading speaker position → Editorial;
- generic layout or copy-blind image → Visual;
- inaccurate typesetting or poor composite → Production;
- ambiguous approval → Authority and Project State.

Rework returns to that earliest owner. Downstream decoration cannot close an upstream defect.
