# ECD V3 — Department Architecture

Status: `v3.0-alpha`
Branch: `v3-department-architecture`
Frozen V2 baseline: `v2.1-legacy` at `cdc48e4eba107dd67a4920d2fd1101058759031b`

## Purpose

ECD V3 changes the system from a small set of overloaded generalist roles into a studio operating system with accountable departments and method-bearing specialist Skills.

The user remains the Executive Creative Director and communicates only with Creative Producer. Internal organizational complexity stays backstage.

## Organization

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

Each department contains specialist Skills. Department Directors assign, review, return, integrate, and sign off their department's work before it reaches Creative Producer.

## Responsibility layers

### Specialist Skill

Owns one professional method and its craft output. It does not approve its own formal result, report directly to the ECD, activate another department, or silently change upstream authority.

### Department Director

Owns professional quality inside one department. The Director chooses the required specialist Skills, defines internal acceptance criteria, runs department review, returns weak work, integrates specialist outputs, and issues a `Department Cleared` package.

### Creative Producer

Owns project interpretation, planning, cross-department dependencies, state, authority, feedback closure, integrated review, ECD-facing release, and stage activation. Producer does not replace department-level professional judgment.

### Executive Creative Director

Owns Greenlight, Script Alignment, governing visual decisions, changes to previously approved decisions, Final Acceptance, and publication authority.

## Formal control loop

```text
ECD brief, decision, or feedback
→ Creative Producer project diagnosis
→ department assignment
→ Department Director capability plan
→ specialist execution and self-check
→ Department Director review
   ├─ Department Rework
   ├─ cross-department working loop
   └─ Department Cleared
→ Creative Producer integrated review
   ├─ return to department
   ├─ coordinate cross-department correction
   └─ Producer Cleared
→ ECD decision when required
→ Creative Producer records authority and activates next work
```

A specialist draft never becomes an authoritative interdepartmental handoff.

## Role and Skill separation

A Role defines accountability, authority, reporting, and review responsibility.

A Skill defines an actual professional method: how work is explored, constructed, judged, corrected, and delivered.

A long role description is not a substitute for a professional Skill. V3 therefore prohibits treating broad phrases such as `owns typography, layout, image making, and QA` as evidence that one role can perform all of those disciplines.

## Department model

### Creative Development Department

Director manages Creative Strategy, Concept Development, Research, Audience / Platform Strategy, and conditional Claims / Rights review.

Formal output: `Department Cleared Creative Treatment Package`.

### Editorial Department

Editorial Director manages Content Architecture, Frame Script Writing, Copywriting, Copy Editing, Proofreading, Evidence Editing, and Localization when required.

Formal output: `Department Cleared Creative Script Package`.

### Visual Department

Art Director manages Visual Concept, Storyboard / Sequence Design, Editorial Design, Typography, Image Direction, Information Design when required, and Design Critique.

Formal output: `Department Cleared Visual Development Package` and later `Department Cleared Art Direction Package`.

For text-bearing Social Editorial work, Editorial Design and Typography are mandatory capabilities. Image Direction is conditional on whether new imagery must be created or materially transformed.

### Production Department

Production Director manages Image Production, Retouch / Compositing, Finished Art, Production Typesetting, Variant Production, Output Engineering, and Technical QA.

Formal output: `Department Cleared Final Production Package`.

## Cross-department working loops

Creative Producer may authorize bounded working loops such as:

- Copywriter ↔ Editorial Designer for fit-preserving copy adjustment;
- Editorial Designer ↔ Image Director for composition and image requirements;
- Art Director ↔ Production Director for feasibility proof;
- Evidence Editor ↔ Information Designer for accurate representation.

These loops do not change authority. Any material change to an approved upstream decision returns to Creative Producer and the earliest affected department.

Formal results still return through Department Directors.

## Seat merging

Small projects may combine execution seats when risk and scope are low. Responsibilities remain distinct and no person or model instance may be the sole approver of its own formal work.

Examples:

- Content Architect and Copywriter may be one execution seat, reviewed by Editorial Director.
- Editorial Designer and Typographic Designer may be one execution seat, reviewed by Art Director.
- Image Production and Retouch may be one execution seat, reviewed by Production Director.

Seat merging reduces operational overhead; it does not erase method, evidence, review, or authority.

## Final sign-off

Before Final Acceptance, Creative Producer coordinates parallel department sign-off:

```text
Editorial Director — copy, facts, names, claims, and language
Art Director — visual fidelity and design quality
Production Director — implementation, variants, and technical integrity
Creative Producer — project integration, scope, feedback, and decision readiness
Executive Creative Director — Final Acceptance and publication authority
```

## Migration strategy

V2 is preserved exactly on `v2.1-legacy`.

V3 is built on `v3-department-architecture`. Existing V2 role and reference files remain migration sources until their methods are either:

- moved into a department Director manual;
- rebuilt as a specialist Skill;
- absorbed into a profile;
- or explicitly retired.

They are not automatically authoritative in V3.

## Build order

1. Establish V3 Core and department control loop.
2. Rebuild Visual Department first.
3. Build professional Editorial Design and Typography Skills.
4. Add Visual Concept, Storyboard, Image Direction, Information Design, and Design Critique.
5. Rebuild Editorial Department Skills.
6. Rebuild Development Department Skills.
7. Rebuild Production Department Skills.
8. Run specialist, department, and end-to-end evaluations before merging V3 to `main`.

## Current milestone

This branch begins Phase 1:

- V2 frozen;
- V3 department architecture established;
- Creative Producer moved to department-based orchestration;
- Department Director contracts established;
- Visual Department professional Skill layer started;
- no claim that V3 is production-ready until department Skills and evaluations pass.
