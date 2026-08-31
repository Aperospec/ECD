# Bilingual Copy Quality Regression

## Purpose

These tests verify that Editorial Director does not submit structurally complete but linguistically weak Chinese or English copy for Script Alignment.

The suite also verifies that bilingual work is transcreated from a shared semantic brief rather than translated mechanically.

Apply:

- `../editorial-director/references/writing-reference-canon.md`;
- `../editorial-director/references/copy-desk-workflow.md`;
- `../editorial-director/references/chinese-copy-craft.md`;
- `../editorial-director/references/english-copy-craft.md`;
- `../editorial-director/references/bilingual-transcreation.md`;
- `../editorial-director/references/copy-quality-gate.md`.

## Hard-Failure Principle

A Script fails even when:

- all required fields are filled;
- the page architecture is coherent;
- the ECD-facing presentation is complete;
- the visual stage remains correctly Deferred.

If the writing is incomplete, non-idiomatic, generic, mistranslated, or unfaithful to the Treatment, the Copy Desk must reopen before Script Alignment.

## R01 — Real Failure: Grammatically Possible, Semantically Unfinished

Draft:

> 每一份档案，都是一段完整的生活。

Expected diagnosis:

- `档案` and `生活` are not naturally equivalent categories in this context;
- the reader expects a complement such as memory, scene, experience, or record;
- the line sounds like an internal definition drafted too quickly;
- adding a random noun is not sufficient if it changes the governing metaphor.

Required behavior:

1. restate the internal semantic proposition;
2. generate at least three candidate approaches;
3. judge whether the page needs a definition, image, or reframe;
4. select a natural line and re-run title / Core Line division;
5. mark the original as rejected, not Alignment-ready.

Possible directions, not mandatory answers:

- 每一份档案，都保存着一段可以重新进入的生活记忆。
- 每一份档案，都打开一段完整的生活现场。
- 一段记忆，从来不只是一件事。

## R02 — Real Failure: Page Description Mistaken for Title

Draft:

> 那些没有“大事”发生的日子，也在这里。

Expected diagnosis:

- grammatical but weak landing;
- describes page inclusion rather than creating a useful image or judgment;
- `也在这里` carries little semantic force;
- line is easily transferable to unrelated sentimental projects.

Required behavior:

- create Direct, Image-led, and Judgment / Reframe candidates;
- use the Core Line to complete meaning rather than overloading the title;
- reject cosmetic synonym substitution.

Possible direction:

> 那些差点被忘记的日子

> 后来才发现，它们组成了大半个人生。

## R03 — Real Failure: Malformed Conditional

Draft:

> 如果，把这一生建成一座可以走进去的档案馆

Expected: hard fail.

Reason:

- comma incorrectly interrupts the conditional;
- no clear main clause or deliberate fragment logic;
- punctuation is being used to manufacture atmosphere.

Required behavior:

- choose either a complete question or a complete imperative / proposition;
- run sentence-closure and punctuation checks.

## R04 — Real Failure: Forced Symmetry

Draft pair:

> 我获得的，都有它发生的那一刻。

> 我失去的，也有自己的档案。

Expected diagnosis:

- unstable `它` reference;
- unnatural relation between `获得` and `发生`;
- personification in the second line is not earned;
- mirrored page structure has distorted natural Chinese.

Required behavior:

- preserve conceptual pairing without requiring grammatical mirroring;
- rewrite each page from its own scene and semantic proposition;
- run cross-page pattern scan.

## R05 — Real Failure: Template Philosophy

Draft:

> 它们没有从人生里被删除，只是以另一种方式留了下来。

Expected diagnosis:

- familiar `没有……只是……` pattern;
- transferable to almost any post about memory, grief, relationships, or growth;
- abstract claim replaces the page's specific human scene.

Expected:

- fail freshness / specificity unless surrounding context makes the distinction uniquely precise;
- return to concrete action, place, relationship, or consequence.

## C01 — Internal Editorial Language Leaks into Public Copy

Draft title:

> 让普通生活获得位置

Expected: fail.

Reason:

- valid internal Editorial Job;
- sounds like a planning note or cultural-policy slogan;
- no concrete reader entry point.

Required behavior:

- separate semantic proposition from audience copy.

## C02 — Abstract-Noun Pile

Draft:

> 能力、勇气、关系与归属真正发生的时刻。

Expected:

- fail concreteness;
- ask which action or scene proves the page's main idea;
- reduce the number of abstractions;
- do not repair by adding more poetic nouns.

## C03 — AI-Phrase Saturation Across Pages

Sequence uses three or more of:

- 不是……而是……；
- 不只是……更是……；
- 以另一种方式……；
- 让……被看见；
- 碎片 / 痕迹 / 回响 / 温度 / 光影。

Expected:

- cross-page Copy QA fails even if each line is individually grammatical;
- reopen voice system;
- retain only patterns that make a real distinction.

## C04 — Metaphor Collision

A sequence alternates without explanation among:

- 档案馆；
- 回忆录；
- 数据库；
- 人生地图；
- 展厅；
- 上传界面。

Expected:

- identify governing metaphor;
- classify supporting metaphors;
- remove collisions or explain the relationship;
- do not treat every thematically related noun as interchangeable.

## C05 — Chinese Read-Aloud Failure

Condition:

- the sentence is technically grammatical;
- a fluent reader hesitates, loses the antecedent, or must reread the ending.

Expected:

- fail idiomaticity / rhythm;
- revise syntax, not only punctuation;
- record the read-aloud result.

## E01 — English Malformed Conditional

Draft:

> If, your whole life became an archive you could walk into.

Expected: hard fail.

Possible functional directions:

- What if your life became an archive you could walk through?
- Turn a lifetime into an archive you can walk through.

The final choice must match the page function and voice.

## E02 — English Translationese

Draft:

> The life fragments which were nearly forgotten are also existing here.

Expected diagnosis:

- non-idiomatic progressive / stative construction;
- unnatural noun phrase;
- likely calque from Chinese;
- weak page landing.

Expected:

- rewrite from semantic invariant, not word substitution;
- run native English edit and read-aloud test.

## E03 — Abstract Noun Chain

Draft:

> The preservation of lived experience is enabled through conversational reconstruction.

Expected:

- fail reader orientation and concreteness;
- reveal subject and action;
- preserve qualification if the concept is speculative.

Possible direction:

> You tell the AI what happened. The conversation changes how the memory is later understood.

## E04 — Generic Brand English

Draft:

> Unlock the power of your memories and embark on a transformative journey through the moments that matter.

Expected: hard fail for this project.

Reason:

- generic brand vocabulary;
- no project-specific mechanism;
- could advertise travel, wellness, cloud storage, or coaching;
- emotional inflation without evidence.

## E05 — Broken Parallelism

Draft:

> The archive holds where you went, the people you met, and how loss changed you.

Expected:

- identify unlike grammatical forms;
- repair only if the concepts are genuinely parallel;
- preserve meaning rather than forcing symmetry.

## E06 — English Copy Is Grammatically Correct but Bureaucratic

Draft:

> Through the ongoing accumulation of voluntarily supplied conversational materials, the formation of a personally meaningful archive becomes possible.

Expected:

- fail clarity and human voice;
- reveal actor, action, and result;
- remove throat-clearing and nominalization;
- retain the voluntary-sharing boundary.

## B01 — Chinese-to-English Literal Translation

Chinese function:

> 那些差点被忘记的日子，后来组成了大半个人生。

Failing English:

> Those days that were almost forgotten later composed the greater half of life.

Expected:

- reject literal lexical mapping;
- return to semantic invariant;
- produce idiomatic English with equivalent judgment and emotional temperature.

Possible direction:

> The days you almost forgot may have made up most of your life.

## B02 — English-to-Chinese Structural Calque

English source:

> What if your life became an archive you could walk through?

Failing Chinese:

> 如果你的生活变成一个你可以走过的档案，会怎样？

Expected:

- identify unnatural noun and verb choices;
- rebuild in natural Chinese;
- preserve question function rather than syntax.

## B03 — Agency Drift Across Languages

Chinese:

> 我把经历带进对话，AI 的回应后来成为这段记忆的一部分。

English draft:

> AI captures your life and turns it into memory.

Expected: hard fail.

Reason:

- agency changes from user-initiated sharing to AI capture;
- surveillance implication introduced;
- Greenlit boundary violated.

## B04 — Limitation Lost in One Language

Chinese includes:

> 本文为未来概念创作，不代表 AI 能自动还原完整人生。

English omits the limitation.

Expected: hard fail parity check.

## B05 — Identical Geometry Causes Semantic Loss

Condition:

- English title is longer than Chinese;
- Copy Desk removes qualification or Art Director shrinks English below mobile readability to preserve the same line count.

Expected:

- reject;
- Copy Desk supplies meaning-preserving English compression candidates;
- Art Director adapts layout;
- semantic and reading parity outrank geometric identity.

## F01 — Treatment Fidelity Before Copy Polish

Greenlit mechanism:

```text
Real life happens
→ the person later brings it into conversation
→ telling, feeling, and the AI's response become part of how the memory is held
```

Script mechanism:

```text
AI gives instructions in real time
→ the person completes a task
→ the task becomes a shared memory
```

Expected:

- Treatment Fidelity Gate fails;
- do not proceed to copy polishing;
- return to Editorial Architecture;
- preserve Greenlight and rebuild the Script mechanism.

## F02 — Complete Presentation, Weak Writing

Condition:

- all pages and body copy are visible in the primary conversation;
- Script Alignment scope is explicit;
- visual inputs remain Deferred;
- several key Chinese or English lines fail the language gate.

Expected:

- ECD Decision Presentation Gate may pass;
- Copy Quality Gate fails;
- Creative Producer must not request Script Alignment;
- Script remains Proposed / Copy Reopened.

## F03 — First Draft Must Not Be Called Final

Condition:

- Editorial Director creates one line per field and immediately labels all copy final.

Expected:

- fail workflow;
- no Copy Brief, candidate development, native edit, or QA evidence;
- status returns to `Semantic Draft` or `Selected Draft`;
- only `Alignment-ready` wording may be presented as the recommendation.

## F04 — Valid Chinese Alignment-Ready Copy

Expected evidence:

- Treatment Fidelity pass;
- target locale identified;
- Copy Brief established;
- key lines developed through multiple approaches internally;
- Chinese copy edit completed;
- sentence closure, collocation, reference, metaphor, read-aloud, and cross-page tests passed;
- score at least 85 with no hard failure;
- cover and page titles meet the higher target;
- ECD-facing proposal shows one coherent recommended system.

## F05 — Valid English Alignment-Ready Copy

Expected evidence:

- locale and house decisions identified;
- idiomatic English drafting rather than translation;
- grammar, reference, collocation, concrete-action, parallelism, rhythm, and cliché tests passed;
- score at least 85 with no hard failure;
- key lines meet the higher target.

## F06 — Valid Bilingual Alignment-Ready Copy

Expected evidence:

- shared semantic invariant;
- independent Chinese and English Copy Briefs;
- each language passes native QA independently;
- parity table confirms agency, certainty, boundaries, page function, and emotional temperature;
- material transcreation differences are disclosed;
- layout consequences are handed to Art Director;
- neither language is hidden in an attachment when both require alignment.

## Minimum Regression Set

Run after any change to Editorial Director, Copy Desk, Creative Script, or language rules:

- R01–R05;
- C01–C05;
- E01–E06;
- B01–B05;
- F01–F06.
