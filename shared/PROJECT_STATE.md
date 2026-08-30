# Project State

## Purpose

Project State is the Creative Producer's authoritative record of where the work is, what is valid, what is locked, and what may happen next.

It prevents role drift, repeated work, forgotten approvals, and contradictory artifact versions. Maintain only the level of detail required by the project's complexity profile.

## Single-Source Principle

At any moment, identify one authoritative version of each active professional artifact. Draft alternatives may exist, but they are not production inputs until their state changes explicitly.

Never infer that the newest-looking document is authoritative merely because it is more detailed.

## State Template

```markdown
# Project State

## 0. Identity

Project ID:
Working title:
ECD / owner:
Created:
Last updated:
Complexity profile: [Compact / Standard / Extended]

## 1. Intake and Route

Original request:
Intended use:
Current entry point:
Why this is the shortest valid route:
Consequential assumptions:
Material unknowns:

## 2. Deliverable Contract

Contract reference:
Target platform / surface:
Required outputs:
Count / duration / size constraints:
Language / locale:
Publication context:

## 3. Evidence and Reference State

Evidence obligation: [Speculative / Conceptual / Evidence-based Editorial / Product / Commercial Validation]
Research state: [not required / working / sufficient / blocked]
Reference intent:
Rights / attribution state:
Material claim limits:

## 4. Phase and Current Owner

Phase: [Development / Greenlight / Editorial / Visual Development / Art Direction / Production / Final Review / Accepted]
Current professional owner:
Current objective:
Next valid action:

## 5. Artifact Register

| Artifact | Version / reference | Owner | State | Authority / notes |
|---|---|---|---|---|
| Creative Treatment | | Development | | |
| Greenlight Record | | Creative Producer / ECD | | |
| Creative Script | | Editorial Director | | |
| Storyboard / Visual Sequence Board | | Art Director | | |
| Representative Design Comp | | Art Director | | |
| Art Direction Package | | Art Director | | |
| Final Assets | | Production Artist | | |
| Acceptance Record | | Creative Producer / ECD | | |

## 6. Active Locks

- premise / angle / proposition:
- public claim / promise:
- factual / speculative boundary:
- exact names / wording:
- evidence / limitation:
- reference / rights boundary:
- visual premise / Design Comp:
- technical specification:

## 7. Unresolved Issues

For each issue:
- issue:
- first affected owner:
- material consequence:
- ECD involvement required: [yes / no]
- blocking: [yes / no]
- recommended action:

## 8. ECD Gate State

Latest ECD Update:
Pending ECD Alignment:
Pending ECD Decision:
Pending ECD Final Acceptance:
Greenlight state:

## 9. Rework Scope

Triggering feedback:
First failed professional object:
Artifact reopened:
Downstream artifacts invalidated:
Artifacts still valid:

## 10. Change Log

- date / version / change / authority / consequence
```

## Compact State

For a Compact project, the Project State may be reduced to:

```markdown
Project:
Deliverable:
Phase / owner:
Complexity:
Evidence obligation:
Current authoritative artifact:
Active locks:
Open issue:
Next action:
ECD gate required:
```

The record may live inside the Creative Producer's working response or project notes. It does not need to become a separate visible document unless useful.

## Transition Rules

### Development → Greenlight

Requires a coherent Creative Treatment and sufficient resolution of material evidence, rights, and reference obligations.

### Greenlight → Editorial

Requires ECD authorization, whether recorded explicitly or as a clear Compact-project instruction.

### Editorial → Visual Development

Requires a Creative Script accepted for handoff, with complete Visual Beats and audience-facing copy at the level needed for composition.

### Visual Development → Art Direction

Requires a coherent Storyboard / Visual Sequence Board and any representative visual question resolved by a Design Comp.

### Art Direction → Production

Requires an accepted Art Direction Package, production assets or acquisition plan, tolerances, and known output conditions.

### Production → Final Review

Requires all requested assets, variants, and QA records.

### Final Review → Accepted

Requires Creative Producer review and ECD Final Acceptance when subjective acceptance or publication authority is required.

## Invalid State Examples

Reject or repair Project State when:

- two different Creative Scripts are both marked authoritative;
- a downstream artifact points to an obsolete upstream version;
- a visual direction is called locked without identifying the representative proof;
- Greenlight is assumed despite a material premise dispute;
- final assets are accepted without matching the Deliverable Contract;
- rework is assigned to the most recent role instead of the first failed owner;
- a routine professional choice is falsely recorded as an ECD decision.
