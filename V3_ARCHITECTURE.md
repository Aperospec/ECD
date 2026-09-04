# ECD V3.2 Architecture

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

V3.2 adds two structural protections:

- high-leverage communication progression is confirmed before dependent page elaboration;
- public social sources used only to discover a topic remain Discovery Signals rather than automatic attribution, evidence, or imitation mandates.

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

Owns Greenlight, required Core Script Alignment, Creative Script Alignment, governing visual approval, changes to previously approved decisions, Final Acceptance, and publication authority.

### Creative Producer

Owns project diagnosis, source posture, adaptive route, high-leverage decision routing, dependencies, state, authority binding, Department assignments, cross-Department loops, feedback closure, integrated review, ECD-facing release, and completion record.

### Department Director

Owns professional quality in one Department. Selects only implemented Specialist Skills, reviews actual artifacts, returns weak work, signs a Department Review Record, and reports a Department Cleared package to Producer.

### Specialist Skill

Owns one professional method. Produces an inspectable Specialist Return. It cannot approve itself, activate another phase, or communicate formal work directly to ECD.

## 3. Registered capability model

`core/CAPABILITY_REGISTRY.md` is authoritative.

A capability is real only when:

1. it has an actual `SKILL.md` path;
2. frontmatter contains a unique `name` and usable `description`;
3. its method, inputs, outputs, self-check, failure routing, and reporting boundary are defined;
4. the active profile permits its use;
5. current Project State activates it.

A Director may not claim to have invoked a profession that exists only as a line in an organization chart.

## 4. Runtime layers

### Advisory layer

Used for discovery, comparison, topic selection, and opportunity assessment. Advisory outputs do not create authoritative project artifacts.

### Development layer

Creates the Creative Treatment and establishes whether the project deserves further development.

### Core communication layer

After Greenlight, `ecd-core-communication-script` writes the actual end-to-end story, argument, explanation, demonstration, comparison, procedure, evidence progression, thematic progression, or mixed form.

This layer exists before page architecture and exact copy.

### Editorial adaptation layer

Maps the approved Core Communication Script into the minimum sufficient format, pages, Frame Scripts, exact copy, and publication copy.

### Visual and Production layers

Create and realize the approved visual system without rewriting upstream meaning.

### Review layer

```text
Specialist self-check
→ Department Director review
→ Producer integrated review
→ ECD decision when required
```

## 5. High-leverage decision model

`core/HIGH_LEVERAGE_DECISIONS.md` determines whether the Core Communication Script requires:

- Separate Core Script Alignment;
- Combined with Creative Script Alignment;
- Existing Aligned reuse;
- Not Applicable.

A separate gate is used when changing the actual communication progression would invalidate substantial dependent page, copy, or visual work.

A combined gate is used only when dependency risk is genuinely low.

The rule protects decisions by invalidation cost, not by fixed page count.

## 6. Authority sequence

```text
Creative Treatment
→ ECD Greenlight
→ Core Communication Script
→ ECD Core Script Alignment when required
→ Creative Script / Editorial Adaptation
→ ECD Creative Script Alignment
→ Visual Development Package
→ ECD Visual Alignment when required
→ Final Production Package
→ ECD Final Acceptance
```

Authority is not inferred from enthusiasm or conversational momentum.

A user reply can approve an artifact only when Project State identifies a current Pending Decision Object with:

- decision ID;
- artifact and version;
- approval type;
- complete visible content;
- approval scope;
- exclusions;
- consequence;
- explicit request.

## 7. Concept Reframing model

`profiles/social-editorial/CONCEPT_REFRAMING.md` distinguishes:

- Discovery Signal;
- Factual Dependency;
- Direct-use Material.

When another social post is only a Discovery Signal:

- engagement informs topic selection;
- the studio independently develops angle, Core Script, examples, copy, and visuals;
- no independent reproduction is required unless the current publication claims reproduction or reliability;
- no public creator attribution, source link, non-testing statement, concept disclaimer, or productization language is added by default;
- source-specific wording, sequence, examples, assets, and visual expression remain excluded.

Factual Dependency and Direct-use Material activate only the controls actually required by the final publication.

## 8. Default Social Editorial chain

```text
Producer Discovery / Initialization

Development Department
Creative Strategy
→ Concept Development
→ Research Verification / Claims Rights only when required
→ Development Director review
→ Producer review
→ ECD Greenlight

Editorial Department — Core Communication
Core Communication Script
→ Editorial Director review
→ Producer review
→ ECD Core Script Alignment when high-leverage

Editorial Department — Adaptation
Content Architecture
→ Frame Script
→ Copywriting
→ native-language / bilingual craft when required
→ Copy Editing
→ Proofreading
→ Editorial Director review
→ Producer review
→ ECD Creative Script Alignment

Visual Department
Visual Concept
→ Storyboard / Sequence when required
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

## 9. Dynamic scale

Small projects may combine execution seats and low-dependency decision scopes, but cannot erase professional questions or review responsibility.

For example, one model pass may perform Core Communication Script and Content Architecture methods in a Compact project only when:

- the Core Script is still visibly distinguishable;
- the High-Leverage Decision Record justifies combined approval;
- the ECD-facing object shows Core Script before page adaptation;
- Editorial Director reviews the actual result;
- no false claim of separate people or agents is made.

## 10. Evidence standard

Every formal clearance identifies:

- actual artifact reviewed;
- registered Skills used;
- professional questions served;
- method evidence;
- high-leverage decision status;
- source posture and reference consequence;
- defects found;
- corrections made;
- unresolved issues;
- Director disposition;
- downstream use requested.

A checklist with every box marked `pass` is not evidence by itself.

## 11. Failure behavior

When a downstream defect appears, Producer and Directors identify the earliest artifact where it became true.

Examples:

- wrong premise → Development;
- weak or uninteresting actual communication progression → Core Communication Script;
- wrong page mapping or exact copy → Editorial Adaptation;
- generic or source-derivative layout → Visual;
- inaccurate typesetting or poor composite → Production;
- ambiguous approval → Authority and Project State.

Rework returns to that earliest owner. Downstream decoration cannot close an upstream defect.
