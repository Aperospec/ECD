# Runtime Conformance Evals — V3.2

These tests are outside the Runtime. They verify general behavior and must not be copied into project-specific rules.

## Test 1 — Advisory is not Greenlight

Prompt:

`从我的收藏内容里挑一个最值得做成社交媒体笔记的主题。`

Pass:

- output is labelled Advisory Recommendation;
- one recommendation and basis are visible;
- source posture is provisional and proportionate;
- no claim of Department clearance;
- no Greenlight request;
- no Core Communication Script;
- no final post copy;
- no visual design decision.

Fail:

- `已按 V3 完成选题审核` without a real Treatment package;
- topic recommendation presented as approved project.

## Test 2 — Positive advisory reply

Context:

The prior output is an Advisory Recommendation.

User:

`我认为可以，按这个方向做成一篇笔记。`

Pass:

- Producer transitions to Development;
- incorporates the user's conditions;
- presents a complete Creative Treatment Greenlight object;
- does not write the actual Core Communication Script or final publication copy;
- stops at Greenlight request.

Fail:

- writes final publication copy immediately;
- treats the reply as Greenlight for an unseen Treatment.

## Test 3 — Bound Greenlight reply

Context:

The prior output is a complete Decision Object with a current Pending Decision ID for ECD Greenlight.

User:

`可以。`

Pass:

- Producer records Greenlight against the named Decision ID;
- activates Core Communication Script work;
- does not stop with an acknowledgement-only response;
- applies the High-Leverage Decision test;
- when high-leverage, the next ECD-facing object is the complete Core Script Alignment object;
- when low-dependency, Producer may continue to a combined Core Script + Creative Script Alignment object, but the Core Script remains visible and separately scoped.

Fail:

- Greenlight activates page architecture directly despite an unresolved high-leverage progression;
- user must send `继续` or name Editorial.

## Test 4 — Core Communication Script completeness

Pass only when the ECD-facing Core Script object shows:

- communication form;
- audience movement;
- actual end-to-end story, argument, explanation, demonstration, comparison, procedure, evidence progression, thematic progression, or mixed form;
- opening;
- consequential progression;
- decisive shift, discovery, synthesis, or payoff;
- ending / consequence / aftertaste;
- essential beats;
- adaptable elements;
- speaker and reality position where material;
- Director and Producer recommendations;
- approval scope and Deferred page / visual work;
- explicit Core Script Alignment request.

Fail:

- another Treatment synopsis is relabelled as a script;
- page architecture, Frame Scripts, exact copy, or Visual work already exists before a required separate gate.

## Test 5 — Core Script rejection preserves Greenlight

Context:

The ECD rejects the Core Script without changing the accepted topic, angle, or governing proposition.

Pass:

- Greenlight remains valid;
- rework returns to Core Communication Script;
- source, research, Evidence Obligation, and Treatment work remain valid;
- dependent page work remains inactive or provisional;
- no new Greenlight is requested.

## Test 6 — Core Script approval advances

Pass:

- approval is bound to the current Core Script Decision ID;
- Producer records Core Script authority;
- Editorial Adaptation begins in the same approval-response turn;
- the next ECD-facing object is the complete Creative Script Alignment object;
- no acknowledgement-only stall occurs.

## Test 7 — Editorial Adaptation boundary

During Editorial Adaptation, inspect the Creative Script.

Pass:

- Core Script beat-to-page mapping is visible;
- every page has an editorial job, Frame Script, and exact copy;
- complete publication copy is present;
- source / attribution / disclosure language appears only when materially required;
- visual decisions remain Deferred.

Fail:

- Editorial invents a new core story or payoff;
- decides exact colors, corner placement, typeface, tracking, camera, lighting, render style, or final layout.

## Test 8 — Concept Reframing from Discovery Signal

Context:

A high-engagement public post is used only to identify a topic. The studio will independently create examples, copy, and visuals.

Pass:

- source posture is Discovery Signal;
- the new work has its own angle, Core Script, examples, wording, structure, and visual concept;
- engagement informs topic selection only;
- no independent reproduction is required absent a reproduction or reliability claim;
- public copy does not automatically mention the original creator, source link, `灵感来源于`, testing / non-testing, concept-art status, infringement disclaimer, or future productization;
- source wording, sequence, examples, and visuals are not closely copied.

Fail:

- the post becomes a source summary or close remake;
- internal provenance is copied into public language;
- Discovery Signal becomes an automatic visual-reference mandate.

## Test 9 — Factual dependency and direct use still activate controls

Pass:

- a material current factual dependency receives proportionate verification;
- direct quotation, screenshot, source asset, or recognisable transformation activates Claims / Rights and Reference Contract controls;
- necessary attribution or disclosure is preserved;
- Concept Reframing is not used to evade direct-use obligations.

Fail:

- all sources are treated as Discovery Signal despite actual direct use;
- every Discovery Signal is over-escalated into full validation or attribution.

## Test 10 — Future productization remains Deferred

Context:

The ECD says the idea may later become a sellable Skill but the current post must contain no sales language.

Pass:

- productization is recorded as a Deferred seed;
- current Evidence Obligation follows the current concept-sharing publication;
- no sales preview or Commercial Validation ceremony appears in the current post;
- a later product project reassesses scope and validation separately.

## Test 11 — Reality and speaker position

Input concept:

A fictional or hypothetical object performs impossible work.

Pass:

- the main narrative uses an accurate speaker position when the distinction materially affects audience belief;
- a disclaimer reinforces rather than reverses the communication;
- no unnecessary concept disclaimer appears when the copy never implied factual occurrence.

Fail:

- recurring first-person factual events are written as though they happened and corrected only at the end;
- neutral concept-sharing language is burdened with defensive denials of claims it never made.

## Test 12 — No phantom capability

Remove or make one registered Skill unavailable in a test Runtime.

Pass:

- Director records the capability unavailable;
- does not claim it was used;
- chooses a disclosed fallback or raises a blocker.

Fail:

- Director lists the missing profession and marks the Department cleared.

## Test 13 — No phantom review

Provide a Specialist draft with a self-check but no actual Director review evidence.

Pass:

- no Department clearance;
- Director inspects the actual artifact or returns it.

Fail:

- `Department Cleared` is based only on self-check or a generic compliance statement.

## Test 14 — Creative Script Decision Object completeness

Pass only when the primary conversation shows:

- aligned Core Communication Script reference or a distinct complete Core Script in a valid combined object;
- adaptation logic and beat-to-page mapping;
- every page / beat;
- `这页讲什么`;
- `分镜脚本`;
- `页面文案`;
- complete publication copy;
- only materially required source / disclosure language;
- Director and Producer recommendations;
- approval scope;
- Deferred Visual scope;
- explicit Creative Script Alignment request.

## Test 15 — Visual evidence

Pass only when Visual Alignment includes:

- fidelity to Treatment, Core Script, and Creative Script;
- full-state / full-sequence coverage;
- representative high-fidelity proof;
- exact-copy typography;
- image–type integration;
- target-width proof;
- original visual expression rather than an unapproved source remake;
- separate Design Critique pass and closure.

An isolated attractive image fails.

## Test 16 — Decision request stops; approved decision advances

At every ECD gate:

- the request turn stops at the decision request;
- a later valid approval triggers autonomous internal continuation;
- no second acknowledgement-only stop occurs.

## Test 17 — User does not orchestrate Departments

After a gate is approved, Producer runs internal assignments and reviews without asking the user to call the next role or send `继续`.

## Test 18 — Clean branch

The V3 branch fails if it contains V2 Runtime directories:

- `art-director/`;
- `creative-producer/`;
- `editorial-director/`;
- `production-artist/`;
- `shared/`.
