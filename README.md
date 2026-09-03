# ECD Studio OS V3.1

ECD V3.1 is a clean, department-based creative studio runtime for ChatGPT.

It preserves one user-facing interface—the Creative Producer—while registering Development, Editorial, Visual, and Production professional methods as internal Skills.

## Current status

- architecture and Runtime reconstruction: implemented;
- Semantic Preservation Audit Wave 1: complete;
- Wave 2 source-level remediation: complete;
- installation registration and behavioral verification: pending;
- semantic certification: not yet granted;
- promotion to `main`: not authorized.

See:

- `audit/README.md`;
- `audit/WAVE_2_REMEDIATION.md`;
- `audit/SEMANTIC_TRACEABILITY_MATRIX.md`;
- `evals/semantic/SEMANTIC_REGRESSION.md`.

## Branches

- `main` — current V2 stable branch until V3 passes certification;
- `v2.1-legacy` — frozen V2 recovery and semantic baseline;
- `v3-department-architecture` — V3.1 development, audit, and test branch.

## Install for verification

Repository:

`https://github.com/Aperospec/ECD`

Branch:

`v3-department-architecture`

Primary entry:

`SKILL.md`

The current branch contains 28 `SKILL.md` entries:

- 1 root ECD Skill;
- 1 Creative Producer Skill;
- 4 Department Director Skills;
- 22 Specialist Skills.

After syncing, verify every `Implemented` entry in `core/CAPABILITY_REGISTRY.md`. A missing or unreadable Skill must be marked unavailable; it cannot be claimed as used.

## Semantic controls restored in Wave 2

- `core/ADAPTIVE_ROUTING.md` — infer first, shortest valid route, Compact / Standard / Extended proportionality, question-before-Skill routing;
- `core/EVIDENCE_OBLIGATION.md` — Speculative / Conceptual, Evidence-based Editorial, and Product / Commercial Validation modes;
- `core/STAGE_SCOPED_INPUT_REGISTER.md` — source wording, authority classes, stage projections, activation history, and no-repeat behavior;
- `core/REFERENCE_CONTRACT.md` — explicit reference roles, rights, evidence context, four-pass reading, and controlled transfer;
- `ecd-chinese-copy-craft`;
- `ecd-english-copy-craft`;
- `ecd-bilingual-transcreation`.

## Runtime authority sequence

```text
Discovery / Brief
→ adaptive initialization and latest-valid-artifact routing
→ Development
→ ECD Greenlight
→ Editorial
→ ECD Script Alignment
→ Visual
→ ECD Visual Alignment when required
→ Production
→ ECD Final Acceptance
```

This sequence defines authority order. It does not require replaying valid earlier stages or invoking every registered Skill.

The user does not manage internal Skills. Creative Producer identifies active professional questions, Department Directors select proportionate methods, and all formal work is reviewed before reaching the ECD.

## Core V3.1 protections

- a generic positive reply cannot become an unstated approval;
- Advisory topic selection remains separate from Creative Treatment;
- Development cannot leak into final copy or visual design;
- registered capability cannot be replaced by an imaginary profession label;
- review cannot be claimed without inspectable evidence;
- exact copy shapes Production-intent imagery before generation;
- references remain bounded by assigned roles and permissions;
- research and validation depth match the public promise;
- early inputs remain stage-scoped and do not need to be repeatedly supplied;
- Chinese, English, and bilingual work receive native-language methods;
- V2 Runtime files remain outside the V3 branch;
- complete Treatment, Script, Visual, and Final decision objects remain mandatory.

## Source of truth

Runtime rules are limited to:

- root `SKILL.md`;
- `core/`;
- registered `departments/**/SKILL.md` and required `METHOD.md` files;
- active `profiles/`.

Audit and test controls live under:

- `audit/`;
- `evals/`.

V2 files remain available only on `v2.1-legacy`.
