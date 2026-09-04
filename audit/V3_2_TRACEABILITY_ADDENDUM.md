# V3.2 Semantic Traceability Addendum

Audit ID: `ECD-SPA-001`

Runtime version: `ECD Studio OS V3.2 / 3.2-alpha`

Primary Runtime implementation commit:

`987624e8cd92776aa38bc9658270f4cc595ee914`

Constitution amendment commit:

`564ced246022b12878472f1780207ecfc7e47760`

Status: `source-level implementation complete; installation and behavioral verification pending`

This addendum extends `audit/SEMANTIC_TRACEABILITY_MATRIX.md`, which remains the Wave 2 baseline matrix.

## New clauses

| Clause | Canonical intent | Authority basis | V3.2 implementation | Source-level status | Required behavior evidence |
|---|---|---|---|---|---|
| SEM-048 | Confirm a high-leverage Core Communication Script before producing dependent page architecture, Frame Scripts, exact copy, publication copy, or visual work; combine only when dependency risk is genuinely low | ACL-012 and ECD direction during live Creative Script review | `core/HIGH_LEVERAGE_DECISIONS.md`; `ecd-core-communication-script`; Editorial Director; Content Architecture; Frame Script; Runtime; Authority; Decision Objects; Producer | Strengthened / pending behavior | W4-01 through W4-06 |
| SEM-049 | A public post used only to discover a topic may remain a backstage Discovery Signal; independently create the new angle, progression, examples, copy, and visuals; do not default to attribution, reproduction validation, or defensive source commentary | ACL-013 and explicit ECD clarification | `profiles/social-editorial/CONCEPT_REFRAMING.md`; Entry Router; Profile; Evidence Obligation; Reference Contract; Development; Claims Rights; Core Script; Copywriting; Copy Editing; Producer | Strengthened / pending behavior | W4-07 through W4-12 |

## Existing-clause impact

### SEM-005 — Shortest valid route

V3.2 adds explicit reuse and recovery rules for:

- an existing aligned Core Communication Script;
- a V3.1 project that has valid Greenlight and provisional page work but lacks Core Script authority;
- preservation of valid downstream material after Core Script approval.

Status: `Strengthened; W4-05 and W4-06 pending`.

### SEM-006 and SEM-007 — Proportional process and non-ceremonial rigor

V3.2 does not impose a universal extra gate. It introduces four gate modes and routes by dependency fan-out and invalidation cost.

Status: `Preserved / Strengthened; W4-01 and W4-04 pending`.

### SEM-011 through SEM-017 — Evidence, source, and reference handling

V3.2 distinguishes:

- engagement as Discovery Signal;
- factual dependency;
- direct-use material;
- internal provenance;
- public attribution.

It limits validation and public source language to the actual publication claim and use.

Status: `Strengthened; W4-07 through W4-11 pending`.

### SEM-020 through SEM-026 — Stage ownership and Script authority

V3.2 retains Greenlight before script development, then separates:

- Core Communication Script authority;
- page-level Creative Script / Editorial Adaptation authority.

Visual requires both when applicable.

Status: `Strengthened; W4-01 through W4-04 pending`.

### SEM-035, SEM-036, and SEM-043 — Inheritance and targeted rework

A rejected Core Script preserves Greenlight unless Development-level meaning changes. Only dependent page and visual artifacts become stale or provisional.

Status: `Strengthened; W4-02 and W4-06 pending`.

### SEM-041 and SEM-042 — Complete decision objects and hard stops

V3.2 adds a fifth possible Decision Object, `Core Script Alignment`, while preserving the request-turn stop and resolution-turn continuation distinction.

Status: `Strengthened; W4-01, W4-03, and W4-04 pending`.

### SEM-047 — Anti-template and project specificity

Concept Reframing now explicitly rejects sentence-level paraphrase, copied source sequence, copied examples, and unapproved visual remakes.

Status: `Strengthened; W4-07 and W4-12 pending`.

## No case-specific Runtime rule

The initiating project exposed two defects, but the Runtime changes are stated generally:

- decision placement follows downstream invalidation cost;
- source handling follows publication dependency and direct use;
- examples, project subjects, and prior output wording remain only in Eval fixtures or audit history.

## Certification effect

V3.2 is not semantically certified until:

- the 29 expected Skill entries register successfully;
- `ecd-core-communication-script` is discoverable and usable;
- W4-01 through W4-12 are executed with observable evidence;
- Wave 2 regression coverage remains passing;
- the new gate does not create ceremonial overhead for low-dependency work;
- Concept Reframing does not weaken factual or direct-use controls when those controls are actually required.
