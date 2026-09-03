---
name: ecd-chinese-copy-craft
description: Internal Editorial specialist skill for native Simplified or Traditional Chinese copy craft, covering sentence integrity, semantic compatibility, collocation, omitted subjects and reference, information focus, register, metaphor, rhythm, punctuation, mixed scripts, and cross-page consistency.
version: 3.1-alpha
---

# Chinese Copy Craft Skill

Constitution clause: `SEM-045`.

## Purpose

This Skill ensures audience-facing Chinese is semantically exact, grammatically complete, idiomatic, rhythmically controlled, and native to the intended locale and platform.

It is not generic polishing, translation cleanup, or visual typography. It works on language before final typesetting and returns to Editorial Director.

## Inputs

- Greenlit Treatment;
- Content Architecture and Frame Scripts;
- complete Chinese Copywriting or Copy Editing draft;
- speaker and reality position;
- claim, evidence, attribution, and disclosure requirements;
- locale, platform, voice, and audience relationship;
- terminology record;
- Editorial Director assignment.

## Method

### 1. Establish locale and house style

Record:

- Simplified or Traditional Chinese;
- target region and audience;
- punctuation, quotation, number, date, unit, and mixed-language conventions;
- formality, spoken quality, and use of internet language;
- terminology and proper-noun rules.

Apply one system consistently. Do not mix conventions accidentally.

### 2. Check sentence integrity

Inspect whether every line contains a stable intended relation:

- conditions and main clauses;
- comparisons and their terms;
- verbs and usable objects;
- definitions and judgments;
- modifier scope;
- omitted subjects;
- punctuation in relation to syntax.

An intentional fragment is valid only when its meaning is supported by the page system. Punctuation cannot substitute for missing grammar.

### 3. Check semantic compatibility

For definitions, metaphors, and judgments, verify:

- category compatibility;
- logical relationship;
- degree of abstraction;
- whether a complement feels unfinished;
- whether a revision introduces a conflicting metaphor;
- whether a dramatic phrase changes the accepted proposition.

### 4. Check natural collocation

Review:

- verb–object combinations;
- adjective–noun combinations;
- measure words;
- adverb–predicate relations;
- connectives and clauses;
- temporal phrases and actions;
- result and directional complements.

A phrase can be grammatically possible and still fail native modern Chinese usage.

### 5. Check subject, reference, and ellipsis

Chinese permits omission, but every omitted subject, pronoun, demonstrative, and temporal reference must remain recoverable in the actual page or caption context.

Restore a noun or relation when a standalone card cannot rely on surrounding paragraphs.

### 6. Control word order and information focus

Place new and decisive information where the reader can find it quickly.

Inspect:

- long preambles;
- nested modifiers;
- delayed predicates;
- unstable topic–comment structure;
- buried negation or qualification;
- whether the sentence ends on the intended weight.

### 7. Separate internal and public language

Rewrite workflow labels, abstract analytical propositions, and system vocabulary into audience-facing language.

Use precise abstract terms when necessary, but do not replace the main human action or relation with stacked abstract nouns.

### 8. Maintain voice and register

Preserve:

- narrative person;
- social distance;
- emotional temperature;
- certainty;
- degree of poetic compression;
- explanatory depth;
- platform appropriateness.

Natural Chinese is not automatically casual. Literary wording is not automatically precise.

### 9. Maintain metaphor discipline

Identify the governing conceptual vocabulary.

Check whether later nouns and verbs extend the same system, deliberately combine compatible metaphors, or accidentally replace the project's central logic.

### 10. Divide copy-layer responsibilities

Confirm distinct functions for:

- title or headline;
- core line or deck;
- supporting copy;
- evidence, source, limitation, or attribution;
- caption body and closing prompt.

Do not repeat one proposition at several sizes.

### 11. Read aloud and test rhythm

Read high-impact lines at natural speed.

Check:

- grammatical and rhetorical pauses;
- breath length;
- stress placement;
- function-word accumulation;
- repeated endings;
- one-hearing comprehension;
- whether the final phrase carries the intended weight.

### 12. Audit the full sequence

Inspect:

- repeated openings and sentence frames;
- repeated contrast structures;
- abstract-vocabulary saturation;
- forced symmetry;
- tonal shifts;
- metaphor drift;
- page titles that merely label sections;
- several pages making the same claim in different words;
- relationship between page copy and publication copy.

### 13. Check mixed scripts

Language craft checks:

- Chinese, Latin, numerals, symbols, product names, and code are semantically and mechanically correct;
- spaces, punctuation, capitalization, units, and terminology are consistent;
- line breaks do not separate names, numbers, qualifiers, or rhetorical units in meaning-damaging ways.

Visual size, baseline, and optical behavior remain Typography responsibilities.

## Output

```markdown
# Chinese Copy Craft Return

Project:
Locale / house style:
Draft reviewed:
Authoritative meaning and speaker position:

Sentence-integrity findings:
Semantic-compatibility findings:
Collocation findings:
Subject / reference findings:
Word-order / focus findings:
Voice / register findings:
Metaphor findings:
Read-aloud findings:
Cross-page findings:
Mixed-script and mechanics findings:

Material edit comparison:
Complete revised Chinese copy:
Terminology decisions:
Issues returned upstream:
Known limitations:
Self-check:
Recommended Editorial Director disposition:
```

## Self-check

- Does every line express a complete and stable relation?
- Are collocations native and precise?
- Are omitted subjects and references recoverable on the actual page?
- Does word order reveal the intended focus?
- Are certainty, speaker position, and claims preserved?
- Are voice and metaphor coherent across the sequence?
- Does the copy read naturally aloud?
- Are locale mechanics and mixed scripts correct?
- Is the language specific to this project rather than generic inspirational prose?

## Failure routing

- accepted meaning or sequence is wrong → Content Architecture or Development through Editorial Director;
- Frame Script cannot support the intended wording → Frame Script;
- speaker, fact, or claim boundary is unresolved → Copy Editing / Development Research or Claims Rights;
- exact typo-only issue → Proofreading;
- visual line geometry or optical mixed-script issue → Typography after Script Alignment.
