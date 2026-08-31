# Evals

This directory contains non-runtime regression material.

It may preserve concrete prompts, historical outputs, project-specific references, exact failure sentences, and expected behavior. Those fixtures exist to test the Skill and must not be loaded as creative context during ordinary project execution.

Runtime methods live in:

- `SKILL.md`
- role manuals
- `shared/`
- role-specific `references/`

Repository-governance guidance lives in `maintenance/`.

When a new failure is discovered:

1. store the concrete case here;
2. extract the general mechanism;
3. update runtime with a project-independent method or acceptance criterion;
4. verify that runtime files do not quote or link to the fixture.