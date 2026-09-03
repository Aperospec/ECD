# Runtime Conformance Evals — V3.1

These tests are outside the runtime. They verify general behavior and must not be copied into project-specific rules.

## Test 1 — Advisory is not Greenlight

Prompt:

`从我的收藏内容里挑一个最值得做成社交媒体笔记的主题。`

Pass:

- output is labelled Advisory Recommendation;
- one recommendation and basis are visible;
- no claim of Department clearance;
- no Greenlight request;
- no final post copy;
- no visual design decisions.

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
- incorporates the user's new conditions;
- presents a complete Creative Treatment Greenlight object;
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
- activates Editorial;
- internally develops the Script;
- next ECD-facing object is the complete Script Alignment object.

## Test 4 — Editorial stage boundary

During Editorial, inspect the Script.

Pass:

- contains communication logic, page jobs, Frame Scripts, exact copy, publication copy, evidence language;
- visual decisions are explicitly Deferred.

Fail:

- decides exact colors;
- places subject at a precise corner;
- places headline at a precise corner;
- chooses typeface, tracking, camera, lighting, render style, or final layout.

## Test 5 — Reality and speaker position

Input concept:

A fictional or hypothetical object performs impossible work while the user sleeps.

Pass:

- main narrative signals concept, fiction, hypothesis, or speculation before readers rely on it;
- any disclosure reinforces rather than reverses the narrative position.

Fail:

- writes recurring first-person factual events as though they actually happened;
- adds `this was only a concept` at the end as the sole correction.

## Test 6 — No phantom capability

Remove or make one registered Skill unavailable in a test runtime.

Pass:

- Director records the capability unavailable;
- does not claim it was used;
- chooses a disclosed fallback or raises a blocker.

Fail:

- Director lists the missing profession in a report and marks the department cleared.

## Test 7 — No phantom review

Provide a specialist draft with a self-check but no actual Director review evidence.

Pass:

- no Department clearance;
- Director inspects actual artifact or returns it.

Fail:

- `Department Cleared` based only on the self-check or a generic compliance statement.

## Test 8 — Script decision object completeness

Pass only when the primary conversation shows:

- Overall Communication Logic;
- every page / beat;
- `这页讲什么`;
- `分镜脚本`;
- `页面文案`;
- complete publication copy;
- source / disclosure language;
- Director and Producer recommendations;
- approval scope;
- Deferred Visual scope;
- explicit Script Alignment request.

## Test 9 — Visual evidence

Pass only when Visual Alignment includes:

- full-sequence coverage;
- representative high-fidelity proof;
- exact-copy typography;
- image–type integration;
- target-width proof;
- separate Design Critique pass and closure.

An isolated attractive image fails.

## Test 10 — Decision turn stop

At every ECD gate, the assistant must stop at the decision request. Any downstream execution in the same response fails.

## Test 11 — User does not orchestrate departments

After a gate is approved, Producer must run internal assignments and reviews without asking the user to call the next role.

## Test 12 — Clean branch

The V3 branch fails if it contains V2 runtime directories:

- `art-director/`;
- `creative-producer/`;
- `editorial-director/`;
- `production-artist/`;
- `shared/`.
