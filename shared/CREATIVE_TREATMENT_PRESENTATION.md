# Creative Treatment Presentation

## Purpose

This protocol defines how Creative Producer presents a Creative Treatment to the Executive Creative Director.

A Creative Treatment is first a **creative proposition** and only second a Development decision package. The ECD should understand the idea before reading its boundaries, state, or process notes.

This protocol controls the user-visible order of every proposed Creative Treatment.

## Non-Negotiable Presentation Order

Every ECD-facing Creative Treatment must begin in this order:

1. **One-Sentence Creative Core**
2. **Creative Treatment / Creative Narrative**
3. **Supplemental Development Information**
4. **Deferred Input Notice**, when useful
5. **Greenlight Scope and Request**

Do not place project metadata, guardrails, evidence notes, reference analysis, stage-state language, or Greenlight mechanics before the first two sections.

## 1. One-Sentence Creative Core

The first substantive line must state, in one complete sentence, what the work is fundamentally doing.

It should be:

- positive rather than primarily defensive;
- concrete enough to picture;
- specific to this project rather than generic;
- understandable without knowledge of the studio workflow;
- a creative proposition, not a platform headline, tagline, slogan, or final audience-facing copy.

A useful form is:

> Turn / reveal / follow / reimagine **this human material** through **this governing creative idea**, so the audience can **perceive this consequence**.

The sentence may contain contrast when necessary, but it must lead with what the project **is**, not a catalogue of what it is not.

Bad opening behavior:

- beginning with surveillance, privacy, rights, or capability disclaimers;
- beginning with “This is not…” and requiring several paragraphs before the actual idea appears;
- using an abstract phrase such as “memory sovereignty” without saying what the audience will experience;
- presenting a slogan that sounds attractive but does not explain the project.

## 2. Creative Treatment / Creative Narrative

Immediately after the one-sentence core, provide a coherent prose explanation of the creative idea.

This is the primary content the ECD is evaluating.

It should explain, in complete connected paragraphs:

- what is happening in the proposed work;
- who or what the audience follows, encounters, or understands;
- how the central material is transformed or reframed;
- the role of AI, a product, a person, an object, or a system when relevant;
- why the idea is emotionally, intellectually, or editorially meaningful;
- what the audience should ultimately understand, feel, notice, imagine, or reconsider.

The narrative should synthesize the Development work. It must not force the ECD to reconstruct the concept from separate fields such as premise, role, truth boundary, audience takeaway, and guardrails.

Use paragraphs rather than a bullet list for this section. A simple project may need one or two paragraphs; a more complex project may need several. Length follows clarity, not paperwork.

The Creative Narrative is not:

- a page-by-page Creative Script;
- final on-screen or companion copy;
- a Storyboard description;
- a visual-style specification;
- an internal reasoning transcript;
- a compliance memorandum.

## 3. Supplemental Development Information

Only after the creative idea is clear may the Treatment add supporting information, such as:

- selected angle and core proposition;
- why the idea matters to the audience;
- factual, speculative, evidence, rights, or claim boundaries;
- concise creative guardrails;
- what the work must preserve;
- what the work must not imply or become;
- material Development risks or unresolved decisions.

These sections protect and qualify the proposal. They must not become longer or more visually dominant than the creative explanation unless the project is genuinely evidence- or rights-sensitive.

Prefer concise grouped notes over repeated defensive statements.

## Internal Development Record vs ECD-Facing Treatment

Creative Producer may maintain a detailed internal Development record containing:

- premise diagnosis;
- evidence and uncertainty;
- reference classifications;
- stage-scoped input projections;
- rights and attribution details;
- rejected alternatives;
- state, lock, and handoff metadata;
- complete risk analysis.

Do not dump that record into the ECD-facing Treatment by default.

The ECD-facing Treatment is a professional synthesis. It should contain only the information needed to understand and decide the creative premise.

Detailed internal records may be surfaced when:

- a material decision depends on them;
- the ECD requests them;
- the project is Extended and the detail is itself decision-critical.

## Cross-Stage Inputs

Apply `STAGE_SCOPED_INPUT_REGISTER.md` before writing the Treatment.

The Creative Narrative may express the **Development meaning** of a cross-stage instruction. It must not prematurely convert later-stage Editorial or Visual projections into final execution.

Example:

```text
ECD source: “建筑非常宏大，人很小。”

Creative Narrative may communicate:
A person's life should feel expansive enough to enter and traverse.

Deferred Visual input remains:
Monumental architecture with a small human figure.
```

The ECD should be told that meaningful downstream instructions were preserved, but the Deferred Input Notice belongs after the creative proposal and supporting Development notes.

## Guardrail Placement

Guardrails belong after the Creative Narrative.

The normal rhetorical order is:

```text
What it is
→ What happens
→ Why it matters
→ What must be protected
→ What remains Deferred
→ What Greenlight authorizes
```

Not:

```text
What it is not
→ Risk catalogue
→ Workflow catalogue
→ Deferred catalogue
→ Hidden creative idea
```

A project may require a prominent warning when safety, legality, or factual truth demands it. Even then, state the creative proposition as clearly and early as the constraint allows.

## Greenlight Presentation

The Greenlight request follows the creative proposal and supplemental information.

It must state:

- the Treatment version;
- what Development-level premise and boundaries acceptance will make authoritative;
- that the next authorized stage is Creative Script development;
- what remains Deferred and unaccepted;
- the decision requested from the ECD.

Then stop the response, as required by `GREENLIGHT_RECORD.md`.

## Creative Treatment Narrative Gate

Do not submit a Treatment for Greenlight unless all of the following are true:

- the first substantive section is a one-sentence creative core;
- the second section is a coherent creative narrative;
- the ECD can understand the proposed work without reading the guardrails;
- the proposal states what the work is before emphasizing what it is not;
- the central creative idea is not scattered across analytical fields;
- workflow, state, evidence, and boundary notes remain subordinate;
- no final Script, Storyboard, or visual execution has been produced;
- the Greenlight scope is explicit.

A Treatment fails this gate when the ECD reasonably has to ask:

> “你真正想表达的内容到底在哪里？”

When that happens, do not defend the document or merely summarize it in a follow-up. Rewrite the Treatment so the missing summary becomes its opening structure, then resubmit the revised version for Greenlight.

## Default ECD-Facing Skeleton

```markdown
# Creative Treatment V[version]｜[working title]

## 1. One-Sentence Creative Core

[One complete sentence stating what the work fundamentally does.]

## 2. Creative Treatment

[One or more connected paragraphs explaining what happens, how the concept works, why it matters, and what the audience ultimately perceives.]

## 3. Supplemental Development Notes

### Selected Angle / Core Proposition
[Concise only when it adds precision beyond the narrative.]

### Why It Matters
[Audience relevance and intended consequence.]

### Boundaries and Guardrails
- [Only material boundaries.]

### Development Decisions Still Open
- [Only material unresolved items.]

## 4. Deferred Inputs Recorded — Not Part of This Greenlight

Editorial:
- 

Visual / Art Direction:
- 

Production:
- 

## 5. Greenlight Scope and Request

Treatment version:
Acceptance will make authoritative:
Next authorized stage: Creative Script development
Still Deferred / unaccepted:
Decision requested: [Greenlight / revision / pause / rejection]
```

Omit empty supplemental subsections. Never omit the first two sections.