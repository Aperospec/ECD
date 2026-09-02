# Lock and Rework Protocol

## Purpose

Locks protect authoritative decisions from silent downstream mutation.

Rework returns a defect to the earliest professional object where it becomes true, preserves unaffected work, and closes ECD feedback through Creative Producer.

## Lock principle

Record decision-level locks rather than freezing an entire artifact by default.

Each lock states:

- artifact and version;
- decision authority;
- protected decision;
- permitted interpretation or implementation tolerance;
- reason;
- dependent downstream artifacts;
- renewal condition.

Locks are reflected in the Artifact Decision Contract.

## Normal lock domains

### Development lock

May protect creative core, governing logic or relationship, audience consequence, factual or speculative boundary, rights, reference roles, claim limits, and semantic guardrails.

### Editorial lock

May protect Overall Communication Logic, sequence, page purpose, Frame Script content, Written Visual Requirements, exact copy, evidence and limitation placement, opening promise, and payoff.

### Visual lock

May protect visual thesis, route, viewer relationship, world logic, reference transfer, metaphor behavior, composition principles, subject hierarchy, representative proof, typography behavior, Design Comp, and sequence system.

### Production lock

May protect final dimensions, exact text composition, approved crop, variants, formats, and accepted final files.

## First-failed-object rule

Creative Producer identifies the earliest object where the defect becomes true:

- source, evidence, validation, rights, creative core, governing logic, or Greenlight basis → Development;
- sequence, page meaning, Frame Script, Written Visual Requirement, or copy → Editorial Director / Copy Desk;
- visual problem, intent, reference reading, metaphor, route, Storyboard, anchor, Design Comp, or Art Direction → Art Director;
- exact implementation, asset defect, typography, crop, variant, or export → Production Artist;
- assignment, state, activation, Producer Review, decision presentation, or feedback closure → Creative Producer.

The latest visible defect is not automatically the earliest failed object.

## Rework control loop

```text
ECD feedback or Producer-detected defect
→ Creative Producer diagnosis
→ earliest failed object
→ focused Rework Brief
→ specialist correction
→ specialist self-QA
→ Producer re-review
→ renewed ECD authority when approved decisions changed
→ valid downstream reactivation
```

## Rework Brief

```markdown
Triggering feedback or review finding:
Observed defect:
Earliest failed object:
Responsible professional owner:
Artifact / decision reopened:
Artifact Decision Contract delta:
Still-valid upstream decisions:
Still-valid downstream material:
Artifacts invalidated:
Decisions that may not change:
Acceptance criteria:
Lowest-cost next proof:
Required ECD authority:
Return to: Creative Producer
```

Creative Producer does not merely forward the ECD's words. It translates feedback into a professional task and acceptance criteria while preserving the source wording or a faithful summary.

## Feedback closure

For each applicable ECD feedback item, record:

- source wording or faithful summary;
- affected artifact;
- Producer diagnosis;
- assigned owner;
- acceptance criteria;
- returned revision;
- Producer verification;
- closure state;
- remaining consequence.

Closure states:

- `Resolved`
- `Partially Resolved`
- `Not Resolved`
- `Conflict`
- `Superseded`
- `Open`

A known unresolved defect may not be resubmitted without explicit disclosure and a genuine ECD decision need.

## Propagation

A changed upstream artifact invalidates only actual dependents.

- local technical correction may require only recomposition or re-export;
- a changed page decision may affect one Board panel, anchor, design, and final asset;
- a changed governing Development decision usually reopens the dependent Script and visual system;
- a changed target surface may remain Production adaptation or become Art Direction rework depending on whether the governing hierarchy changes.

Use the Artifact Decision Contract to determine actual dependency and delta.

## Producer Review after rework

Rework is not complete when a specialist states that the change was made.

Creative Producer verifies:

- the original defect is actually resolved;
- no unauthorized new delta was introduced;
- unaffected decisions remain intact;
- all dependent artifacts are current or invalidated;
- applicable feedback is closed;
- the revised object is mature enough for release.

## Stage-authority violation

Work created outside the valid stage, Producer Review, or ECD authority sequence is `Unauthorized / Invalid`.

Creative Producer:

1. stops downstream work;
2. identifies the missing gate or earliest affected object;
3. preserves only material that does not bias the correct professional owner;
4. restores the valid sequence;
5. reruns specialist self-QA and Producer Review;
6. obtains required ECD authority;
7. reactivates downstream capabilities explicitly.

## Rework QA

Rework passes when:

- the earliest failed object is correctly identified;
- the change is no broader than necessary;
- the decision delta and authority consequence are explicit;
- unaffected work remains authoritative;
- actual dependents are updated or invalidated;
- applicable ECD feedback is closed or disclosed;
- specialist self-QA and Producer Review pass;
- required ECD authority is renewed before downstream activation.
