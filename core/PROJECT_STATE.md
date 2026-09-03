# Project State — V3.1

Creative Producer maintains one authoritative Project State.

## Required fields

```markdown
# Project State

Project ID:
Working title:
Profile:
Executive Creative Director:
Creative Producer Skill / version:

## Request and contract
Original request:
Intended use:
Audience:
Platform / placement:
Language:
Deliverables:
Target dimensions / variants:
Evidence / rights / disclosure obligations:
Success condition:

## Entry
Entry mode:
- Advisory Discovery
- Project Start
- Continuation
- Craft-only
Entry evidence:

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
Creative Script / version / authority:
Visual Development Package / version / authority:
Art Direction Package / version / authority:
Final Production Package / version / authority:
Completion Record:

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

## Inputs
Active inputs:
Deferred inputs:
Sources and provenance:
References and transfer limits:

## Feedback
Open feedback items:
Resolved feedback items:
Conflicts requiring ECD:

## Capability integrity
Implemented Skills required:
Skills available in runtime:
Skills unavailable in runtime:
Skills omitted and reasons:
Capability limitations disclosed:

## Next action
Next legitimate action:
Owner:
Stop condition:
```

## State update rules

Only Creative Producer updates Project State.

Every update must cite the evidence that justifies it:

- user request;
- ECD Decision Object and response;
- Specialist Return;
- Department Review Record;
- Producer Integrated Review;
- blocker evidence;
- final sign-off.

A conversational summary such as `用户同意了` is insufficient unless it identifies the bound pending Decision Object.

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
Dependencies invalidated or preserved:
```

## Stale dependency rule

When an upstream authoritative artifact is reopened:

- mark all dependent downstream artifacts `stale pending revalidation`;
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
- Script / Alignment
- Visual Package / Alignment
- Final Package / Acceptance

Registered Skills actually used:
Department Review Records:
Final sign-offs:
Major ECD decisions:
Feedback closure:
Authorized deviations:
Known limitations:
Publication state:
Reusable evaluation findings:
```
