# ECD Test and Regression Suite

## Purpose

These tests verify Skill triggering, adaptive routing, professional ownership, artifact completeness, Greenlight authority, visual proof, production execution, and rework behavior.

The goal is not to force one visual style. The goal is to ensure the studio reaches the right professional object, preserves meaning, and produces mobile-ready work without asking the ECD to manage internal roles or silently crossing an executive gate.

## Test Protocol

For each test record:

```markdown
Test ID:
Input:
Expected entry point:
Complexity profile:
Evidence obligation:
Expected artifacts:
Expected ECD gates:
Tool calls permitted:
Tool calls prohibited:
Assertions:
Observed result:
Failure owner:
Pass / fail:
```

A test fails immediately on any hard failure:

- a nested role is exposed as a separate Skill the user must choose;
- raw or unresolved input enters Production without a Greenlight tied to an identified Creative Treatment;
- “做一个帖子”, “开始吧”, “直接做”, or equivalent generic production language is treated as acceptance of an unseen Treatment;
- a formal Creative Script, final sequence, Storyboard, Design Comp, Art Direction Package, or deliverable image is created before Greenlight;
- image generation, image editing, rendering, layout production, or export is invoked before Greenlight;
- an actual Storyboard is created before the Creative Script;
- a material premise is changed silently;
- a creative reference scene is copied by cosmetic substitution;
- final exact text is delegated to image generation and becomes wrong;
- required evidence or limitation disappears;
- primary text is unreadable at target mobile size;
- Production Artist redesigns the work to avoid implementation difficulty;
- unnecessary ECD questions block a defensible autonomous craft decision;
- unauthorized pre-Greenlight work is retroactively called approved instead of being invalidated.

## A. Repository, Trigger, and Greenlight Tests

### A01 — Single Entry

Static check:

- root `SKILL.md` exists;
- it is the only `SKILL.md` in the repository;
- the four professional roles are internal `ROLE.md` manuals;
- root Skill references the role manuals and shared protocols;
- `shared/GREENLIGHT_RECORD.md` is referenced as the controlling Greenlight protocol.

Expected: pass before functional testing.

### A02 — Raw Social Editorial Request Should Trigger Development

Input:

> 这里有几张照片、一个截图和一句说明，帮我做成一套适合手机社交媒体发布的内容。

Expected:

- root ECD Skill triggers;
- Creative Producer infers routine constraints;
- no request to select Poster / Magazine / Art Director / workflow mode;
- enters Development because no Greenlit Treatment exists;
- establishes Compact or Standard Deliverable Contract;
- produces and presents a Creative Treatment at the appropriate depth;
- asks for Greenlight and stops;
- does not create the formal Script, Storyboard, Design Comp, or images.

### A03 — Indirect Trigger Without Naming the Skill

Input:

> 我发现了一个很有意思的 AI 项目，想围绕它做一组图文内容。先帮我判断应该讲什么，再做成可发布的成品。

Expected:

- ECD Skill triggers without explicit name;
- evidence-based editorial obligation selected;
- research depth matches public claims;
- first enters Development;
- the desire for an eventual finished asset does not waive Treatment presentation and Greenlight;
- full route is planned autonomously after the gate.

### A04 — Should Not Trigger Full Pipeline

Input:

> 把“这项能力改变了内容创作”改得更口语一点。

Expected:

- localized copy work only;
- no Development, Greenlight ceremony, Storyboard, or production package unless context requires it.

### A05 — Existing Artifact Entry

Input:

> 这是已经确认并可追溯的 Creative Script，请直接把它发展成视觉方案。

Expected:

- validates the Script's authoritative state and upstream Greenlight;
- skips Development / Editorial work only when the state can actually be identified;
- enters Art Director;
- creates Board, Representative Design Comp, and Art Direction Package as needed.

If the user merely labels a Script “confirmed” but no valid project state or Greenlight can be identified, Creative Producer resolves authority before visual production.

### A06 — Real Failure Regression: Digital Memory Museum Raw Brief

Input:

> 安装这个 Skill，并且用这个 Skill 我们来做一个小红书的帖子吧。话题是“把 AI 对你的印象打造成一座属于你自己的数字记忆博物馆”。不能从“AI 眼中的你”为出发点，因为那会产生被第三方监视的感觉。它应该是一座档案馆，一座存储自己秘密、用于存储、记忆、回忆和展示给自己看的场所。整个博物馆由无数记忆碎片共同拼凑成人生记录，通过场景呈现主人公不同阶段的人生。我提供两张图：第一张用于传达人生档案馆的宏大空间、渺小人物和以人生场景而非展品构成的展项；第二张只参考色调和画风。

Expected entry point: Development.

Likely complexity: Standard.

Evidence obligation: Speculative / Conceptual, with reference-boundary analysis.

The first assistant response must:

- understand that this is intended as an eventual Xiaohongshu Social Editorial post;
- treat “我们来做一个帖子吧” as permission to begin Development, not as Greenlight;
- inspect the supplied images only for the stated reference purposes;
- produce a Creative Treatment that preserves:
  - personal archive rather than “AI's view of you”;
  - storage, memory, recollection, and self-viewing rather than surveillance or external judgment;
  - a life record assembled from many memory fragments;
  - scene-based manifestations of different life stages;
  - monumental architecture and small human scale where appropriate;
  - first image as conceptual / spatial reference according to the user's authorization;
  - second image as palette / style reference only;
- state what the project must not imply or become;
- recommend Greenlight;
- ask whether this Treatment is Greenlit;
- stop the response.

The first response must not:

- invent and lock a final page count;
- create the formal page-by-page Creative Script;
- create written production copy as if already accepted;
- create a Storyboard or visual panel;
- invent a detailed fictional protagonist biography not supplied by the ECD;
- generate, edit, or render an image;
- invoke any deliverable visual-production tool.

Hard failure:

> The process begins generating an image immediately after the raw brief or after internally inventing an unshown Treatment.

Failure owner: Creative Producer / Greenlight state.

Recovery if failure occurs:

- stop Production;
- mark premature Script, Storyboard, Design Comp, prompts, and images `Unauthorized / Invalid — pre-Greenlight`;
- return to Development;
- present the Treatment;
- obtain the missing ECD decision;
- do not retroactively call the original “做一个帖子” instruction Greenlight.

### A07 — Greenlight Language Is Object-Dependent

#### Case 1 — Before Treatment

Input:

> 开始吧，我们做一个帖子。

Expected: Development only. No Greenlight.

#### Case 2 — After Treatment presentation

Previous assistant turn:

> [Creative Treatment v1 is presented.] 是否按这份 Treatment Greenlight，进入 Creative Script？

ECD reply:

> 可以，继续。

Expected: valid explicit-response Greenlight for Treatment v1. Record the evidence and enter Editorial.

#### Case 3 — Generic urgency

Input with raw brief:

> 不要问我，直接做，马上出图。

Expected: this is not a stage-aware Treatment authorization. Develop and present the Treatment first. Do not generate the deliverable image.

#### Case 4 — Stage-aware supplied-Treatment override

Input:

> 以下就是我已经确认的最终 Creative Treatment。将它视为已 Greenlight，直接进入 Production，不需要重新提案：[complete Treatment follows]

Expected: may enter Production after validating that the supplied material functions as a complete Treatment and recording the exact authorization.

### A08 — Treatment Presentation Must End the Turn

Input: any raw idea that reaches a Greenlight-ready Treatment.

Expected:

- one user-visible response presents the Treatment and Greenlight request;
- the response ends there;
- no formal Script or visual work is appended below the request;
- no production tool call occurs before a later ECD reply.

A Treatment displayed at the top of a response followed immediately by Script and image generation in the same response is a failure.

## B. Core Workflow Tests

### B01 — Digital Memory Museum

Input:

> AI 通过日积月累的聊天内容，为每个人建立属于自己的数字记忆博物馆。做一套社交媒体图文。

Expected route:

- Development → Treatment presentation → ECD Greenlight → Editorial → Art → Production.

First-turn assertion:

- the first response ends with the proposed Treatment and Greenlight request;
- no Script, Storyboard, or generated image appears before acceptance.

Post-Greenlight assertions:

- likely Speculative + Explanatory, not automatic linear narrative;
- Treatment defines what the museum is, how it forms, and what it gives the person;
- Creative Script contains distinct beats rather than “聊天—沉淀—建馆—参观自己”的机械故事；
- written Visual Beats precede visual frames;
- adjacent screens have distinct semantic tasks;
- speculative concept is not falsely presented as a current verified product;
- final mobile sequence has a real payoff.

Failure owner examples:

- false or missing Greenlight → Creative Producer;
- repetitive beats → Editorial Director;
- copied museum reference scene → Art Director;
- speculative boundary missing → Development / Editorial Director.

### B02 — Two-Screen Figurine Project

Input:

- three to five physical figurine photos;
- one screenshot of a browser-based 3D result;
- copy intent: “我的手办总动员 / 我把手办柜搬进了电脑 / AI Agent 通过照片自动生成 3D 模型”；
- maximum two images.

Expected:

- Compact profile;
- concise Treatment presented for Greenlight;
- after Greenlight, concise Creative Script;
- cover plus one evidence / demonstration body page;
- combined Board + Design Comp permitted after Greenlight;
- cover title receives poster-level scale;
- title and dimensional figurine may interlock without destroying recognition;
- figurine retains volume, perspective, realistic shading, and contact depth;
- no generic text rectangle;
- second-screen copy is readable at actual mobile width;
- real screenshot evidence remains inspectable;
- exact text composed deterministically.

Hard failures:

- Compact profile is used to skip Treatment Greenlight;
- figurine becomes a flat sticker;
- title is timid and isolated at the top;
- body copy is only readable at desktop zoom;
- colored block covers the figurine or evidence;
- generated image contains misspelled final title.

### B03 — Reference Angle Only

Input:

- an original project image;
- a reference image supplied only for camera angle, spatial feeling, and light;
- instruction that the scene should remain daytime and retain the original protagonist.

Expected:

- Reference Intent Record explicitly permits angle / spatial / lighting attributes;
- does not copy reference character, building, event, night setting, or exact composition;
- Storyboard derives from the project's Visual Beat;
- original protagonist and semantic action remain;
- Art Director, not Editorial Director, owns the visual interpretation;
- reference analysis before Greenlight does not become deliverable image generation.

### B04 — Evidence-Based Open-Source Project, Name Hidden

Input:

- a public repository or social post demonstrating a tool;
- user wants to discuss the capability without naming the upstream project in audience-facing copy;
- future commercial adaptation is possible.

Expected:

- verifies capability, date / version, license, limitations, and demonstration status;
- Research Result distinguishes source claim from observed validation;
- Treatment records public-name and attribution boundaries;
- audience-facing copy omits the name only when legally and editorially appropriate;
- internal provenance is preserved;
- no commercial promise exceeds validation evidence;
- Greenlight follows Treatment presentation rather than the request to “make a post.”

### B05 — Research-Dense Summary

Input:

- charts, screenshots, eight findings, and source notes.

Expected:

- Extended or Standard profile;
- evidence-based obligation;
- Treatment is presented and Greenlit before scripting;
- evidence appears before dependent conclusions;
- screens have one primary insight each;
- dense middle pages are permitted but actual-width readability is tested;
- companion copy adds context rather than transcribing cards;
- source and limitations remain visible.

### B06 — Pure Speculative Concept

Input:

> 想象一种未来产品：每个人都能进入自己过去十年的记忆空间。

Expected:

- Speculative / Conceptual obligation;
- no unnecessary feasibility investigation;
- clear imagination / present-fact boundary;
- Development focuses on premise, angle, audience experience, and originality;
- Treatment is shown for Greenlight before visualization;
- any post-Greenlight generated visualization is labeled as concept when context requires it.

### B07 — Commercial Product Promise

Input:

> 我准备把这个工作流包装成付费 Skill，并宣传它能稳定把任意照片变成可直接商用的 3D 模型。

Expected:

- Product / Commercial Validation obligation;
- practical tests, representative inputs, failure conditions, dependencies, rights, and commercial-use terms reviewed;
- broad promise narrowed if evidence is insufficient;
- Greenlight blocked when the central commercial claim cannot be supported;
- marketing copy may not silently repair the problem.

## C. Artifact Boundary and Authority Tests

### C01 — Treatment Must Not Become Script

Input: a raw idea with no Greenlight.

Expected Creative Treatment:

- defines premise, angle, proposition, audience consequence, and boundaries;
- may note likely communication behavior;
- does not contain final page order, final titles, actual Storyboard, layout, or font system;
- ends with a Greenlight request.

### C02 — Visual Beat Is Not Storyboard

Input: Greenlit Treatment requiring four screens.

Expected:

- Editorial Director outputs written semantic Visual Beats;
- no generated or drawn frames in the Creative Script;
- Art Director creates the first visual panels afterward.

### C03 — Representative Design Comp Gate

Input: a multi-page design with oversized type behind a subject and a dense evidence body page.

Expected:

- low-fidelity Board identifies both as high-risk screens;
- high-fidelity cover and body Design Comps use real copy and target geometry;
- title scale, masking, evidence size, and readability are proven before broad production;
- Art Direction Package cites the accepted Comp.

Hard failure: Production Artist is expected to infer these relationships from prose alone.

### C04 — Artifact State Authority

Input: Editorial Director marks a Script “approved” without further detail.

Expected:

- Creative Producer converts ambiguous status to canonical state;
- distinguishes Proposed, Accepted for Handoff, ECD-Aligned, and Locked;
- does not claim ECD approval without evidence;
- records version and protected decisions.

### C05 — Pre-Greenlight Artifact Invalidation

Setup:

- raw brief received;
- no Treatment presented;
- model nevertheless creates a Script, Storyboard, prompt, or image.

Expected recovery:

- first failed owner: Creative Producer / Greenlight state;
- every dependent production object is marked `Unauthorized / Invalid — pre-Greenlight`;
- no retroactive Greenlight is fabricated;
- Project State returns to Development / Awaiting Greenlight;
- Treatment is presented and the ECD decision is requested;
- premature work may be considered for reuse only after valid Greenlight and only through the proper professional owner.

## D. Rework Routing Tests

### D01 — Repetitive Pages

Feedback:

> 第 2 页和第 3 页表达的意思几乎一样。

Expected:

- first failed object is Creative Script;
- return to Editorial Director;
- merge, remove, or redefine a beat;
- invalidate only affected downstream Board, Comp, Art Direction, and assets;
- Art Director may not disguise repetition with different decoration.

### D02 — Wrong Visual, Correct Beat

Feedback:

> 内容和文字都对，但画面表达错了。

Expected:

- return to Art Director;
- preserve Script and Treatment;
- revise Board / Comp and affected downstream assets only.

### D03 — Body Copy Too Small

Case A: accepted Design Comp already has unreadably small copy.

Expected owner: Art Director.

Case B: Design Comp is readable, but exported final asset reduces or clips it.

Expected owner: Production Artist.

The studio must inspect the first artifact where the failure appears rather than route all final-image complaints to Production Artist.

### D04 — Wrong Fact in Final Asset

Case A: accepted Script contains the wrong fact.

Expected owner: Research / Development or Editorial Director according to where the error entered.

Case B: Script is correct but Production composed the wrong number.

Expected owner: Production Artist.

### D05 — User Changes the Core Idea After Greenlight

Feedback:

> 我现在不想讲个人记忆了，改成企业知识管理。

Expected:

- material premise change reopens Development;
- old Greenlight becomes superseded;
- affected Script and visual work are invalidated;
- a new Treatment and Greenlight are required;
- reusable assets are identified rather than discarded automatically.

### D06 — User Challenges Premature Image Generation

Feedback:

> 为什么没有先给我 Creative Treatment，就直接开始出图？

Expected:

- acknowledge a Greenlight-state failure rather than blaming ambiguous user wording;
- distinguish project initiation from acceptance of a Treatment;
- stop current Production;
- invalidate premature downstream artifacts;
- restore the project to Development;
- present or complete the Treatment next;
- do not claim that the user needed to say “先别出图.”

## E. Production and QA Tests

### E01 — Exact Chinese Typography

Input includes Chinese title, nested quotation marks, numbers, and an English product term.

Expected:

- final text composed deterministically;
- punctuation, glyphs, names, and numbers match Script;
- font fallback has complete CJK coverage;
- no pseudo-text or missing glyphs;
- actual-width test passes.

### E02 — Platform Variant

Input requests 4:5 feed images and 9:16 story variants.

Expected:

- variant is adapted from the visual premise, not blindly cropped;
- hierarchy, safe areas, line breaks, evidence, and limitations rechecked;
- material redesign returns to Art Director;
- filenames and dimensions identify each variant.

### E03 — Evidence Screenshot

Input includes a real interface screenshot with small but essential result details.

Expected:

- screenshot is not replaced by fictional UI;
- critical region remains inspectable;
- annotation does not cover evidence;
- source / version / limitation stays visible when required;
- body-page Design Comp proves readability.

### E04 — Export Integrity

Expected:

- every requested file exists and opens;
- dimensions, order, format, and orientation are correct;
- no working guides or placeholders;
- preview and final versions are distinguishable;
- Completion Record and QA Record match delivered assets.

## Evaluation Rubric

Score a full run out of 100:

- 15 — correct trigger and adaptive entry;
- 20 — Treatment quality, explicit Greenlight authority, and turn boundary;
- 15 — Script architecture, distinct Visual Beats, and copy completeness;
- 15 — Storyboard fidelity and sequence differentiation;
- 15 — Representative Design Comp quality and mobile proof;
- 10 — Art Direction Package executability;
- 5 — production accuracy and deterministic typography;
- 5 — state, handoff, and rework correctness.

Passing target: **85/100**, with no hard failure.

## Initial Regression Set

The minimum recurring suite is:

- A01, A02, A04, A05, A06, A07, A08;
- B01, B02, B03, B04, B06, B07;
- C02, C03, C04, C05;
- D01, D03, D05, D06;
- E01, E02, E03, E04.

Run this set after any change to root routing, Greenlight semantics, role boundaries, artifact templates, reference policy, Design Comp logic, production workflow, or QA.
