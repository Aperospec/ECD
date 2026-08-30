# Greenlight Protocol and Record

## Purpose

Greenlight identifies the exact **Creative Treatment** the Executive Creative Director has authorized and records the evidence of that authorization.

Greenlight is an executive decision about a specific production premise. It is not a generic signal that the user wants something made, and it is not generic approval of later Script, Storyboard, Design Comp, Art Direction, or final assets.

For a raw project, Greenlight opens only the **next professional stage: Creative Script development**. Later-stage inputs and artifacts remain governed by their own activation and handoff conditions.

This file is the controlling Greenlight rule for the ECD Skill.

## Non-Negotiable Object Rule

A Greenlight must point to an identifiable Creative Treatment version or an explicitly supplied equivalent.

The studio may not Greenlight:

- an interpretation that has not been shown to the ECD;
- an unstated premise inferred from raw materials;
- a future Treatment that does not yet exist;
- a topic, mood reference, deliverable request, or collection of notes by itself.

A detailed brief can make Development faster, but detail alone does not convert raw input into an accepted Treatment.

## Cross-Stage Brief Rule

A raw brief may contain information intended for Editorial Director, Art Director, or Production Artist before those stages begin.

Creative Producer must capture those instructions in `STAGE_SCOPED_INPUT_REGISTER.md` and keep their downstream projections Deferred.

Greenlight accepts only:

- the Development-level premise;
- selected angle and core proposition;
- audience takeaway;
- Development-level semantic guardrails;
- factual, speculative, rights, claim, and reference-use boundaries required to authorize the premise.

Greenlight does **not** accept or activate merely because they appeared in the same original brief:

- final page count or sequence;
- final titles or body copy;
- user-supplied Editorial Seeds as a finished Script;
- a Storyboard or concrete scene design;
- palette, lighting, camera, style, typography, or composition interpretation;
- a Representative Design Comp;
- Art Direction;
- deliverable image generation or production execution.

A user-supplied downstream **Hard Constraint** remains authoritative as a future-stage instruction, but it is not the same thing as approval of the downstream artifact that will later implement it.

## Normal Turn Boundary

For raw or unresolved input, Greenlight normally requires two separate conversational steps:

```text
Assistant turn
- present the proposed Creative Treatment;
- identify material Development boundaries and unresolved conditions;
- optionally state which downstream inputs were preserved as Deferred;
- state that Greenlight will authorize Creative Script development next;
- state what remains unaccepted after Greenlight;
- ask for Greenlight / revision / pause / rejection;
- stop.

Later ECD turn
- accept, revise, pause, or reject the identified Treatment.
```

The response that presents a new Treatment is a hard stop. Do not create or commission Production artifacts in that same response.

A short answer such as “可以”, “继续”, “通过”, “就按这个做”, or “Greenlight” may be sufficient only when it clearly answers the immediately preceding Greenlight request for the identified Treatment.

## What Does Not Count as Greenlight

Before a specific Treatment has been presented or identified, the following are project-initiation or Development instructions only:

- “做一个帖子”;
- “我们来做吧”;
- “开始吧”;
- “帮我做成小红书图文”;
- “设计一组图”;
- “直接做”;
- “出图吧” when no Treatment has yet been accepted;
- equivalent verbs expressing desired output, speed, or urgency.

These statements show that the user wants a project or deliverable. They do not show acceptance of the studio's still-unseen angle, proposition, boundaries, or interpretation.

Do not infer Greenlight from:

- Compact complexity;
- a small number of screens;
- a highly detailed raw brief;
- supplied visual references;
- the user's willingness to begin;
- the absence of an explicit instruction to stop before Production.

The user is not required to say “先别出图” or “先不要立项.” The gate is the studio's responsibility.

## Valid Greenlight Forms

### 1. Explicit response to a presented Treatment

The ECD accepts a specific Treatment after it has been shown and submitted for Greenlight.

Record:

- Treatment version / reference;
- presentation turn / reference;
- exact or concise authorization evidence;
- material conditions or corrections included in the response.

### 2. Identified prior Greenlight

The ECD directs the studio to continue from a previously Greenlit Treatment and that prior artifact and decision can be identified.

Do not rely on vague claims such as “之前已经定了” when no authoritative artifact can be located. Resolve the state before Production.

### 3. Stage-aware supplied-Treatment override

The ECD may intentionally bypass a new presentation turn only by explicitly doing both:

1. identifying supplied material as the final / approved Creative Treatment or its professional equivalent;
2. explicitly authorizing Production from that exact premise.

Example:

> “以下内容就是我已经确认的最终 Creative Treatment。将它视为已 Greenlight，直接进入 Production，不需要重新提案。”

This exception preserves ECD authority over workflow. Generic “直接做”, “开始”, or “不用问我” language does not satisfy it because it does not identify the authoritative Treatment being accepted.

Even under this override, later-stage inputs are activated in order unless the ECD separately supplies and authorizes an already accepted downstream artifact.

## Complexity Rule

Compact, Standard, and Extended projects use the same Greenlight authority and stage-scope rules.

Complexity changes only:

- Treatment length;
- record detail;
- whether adjacent post-Greenlight artifacts may be combined;
- how much evidence and state documentation is required.

Complexity never authorizes acceptance of an unseen premise or activation of a later professional stage before its handoff condition.

## Pre-Greenlight Hard Prohibition

Before Greenlight, allowed work includes:

- intake and consequential assumption recording;
- Deliverable Contract drafting;
- Stage-Scoped Input Register creation;
- research, verification, and validation;
- supplied-image inspection;
- reference-intent and rights analysis;
- Editorial Development;
- Creative Treatment drafting and revision.

Before Greenlight, do not create, commission, or invoke tools for:

- formal Creative Script;
- final page / card / beat sequence;
- final audience-facing production copy;
- Storyboard / Visual Sequence Board;
- Representative Design Comp;
- Art Direction Package;
- deliverable image generation or image editing;
- visual rendering, layout composition, production export, or final assets.

Research image discovery or inspection is permitted when needed, but it must not become deliverable visual production.

Any Production artifact created before Greenlight is unauthorized. Mark it invalid, preserve it only as failure evidence if useful, and return Project State to Development / Awaiting Greenlight.

## Post-Greenlight Activation Rule

After valid Greenlight:

1. mark the accepted Treatment decisions and Greenlight boundaries authoritative;
2. activate Deferred **Editorial** projections in the Stage-Scoped Input Register;
3. keep Visual / Art Direction and Production projections Deferred;
4. set the authorized next stage to `Editorial Director → Creative Script`;
5. do not start Storyboard, Design Comp, image generation, or visual production until the Creative Script is Accepted for Handoff and any required Script Alignment is resolved.

The correct Greenlight consequence is:

> “This Treatment is now authoritative. Next, develop the Creative Script using the Activated Editorial inputs.”

An incorrect consequence is:

> “This authorizes the Creative Script and visual production.”

## Greenlight Record Template

```markdown
# Greenlight Record

Project:
Date:
Creative Treatment version / reference:
Treatment presentation turn / reference:
Greenlight authority: Executive Creative Director
Greenlight form: [explicit response to presented Treatment / identified prior Greenlight / stage-aware supplied-Treatment override]
Authorization evidence:
Conditions or corrections attached to authorization:
Stage-Scoped Input Register reference:

## Accepted Development Premise

Core premise:
Selected angle:
Core proposition:
Audience takeaway:
Why the project is proceeding:

## Authoritative Development Boundaries

- factual / speculative boundary:
- public claim / promise boundary:
- required evidence / limitation:
- reference-use / rights boundary:
- must preserve semantically:
- must not imply or become:

## Deferred Inputs Not Accepted by This Greenlight

Editorial input IDs awaiting activation:
Visual / Art Direction input IDs remaining Deferred:
Production input IDs remaining Deferred:
User-supplied downstream Hard Constraints preserved for later activation:

## Open but Non-Blocking Questions

- 

## Stage Authorization

Authorized next stage: Editorial Director / Creative Script
Editorial inputs activated:
Visual inputs remain Deferred: [yes]
Production inputs remain Deferred: [yes]
Material ECD Script Alignment expected later:
Material ECD Visual Alignment expected later:
What is not yet accepted:

## State

Greenlight state: [Greenlit / conditional Greenlight / reopened / superseded]
Recorded by Creative Producer:
Editorial Production may begin: [yes / no]
Visual Production may begin: [no unless a separately accepted Script / downstream artifact authorizes entry]
```

## Compact Record

For a simple project, shorten the record without weakening evidence or stage scope:

```markdown
Greenlit Treatment summary and version:
Authorization evidence:
Stage Input Register:
Material Development locks:
Editorial input IDs activated:
Visual / Production input IDs still Deferred:
Authorized next stage: Creative Script
```

A concise record is valid. An inferred decision or all-stage authorization is not.

## Conditional Greenlight

Use only when a non-premise condition can be resolved during Editorial Production without changing what the project fundamentally is.

Do not use conditional Greenlight to hide:

- an unverified central claim;
- unresolved rights to an essential concept or asset;
- a disputed core proposition;
- uncertainty about what the project is actually saying;
- an absent ECD decision on the Treatment.

Conditional Greenlight does not waive later stage activation conditions.

## Reopening Greenlight

Reopen Development when a proposed change materially alters:

- premise;
- angle;
- proposition;
- public position or promise;
- factual / speculative boundary;
- essential rights or reference foundation;
- audience takeaway.

When reopening, re-project affected source inputs in the Stage-Scoped Input Register and record which downstream artifacts become invalid and which remain reusable.

## Gate QA

Reject a claimed Greenlight when:

- no Treatment version or equivalent is identified;
- the alleged authorization predates presentation of the premise it supposedly accepts;
- the evidence is only a generic request to make or start the project;
- the studio treated silence as consent;
- Compact complexity was used as the reason to bypass the decision;
- Production artifacts were created before the gate;
- an internal professional role granted Greenlight on the ECD's behalf;
- the Greenlight record says it authorizes immediate visual production from a raw brief;
- Deferred Editorial or Visual instructions are recorded as already accepted downstream artifacts;
- the Stage-Scoped Input Register is absent for a material cross-stage brief.
