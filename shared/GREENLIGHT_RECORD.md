# Greenlight Protocol and Record

## Purpose

Greenlight identifies the exact **Creative Treatment** the Executive Creative Director has authorized for Production and records the evidence of that authorization.

Greenlight is an executive decision about a specific production premise. It is not a generic signal that the user wants something made, and it is not generic approval of later Script, Storyboard, Design Comp, Art Direction, or final assets.

This file is the controlling Greenlight rule for the ECD Skill.

## Non-Negotiable Object Rule

A Greenlight must point to an identifiable Creative Treatment version or an explicitly supplied equivalent.

The studio may not Greenlight:

- an interpretation that has not been shown to the ECD;
- an unstated premise inferred from raw materials;
- a future Treatment that does not yet exist;
- a topic, mood reference, deliverable request, or collection of notes by itself.

A detailed brief can make Development faster, but detail alone does not convert raw input into an accepted Treatment.

## Normal Turn Boundary

For raw or unresolved input, Greenlight normally requires two separate conversational steps:

```text
Assistant turn
- present the proposed Creative Treatment;
- identify material boundaries and unresolved conditions;
- state what Greenlight will authorize;
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

## Complexity Rule

Compact, Standard, and Extended projects use the same Greenlight authority rule.

Complexity changes only:

- Treatment length;
- record detail;
- whether adjacent post-Greenlight artifacts may be combined;
- how much evidence and state documentation is required.

Complexity never authorizes acceptance of an unseen premise.

## Pre-Greenlight Hard Prohibition

Before Greenlight, allowed work includes:

- intake and consequential assumption recording;
- Deliverable Contract drafting;
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

## Accepted Production Premise

Core premise:
Selected angle:
Core proposition:
Audience takeaway:
Why the project is proceeding:

## Authoritative Boundaries

- factual / speculative boundary:
- public claim / promise boundary:
- required evidence / limitation:
- exact names / wording:
- reference-use boundary:
- rights / attribution condition:
- deliverable / scope condition:
- must preserve:
- must not imply or become:

## Open but Non-Blocking Questions

- 

## Production Authorization

Authorized next stage:
Material ECD alignment expected later:
What is not yet accepted:

## State

Greenlight state: [Greenlit / conditional Greenlight / reopened / superseded]
Recorded by Creative Producer:
Production may begin: [yes / no]
```

## Compact Record

For a simple project, shorten the record without weakening the evidence rule:

```markdown
Greenlit Treatment summary and version:
Treatment presentation or supplied-Treatment reference:
Authorization evidence:
Material locks:
Open non-blocking issue:
Authorized next stage:
```

A concise record is valid. An inferred decision is not.

## Conditional Greenlight

Use only when a non-premise condition can be resolved during Production without changing what the project fundamentally is.

Do not use conditional Greenlight to hide:

- an unverified central claim;
- unresolved rights to an essential concept or asset;
- a disputed core proposition;
- uncertainty about what the project is actually saying;
- an absent ECD decision on the Treatment.

## Reopening Greenlight

Reopen Development when a proposed change materially alters:

- premise;
- angle;
- proposition;
- public position or promise;
- factual / speculative boundary;
- essential rights or reference foundation;
- audience takeaway.

Record which downstream artifacts become invalid and which remain reusable.

## Gate QA

Reject a claimed Greenlight when:

- no Treatment version or equivalent is identified;
- the alleged authorization predates presentation of the premise it supposedly accepts;
- the evidence is only a generic request to make or start the project;
- the studio treated silence as consent;
- Compact complexity was used as the reason to bypass the decision;
- Production artifacts were created before the gate;
- an internal professional role granted Greenlight on the ECD's behalf.
