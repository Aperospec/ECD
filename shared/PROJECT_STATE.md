# Project State

## Purpose

Project State is the Creative Producer's authoritative record of where the work is, what is valid, what is locked, which user inputs are currently active, which are deferred, and what may happen next.

It prevents role drift, repeated work, forgotten approvals, contradictory artifact versions, premature downstream execution, and loss of early user instructions. Maintain only the level of detail required by the project's complexity profile.

## Single-Source Principle

At any moment, identify one authoritative version of each active professional artifact and one authoritative `Stage-Scoped Input Register`.

Draft alternatives may exist, but they are not production inputs until their state changes explicitly.

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

## 3. Stage-Scoped Input State

Register reference / version:
Current active stage:
Active input IDs:
Deferred Editorial input IDs:
Deferred Visual / Art Direction input IDs:
Deferred Production input IDs:
Conflicts / ambiguities:
Last activation event:
Next activation condition:

## 4. Evidence and Reference State

Evidence obligation: [Speculative / Conceptual / Evidence-based Editorial / Product / Commercial Validation]
Research state: [not required / working / sufficient / blocked]
Reference intent:
Rights / attribution state:
Material claim limits:

## 5. Phase and Current Owner

Phase: [Development / Awaiting Greenlight / Editorial / Awaiting Script Alignment / Visual Development / Awaiting Visual Alignment / Art Direction / Production / Final Review / Accepted]
Current professional owner:
Current objective:
Next valid action:

## 6. Artifact Register

| Artifact | Version / reference | Owner | State | Authority / notes |
|---|---|---|---|---|
| Stage-Scoped Input Register | | Creative Producer | | |
| Creative Treatment | | Development | | |
| Greenlight Record | | Creative Producer / ECD | | |
| Creative Script | | Editorial Director | | |
| Storyboard / Visual Sequence Board | | Art Director | | |
| Representative Design Comp | | Art Director | | |
| Art Direction Package | | Art Director | | |
| Final Assets | | Production Artist | | |
| Acceptance Record | | Creative Producer / ECD | | |

## 7. Active Locks

- premise / angle / proposition:
- public claim / promise:
- factual / speculative boundary:
- exact names / wording:
- evidence / limitation:
- reference / rights boundary:
- user-supplied downstream Hard Constraints currently active:
- visual premise / Design Comp:
- technical specification:

## 8. Unresolved Issues

For each issue:
- issue:
- first affected owner:
- material consequence:
- ECD involvement required: [yes / no]
- blocking: [yes / no]
- recommended action:

## 9. ECD Gate State

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
Script alignment state: [not applicable / not required / pending / aligned]
Visual alignment state: [not applicable / not required / pending / aligned]

## 10. Rework Scope

Triggering feedback:
First failed professional object:
Artifact reopened:
Input projections reopened / reclassified:
Downstream artifacts invalidated:
Artifacts still valid:

## 11. Change and Activation Log

- date / version / change / authority / consequence
- date / stage transition / input IDs activated / receiving owner
```

## Compact State

For a Compact project, the Project State may be reduced to:

```markdown
Project:
Deliverable:
Phase / owner:
Complexity:
Evidence obligation:
Stage Input Register:
Active input IDs:
Deferred input IDs by next stage:
Current authoritative artifact:
Treatment version:
Greenlight state and evidence:
Script / visual alignment state when material:
Active locks:
Open issue:
Next action:
Next input activation condition:
```

The record may live inside the Creative Producer's working response or project notes. It does not need to become a separate visible document unless useful.

A compact record may be short. It still must distinguish `Awaiting Greenlight` from `Greenlit`, identify authorization evidence before Editorial Production, and prevent visual or production inputs from activating prematurely.

## Input Activation Rules

Use `STAGE_SCOPED_INPUT_REGISTER.md` as the controlling source for staged inputs.

### Intake → Development

Activate:

- global / Deliverable Contract projections;
- Development projections;
- evidence and reference-boundary questions required to form the Treatment.

Keep Editorial, Visual, and Production projections Deferred.

### Greenlight → Editorial

Requires a valid Greenlight Record tied to the authoritative Treatment.

On transition:

1. lock only accepted Treatment decisions and Greenlight boundaries;
2. activate Deferred Editorial projections;
3. preserve Visual and Production projections as Deferred;
4. log the IDs activated and hand them to Editorial Director;
5. set next authorized artifact to Creative Script.

Greenlight is not permission to create a Storyboard, Design Comp, Art Direction Package, or deliverable image.

### Creative Script Accepted for Handoff → Visual Development

Requires:

- a valid Script state;
- all Activated Editorial projections resolved or explicitly superseded;
- material Script Alignment resolved when required.

On transition:

1. activate Deferred Visual / Art Direction projections;
2. transfer original source wording, references, authority classes, and prohibited transfer boundaries to Art Director;
3. keep Production projections Deferred;
4. log the activation.

### Art Direction Package Accepted for Handoff → Production

Requires:

- accepted visual direction;
- required ECD Visual Alignment resolved;
- production assets or acquisition plan, tolerances, and output conditions.

On transition:

1. activate Deferred Production projections;
2. transfer technical requirements and Hard Constraints to Production Artist;
3. log the activation.

## Artifact Transition Rules

### Development → Awaiting Greenlight

Requires:

- a coherent Creative Treatment;
- sufficient resolution of material evidence, rights, and reference obligations;
- the Treatment presented to the ECD or an explicitly identified supplied equivalent;
- a clear statement of what Greenlight will authorize;
- later-stage user inputs preserved as Deferred rather than interpreted into downstream decisions.

After presentation, the next valid action is an ECD decision. No Production artifact may be created while this state is active.

### Awaiting Greenlight → Editorial

Requires a valid Greenlight Record tied to the authoritative Treatment and one of the accepted authorization forms in `GREENLIGHT_RECORD.md`.

A generic request to make, start, design, or directly produce a post does not satisfy this transition when it preceded the Treatment or did not identify the Treatment being accepted.

Complexity profile does not alter this requirement.

The transition activates Editorial inputs only.

### Existing Greenlit Treatment → Editorial

May enter directly only when the Treatment and prior ECD authorization are identifiable, or when the ECD gives a stage-aware supplied-Treatment override.

Reconstruct Deferred Editorial / Visual / Production inputs from the supplied project context rather than losing them.

### Editorial → Awaiting Script Alignment

Use when the Creative Script creates a material sequence, fictional-content, headline, public-position, or communication choice not already resolved by the Treatment and the decision requires ECD authority.

Visual inputs remain Deferred while this state is active.

### Editorial / Awaiting Script Alignment → Visual Development

Requires a Creative Script Accepted for Handoff, complete written Visual Beats and audience-facing copy at the level needed for composition, and any required Script Alignment resolved.

This transition activates Visual / Art Direction inputs.

### Visual Development → Awaiting Visual Alignment

Use when the Storyboard or Representative Design Comp creates a materially subjective visual interpretation requiring ECD alignment.

Production inputs remain Deferred.

### Visual Development / Awaiting Visual Alignment → Art Direction

Requires a coherent Storyboard / Visual Sequence Board and any representative visual question resolved by a Design Comp and alignment where material.

### Art Direction → Production

Requires an Art Direction Package Accepted for Handoff, production assets or acquisition plan, tolerances, and known output conditions.

This transition activates Production inputs.

### Production → Final Review

Requires all requested assets, variants, and QA records.

### Final Review → Accepted

Requires Creative Producer review and ECD Final Acceptance when subjective acceptance or publication authority is required.

## Deferred Input Integrity

A Deferred input is not inactive memory. It is an authoritative future-stage instruction whose execution is intentionally postponed.

Reject or repair Project State when:

- a Deferred Hard Constraint disappears before its activation stage;
- the ECD is asked to repeat a stored instruction without a material reason;
- an Assistant Inference is recorded as a user instruction;
- a visual preference is paraphrased so aggressively during Development that its original intent is lost;
- Greenlight is recorded as approval of Deferred Editorial or Visual output;
- visual inputs are activated before the Script is Accepted for Handoff;
- production inputs are activated before Art Direction is Accepted for Handoff.

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
- Greenlight is treated as authorization for immediate visual production;
- a cross-stage brief was flattened into the Treatment instead of registered by stage;
- final assets are accepted without matching the Deliverable Contract;
- rework is assigned to the most recent role instead of the first failed owner;
- a routine professional choice is falsely recorded as an ECD decision;
- unauthorized pre-Greenlight work is treated as approved merely because it already exists.
