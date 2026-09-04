# Project State — V3.2

Creative Producer maintains one authoritative Project State.

## Required fields

```markdown
# Project State

Project ID:
Working title:
Profile:
Profile extensions:
Executive Creative Director:
Creative Producer Skill / version:

## Request and contract
Original request:
Intended use:
Audience:
Platform / placement:
Language / locale:
Deliverables:
Target dimensions / variants:
Evidence / rights / disclosure obligations:
Success condition:
Deliverable Contract / version:

## Entry and adaptive route
Entry mode:
- Advisory Discovery
- Project Start
- Continuation
- Craft-only
Entry evidence:
Latest valid artifact:
Latest-valid-artifact validation:
Complexity / risk profile: [Compact / Standard / Extended]
Adaptive Route Record:
Professional questions active:
Professional questions already resolved:
Temporary assumptions:
Material questions for ECD:

## High-leverage decisions
High-Leverage Decision Record:
Core Script required: [yes / no]
Core Script gate mode:
- Separate Alignment
- Combined with Creative Script Alignment
- Existing Aligned
- Not Applicable
Dependency fan-out:
Invalidation consequence:
Dependent artifacts kept inactive:

## Source posture and Concept Reframing
Concept Reframing active: [yes / no]
Discovery source:
Engagement signal:
Source posture:
- Discovery Signal
- Factual Dependency
- Direct-use Material
Publication dependency:
Source-specific expression excluded:
Public attribution required:
Public disclaimer required:
Independent reproduction claimed:
Deferred productization seed:
Concept Reframing Record:

## Evidence obligation
Primary Evidence Obligation:
- Speculative / Conceptual
- Evidence-based Editorial
- Product / Commercial Validation
Claim-level overrides:
Evidence Obligation Record:
Public claim ceiling:
Validation gaps / blockers affecting current publication:

## Runtime
Current state:
Active department:
Active registered Skills:
Deferred departments / Skills:
Current department assignment:
Current blockers:

## Authoritative artifacts
Advisory Recommendation:
Creative Treatment / version / authority:
Core Communication Script / version / authority:
Creative Script / Editorial Adaptation / version / authority:
Visual Development Package / version / authority:
Art Direction Package / version / authority:
Final Production Package / version / authority:
Completion Record:

## Core Script dependency map
Core Script essential beats:
Core Script adaptable elements:
Core Script order constraints:
Core Script beat-to-page map:
Downstream artifacts dependent on Core Script:
Provisional artifacts awaiting Core Script authority:

## Reviews
Latest Specialist Returns:
Latest Department Review Record:
Latest Department clearance:
Latest Producer Integrated Review:
Required final sign-offs:

## Pending ECD decision
Decision ID:
Decision type:
Artifact / version:
Approval scope:
Exclusions:
Consequence:
Release turn:
Status:

## Decisions and locks
ECD decisions:
Department decisions:
Producer coordination decisions:
Locked decisions:
Open variables:
Tolerances:

## Stage-scoped inputs
Stage-Scoped Input Register / version:
Active input IDs:
Deferred Core Script input IDs:
Deferred Editorial Adaptation input IDs:
Deferred Visual input IDs:
Deferred Production input IDs:
Input conflicts:
Latest activation-log entry:
Latest supersession-log entry:

## Sources and references
Sources and provenance:
Reference Contract records:
Activated reference roles:
Deferred reference roles:
Authorized direct-use assets:
Reference transfer limits:
Evidence context to preserve:
Rights / attribution / version conditions:

## Feedback
Open feedback items:
Resolved feedback items:
Conflicts requiring ECD:

## Capability integrity
Implemented Skills required by active professional questions:
Skills available in runtime:
Skills unavailable in runtime:
Skills omitted and reasons:
Combined execution seats or decision scopes:
Capability limitations disclosed:

## Next action
Next legitimate action:
Owner:
Stop condition:
```

## State update rules

Only Creative Producer updates Project State.

Every update must cite the evidence that justifies it:

- user request or faithful source wording;
- Adaptive Route Record;
- High-Leverage Decision Record;
- Concept Reframing Record;
- Evidence Obligation Record;
- Stage-Scoped Input Register activation or supersession;
- Source / Reference Record or transfer result;
- ECD Decision Object and response;
- Specialist Return;
- Department Review Record;
- Producer Integrated Review;
- blocker evidence;
- final sign-off.

A conversational summary such as `用户同意了` is insufficient unless it identifies the bound Pending Decision Object.

## Temporary assumptions

A temporary assumption must be recorded as an Assistant Inference with:

```markdown
Assumption:
Evidence:
Affected stage:
Reversible: [yes / no]
What changes if wrong:
Expiry / confirmation condition:
```

A temporary assumption may not authorize an irreversible action or alter an ECD-approved decision.

## Approval recording

When recording ECD approval, include:

```markdown
Decision ID:
Decision Object artifact / version:
User response:
Producer interpretation:
Authority granted:
Scope:
Exclusions:
Newly active state / department:
Input IDs activated:
Reference roles activated:
Dependencies invalidated or preserved:
```

For combined Core Script + Creative Script Alignment, record the two authority scopes separately even when one Decision ID resolves both.

## Stage transition recording

Before changing stage, Producer confirms:

- the current artifact is authority-complete for the next use;
- the Adaptive Route still matches scope and risk;
- the High-Leverage Decision Record permits dependent work;
- the Evidence Obligation remains correct;
- source posture and Concept Reframing rules remain correct;
- all material inputs are registered;
- current-stage projections are resolved;
- next-stage projections are activated with original source wording and authority class;
- reference roles and prohibited transfers are carried forward;
- no known input is being requested from the ECD a second time without cause.

## Core Script dependency rule

When Separate Core Script Alignment is required:

- page architecture, Frame Scripts, exact copy, publication copy, Visual, and Production remain inactive;
- any such artifacts produced early are marked `provisional / unauthorized dependency`;
- after Core Script approval, revalidate and reuse only the portions that remain faithful;
- rejection of the Core Script does not reopen the Treatment unless the feedback changes accepted Development decisions.

When an aligned Core Script changes materially:

- mark dependent page architecture, Frame Scripts, exact copy, Visual, and Production artifacts `stale pending revalidation`;
- preserve unaffected source, research, Treatment, and other independent work;
- request renewed Core Script authority before resuming dependent adaptation.

## Source posture update rule

A Discovery Signal remains backstage and does not activate public attribution, evidence, or visual-reference obligations by default.

If later work introduces a specific factual dependency or direct-use material:

- update the source posture;
- activate only the required research, rights, attribution, and reference controls;
- do not restart unrelated work.

If future productization becomes a separate current commission, create a new or expanded Deliverable Contract and reassess Evidence Obligation rather than silently changing the current concept-sharing post.

## Stale dependency rule

When an upstream authoritative artifact is reopened:

- mark only actual dependent downstream artifacts `stale pending revalidation`;
- mark dependent input projections and reference instructions stale where necessary;
- keep unaffected work available as reference;
- prevent stale artifacts from authorizing new work;
- revalidate or rebuild only what the upstream delta affects.

## Completion Record

After Final Acceptance, Producer records:

```markdown
# Project Completion Record

Project:
Completion date:
Final status:
Final deliverables:

Authoritative chain:
- Treatment / Greenlight
- Core Communication Script / gate mode / Alignment
- Creative Script / Alignment
- Visual Package / Alignment
- Final Package / Acceptance

Adaptive Route and final complexity profile:
High-Leverage Decision Record:
Concept Reframing and final source posture:
Evidence Obligation and validation state:
Stage-Scoped Input Register closure:
Reference Records and final permitted uses:
Registered Skills actually used:
Skills omitted and reasons:
Combined execution seats / decision scopes:
Department Review Records:
Final sign-offs:
Major ECD decisions:
Feedback closure:
Authorized deviations:
Known limitations:
Publication state:
Reusable evaluation findings:
```
