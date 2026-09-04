# Wave 4 — Core Communication Script and Concept Reframing

Audit ID: `ECD-SPA-001`

Status: `source-level implementation prepared; installation and behavior verification pending`

Target version: `ECD Studio OS V3.2 / 3.2-alpha`

Parent Runtime before Wave 4:

`2185d2b57ab7b1d45b540e200bbd78bffe161229`

## Scope

Wave 4 addresses two general semantic defects discovered during live project testing and subsequent ECD clarification.

### F-007 — The actual communication progression was confirmed too late

Earlier behavior:

- Greenlight approved the Treatment-level concept;
- Editorial then generated the first actual story, argument, explanation, demonstration, comparison, procedure, or thematic progression together with page architecture, Frame Scripts, exact page copy, and publication copy;
- the ECD therefore first judged the underlying progression only after several dependent artifacts existed;
- rejection of the progression could invalidate most of the Editorial package.

General invariant:

> A decision that controls several dependent professional artifacts must be exposed and confirmed before high-cost dependent elaboration begins.

Wave 4 implementation:

- adds `core/HIGH_LEVERAGE_DECISIONS.md`;
- adds registered Skill `ecd-core-communication-script`;
- retains Greenlight before Core Script development;
- separates the actual communication progression from page adaptation;
- adds conditional `Core Script Alignment` after Greenlight and before Content Architecture, Frame Scripts, exact page copy, and publication copy;
- permits a combined Core Script + Creative Script Alignment only when dependency and invalidation risk are genuinely low;
- preserves the Greenlit Treatment when a Core Script is rejected unless the requested change alters Development-level authority;
- adds V3.1-to-V3.2 recovery that preserves valid work and marks only dependent page artifacts provisional or stale.

Affected semantic clauses:

- `SEM-005`–`SEM-008`;
- `SEM-025`;
- `SEM-035`–`SEM-036`;
- `SEM-043`–`SEM-044`;
- new `SEM-048`.

Primary implementation:

- `core/HIGH_LEVERAGE_DECISIONS.md`;
- `departments/editorial/skills/core-communication-script/SKILL.md`;
- `departments/editorial/SKILL.md`;
- `departments/editorial/skills/content-architecture/SKILL.md`;
- `departments/editorial/skills/frame-script/SKILL.md`;
- `core/RUNTIME_STATE_MACHINE.md`;
- `core/AUTHORITY_AND_DECISION_OBJECTS.md`;
- `core/DECISION_RESOLUTION_PROTOCOL.md`;
- `profiles/social-editorial/DECISION_OBJECTS.md`.

### F-008 — Discovery sources were treated too defensively

Earlier risk:

- a popular social post used to discover a topic could trigger broad factual, attribution, non-testing, concept-art, or commercial-validation language even when the new publication did not rely on the source's expression or claim reproduction;
- the resulting public copy could become source-centered, defensive, or conspicuously over-explanatory;
- future productization mentioned as an idea could incorrectly raise the current concept-sharing post to Commercial Validation.

ECD clarification:

- the intended workflow is to identify a public topic, independently rewrite the idea, use independently conceived examples or materials, and create original visuals;
- ordinary concept sharing is not a tutorial, reproduction report, or claim that the studio tested the source method;
- the final publication should not mention the original author or add defensive disclaimers unless the ECD requests it or the actual factual / direct-use / rights condition requires it.

General invariant:

> Topic discovery, factual dependency, and direct use are different source relationships. A Discovery Signal may remain backstage while the studio independently develops and publishes its own expression.

Wave 4 implementation:

- adds `profiles/social-editorial/CONCEPT_REFRAMING.md`;
- adds source posture: `Discovery Signal`, `Factual Dependency`, `Direct-use Material`;
- treats engagement as a topic-selection signal, not reliability evidence;
- does not require independent reproduction when the current publication makes no reproduction or reliability claim;
- does not automatically insert creator attribution, source links, inspiration language, testing / non-testing statements, concept-art disclaimers, infringement disclaimers, or future productization language;
- activates verification, attribution, or rights controls only when the final work has a material factual dependency, direct use, applicable rights / platform condition, audience-interpretation need, or explicit ECD instruction;
- requires independent angle, Core Script, examples, copy, and visuals rather than sentence-level paraphrase or structural / visual copying;
- keeps future productization as a Deferred seed until separately commissioned.

Affected semantic clauses:

- `SEM-011`–`SEM-017`;
- `SEM-047`;
- new `SEM-049`.

Primary implementation:

- `profiles/social-editorial/CONCEPT_REFRAMING.md`;
- `profiles/social-editorial/ENTRY_ROUTER.md`;
- `profiles/social-editorial/PROFILE.md`;
- `core/EVIDENCE_OBLIGATION.md`;
- `core/REFERENCE_CONTRACT.md`;
- `core/STAGE_SCOPED_INPUT_REGISTER.md`;
- Development Director and Claims / Rights Skills;
- Core Communication Script, Copywriting, and Copy Editing Skills;
- Creative Producer and Project State.

## Version and capability effect

Wave 4 advances the Runtime from `3.1-alpha` to `3.2-alpha`.

Expected installed Skill entries:

- 1 root Skill;
- 1 Creative Producer Skill;
- 4 Department Director Skills;
- 23 Specialist Skills;
- total: 29 `SKILL.md` entries.

New registered capability:

- `ecd-core-communication-script`.

## Migration rule for active V3.1 projects

When an active project already has Greenlight and a page-level Creative Script but no Core Script authority:

1. preserve Greenlight, Treatment, source, research, evidence, and rights work that remains valid;
2. extract the proposed actual progression into a Core Communication Script candidate;
3. apply the High-Leverage Decision test;
4. if Separate Alignment is required, mark dependent Content Architecture, Frame Scripts, page copy, and publication copy provisional rather than authoritative;
5. request Core Script Alignment;
6. after approval, reuse dependent material that remains faithful and rebuild only affected parts;
7. do not request Greenlight again unless the Core Script feedback changes the accepted project premise or boundaries.

## Verification required

Wave 4 is not behavior-certified until tests demonstrate:

- Greenlight approval advances to Core Communication Script rather than directly to page adaptation on a high-leverage project;
- the Core Script object shows the actual communication, not another synopsis;
- rejecting a Core Script does not invalidate unrelated Treatment or source work;
- a low-dependency project may validly combine Core Script and Creative Script scopes without hiding the Core Script;
- Discovery Signal Concept Reframing does not produce default attribution, source explanation, non-testing language, concept disclaimer, or productization language;
- factual dependencies and direct-use materials still trigger their necessary controls;
- the resulting work is independently structured, written, and visualized.

Primary tests:

- `evals/semantic/WAVE4_CORE_SCRIPT_AND_REFRAMING.md`;
- `SREG-24` and `SREG-25` when incorporated into the main semantic suite.
