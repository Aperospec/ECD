# Stage-Scoped Input Regression Suite

## Purpose

These regressions verify that one natural-language ECD brief may safely contain information for multiple professional stages without either premature execution or later instruction loss.

Use together with root `TESTS.md`.

## Hard Failures

A run fails immediately when any of the following occurs:

- the entire raw brief is flattened into the Creative Treatment regardless of stage;
- a visual preference supplied early becomes an Art Direction lock during Development;
- a detailed palette, lighting, camera, typography, or composition extraction is performed before Visual activation when the ECD did not explicitly supply those details;
- Greenlight is described as authorization for both Creative Script and visual production;
- Storyboard, Design Comp, image generation, or visual rendering starts immediately after Greenlight before the Creative Script is Accepted for Handoff;
- a Deferred Editorial / Visual / Production input is forgotten;
- the ECD is asked to repeat an instruction already preserved in the Stage-Scoped Input Register without a material reason;
- an Assistant Inference is silently upgraded into a Hard Constraint or user preference;
- Art Director receives only a Development paraphrase when the original ECD visual instruction / reference is available;
- acceptance of a Development projection is treated as acceptance of another stage's projection from the same source statement.

## S01 — Cross-Stage Digital Memory Museum Raw Brief

Input:

> 安装这个 Skill，并且用这个 skill 我们来做一个小红书的帖子吧，话题是“把 AI 对你的印象打造成一座属于你自己的数字记忆博物馆”，不能从“AI眼中的你”为出发点，因为这句话会让所有人都觉得有一个第三方在一直盯着自己、一直在监视着自己。我们应该把它变成一座档案馆，一座存储了自己所有秘密的场所。它只是起到存储、记忆、回忆、展示给自己看这样的作用，而不是“某某眼中的我”。所以整个博物馆应该是一个通过无数记忆碎片共同拼凑出的人生记录，记录了我人生中的点点滴滴和各种各样的场景。所以我们更多的其实是表现一些场景，通过场景画面来呈现出主人公不同阶段的人生。我给你提供了两张图，其中一张应该能传达出我想要表达的人生档案馆的感觉，建筑非常宏大，人很小，里面的展项不是展品，而是场景，人生不同时刻的场景。另外我提供一张图，是我喜欢它的色调，画风。

Expected internal decomposition:

### Global / Deliverable — Active

- Xiaohongshu Social Editorial post.

### Development — Active

- private memory archive rather than “AI's view of you”;
- AI is not observer / judge / personality authority;
- archive functions as storage, memory, recollection, and self-viewing;
- memories together form a life record without claiming complete truth;
- life scenes, not conventional exhibit objects, are the semantic unit;
- surveillance / external judgment framing is prohibited.

### Editorial — Deferred

- express the concept through scenes;
- use different stages / moments of the protagonist's life as content seed;
- memories form a larger life record;
- do not invent a detailed biography unless Editorial development and ECD authority support it.

### Visual / Art Direction — Deferred

- monumental architecture;
- small human figure;
- scene-based exhibits inside the archive;
- reference A for archive-space / scale / conceptual feeling according to ECD intent;
- reference B for color / visual-style preference only;
- do not copy reference-specific subjects, events, paths, buildings, or exact compositions unless separately authorized.

Expected first assistant response:

1. establish Development state;
2. produce Creative Treatment only from Active Development projections;
3. optionally show a concise `Deferred Inputs Recorded — Not Part of This Greenlight` notice;
4. keep Deferred notice close to the ECD's wording;
5. do **not** decide exact page count, final titles, final scenes, protagonist biography, palette values, lighting recipe, camera plan, typography, composition, or Storyboard;
6. ask whether the Treatment is Greenlit;
7. state that Greenlight authorizes **Creative Script development next**;
8. state that visual inputs remain Deferred;
9. stop.

Expected good Deferred Notice example:

```text
Editorial inputs recorded for post-Greenlight activation:
- scene-based expression of different life stages / moments.

Visual inputs recorded for later Art Direction:
- monumental architecture and small protagonist;
- scene-based exhibits;
- Reference A for archive-space / scale concept;
- Reference B for color / style preference.
```

Hard failure example:

```text
Reference A = blue-gray + ivory + warm gold, high cool skylight, hand-painted concept-art grain.
```

Fail unless those exact attributes were explicitly stated by the ECD. That extraction belongs to Art Director after Visual activation.

## S02 — Greenlight Activates Editorial Only

Previous assistant turn:

- Creative Treatment v1 presented;
- Deferred Editorial and Visual inputs recorded;
- ECD asked for Greenlight.

ECD reply:

> Greenlight，就按这份 Treatment 继续。

Expected next state:

```text
Treatment v1 → Greenlit / authoritative
Editorial input IDs → Activated
Visual input IDs → Deferred
Production input IDs → Deferred
Next owner → Editorial Director
Next artifact → Creative Script
```

Expected assistant work:

- produce Creative Script using the Activated Editorial inputs;
- determine communication mode, sequence, written Visual Beats, on-screen copy, and companion copy;
- explicitly avoid “AI眼中的你” framing;
- use the scene-based life-record idea as an Editorial Seed with professional judgment;
- record whether page count / sequence / fictional content creates a material Script Alignment need.

Must not:

- generate images;
- create Storyboard / Design Comp;
- perform final palette / lighting / style extraction;
- claim that the earlier Greenlight already accepted the visual direction.

Hard failure:

> “Greenlight confirmed; I’ll now write the Script and generate the cover / storyboard.”

## S03 — Script Alignment Before Visual Activation When Material

Suppose Creative Script introduces:

- six final screens;
- a fictional protagonist represented at childhood, adolescence, adulthood, and old age;
- specific headline system and life-event progression not explicitly supplied by the ECD.

Expected:

- Editorial Director flags the invented biography / durable progression as material;
- Creative Producer presents Script consequence for ECD Script Alignment;
- Visual inputs remain Deferred until the Script is aligned / Accepted for Handoff;
- no Storyboard or image generation occurs while Script Alignment is pending.

If the Script only makes routine craft decisions within explicit ECD constraints, Creative Producer may accept it for handoff without unnecessary ceremony.

## S04 — Visual Inputs Activate From Original Source

Preconditions:

- Treatment Greenlit;
- Creative Script Accepted for Handoff;
- material Script Alignment resolved.

Expected activation:

```text
Visual input IDs → Activated
Production input IDs → Deferred
Next owner → Art Director
```

Art Director must receive:

- original ECD statements about monumental architecture / small human scale;
- original reference images;
- original statement of each reference's intended use;
- reference prohibition boundaries;
- authority class for each visual input;
- accepted Creative Script and Visual Beats.

Art Director may now professionally extract:

- palette;
- light behavior;
- materiality;
- atmosphere;
- scale;
- camera / composition temperament;
- typography compatibility.

But only from attributes authorized by the ECD's reference intent.

Hard failure:

- Art Director receives only the Treatment sentence “人生足够广阔” and loses the actual monumental-building / small-person visual preference;
- or Art Director copies reference-specific scene events because the original reference boundary was lost.

## S05 — No Re-Ask of Stored Inputs

After Greenlight and Script handoff, assistant asks:

> 你希望建筑是宏大还是亲密？人物要大还是小？第二张参考图你到底想参考色调还是构图？

Expected: fail, because those instructions were already present in the registered source brief.

Correct behavior:

- carry the stored inputs forward automatically;
- ask only if a new conflict or ambiguity emerges from the accepted Script.

## S06 — Cross-Stage Projection Does Not Share Acceptance

ECD source:

> “建筑非常宏大，人很小。”

Treatment v1 uses Development projection:

> “让个人生命本身显得足够辽阔。”

ECD Greenlights Treatment v1.

Expected:

- Development meaning becomes authoritative;
- Visual projection remains Deferred but preserved;
- Greenlight is not recorded as acceptance of the Art Director's future exact scale, lens, crop, architecture, or composition.

## S07 — User Visual Hard Constraint Versus User Preference

Case A:

> “建筑必须非常宏大，人物必须保持很小，这是不可改的。”

Expected:

- Visual projection authority class = Hard Constraint;
- status = Deferred before visual activation;
- after Script handoff it activates and Art Director must preserve it;
- ECD still has not accepted the complete downstream composition merely by Greenlighting the Treatment.

Case B:

> “我喜欢宏大建筑、小人物的感觉，你可以判断是否适合。”

Expected:

- authority class = User Preference;
- Art Director may professionally adapt after activation;
- material departure or competing direction may require ECD Visual Alignment depending on consequence.

## S08 — Assistant Inference Cannot Become User Authority

ECD source:

> “我喜欢这张图的色调、画风。”

During Development the assistant infers:

> “可能是青灰 + 米白 + 少量暖金。”

Expected:

- if recorded before visual activation, this is `Assistant Inference`, not `User Preference` or `Hard Constraint`;
- it may not appear in Treatment as something the ECD chose;
- after visual activation Art Director may test, revise, or reject the inference against the actual reference.

## S09 — Downstream Input Survives Treatment Revision

ECD revises Treatment premise but does not withdraw the earlier reference preferences.

Expected:

- affected Development projection becomes Superseded / revised;
- unrelated Deferred Visual projection remains valid unless the new premise creates a conflict;
- Producer does not discard all deferred inputs merely because Treatment version changed.

## S10 — Conflict at Activation Time

Early brief:

> “整体要安静、温暖。”

Later Greenlit Treatment:

> “最终应产生明显的不安和疏离感。”

Expected:

- when Visual input activates, register marks Conflict rather than silently choosing one;
- Creative Producer decides whether this is a Development contradiction, a deliberate tonal arc, or a visual interpretation question;
- ECD is involved only if the conflict materially changes the accepted project meaning.

## S11 — Production Input Activates Last

Raw brief includes:

> “最终要 1080×1440 PNG，另外给一个 9:16 版本。”

Expected:

- output requirements may enter Deliverable Contract immediately;
- implementation-specific Production projection remains Deferred until Art Direction Package Accepted for Handoff;
- Art Director knows target surfaces because geometry affects design;
- Production Artist receives Activated variant / export requirements only at Production handoff;
- the studio does not export files before accepted visual direction exists.

## S12 — Full Multi-Turn Expected Path

Turn 1 ECD: raw cross-stage brief.

Assistant turn 1:

```text
Development understanding
→ Creative Treatment v1
→ Deferred Input Notice
→ Greenlight request
STOP
```

Turn 2 ECD:

> Greenlight.

Assistant turn 2:

```text
Greenlight Record
→ activate Editorial inputs
→ Creative Script
→ if material, Script Alignment request
STOP before visual work when alignment is required
```

Turn 3 ECD:

> Script 方向确认。

Assistant turn 3:

```text
Script Accepted for Handoff
→ activate Visual inputs
→ Storyboard / Visual Sequence Board
→ Representative Design Comp / visual-direction proposal
→ if material, Visual Alignment request
STOP before broad Production when alignment is required
```

Turn 4 ECD:

> 视觉方向确认。

Assistant turn 4:

```text
Art Direction Package accepted
→ activate Production inputs
→ Production Artist
→ final assets
→ mobile / technical QA
→ ECD Final Acceptance
```

The exact number of turns may compress when no material alignment is required, but **stage activation order may not be compressed into an earlier authority state**.

## Evaluation

A stage-scoped run passes only when:

- all material raw inputs are registered;
- active / deferred classification is correct;
- original source and authority are preserved;
- Greenlight accepts only the Treatment;
- Editorial inputs activate after Greenlight;
- Visual inputs activate after Script handoff;
- Production inputs activate after Art Direction handoff;
- no previously supplied instruction is lost or unnecessarily re-requested;
- no Assistant Inference is promoted to ECD authority;
- stage-local ECD alignment is used only when material;
- final assets can be traced back through resolved registered inputs.