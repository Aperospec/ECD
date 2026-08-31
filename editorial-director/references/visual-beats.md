# Written Visual Requirements

## Purpose

Written Visual Requirements preserve the semantic conditions that later visual work must satisfy.

They were previously described as Written Visual Beats. The term remains compatible with earlier project records, but this file now distinguishes them clearly from the ECD-facing **Frame Script**.

A Written Visual Requirement is an acceptance criterion. It is not the page's concrete scene description and not a visual artifact.

## Relationship to the Frame Script

```text
Internal Semantic Proposition
states what the page means

Frame Script
states what the audience will visibly encounter

Written Visual Requirements
state what the later visual interpretation must preserve

Storyboard / Visual Sequence Board
creates the first actual visual staging
```

A Creative Script needs both the Frame Script and the Written Visual Requirements.

The Frame Script lets the ECD picture the proposed content. The requirements protect that content during Art Direction and Production.

## Responsibilities

For each page, record only the semantic conditions necessary to preserve editorial meaning, such as:

- a required subject, object, action, state, or relationship;
- a transformation that must be visible;
- an input, handoff, conflict, comparison, or result that must remain legible;
- evidence that must be shown rather than merely described;
- continuity across pages;
- a limitation or qualification that affects interpretation;
- a required perception of scale, absence, accumulation, isolation, or change;
- the distinction between several roles or states when that distinction carries the idea.

## Boundary

Written Visual Requirements do not specify routine visual execution such as:

- exact composition or placement;
- final camera, lens, or crop;
- typography, grid, or spacing;
- final palette, lighting, material, or rendering style;
- detailed visual metaphor implementation;
- image-generation prompts;
- production technique.

Those belong to Art Director or Production Artist.

## ECD-Facing Use

Written Visual Requirements normally remain in the internal Creative Script Package.

Do not display them as a separate field on every page merely to prove process completeness. Surface a requirement to the ECD only when:

- it is a material creative choice;
- it defines a factual, fictional, evidentiary, or ethical boundary;
- accepting the Frame Script would otherwise leave the decision ambiguous;
- it conflicts with another user instruction;
- it materially limits the later visual direction.

When surfaced, translate it into ordinary language under a brief `Decision note` rather than exposing internal terminology.

## Requirement Template

```markdown
Page / Beat:
Source Frame Script:
Required visible subject / state / relation:
Required evidence or limitation:
Continuity requirement:
Meaning that must survive:
Variables left to Art Director:
```

## Evidence-Led Requirements

When screenshots, outputs, documents, interfaces, charts, tests, or comparisons carry proof:

- identify the evidence object;
- preserve context needed for correct interpretation;
- identify the limitation that must remain near the evidence;
- distinguish actual evidence, reconstruction, simulation, and speculation;
- require equivalent comparison conditions when a before / after claim depends on them.

## QA

For every set of requirements confirm:

- each requirement protects a necessary meaning rather than a preferred decoration;
- it derives from the Greenlit Treatment, Activated Editorial inputs, or an authorized editorial decision;
- it does not repeat the Frame Script in abstract language without adding a preservation condition;
- it does not perform Art Direction prematurely;
- Art Director can create more than one valid visual solution;
- evidence and limitations cannot disappear during visual simplification;
- the set is concise enough to function as real acceptance criteria.

## Failure Conditions

A Creative Script fails when:

- the Written Visual Requirements are used instead of a concrete Frame Script;
- the requirements merely say what the audience should understand without identifying what must remain visible;
- every possible detail is labeled mandatory;
- later-stage aesthetic preferences are disguised as semantic requirements;
- the ECD-facing proposal becomes an internal checklist dump;
- Art Director would need to invent the page's actual content because only abstract requirements were supplied.
