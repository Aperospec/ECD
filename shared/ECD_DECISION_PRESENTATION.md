# ECD Decision Presentation Protocol

## Purpose

This protocol defines how the studio presents any artifact that requires an Executive Creative Director decision.

An internal artifact may be complete while its ECD-facing handoff is still invalid. The ECD must not be asked to approve, align, accept, or lock an object that has not been presented clearly and completely in the primary conversation.

This protocol controls all ECD gates:

- Creative Treatment → Greenlight;
- Creative Script → Script Alignment;
- Storyboard / Representative Design Comp → Visual Alignment;
- Final Assets → Final Acceptance.

## Core Principle

> Every ECD decision must be attached to a complete, visible, identifiable decision object.

The primary conversation is the default decision surface. A file, attachment, project note, or archival document may mirror the work, preserve internal state, or provide additional detail, but it must not contain the only copy of information the ECD needs in order to decide.

The ECD should be able to understand:

- what is being proposed;
- why it is being proposed;
- what exactly will become authoritative;
- what remains open or deferred;
- what decision is requested;

without opening an attachment.

## Complete Does Not Mean Raw

A complete ECD-facing proposal is not a dump of the internal working file.

Creative Producer must synthesize the artifact into a decision-ready presentation:

- include every material creative choice requiring ECD authority;
- include enough detail to judge the whole proposal rather than a summary of it;
- remove or demote internal IDs, bookkeeping, duplicated state tables, and routine QA detail;
- preserve exact audience-facing copy, page logic, visual proof, or final assets when those are the decision object;
- distinguish user-supplied constraints from studio inference;
- state what remains outside the current decision.

The standard is **decision completeness with professional synthesis**.

## Primary Conversation Rule

Unless the ECD explicitly chooses a document as the review surface, the primary conversation must contain the complete ECD-facing proposal.

Invalid patterns include:

- “Here are the seven page titles; the full script is in the file.”
- “The detailed visual direction is attached; reply Approved.”
- “See the document for the body copy and alignment scope.”
- asking for a decision after showing only an executive summary;
- placing unique material content only in an attachment;
- requiring the ECD to reconstruct the proposal from internal records.

A file may still be generated for:

- archival completeness;
- version control;
- internal input-resolution tables;
- detailed QA;
- production handoff;
- later retrieval.

The file supplements the proposal. It does not substitute for it.

## Decision-Object Visibility Gate

Before requesting any ECD decision, Creative Producer must verify:

1. the artifact and version are identified;
2. the complete decision-relevant content is visible in the primary conversation;
3. the proposal is understandable without an attachment;
4. the ECD can see what is new relative to the previous accepted artifact;
5. the exact alignment / acceptance scope is stated;
6. items that remain Deferred or unaccepted are stated;
7. the requested response is explicit;
8. the response ends at the decision gate when downstream work depends on it.

If any condition fails, the artifact remains `Proposed` and the decision request is invalid.

## Gate-Specific Minimums

### Creative Treatment / Greenlight

Present:

- One-Sentence Creative Core;
- complete Creative Treatment narrative;
- necessary supplemental Development information;
- Deferred Input Notice when useful;
- exact Greenlight scope and request.

Apply `CREATIVE_TREATMENT_PRESENTATION.md`.

### Creative Script / Script Alignment

Present:

- Script Core;
- Communication Strategy;
- complete page / beat sequence;
- for every page: function, editorial job, audience change, written Visual Beat, final on-screen copy, material limitation / preservation rule, and transition when relevant;
- complete companion / body copy;
- fidelity and sequence QA summary;
- exact Script Alignment scope;
- what remains Deferred for Art Director;
- decision request.

Apply `../editorial-director/references/creative-script-presentation.md`.

A list of page titles and one sentence per page is a **sequence summary**, not a Creative Script Proposal.

### Storyboard / Representative Design Comp / Visual Alignment

Show the representative visual proof itself in the conversation, together with:

- the visual thesis;
- what the proof establishes;
- reference interpretation and prohibited transfer;
- material tradeoff or risk;
- what will become visually locked;
- what remains open for production.

A prose-only description is not a substitute for a visual object when the ECD is being asked to align a visual premise.

### Final Assets / Final Acceptance

Present the final assets or directly accessible final previews, plus:

- deliverable completeness;
- material deviations;
- mobile and technical QA result;
- known limitations;
- publication state;
- exact Final Acceptance request.

## Presentation Record

For every ECD gate, record at the depth required by the project:

```markdown
Decision object:
Artifact type:
Version / reference:
ECD-facing presentation turn / reference:
Complete proposal visible in primary conversation: [yes / no]
Archive / internal file reference:
Material decisions presented:
Items explicitly outside this decision:
Decision requested:
ECD response / evidence:
Resulting state:
```

An archive-file reference without an ECD-facing presentation reference is not sufficient evidence of alignment.

## Failure Recovery

When the studio requests a decision from an incomplete or summary-only presentation:

1. withdraw the decision request;
2. keep the internal artifact `Proposed`;
3. identify the missing decision-relevant content;
4. create a complete ECD-facing proposal as a new presentation version;
5. preserve the underlying internal artifact when still valid;
6. request the decision again only after the full object is visible;
7. do not treat the ECD's response to an incomplete summary as valid alignment unless the ECD explicitly states that they reviewed and accepted the complete identified artifact elsewhere.

If the internal artifact itself also fails content fidelity or quality, revise the artifact before resubmitting; do not merely copy a defective file into the conversation.

## Hard Failures

The following are hard failures:

- requesting Greenlight, Script Alignment, Visual Alignment, or Final Acceptance for an object not fully presented;
- using an attachment as the only location of the full decision object;
- calling a page-title list a complete Creative Script;
- hiding body copy, written Visual Beats, material fictional additions, or alignment scope in a file;
- presenting internal completeness as proof of ECD-facing completeness;
- advancing downstream because an attachment exists;
- recording ECD alignment without an identifiable presentation and decision object;
- requiring the ECD to ask where the actual proposal is.

## Relationship to Other Protocols

This protocol governs **how an ECD decision object is presented**.

Other protocols continue to govern:

- what belongs to each stage;
- which inputs are Active or Deferred;
- artifact ownership;
- Greenlight authority;
- content and visual quality;
- handoff and rework.

A proposal must pass both its professional quality gate and this presentation gate before it can receive a valid ECD decision.
