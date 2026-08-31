# ECD Decision Presentation Protocol

## Purpose

This protocol defines how the studio presents any artifact that requires an Executive Creative Director decision.

An internal artifact may be complete while its ECD-facing handoff is invalid. The ECD must not be asked to approve, align, accept, or lock an object that has not been presented clearly and completely in the primary conversation.

This protocol controls:

- Creative Treatment → Greenlight;
- Creative Script → Script Alignment;
- Visual Direction → Visual Direction Alignment;
- Anchor Keyframes / Representative Design Comp → Anchor / Design Alignment;
- Final Assets → Final Acceptance.

## Core Principle

> Every ECD decision must be attached to a complete, visible, identifiable decision object.

The primary conversation is the default decision surface. A file, attachment, project note, or archival record may preserve internal state and detail, but it must not contain the only information the ECD needs to decide.

The ECD should understand, without opening an attachment:

- what is being proposed;
- why it is being proposed;
- what evidence or visual proof supports it;
- what will become authoritative;
- what remains open or Deferred;
- what decision is requested.

## Complete Does Not Mean Raw

A complete proposal is not a dump of internal working files.

Creative Producer must synthesize:

- every material creative choice requiring ECD authority;
- enough detail or visual evidence to judge the whole proposal;
- the professional recommendation and tradeoff;
- the ECD's original source instruction where material;
- the distinction between user authority and studio inference;
- the exact decision scope.

Demote internal IDs, bookkeeping, exhaustive QA, prompt syntax, and routine technical notes.

The standard is **decision completeness with professional synthesis**.

## Primary Conversation Rule

Unless the ECD explicitly chooses a document as the review surface, the primary conversation must contain the complete ECD-facing proposal.

Invalid patterns include:

- page-title list plus “full Script in the file”;
- “detailed visual direction attached; reply Approved”;
- prose-only visual alignment without showing the relevant proof;
- six final-looking images with no explanation of the visual problem, reference transfer, route, or alignment scope;
- asking the ECD to inspect prompts or technical jargon to infer the difference;
- placing unique material content only in an attachment.

Files may still serve:

- archival completeness;
- version control;
- source and input-resolution tables;
- detailed QA;
- production handoff;
- later retrieval.

A file supplements the decision object. It does not substitute for it.

## Decision-Object Visibility Gate

Before requesting any ECD decision, verify:

1. artifact and version are identified;
2. complete decision-relevant content or visual proof is visible;
3. the proposal is understandable without an attachment;
4. the ECD can see what is new relative to the accepted upstream artifact;
5. the recommendation and material alternatives are clear;
6. exact alignment / acceptance scope is stated;
7. items remaining open or Deferred are stated;
8. requested response is explicit;
9. the response stops at the decision gate when downstream work depends on it.

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
- Language and Copy Direction;
- complete page / beat sequence;
- page function, Editorial Job, Audience Change, Written Visual Beat, exact copy, material limitation, and transition;
- complete companion / body copy;
- fidelity, sequence, and copy QA summary;
- exact Script Alignment scope;
- what remains Deferred for Art Director;
- decision request.

Apply `../editorial-director/references/creative-script-presentation.md`.

A list of titles and one sentence per page is a sequence summary, not a Creative Script Proposal.

### Visual Direction Alignment

Use before Storyboard / anchor production when a material visual system is new or unresolved.

Present:

- what Art Director believes the ECD means, in plain language;
- Visual Problem Statement synthesis;
- visible evidence from supplied references;
- reference roles and controlled transfer;
- Visual Metaphor synthesis when relevant;
- two or three materially different Concept Routes or a clear reason only one route is valid;
- low-cost visual evidence for each route;
- Art Director recommendation;
- principal benefit and risk of each route;
- no more than a few high-consequence questions;
- what the selected direction will authorize next;
- what remains unapproved.

The ECD must not be required to know art-direction vocabulary. Questions should concern observable audience experience and consequences.

A raw reference image plus “make it like this” is not a complete direction object.

### Anchor / Design Alignment

Use before broad production when the project is reference-led, metaphor-led, world-led, or materially new.

Show the actual visual proofs:

- World / Cover Anchor;
- Representative Body Anchor;
- additional distinct page-class anchor only with reason;
- Representative Design Comp when typography / layout is material.

Present:

- what each proof establishes;
- how the anchors belong to one visual system;
- how the selected metaphor and world logic are visible;
- what reference principles were transferred;
- what source-specific content was intentionally not copied;
- subject–environment hierarchy;
- principal remaining risk;
- what will become locked;
- what remains open for Color Script, Art Direction, and Production.

A montage of many unaligned final-looking images is not a substitute for representative anchors.

### Final Assets / Final Acceptance

Present final assets or directly accessible final previews, plus:

- deliverable completeness;
- fidelity to Treatment, Script, accepted visual route, anchors, and Design Comp;
- material deviations;
- copy accuracy;
- mobile and technical QA;
- known limitations;
- publication state;
- exact Final Acceptance request.

## ECD-Friendly Visual Decision Rule

For visual gates, Art Director must analyze before asking.

Valid alignment questions sound like:

- Should the whole world lead the image, with people proving it is lived in, or should one person's emotion lead?
- Should the amusement-world idea remain clear even when recognizable rides are removed?
- Which failure is least acceptable: commercial attraction poster, cold institution, or sentimental film still?

Invalid questions outsource professional work:

- Which lens should we use?
- What spatial topology do you prefer?
- Please write the visual prompt.

Apply `../art-director/references/ecd-friendly-visual-alignment.md`.

## Presentation Record

```markdown
Decision object:
Artifact type:
Version / reference:
ECD-facing presentation turn / reference:
Complete proposal / proof visible in primary conversation: [yes / no]
Archive / internal file reference:
Material decisions presented:
Art Director / Editorial recommendation:
Alternatives and tradeoffs:
Items explicitly outside this decision:
Decision requested:
ECD source response:
Professional translation when needed:
Resulting state:
```

An archive-file reference without an ECD-facing presentation reference is not sufficient evidence of alignment.

## Failure Recovery

When a decision is requested from an incomplete, summary-only, prose-only, or unproven presentation:

1. withdraw the decision request;
2. keep the artifact `Proposed`;
3. identify missing decision-relevant content or proof;
4. revise the professional artifact first if it also fails quality;
5. create a complete ECD-facing presentation;
6. request the decision only after the full object is visible;
7. do not advance downstream.

If a batch of visual assets was produced before a valid visual direction or anchor gate:

- stop broad production;
- mark the batch non-authoritative;
- preserve it only as failure evidence or exploratory material;
- diagnose the first failed visual object;
- restore the missing gate;
- do not pressure the ECD to accept it because it already exists.

## Hard Failures

- requesting any ECD decision for an object not fully presented;
- using an attachment as the only location of the full decision object;
- calling a page-title list a complete Script;
- requesting Visual Alignment without showing the relevant route or proof;
- treating a supplied reference as the selected direction without analysis;
- asking the ECD to provide specialist terminology or prompt syntax;
- generating a broad final-looking image set before Anchor / Design Alignment;
- recording ECD alignment without an identifiable presentation and decision object;
- requiring the ECD to ask where the actual proposal or visual idea is.

## Relationship to Other Protocols

This protocol governs **how an ECD decision object is presented**.

Other protocols govern:

- stage scope and activation;
- artifact ownership;
- Greenlight authority;
- writing quality;
- visual problem, reference, metaphor, route, anchor, and production quality;
- handoff and rework.

A proposal must pass both its professional quality gate and this presentation gate before it can receive a valid ECD decision.
