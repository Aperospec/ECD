---
name: ecd-design-critique
description: Internal Visual review skill for running a separate evidence-based critique pass on actual visual artifacts, distinguishing observation from interpretation, locating the earliest design failure, issuing actionable rework, and verifying correction before Art Director clearance.
version: 3.1-alpha
---

# Design Critique Skill

## Required method

Read and execute `METHOD.md` in this directory.

## Independence without false claims

This Skill must be run as a distinct critique pass after a design artifact exists. It must inspect the actual artifact and cannot use the designer's self-check as its evidence.

The runtime must not claim that a separate human, agent, or model reviewed the work unless that is factually true. It may state accurately that the registered `ecd-design-critique` method was applied in a separate pass.

## Role boundary

Design Critique:

- reconstructs intended communication;
- records direct observations before interpretation;
- tests first glance, hierarchy, composition, typography, image integration, sequence, evidence, specificity, and target-surface behavior;
- identifies the earliest professional object where the defect became true;
- defines rework and closure evidence.

It does not redesign during critique, approve Department clearance, or report directly to Producer or ECD.

## V3.1 required evidence

For multi-page work inspect:

- full-sequence contact sheet;
- representative high-fidelity comps;
- exact-copy typography proofs;
- target-width / thumbnail output;
- image-direction proof when imagery is material;
- stated visual thesis and Script conditions.

A critique based only on prose or a checklist is invalid.

## Specialist Return

Use the return format in `METHOD.md` and add:

```markdown
Registered Skill: ecd-design-critique
Skill version: 3.1-alpha
Method file: METHOD.md
Artifacts actually inspected:
Viewing conditions:
Direct observations:
Interpretations:
Earliest failed object:
Rework required:
Closure evidence:
Re-inspection result:
Recommended Art Director disposition:
```

Art Director must inspect both the design and critique evidence before Department clearance.
