# Runtime Context Hygiene

## Status

Maintenance-only repository governance. This file is not part of project execution.

## Purpose

Keep the runtime Skill project-independent while preserving concrete historical cases as isolated evaluation fixtures.

## Repository zones

### Runtime

Root Skill, role manuals, shared protocols, and craft references used during project execution.

Runtime content may contain:

- project-independent methods;
- artifact definitions and templates;
- authority and state rules;
- positive acceptance criteria;
- generic placeholders;
- stable professional terminology.

### Evals

Regression prompts, historical outputs, exact failure sentences, project-specific references, and expected behavior.

Evals may contain concrete content because they are not loaded during ordinary project execution.

### Maintenance

Repository-governance rules, audit procedures, migration notes, and contributor guidance.

## Runtime exclusion rules

A runtime file must not include:

- a real user's quoted project brief;
- a historical project name or concept world;
- an exact failed output retained only as a lesson;
- case-specific objects, scenes, colors, page counts, or visual symptoms;
- a regression fixture disguised as a general example;
- a blacklist of content that has no universal workflow meaning;
- references to eval cases as project instructions.

## Allowed constraints

Runtime may contain control-layer constraints that govern the system across projects, including:

- stage authority;
- professional ownership;
- reference rights and transfer roles;
- artifact completeness;
- quality gates;
- representative proof before broad production;
- first-failed-object routing.

These should be phrased as positive acceptance conditions whenever possible.

## Abstraction procedure

When a real test reveals a failure:

1. preserve the exact prompt and output under `evals/`;
2. identify the project-independent failure mechanism;
3. express the runtime fix without case-specific nouns or phrasing;
4. use placeholders when an example is necessary;
5. add a positive acceptance condition;
6. add or update the regression fixture;
7. verify that runtime files do not link to or load the fixture;
8. scan the runtime reference graph for copied case language.

## Runtime audit questions

For every proposed runtime addition, ask:

- Is this a general method or a historical fact?
- Does a new project need this content to perform correctly?
- Can the rule be stated without the original project's nouns?
- Is the statement about system behavior or about one case's desired content?
- Does the wording introduce a visual, narrative, or linguistic prior that the new project did not request?
- Would this material be more useful as an eval fixture?
- Can a negative list be replaced by a positive acceptance condition?

## Static audit targets

Scan runtime files for:

- repeated literal phrases from eval prompts;
- proper nouns or project titles that appear only in evals;
- exact rejected copy lines;
- case-specific visual objects or palettes;
- case-specific quantities retained as universal rules;
- runtime references to `evals/` or `maintenance/`;
- examples longer than necessary to explain a method.

## Review outcome

A hygiene review records:

```markdown
Files reviewed:
Case-specific content removed:
Content moved to evals:
Rules abstracted:
Negative rules converted to positive criteria:
Runtime references verified:
Remaining exceptions and rationale:
Reviewer:
Commit:
```

## Contributor rule

A regression case may change runtime behavior, but it may not become runtime subject matter.