# Authorized Change Ledger

Status: `draft reconstructed from explicit ECD directives and accepted repository changes`

This ledger distinguishes intentional evolution from semantic loss. An entry records the earlier behavior, the later authorized behavior, the reason, and the affected Constitution clauses.

## ACL-001 — One user-facing ECD Skill with one Producer interface

Earlier state:

- early skeletons exposed several role Skills;

Authorized state:

- ECD remains one user-facing studio Skill;
- the human communicates formally only with Creative Producer;
- internal professional complexity remains backstage.

Authority basis:

- accepted one-skill architecture and repeated ECD directives that the user must not manage internal roles.

Affected clauses:

- `SEM-002`, `SEM-003`, `SEM-044`.

## ACL-002 — Department architecture replaces overloaded universal roles

Earlier state:

- Editorial Director, Art Director, and Production Artist each combined several professional crafts.

Authorized state:

- Development, Editorial, Visual, and Production operate as departments;
- each Department Director owns department quality;
- Specialist Skills own distinct methods;
- Department Directors report to Creative Producer.

Authority basis:

- explicit ECD directive to split all roles other than Producer and allow the existing roles to become department leaders where appropriate.

Affected clauses:

- `SEM-039`, `SEM-040`.

## ACL-003 — Creative Producer becomes single accountable project owner

Earlier state:

- Producer primarily routed, recorded, and presented work.

Authorized state:

- every formal department package returns to Producer;
- Producer performs integrated review, feedback closure, decision readiness, state updates, and stage activation;
- Producer must not use the ECD as first-line QA.

Authority basis:

- explicit ECD directive that Producer is the project manager and must perform final project-level control before reporting.

Affected clauses:

- `SEM-002`, `SEM-038`, `SEM-040`, `SEM-041`, `SEM-043`, `SEM-044`.

## ACL-004 — Every new Creative Script requires explicit Script Alignment

Earlier state:

- founding implementation allowed Script decisions to return to ECD only when judged material.

Authorized state:

- every newly created Creative Script requires an explicit, complete, bound ECD Script Alignment object;
- only non-semantic technical correction inside an already aligned Script may retain prior authority after delta review.

Authority basis:

- explicit ECD decision during V2 hardening.

Disposition:

- intentional supersession, not semantic loss.

Affected clauses:

- `SEM-025`, `SEM-038`, `SEM-041`.

## ACL-005 — Advisory acceptance is not Greenlight

Earlier state:

- a concise Treatment summary could sometimes be inferred from a clear Compact brief, and informal approval could be treated as authorization.

Authorized state:

- topic selection or recommendation is Advisory Discovery;
- accepting an Advisory authorizes Development to prepare a Treatment;
- Greenlight exists only when the response is bound to a complete pending Treatment Decision Object.

Authority basis:

- explicit ECD rejection of the `把照片做成海报` test behavior and instruction to restore the Treatment gate.

Disposition:

- intentional supersession of the Compact implicit-Greenlight shortcut.

Affected clauses:

- `SEM-021`, `SEM-038`, `SEM-041`, `SEM-042`.

## ACL-006 — Project-specific failures belong in evals, not Runtime rules

Earlier state:

- iterative fixes risked embedding project-specific mechanisms and examples into general rules.

Authorized state:

- Runtime contains only general professional invariants;
- concrete completed projects may become external evaluation fixtures;
- a case detail cannot become a general rule unless its underlying invariant is independently stated.

Authority basis:

- explicit ECD instruction not to treat symptoms or import individual project problems into the Skill.

Affected clauses:

- `SEM-035`, `SEM-043`, `SEM-047`.

## ACL-007 — Copy-aware composition becomes a hard pre-image obligation

Earlier state:

- exact copy and image–type design were professional intentions but not consistently enforced before image generation.

Authorized state:

- exact copy geometry, hierarchy, protected zones, image–type relationship, contrast, crop, and variant consequences must shape every Production-intent image before creation or commitment;
- generated imagery and deterministic final typography remain separate;
- Type-Fit is required after image realization.

Authority basis:

- explicit ECD directive recalling and restoring the original pre-layout and text-avoidance / integration logic.

Affected clauses:

- `SEM-029`, `SEM-030`, `SEM-032`, `SEM-034`.

## ACL-008 — Skill methods cannot be presented as fictional employees or agents

Earlier state:

- department diagrams could imply that separate people or agents had independently performed work.

Authorized state:

- Role defines accountability;
- Skill defines method;
- a separate human, model, or Agent review may be claimed only if separate execution actually occurred;
- otherwise the system may only claim a distinct method pass with evidence.

Authority basis:

- V3 implementation correction accepted after the first V3 test.

Affected clauses:

- `SEM-039`, `SEM-040`.

## ACL-009 — Clean V3 Runtime; V2 retained only as a frozen baseline

Earlier state:

- V3 branch contained both V2 and V3 Runtime files.

Authorized state:

- `v2.1-legacy` preserves the V2 implementation;
- V3 physically contains only current V3 Core, departments, registered Specialist Skills, profiles, evals, and audit records;
- a V2 principle survives only through explicit V3 migration.

Authority basis:

- accepted branch and migration plan.

Affected clauses:

- all clauses through traceability requirements.

## ACL-010 — Full-sequence evidence plus representative fidelity proof

Earlier state:

- representative anchors or comps could prove visual quality while leaving unshown pages underdefined.

Authorized state:

- multi-page Visual Alignment requires full-sequence coverage and the smallest sufficient high-fidelity page-class proof;
- neither form of evidence substitutes for the other.

Authority basis:

- accepted generalization from completed project review.

Affected clauses:

- `SEM-028`, `SEM-031`, `SEM-034`.

## ACL-011 — Final acceptance requires department sign-offs and Producer integration

Earlier state:

- Producer and Production review carried most final verification.

Authorized state:

- Editorial signs final copy and claims;
- Art Director signs design fidelity;
- Production signs implementation and technical integrity;
- Producer integrates them before ECD Final Acceptance.

Authority basis:

- accepted department-accountability architecture.

Affected clauses:

- `SEM-010`, `SEM-034`, `SEM-038`, `SEM-040`, `SEM-041`.

## Ledger maintenance rule

A future audit may add an entry only when it identifies:

- the previous semantic behavior;
- the new behavior;
- explicit ECD authority or general professional necessity;
- affected Constitution clauses;
- whether the change strengthens, translates, or supersedes the previous behavior.

A commit message alone is not sufficient evidence of user authorization.