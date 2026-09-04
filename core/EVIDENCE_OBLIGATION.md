# Evidence Obligation — V3.2

Constitution clauses: `SEM-011`–`SEM-013`, `SEM-017`, `SEM-049`.

## Purpose

Evidence depth follows the promise the work makes, not merely the existence or popularity of a source.

A conceptual image, an editorial explanation based on a public demonstration, an independently reframed public topic, and a productized workflow offered with a reliability promise are not held to the same proof standard.

Creative Producer records one primary Evidence Obligation during initialization. Individual claims may receive a stricter local obligation.

## Engagement is not validation

Views, likes, saves, reposts, and comments may be used as a Discovery Signal indicating audience interest.

They do not prove that every source claim is correct, reproducible, available, safe, or commercially reliable.

At the same time, the presence of a Discovery Signal does not force independent reproduction or public source commentary when the new publication makes no such claim.

## Modes

### 1. Speculative / Conceptual

Use when the work is primarily:

- imagination;
- metaphor;
- hypothetical example;
- fictional scene;
- concept visualization;
- speculative future;
- creative exploration;
- Concept Reframing that discusses a general idea using independently created examples, language, and visuals without relying on a specific current capability claim.

Required behavior:

- preserve an accurate conceptual, hypothetical, fictional, or speculative position when the audience could otherwise mistake the content for a factual result;
- verify only external factual premises that materially affect meaning;
- do not demand product testing merely because the concept is futuristic or was discovered through a public demonstration;
- distinguish a Discovery Signal from any factual dependency;
- record rights and direct-use limits only for third-party material actually used or materially depended on;
- avoid adding defensive source, non-testing, or concept disclaimers when the publication makes no claim requiring them.

Claim ceiling:

- may state what the work imagines, explores, reframes, explains, or proposes;
- may present independently created examples and visuals as the work's own editorial expression;
- may not imply a specific unverified product capability, reliable operation, or personal experience that the ECD did not establish.

### 2. Evidence-based Editorial

Use when publication materially relies on a real:

- post, demonstration, repository, paper, product, event, dataset, screenshot, interface, news item, or public claim.

Required behavior:

- inspect the relevant original or primary source where available;
- verify only the key facts the public communication actually depends on;
- separate source claim, observed demonstration, independently verified fact, inference, and interpretation;
- record date, version, region, availability, sample, or other material limits when they affect the statement;
- preserve context needed to interpret evidence correctly;
- keep evidence inspectable when the final claim depends on it;
- do not escalate automatically into complete product validation when the publication makes only a narrow editorial claim;
- do not add public attribution or source explanation solely because the topic was discovered elsewhere when source identity is not material to the final claim.

Claim ceiling:

- public language may be no stronger than the verified source and observed evidence;
- a demonstration is not proof of general reliability, availability, safety, or commercial readiness;
- a narrow factual dependency does not require the publication to become a tutorial, review, or reproduction report.

### 3. Product / Commercial Validation

Use when the current project intends to:

- sell or productize a Skill, workflow, product, or service;
- recommend it as reliably usable;
- make a concrete performance, repeatability, compatibility, cost, or operational promise;
- support a purchase, deployment, or other consequential decision.

A future productization idea recorded for later does not activate this mode for a current concept-sharing post that contains no offer or reliability promise.

Required behavior, as applicable:

- validate setup and execution on representative inputs;
- record environment, dependencies, version, access, region, and tool requirements;
- test reproducibility rather than relying on one successful example;
- document failure cases, boundaries, and recovery conditions;
- distinguish upstream creator claims from observed studio results;
- identify cost, time, operational, privacy, security, rights, license, and redistribution constraints;
- define what the offer includes and excludes;
- narrow the public promise when evidence is insufficient.

Claim ceiling:

- a commercial or reliability claim may not exceed observed and reproducible evidence;
- when practical validation cannot be performed, the system must narrow or remove the affected commercial claim rather than relabel source claims as validated performance.

## Concept Reframing overlay

When `profiles/social-editorial/CONCEPT_REFRAMING.md` is active, record the source posture separately from Evidence Obligation:

- `Discovery Signal` — topic discovery only;
- `Factual Dependency` — one or more public statements depend on specific external facts;
- `Direct-use Material` — source expression or assets enter the publication.

Evidence mode follows the final claims, not the source posture alone.

Typical combinations:

- Discovery Signal + independent concept discussion → `Speculative / Conceptual`;
- Discovery Signal + one current product fact → primary `Speculative / Conceptual` with a local `Evidence-based Editorial` override, or primary `Evidence-based Editorial` if the fact dominates;
- Direct-use Material → rights and attribution review regardless of evidence mode;
- current sales or reliability promise → `Product / Commercial Validation` for the affected offer.

Concept Reframing does not require the public text to mention the original creator, say whether the studio tested anything, or explain that visuals are conceptual unless the actual claim or direct-use condition requires it.

## Hybrid projects and local overrides

A project has one primary Evidence Obligation, but individual statements may require a stricter mode.

Examples of valid structure:

- a speculative visual concept built around one current factual premise: primary `Speculative / Conceptual`, with the premise verified as `Evidence-based Editorial`;
- an editorial post that later inspires a separate product idea: the current post remains at its own evidence level; the future product project remains unvalidated until separately commissioned;
- a concept-sharing post using an original example and one directly quoted source sentence: the concept may be `Speculative / Conceptual`, while the quotation receives factual, attribution, and rights treatment.

The stricter obligation governs the affected claim, not necessarily every part of the project.

## Selection test

Producer and Development Director answer:

1. What would a reasonable audience believe after seeing this work?
2. What specific facts, if any, does the final publication depend on?
3. Does the work claim that something is true now, was actually experienced, or works reliably?
4. Is the audience being asked to buy, deploy, trust, or act on a capability?
5. Is the social source only a Discovery Signal, or does its identity / evidence enter the publication?
6. What evidence would be necessary if the actual published claim were challenged?
7. What is the consequence of being wrong?

Choose the lowest mode that fully supports the actual promise. Do not under-validate for speed or over-validate for ceremony.

## Stage consequences

### Development

- records primary mode, source posture, and claim-level overrides;
- commissions Research Verification and Claims Rights only to the depth required;
- limits the Treatment to supportable fact, concept, or commercial position;
- records a future productization idea as Deferred when it is outside the current publication;
- records validation gaps as boundaries or blockers only when they affect the current claim.

### Core Communication Script and Editorial Adaptation

- preserve certainty, speaker position, source context, qualification, attribution, and disclosure only where materially required;
- do not convert a Discovery Signal into a source-centered article unless the ECD chooses that angle;
- do not insert `我们实测`, `我们没有实测`, `概念创作`, or attribution language when the script does not make a claim that needs it;
- do not convert a conceptual or source-claimed result into personal fact or validated capability.

### Visual

- distinguishes evidence, reconstruction, simulation, and concept imagery when that distinction affects audience belief;
- keeps material proof inspectable;
- does not use visual realism to imply a stronger reality status than the approved claim;
- does not add source-facing labels merely because a topic began with a Discovery Signal.

### Production

- preserves required evidence labels, source context, qualifiers, and disclosures;
- does not add defensive notices that are not part of the approved Script;
- does not crop, retouch, or redesign evidence into a materially different claim.

## Evidence Obligation Record

```markdown
# Evidence Obligation Record

Project:
Primary mode:
Reason for mode:
Source posture:
- Discovery Signal
- Factual Dependency
- Direct-use Material
Audience belief / action at stake:
Claim units with stricter local mode:

Required verification:
Required practical validation:
Required rights / license review:
Required attribution / disclosure:
Material date / version / region / sample limits:
Evidence that may remain illustrative only:
Deferred productization or commercial seed:

Public claim ceiling:
Claims prohibited until further evidence:
Validation limitations affecting current publication:
Responsible registered Skills:
Completion evidence:
Status:
```

## Research and validation sufficiency

Research is sufficient when it answers the decision the current project actually needs and constrains the public promise accordingly.

For Concept Reframing with a Discovery Signal and no factual dependency, sufficient work may consist of understanding the topic, separating source-specific expression, and independently developing the new piece. Independent reproduction is not required.

Product / Commercial Validation is sufficient only when:

- representative execution or a documented substitute exists;
- reproducibility and failure boundaries are known to the degree promised;
- dependencies and operational conditions are stated;
- rights and commercial-use conditions are understood;
- public language matches the evidence.

A source article, creator video, engagement count, or one attractive output alone is not product validation.

## Failure routing

- incorrect mode, source posture, or promise → Creative Producer / Development Director;
- missing or stale factual dependency → Research Verification;
- direct-use, license, quotation, attribution, likeness, or implied endorsement → Claims Rights;
- source-specific expression remains in Concept Reframing → Development / Editorial / Visual as appropriate;
- evidence changes the premise → Concept Development;
- public copy exceeds evidence or adds unnecessary defensive explanation → Copywriting / Copy Editing;
- visual proof implies unsupported reality → Visual Department;
- validation cannot support a current commercial promise → Blocked or narrower claim, recorded by Producer.

## Quality gate

Pass only when:

- the Evidence Obligation and source posture are explicit;
- research depth is proportionate to the actual publication;
- engagement signal is not confused with reliability evidence;
- Concept Reframing is not burdened with irrelevant reproduction or attribution work;
- claim-level overrides are recorded;
- fact, source claim, inference, concept, demonstration, simulation, and validated result remain distinct where material;
- the public claim ceiling is usable downstream;
- current validation gaps are disclosed only when they affect the current publication.
