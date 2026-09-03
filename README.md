# ECD Studio OS V3.1

ECD V3.1 is a clean, department-based creative studio runtime for ChatGPT.

It preserves one user-facing interface—the Creative Producer—while registering the professional methods required by Development, Editorial, Visual, and Production as real internal Skills.

## Branches

- `main` — current V2 stable branch until V3 passes testing;
- `v2.1-legacy` — frozen V2 recovery point;
- `v3-department-architecture` — V3.1 development and test branch.

## Install for testing

Repository:

`https://github.com/Aperospec/ECD`

Branch:

`v3-department-architecture`

Primary entry:

`SKILL.md`

After syncing, verify that the root ECD Skill, four Department Director Skills, and all Skills listed as `Implemented` in `core/CAPABILITY_REGISTRY.md` are registered.

## Runtime sequence

```text
Discovery / Brief
→ Development
→ ECD Greenlight
→ Editorial
→ ECD Script Alignment
→ Visual
→ ECD Visual Alignment when required
→ Production
→ ECD Final Acceptance
```

The user does not manage internal skills. Creative Producer selects departments, Department Directors select specialist methods, and all formal work is reviewed before it reaches the user.

## Key V3.1 corrections

- restores explicit state and authority contracts;
- prevents a generic positive reply from becoming an unstated approval;
- distinguishes advisory topic selection from Creative Treatment;
- prevents final copy and visual decisions from leaking into Development;
- registers real specialist Skills instead of listing imaginary capabilities;
- prevents claims of review without inspectable work evidence;
- removes V2 runtime files from the V3 branch;
- restores complete ECD-facing Treatment, Script, Visual, and Final decision objects.

## Source of truth

Runtime rules are limited to:

- root `SKILL.md`;
- `core/`;
- registered `departments/**/SKILL.md` files;
- active `profiles/`;
- `evals/` for non-runtime conformance tests.

V2 files are available only on `v2.1-legacy`.
