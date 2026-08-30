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

Phase: [Development / Awaiting Greenlight / Editorial / Visual Development / Art Direction / Production / Final Review / Accepted]
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
Creative Treatment presented to ECD: [yes / no / prior artifact]
Treatment version / reference:
Treatment presentation turn / reference:
Greenlight request issued: [yes / no]
Greenlight authorization evidence:
Greenlight form: [none / explicit response to presented Treatment / identified prior Greenlight / stage-aware supplied-Treatment override]
Greenlight state: [not requested / awaiting ECD / Greenlit / conditional / reopened / superseded]

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
Treatment version:
Greenlight state and evidence:
Active locks:
Open issue:
Next action:
ECD gate required:
```

The record may live inside the Creative Producer's working response or project notes. It does not need to become a separate visible document unless useful.

A compact record may be short. It still must distinguish `Awaiting Greenlight` from `Greenlit` and identify the authorization evidence before Production.

## Transition Rules

### Development → Awaiting Greenlight

Requires:

- a coherent Creative Treatment;
- sufficient resolution of material evidence, rights, and reference obligations;
- the Treatment presented to the ECD or an explicitly identified supplied equivalent;
- a clear statement of what Greenlight would authorize.

After presentation, the next valid action is an ECD decision. No Production artifact may be created while this state is active.

### Awaiting Greenlight → Editorial

Requires a valid Greenlight Record tied to the authoritative Treatment and one of the accepted authorization forms in `GREENLIGHT_RECORD.md`.

A generic request to make, start, design, or directly produce a post does not satisfy this transition when it preceded the Treatment or did not identify the Treatment being accepted.

Complexity profile does not alter this requirement.

### Existing Greenlit Treatment → Editorial

May enter directly only when the Treatment and prior ECD authorization are identifiable, or when the ECD gives a stage-aware supplied-Treatment override.

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

## Unauthorized Pre-Greenlight Work

If a Script, Storyboard, Design Comp, generated image, layout, or final asset was created before valid Greenlight:

1. mark it `Unauthorized / Invalid — pre-Greenlight` in the authority notes;
2. do not promote it to authoritative state;
3. preserve it only as failure evidence or optional non-authoritative exploration when useful;
4. return Phase to `Development` or `Awaiting Greenlight`;
5. present the Treatment and obtain the missing decision.

Do not retroactively manufacture Greenlight to legitimize already-created work.

## Invalid State Examples

Reject or repair Project State when:

- two different Creative Scripts are both marked authoritative;
- a downstream artifact points to an obsolete upstream version;
- a visual direction is called locked without identifying the representative proof;
- Greenlight is assumed because the user said “做一个帖子”, “开始吧”, or equivalent before seeing the Treatment;
- Greenlight has no identified Treatment, presentation reference, or authorization evidence;
- Compact complexity is recorded as the reason Greenlight was skipped;
- final assets are accepted without matching the Deliverable Contract;
- rework is assigned to the most recent role instead of the first failed owner;
- a routine professional choice is falsely recorded as an ECD decision;
- unauthorized pre-Greenlight work is treated as approved merely because it already exists.
