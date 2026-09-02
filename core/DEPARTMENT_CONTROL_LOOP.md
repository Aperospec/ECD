# Department Control Loop

## Purpose

This protocol defines how ECD V3 departments perform professional work without forcing Creative Producer to impersonate every discipline or forcing the Executive Creative Director to become first-line quality assurance.

## Core invariant

> A formal specialist output must pass Department Review before it can reach Creative Producer, and it must pass Producer Integrated Review before it can reach the Executive Creative Director or activate downstream work.

## Canonical department loop

```text
Creative Producer assignment
→ Department Director intake
→ capability and dependency plan
→ specialist assignments
→ specialist execution
→ specialist self-check
→ specialist return to Department Director
→ Department Review
   ├─ Department Rework
   ├─ bounded cross-department working loop
   ├─ authority conflict returned to Creative Producer
   └─ Department Cleared
→ formal department return to Creative Producer
```

## Department assignment envelope

Creative Producer supplies:

```markdown
Project / version:
Active project phase:
Department:
Authoritative upstream artifacts:
ECD decisions and locks:
Requested department outcome:
Deliverable Contract:
Decisions owned by department:
Decisions outside department authority:
Active inputs and source authority:
Deferred inputs and capabilities:
Cross-department dependencies:
Known risks and open issues:
Acceptance criteria:
Expected ECD gate:
Return conditions:
```

Department Director may refine internal tasks but may not expand scope, change authority, or activate another department without Producer approval.

## Capability plan

Before execution, Department Director identifies:

- the professional problem to solve;
- specialist Skills required;
- specialist Skills not required;
- task sequence and working loops;
- authoritative inputs for each task;
- expected outputs and evidence;
- review criteria;
- unresolved dependency or authority risk.

The plan is proportional. A simple project may use fewer Skills, but omission must be a professional decision rather than an assumption that one generalist can do everything.

## Specialist return

Each specialist returns:

```markdown
Skill:
Task:
Authoritative inputs used:
Method followed:
Output:
Professional decisions introduced:
Open questions:
Known limitations:
Self-check evidence:
Recommended department disposition:
```

A list of completed activities is not evidence of professional sufficiency.

## Department Review

Department Director independently evaluates the actual artifact, not only the specialist's self-report.

Review must cover:

### 1. Upstream fidelity

The artifact preserves authoritative project decisions, language, evidence, rights, constraints, and current feedback.

### 2. Method sufficiency

The specialist used an appropriate professional method rather than jumping directly to one answer, copying a template, or decorating an unresolved idea.

### 3. Craft quality

The artifact meets the department's discipline-specific standard. This judgment belongs to the Department Director, not Creative Producer.

### 4. Internal coherence

Outputs from different specialist Skills agree and form one department solution.

### 5. Evidence

The review is based on inspectable work: drafts, alternatives, proofs, contact sheets, text comparisons, layout studies, rendered files, or other discipline-appropriate evidence.

### 6. Downstream readiness

The next department can act without inventing unresolved professional decisions.

### 7. Feedback closure

Applicable ECD and Producer feedback is demonstrably resolved, not merely marked `done`.

## Department dispositions

### Department Rework

Use when the department can correct the problem internally.

The Director identifies:

- earliest failed specialist object;
- valid work to preserve;
- required correction;
- acceptance evidence;
- owner and return path.

### Cross-department correction request

Use when another department's input creates a professional constraint or contradiction.

The Director sends the issue to Creative Producer, who authorizes a bounded working loop or reopens the earliest affected department artifact.

### Authority conflict

Use when resolution requires changing an ECD-approved decision, project scope, Deliverable Contract, or another department's authoritative output.

Department Director does not negotiate authority directly with another department.

### Department Cleared

Use only when the Director is prepared to sign the professional quality of the integrated department package.

Department clearance means:

- required specialist methods were used;
- defects detectable within the department were corrected internally;
- the package is coherent and inspectable;
- open limitations are explicit;
- the next use is named.

It does not equal Producer clearance or ECD approval.

## Department Review Record

```markdown
# Department Review Record

Project:
Department:
Director:
Package / version:
Intended next use:

Specialist Skills activated:
Specialist outputs reviewed:
Actual evidence inspected:
Upstream fidelity:
Method sufficiency:
Craft quality:
Internal coherence:
Downstream readiness:
Feedback closure:
Known limitations:
Required rework:
Authority conflict:
Director recommendation:
Disposition: [Department Rework / Cross-department Request / Authority Conflict / Department Cleared]
Signed by:
```

## Department return to Creative Producer

A valid formal return contains:

- Department Cleared package and version;
- Department Review Record;
- authoritative dependencies;
- decision delta;
- unresolved limitations and risks;
- cross-department consequences;
- required ECD authority;
- Director recommendation;
- requested Producer disposition.

Creative Producer receives department-level work, not unmanaged specialist drafts.

## Producer Integrated Review

Producer checks project-level integration rather than repeating department craft review.

Producer verifies:

- correct project and current versions;
- all required department sign-offs;
- cross-department consistency;
- scope and Deliverable Contract completeness;
- authority and stage validity;
- user feedback closure;
- decision-object completeness;
- next-stage readiness.

Producer may reject obvious defects or incomplete evidence, but does not replace a Director's discipline-specific method. When craft quality is doubtful, Producer returns the package to the responsible Director for professional re-review.

## Cross-department working loops

A working loop must state:

```markdown
Problem:
Participating departments / Skills:
Lead Director:
Authoritative decisions held fixed:
Variables allowed to change:
Evidence required:
Stop condition:
Formal owner of resulting artifact:
Return path to Creative Producer:
```

Working loops are not informal authority channels. Material upstream change still follows the normal rework and ECD decision process.

## No self-approval

The same execution seat may perform several specialist tasks in Compact work, but it may not be the sole reviewer of its own formal department package.

A Department Director must inspect the actual result and issue an independent disposition.

## Final multi-department sign-off

Before Final Acceptance:

- Editorial Director signs language, facts, names, claims, and copy;
- Art Director signs visual concept and design fidelity;
- Production Director signs implementation and technical integrity;
- Creative Producer signs project integration and decision readiness.

A missing sign-off is a blocking condition unless the Deliverable Contract establishes that the department is genuinely out of scope.
