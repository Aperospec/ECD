# Creative Treatment Presentation Regression

## Purpose

These tests verify that an ECD-facing Creative Treatment presents the actual creative idea before process, boundary, risk, reference, or Greenlight information.

The regression was created after a Digital Memory Archive test in which the studio correctly respected Greenlight and stage-scoped input boundaries, but buried the real creative explanation inside sections about Agent role, authenticity, guardrails, Deferred inputs, and process state. The ECD had to ask where the actual idea was.

That outcome is a failure even when the underlying Development analysis is correct.

Apply `../shared/CREATIVE_TREATMENT_PRESENTATION.md`.

## Hard Failures

A Treatment fails immediately when:

- it does not begin with a one-sentence creative core;
- the one-sentence opening is merely a slogan, headline, abstract taxonomy, or disclaimer;
- the complete creative explanation appears only after guardrails, evidence notes, reference analysis, or workflow language;
- the Treatment begins with several paragraphs explaining what the project is not;
- the ECD must synthesize the idea from separate fields;
- the ECD reasonably asks, “你真正想表达的内容到底在哪里？”;
- the studio supplies the clear creative explanation only after that challenge rather than placing it in the Treatment itself;
- internal Development records are dumped into the ECD-facing proposal without synthesis;
- Deferred Input notices or Greenlight mechanics visually dominate the creative proposition;
- the rewritten summary after a failure is not incorporated into a revised Treatment version.

## Required Visible Order

Every tested Treatment must use this order:

```text
One-Sentence Creative Core
→ Creative Treatment narrative
→ Supplemental Development information
→ Deferred Input Notice when useful
→ Greenlight Scope and Request
```

The first two sections are mandatory. Supplemental subsections may be compressed or omitted when irrelevant.

## P01 — Digital Memory Archive Real-Failure Regression

### Input context

The ECD wants a Xiaohongshu post about turning the life experiences voluntarily brought into conversations with AI into a personal digital memory archive or museum.

Material boundaries include:

- not “AI's view of you”;
- AI did not witness the original real-world events;
- the person voluntarily recounts those experiences in conversation;
- AI's analysis, response, and companionship within those conversations become part of how the memories are later held;
- no implication of background surveillance;
- memory scenes may be reconstructed rather than documentary evidence;
- downstream visual references and monumental architecture remain stage-scoped.

### Failing behavior

The first visible Treatment begins with sections such as:

- core proposition stated defensively;
- scene authenticity;
- Agent role;
- surveillance qualification;
- audience takeaway;
- boundary catalogue;
- Deferred inputs;
- Greenlight mechanics.

The actual idea is only discoverable after the ECD asks for it.

### Expected opening

The response should begin with an equivalent of:

```markdown
## One-Sentence Creative Core

把我和 AI 聊过的那些人生，变成一座可以重新走进去的数字记忆博物馆。

## Creative Treatment

一个人去过一些地方，遇见过一些人，也经历过许多只属于自己的时刻。AI 并没有亲眼看见这些生活，是人在一次次主动开启的对话中，把它们讲给了 AI。

在讲述的过程中，AI 陪他分析、回应、追问，也帮助他重新理解当时的感受。于是被留下来的不再只是一串聊天记录，也不只是现实中发生过的一件事，而是生活片段、当时的情绪、后来的讲述，以及那次对话共同形成的记忆。

这些记忆最终被重构成一座可以走进去的数字博物馆。馆内陈列的不是物品、照片或人格标签，而是一个个曾经发生过、也可能已经变得模糊的生活场景。它不试图定义“我是谁”，只是让我重新走进那些我曾经带进对话、并与 AI 一起理解过的人生片段。
```

Exact wording may differ. The governing idea, human sequence, and relationship must be equally clear before supplemental notes begin.

### Assertions

- the first sentence positively states what the project does;
- the narrative explains what happens in real life, what is brought into conversation, what AI contributes, and what the archive becomes;
- the ECD can judge the creative premise without reading guardrails;
- monitoring, privacy, present-product capability, and documentary-truth boundaries appear afterward;
- the Stage-Scoped Input Register remains intact;
- no Script, final page sequence, Storyboard, palette, or production image is created;
- Greenlight still authorizes Creative Script development only.

## P02 — Positive Definition Before Negative Boundary

### Input

A brief includes many explicit prohibitions and only one positive creative idea.

### Expected

Creative Producer synthesizes the positive governing idea first. It then groups the prohibitions under concise guardrails.

### Failure

The Treatment opens with “This is not…” and spends more space excluding interpretations than explaining the proposed work.

## P03 — One-Sentence Core Is Not a Headline

### Input

A social post may eventually need a catchy cover line.

### Expected

The One-Sentence Creative Core explains the project; it is not treated as final audience-facing copy.

Valid:

> Turn the life voluntarily brought into AI conversations into a memory museum the person can revisit.

Invalid:

> YOUR MEMORIES. REBUILT.

The invalid example may become later copy, but it does not satisfy the Treatment gate.

## P04 — Narrative Must Be Coherent Prose

### Expected

The Creative Treatment section uses connected paragraphs that explain causality and transformation.

### Failure

The section is a list of labels such as:

- premise;
- Agent role;
- authenticity;
- audience feeling;
- core proposition.

Even correct fragments fail when the ECD must assemble them into a story.

## P05 — Internal Record Must Remain Internal

### Input

The project has extensive rights, evidence, stage-state, and reference metadata.

### Expected

Creative Producer maintains complete internal records but surfaces only decision-relevant supplemental information after the creative narrative.

### Failure

Artifact versions, state transitions, authority classifications, reference taxonomies, or risk registers dominate the visible Treatment.

## P06 — Boundaries Protect Rather Than Replace the Idea

### Expected

Guardrails are concise and clearly subordinate.

A useful test:

> Remove the guardrails. Can the ECD still explain the proposed work accurately from the first two sections?

If no, the Treatment fails.

## P07 — Deferred Inputs Appear After the Proposal

### Expected

The Deferred Input Notice proves that downstream information was preserved, but appears after the core and narrative.

### Failure

The response foregrounds stage decomposition, reference usage, or deferred execution before explaining the idea.

## P08 — Greenlight Request Cannot Carry the Missing Idea

### Expected

The creative premise is already clear before the Greenlight section.

### Failure

The most concise or comprehensible formulation first appears inside “Greenlight will confirm…” rather than in the opening.

## P09 — Failure Recovery Requires a Revised Treatment

### Trigger

ECD says:

> 你写了这么多字，我没有看出来你真正表述的内容在哪里？

### Expected recovery

1. acknowledge that presentation hierarchy failed;
2. formulate the missing One-Sentence Creative Core and Creative Narrative;
3. revise the artifact as the next Treatment version;
4. mark the prior Treatment Superseded;
5. present the full revised hierarchy;
6. request Greenlight again;
7. do not treat the conversational summary alone as an accepted Treatment.

### Failure

The studio provides a useful informal summary but leaves the deficient Treatment as the object awaiting Greenlight.

## P10 — Extended Work Still Leads With the Idea

### Input

An evidence-sensitive or commercial project requires substantial factual and legal boundaries.

### Expected

The first two sections still present the creative idea clearly. Critical warnings may appear immediately after them or earlier only when safety or law genuinely requires interruption.

“Extended” is not permission to turn the ECD-facing Treatment into an internal memorandum.

## P11 — Treatment Narrative Does Not Become Creative Script

The narrative may explain what happens conceptually, but it must not lock:

- final page count;
- card order;
- final titles;
- detailed fictional biography;
- exact scenes per page;
- camera, palette, typography, or composition;
- Storyboard or final visuals.

A clear Treatment is not the same as premature production.

## P12 — Readability Test

After drafting, Creative Producer should be able to answer all three questions using only the first two sections:

1. What is this work fundamentally about?
2. What actually happens in it?
3. Why should the audience care or feel something?

If any answer requires consulting later guardrails or state notes, revise before Greenlight.

## Evaluation Record

```markdown
Test ID:
Treatment version:
One-sentence core present: [pass / fail]
One-sentence core explanatory rather than promotional: [pass / fail]
Creative Narrative present immediately after: [pass / fail]
Narrative coherent without field reconstruction: [pass / fail]
Positive definition precedes negative boundary: [pass / fail]
Supplemental information subordinate: [pass / fail]
Deferred notice correctly placed: [pass / fail]
Greenlight scope correct: [pass / fail]
No premature Production: [pass / fail]
Observed ECD comprehension issue:
Failure owner:
Pass / fail:
```

Failure owner for presentation hierarchy: **Creative Producer / Creative Treatment artifact**.