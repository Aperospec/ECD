# ECD Decision Presentation

## Purpose

Every ECD decision attaches to a complete, visible, identifiable, Producer Cleared decision object.

The primary conversation is the default decision surface unless the ECD explicitly selects another review surface.

An internal artifact may be technically complete while the ECD-facing object is incomplete, unclear, or not ready. Creative Producer owns the readiness judgment, recommendation, and release.

## Release prerequisite

Before any ECD decision request:

```text
Specialist Self-QA
→ Producer Review
→ Producer Cleared
→ ECD-facing decision release
```

A failed Producer Review returns internally. The ECD is not used to identify defects that the studio can resolve itself.

## Decision-Object Standard

A valid ECD-facing decision object contains:

1. **Object identity** — artifact type, version, and decision being requested.
2. **Producer recommendation** — the proposed decision and why the project is ready for it.
3. **Complete decision content** — everything the ECD needs to judge the actual proposal.
4. **Delta** — relevant additions, refinements, changes, or removals from the last authoritative version.
5. **Feedback closure** — applicable prior ECD feedback and any unresolved consequence.
6. **Approval scope** — what acceptance will make authoritative.
7. **Exclusions** — what remains open, Deferred, or outside the decision.
8. **Consequence** — which stage, capabilities, or locks approval will authorize.
9. **Explicit request** — approve, revise, choose, pause, return upstream, or reject.

The proposal must be understandable without:

- opening an archive file;
- decoding internal workflow vocabulary;
- reconstructing missing creative content;
- guessing the Producer's recommendation.

Completeness means professional synthesis, not a raw dump of internal IDs, worksheets, role labels, or exhaustive QA.

## Turn boundary

A response that releases a decision object ends at the decision request.

Creative Producer may not execute the next stage, call downstream Production capabilities, or present the decision as already accepted in the same response.

## Frontstage / Backstage Principle

The studio may require detailed internal records.

Backstage fields remain backstage unless they create a decision, delta, risk, or unresolved conflict the ECD needs to understand.

The ECD-facing object should expose the complete creative proposal and the consequence of accepting it, not the studio's internal bookkeeping.

## Gate-specific minimums

### Creative Treatment / Greenlight

Present in this order:

1. One-Sentence Creative Core;
2. complete Creative Treatment narrative;
3. necessary Development context and boundaries;
4. concise Deferred Input Notice when useful;
5. Producer recommendation;
6. relevant delta from a prior Treatment, when applicable;
7. exact Greenlight scope and next authorized stage;
8. Decision Request.

A new Treatment requires explicit ECD Greenlight.

### Creative Script / Script Alignment

Present:

1. **Overall Communication Logic** — how the complete piece communicates from opening to payoff, in plain language.
2. **Every proposed page**, normally using only:
   - **What this page says**;
   - **Frame Script**;
   - **Page Copy**.
3. **Complete Companion / Body Copy**.
4. **Relevant Script delta and prior-feedback closure**.
5. **Alignment Scope**.
6. **Deferred Visual Scope**.
7. **Producer recommendation**.
8. **Decision Request**.

The Frame Script is mandatory and must describe the proposed visible scene, action, transformation, comparison, evidence state, or information relationship concretely enough for the ECD to imagine the page.

The following normally remain backstage:

- Function;
- Editorial Job;
- Audience Change;
- Internal Semantic Proposition;
- Written Visual Requirements;
- transition bookkeeping;
- input IDs;
- detailed QA;
- Artifact Decision Contract;
- handoff metadata.

Surface one only when it creates a material decision, and translate it into ordinary language.

Every new Creative Script requires explicit ECD Script Alignment.

### Visual Direction / Visual Alignment

When a new or changed governing visual decision requires ECD authority, present actual representative proof together with:

- Visual Problem Statement in plain language;
- the accepted Script condition the proof must satisfy;
- reference roles and controlled-transfer logic;
- concept routes or selected route;
- Producer and Art Director recommendation;
- relevant visual delta;
- main tradeoff or misreading risk;
- questions the proof resolves;
- decisions proposed for lock;
- variables remaining open;
- consequence for Art Direction or Production;
- Decision Request.

When the decision depends on visual relationships, prose alone is insufficient.

When the work combines required copy with imagery and the image–type relationship is decision-bearing, the representative proof must also show:

- exact ECD-aligned copy in target geometry;
- the Copy-Aware Layout Map or a plain-language rendering of its consequential decisions;
- provisional or intended line behavior;
- copy footprint and minimum readable scale;
- protected subject, action, interface, or evidence zones;
- intended quiet, overlap, occlusion, and layer-order behavior;
- representative Type-Fit and mobile-width result;
- whether the image is Exploratory or Production-intent.

An isolated attractive image is not a complete visual decision object when final copy fit has not been demonstrated.

Apply `../art-director/references/copy-aware-composition.md`.

### Final Assets / Final Acceptance

Present final assets or directly accessible previews together with:

- deliverable completeness;
- authoritative upstream references;
- Producer Final Review result and recommendation;
- applicable feedback closure;
- material implementation delta or authorized deviations;
- Copy-Aware Layout Map coverage;
- Production-intent image provenance and compliance;
- exact-copy Type-Fit and mobile evidence;
- technical QA;
- known limitations;
- publication state;
- exact Final Acceptance request.

## Producer Release Summary

Use a concise block when useful:

```markdown
## Producer Review

Artifact / version:
Review result: Producer Cleared
Producer recommendation:
Relevant delta:
Previous ECD feedback:
Copy-aware / Type-Fit state, when applicable:
Known limitation or unresolved tradeoff:
Decision requested:
Consequence if approved:
```

This summary does not replace the complete decision content.

## Presentation Record

```markdown
Decision object:
Artifact type:
Version / reference:
Producer Review Record:
Producer recommendation:
ECD-facing presentation reference:
Archive reference:
Material decisions presented:
Relevant delta:
Prior feedback closure:
Copy-aware proof reference, when applicable:
Items outside this decision:
Decision requested:
ECD response / evidence:
Resulting authority state:
Resulting stage activation:
```

## Failure recovery

When a decision was requested from an object that was incomplete, overly abstract, internally cluttered, professionally weak, copy-blind, or not Producer Cleared:

1. withdraw the request;
2. keep downstream capabilities inactive;
3. identify the missing content, proof, Layout Map, Type-Fit, authority, or review;
4. return the earliest failed professional object for correction;
5. rerun specialist self-QA and Producer Review;
6. synthesize a new ECD-facing presentation version;
7. request the decision again.

## Quality gate

A decision presentation passes when:

- the underlying artifact is Producer Cleared;
- the complete proposal is visible;
- the Producer recommendation is explicit;
- relevant delta and feedback status are clear;
- approval scope, exclusions, and consequence are exact;
- consequential image–type decisions are shown with exact copy and representative fit;
- the ECD can respond without performing studio QA;
- the response ends at the requested decision.
