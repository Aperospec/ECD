# Visual Intent and Reference Regression

## Purpose

These tests verify that Art Director treats natural-language visual judgment and supplied images as professional research inputs rather than direct production prompts.

Apply:

- `../art-director/references/visual-problem-framing.md`;
- `../art-director/references/visual-intent-elicitation.md`;
- `../art-director/references/reference-reading-and-transfer.md`;
- `../art-director/references/ecd-friendly-visual-alignment.md`;
- `../shared/STAGE_SCOPED_INPUT_REGISTER.md`.

## Hard Failures

- user is told their wording is too vague because it lacks art terminology;
- reference and one sentence trigger a final-looking batch;
- “I like this image” is treated as approval of all visible attributes;
- Art Director asks the ECD to write the image prompt;
- generic questions such as “what style and colors?” appear before professional analysis;
- reference roles are not separated;
- source observation, Art Director inference, and ECD authority are merged;
- the original ECD wording is lost;
- a reference liked for structure dictates content, composition, and style;
- six images are generated before the visual problem is framed.

## V01 — Real-Failure Input: Life Archive as Life Amusement World

Input state:

- Creative Script is Accepted for Handoff;
- visual inputs are active;
- ECD supplies a detailed mountain amusement-world image;
- ECD says the image content is excellent, amusement elements fit the life archive, and the life archive is effectively a life amusement world.

Expected first response:

1. register the source statement as Reference Intent + Creative Seed + Aesthetic Judgment;
2. state that it is sufficient to begin visual development but not broad production;
3. create a concise Visual Problem Statement;
4. provide an initial hypothesis such as:
   - the value is one coherent explorable world;
   - layered routes, regions, ascent, descent, return, density, and warm lived activity matter;
   - the visual goal is not a commercial park poster;
5. cite visible evidence in the reference;
6. distinguish transferable principles from source-specific content;
7. identify the principal misread risk;
8. ask no more than three to five plain-language questions if material;
9. state the next low-cost proof;
10. generate no final batch.

Expected prohibited transfer:

- exact mountain silhouette;
- rides and cable-car combination;
- attraction signage and brands;
- shops / souvenir logic;
- exact composition;
- tourism-ad framing.

## V02 — Reference Role Separation

Input:

> 第一张图我喜欢它的世界结构；第二张图只参考色调和画风；第三张图只是不想要的人物近景效果。

Expected register:

- Reference A: World-Structure / Concept;
- Reference B: Color-Light / Style;
- Reference C: Negative Reference;
- roles remain distinct;
- no content or composition transfer from B;
- no positive transfer from C beyond the diagnosed failure dimension.

Hard failure: all three are merged into a generic mood board or one production prompt.

## V03 — “This Feels Right” Without Specialist Vocabulary

Input:

> 这张图就是对的，但我说不出来为什么。

Expected:

- Art Director observes first;
- forms a hypothesis using visible evidence;
- paraphrases in ordinary language;
- asks the ECD to confirm or correct the hypothesis;
- uses comparison or laddering if needed;
- does not demand terms such as spatial topology, value grouping, focal hierarchy, or lens.

## V04 — Aesthetic Rejection

Input:

> 我不知道专业上哪里不对，但它看起来很廉价。

Expected:

- register Aesthetic Judgment;
- identify observable causes and likely categories;
- distinguish concept, genre association, composition, material, lighting, and execution;
- ask only unresolved subjective questions;
- do not dismiss the feedback as non-actionable.

## V05 — Triadic Comparison

Inputs:

- Route A: world-led, layered, explorable;
- Route B: abstract institutional archive;
- Route C: character-led cinematic memory scene.

ECD says:

> A 和 C 比较接近，B 太冷；但 C 又太像电影剧照。

Expected professional translation:

- preserve world-led structure from A;
- retain lived warmth, not C's character dominance;
- reject institutional distance;
- define character as evidence of use rather than primary subject;
- source response and translation recorded separately.

## V06 — New Reference During Art Direction

Input:

- Concept Route already selected;
- ECD introduces a new image and says it better captures the world structure.

Expected:

- register new source input;
- classify role and materiality;
- determine whether Visual Problem, Reference Reading, Concept Route, Storyboard, or anchors reopen;
- preserve unaffected work;
- no direct batch generation from the new image.

## V07 — Routine Visual Preference

Input:

> 这个已经确认的版式里，阴影稍微柔和一点。

Expected:

- no unnecessary full elicitation ceremony;
- classify as routine Art Direction / production-tolerance request when it does not alter the visual premise;
- apply or route to the correct owner;
- preserve existing alignment.

## Evaluation

Pass when the studio:

- treats ordinary-language judgment as valid;
- performs professional interpretation before execution;
- preserves source authority;
- separates reference roles;
- asks only material, understandable questions;
- produces a diagnostic next step rather than a batch.
