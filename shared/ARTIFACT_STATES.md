# Artifact States and Authority

## Purpose

This document defines canonical artifact states, who may assign them, and what downstream work may assume.

Do not use `approved` without naming the object, authority, version, and decision scope.

## Canonical States

### Working

The professional owner is developing the artifact. It may change without formal rework.

### Needs Interpretation

A valid source input or aesthetic judgment is active as research but has not yet been translated into an executable professional direction.

Typical examples:

- “这张图很对”;
- “人生档案馆就是人生游乐场”;
- “这组图很难看.”

This state authorizes analysis and elicitation, not batch production.

### Proposed

The owner considers the artifact ready for professional or ECD review. It is not yet authoritative downstream input.

### Accepted for Handoff

Creative Producer confirms the artifact is sufficiently complete, coherent, and within scope for the next professional owner.

This is a production-management decision. It does not substitute for ECD authority over material creative choices.

### ECD-Aligned

The ECD has confirmed a material interpretation or direction shown through an identifiable decision object.

Examples:

- Script architecture;
- selected visual Concept Route;
- reference interpretation;
- visual metaphor;
- World / Cover and Body anchors;
- Representative Design Comp.

Alignment is limited to the decisions explicitly presented.

### Locked

Creative Producer records that named decisions in an artifact version must be preserved unless reopened.

A lock must identify what is protected. Do not make the whole artifact immutable when only selected relationships are authoritative.

### Final Accepted

The ECD has accepted the final deliverable for intended use, subject to recorded limitations and publication state.

### Superseded

A later authoritative version replaced this artifact.

### Reopened

A previously accepted or locked object returned to its professional owner because feedback or change identified a material defect.

### Non-Authoritative Exploration

The artifact may be useful as study, failed evidence, or discarded direction, but cannot drive downstream production.

Examples:

- low-fidelity route studies;
- rejected thumbnails;
- visual experiments;
- a polished but unaligned generation.

### Unauthorized / Invalid

The artifact was produced outside the valid authority sequence, such as:

- Script before Greenlight;
- broad visual batch before Anchor Gate;
- Production before Art Direction handoff;
- ECD alignment recorded for an object not shown.

It is not authoritative merely because it exists or is visually polished.

## Authority Matrix

| Object | Professional owner | ECD authority normally required when | Downstream authority condition |
|---|---|---|---|
| Deliverable Contract | Creative Producer | material scope, rights, publication, or cost | accepted contract |
| Creative Treatment | Development / Producer | always for raw project Greenlight | ECD Greenlight |
| Creative Script | Editorial Director | material sequence, copy, framing, or fictional content | Accepted for Handoff after any required Script Alignment |
| Copy system | Copy Desk / Editorial Director | material voice / public-position choice | copy status Alignment-ready and Script accepted |
| Visual Problem Statement | Art Director | interpretation materially defines what the work visually is | professionally accepted or ECD-Aligned |
| Visual Intent Record | Art Director | user intuition has consequential alternative readings | interpretation recorded / aligned |
| Reference Reading / Transfer | Art Director | reference meaning or allowed transfer is subjective / material | transfer rules accepted |
| Visual Metaphor Map | Art Director | metaphor defines the world or audience understanding | route may develop after acceptance |
| Concept Routes | Art Director | new world, style, viewer relation, or durable visual identity | selected route accepted / ECD-Aligned |
| Formal Studies | Art Director | rarely; routine unless they reveal material route change | sufficient for Storyboard |
| Storyboard | Art Director | sequence interpretation materially changes visual meaning | accepted for anchor development |
| Anchor Keyframes | Art Director | materially new image world or representative scene language | Anchor Gate passed after required alignment |
| Representative Design Comp | Art Director | hierarchy, typography, or page system requires subjective authority | passed / ECD-Aligned |
| Color Script | Art Director | material emotional / world progression choice | accepted inside Art Direction |
| Art Direction Package | Art Director | unresolved material visual direction remains | Accepted for Handoff |
| Final Assets | Production Artist | final subjective quality / publication | ECD Final Acceptance |

## Greenlight Is Stage-Local

Greenlight accepts the Creative Treatment and opens Editorial Production.

It does not accept:

- page count or final copy;
- visual problem interpretation;
- reference transfer;
- Concept Route;
- palette, camera, composition, or typography;
- Storyboard, anchors, Design Comp, or final assets.

## Script Alignment Is Stage-Local

Script Alignment accepts named editorial decisions and allows Visual Research / Intent activation.

It does not approve visual execution.

## Visual Direction Alignment Is Stage-Local

Visual Direction Alignment accepts named choices such as:

- what the visual problem is;
- selected Concept Route;
- world / character hierarchy;
- reference principles;
- visual metaphor;
- intended audience relationship.

It does not approve final images or broad production.

## Anchor / Design Alignment Is Stage-Local

This alignment accepts representative image and page-design relationships shown through actual proofs.

It does not automatically accept every later frame. Art Direction must specify how the accepted system extends and what Production may vary.

## Anchor Gate State

Use:

- `Not Started`;
- `Working`;
- `Proposed`;
- `Passed`;
- `Failed / Reopened`;
- `Bypassed — reason recorded`.

A multi-image batch may not become authoritative while the gate is Not Started, Working, Proposed, or Failed.

## Compact Rule

Compact work may combine adjacent artifacts when one object genuinely resolves their questions.

Example:

```text
Two-screen project:
- one combined Storyboard + World / Cover Anchor;
- one Representative Body Anchor + Design Comp;
- one ECD Anchor / Design Alignment.
```

Compact does not permit:

- unaligned reference transfer;
- skipping representative proof;
- batch production before the proof;
- inferred ECD authority.

## Lock Granularity Examples

- world-led composition locked;
- people remain secondary scale / use evidence;
- reference contributes layered navigability, not literal rides;
- exact source composition prohibited;
- cover title scale locked;
- body-page minimum readable size locked;
- Color Script progression locked;
- specific texture or crop remains flexible.

## State QA

Reject or repair records such as:

- `approved` with no authority;
- `this image feels right → Production Activated`;
- `Reference accepted` without role or transfer boundary;
- `Visual Direction aligned` without visible route proposal;
- `Anchor Gate passed` without representative anchors;
- `final-looking batch` treated as proof of direction;
- `Production ready` while Art Direction Package is only Proposed;
- `ECD accepted` when only Creative Producer reviewed;
- an unauthorized batch promoted because it is expensive or detailed;
- a source judgment and Art Director inference stored as the same statement.
