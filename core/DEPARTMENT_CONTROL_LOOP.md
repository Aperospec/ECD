# Department Control Loop — V3.1

## Purpose

Department Control converts registered specialist methods into one professionally accountable department package.

A Department Director is not a decorative title and does not perform every craft task by default. The Director selects implemented Skills, inspects actual work, returns weak work, integrates the accepted results, and signs professional readiness.

## Canonical loop

```text
Creative Producer Department Assignment
→ Director validates authority, state, and available capabilities
→ Director creates Capability Plan
→ registered Specialist Skills execute
→ each Specialist produces an inspectable Return and self-check
→ Director reviews actual artifacts
   ├─ Department Rework
   ├─ bounded internal iteration
   ├─ cross-department issue returned to Producer
   ├─ capability blocker returned to Producer
   └─ Department Cleared Package
→ Creative Producer Integrated Review
```

## Capability Plan

Before specialist work, Director records:

```markdown
Department:
Active Project State:
Producer assignment:
Authoritative inputs and versions:
Department outcome:
Decisions owned:
Decisions outside authority:
Registered Skills required:
Registered Skills conditional:
Skills omitted and why:
Evidence required from each Skill:
Internal order and dependencies:
Cross-department loop required:
Department acceptance criteria:
Return conditions:
```

The Director must check every proposed Skill against `CAPABILITY_REGISTRY.md`.

## Specialist Return standard

Every registered Skill returns:

```markdown
Skill name and version:
Task:
Authoritative inputs:
Method stages completed:
Artifact produced:
Alternatives considered when relevant:
Direct observations / evidence:
Decisions introduced:
Dependencies and constraints:
Known limitations:
Self-check result:
Failure or escalation condition:
Recommended Director disposition:
```

A profession name, role-play statement, or checklist without a real artifact does not count as a Specialist Return.

## Department Review

Director reviews the actual work under the intended viewing or use conditions.

The review must address:

### 1. Authority fidelity

- Does the work use the latest authoritative inputs?
- Did it stay inside department authority?
- Did it silently change an upstream decision?

### 2. Capability sufficiency

- Were the required registered Skills actually used?
- Was an essential capability omitted?
- Is a claimed capability unavailable or imaginary?

### 3. Method evidence

- Did each Skill perform its method rather than jump to a conclusion?
- Are explorations, comparisons, drafts, proofs, or inspections visible where required?

### 4. Professional quality

- Is the work strong enough in the department's craft?
- Are defects specific and consequential, not merely stylistic preferences?

### 5. Internal coherence

- Do the specialist outputs agree with one another?
- Did one skill invalidate another skill's assumptions?

### 6. Downstream executability

- Can the next department work without inventing missing decisions?
- Are locks, open variables, tolerances, and failure conditions clear?

### 7. Feedback closure

- Did the department address every applicable ECD and Producer feedback item?
- Is closure supported by revised evidence rather than assertion?

## Evidence-backed Department Review Record

```markdown
# Department Review Record

Project:
Department:
Director Skill:
Artifact / version reviewed:
Registered Specialist Returns reviewed:
Actual evidence inspected:
Viewing / test conditions:

Authority findings:
Capability findings:
Method findings:
Professional findings:
Cross-skill coherence findings:
Downstream readiness findings:
Feedback closure findings:

Defects found:
Rework issued:
Correction evidence inspected:
Remaining limitations:

Disposition:
- Department Rework
- Return to Producer for cross-department correction
- Return to Producer for capability / authority blocker
- Department Cleared

Director recommendation:
Next legitimate use:
```

A Director may not issue `Department Cleared` when this record lacks actual artifact and evidence references.

## Department Rework Brief

```markdown
Artifact to reopen:
Earliest defect:
Why it matters:
Responsible registered Skill:
Authoritative decisions that remain fixed:
Variables allowed to change:
Required correction:
Acceptance evidence:
Stop condition:
```

Rework returns to the earliest failed specialist object. A downstream skill must not decorate over an upstream defect.

## Cross-department loop

A Director cannot directly change another department's authoritative artifact.

When work is interdependent, return to Producer with:

```markdown
Lead department:
Partner department:
Shared problem:
Fixed authority:
Allowed variables:
Required Skills:
Evidence exchanged:
Decision owner:
Stop condition:
```

Producer authorizes and records the loop.

## Department Cleared Package

A valid package contains:

- department artifact and version;
- Capability Plan;
- registered Skills used and Returns;
- Department Review Record;
- authoritative dependencies;
- decisions added and delta;
- evidence;
- feedback closure;
- open variables and limitations;
- Director recommendation;
- requested next use.

`Department Cleared` means the Director is professionally willing to stand behind the package. It does not mean Producer or ECD approval.

## Compact work

Compact work may combine execution passes, but the following remain distinct:

- specialist method;
- specialist return;
- Director review;
- Producer integration;
- ECD authority when required.

The same model may perform multiple registered methods in sequence, but it must not claim a separate person or agent performed them, and it must not use one self-check as the required Director or critique review.
