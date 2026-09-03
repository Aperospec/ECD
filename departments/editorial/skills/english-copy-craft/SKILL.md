---
name: ecd-english-copy-craft
description: Internal Editorial specialist skill for native English copy craft, covering locale, sentence integrity, agency, idiom, collocation, articles, reference, modifier placement, parallelism, register, rhythm, translation smell, mechanics, and cross-page consistency.
version: 3.1-alpha
---

# English Copy Craft Skill

Constitution clause: `SEM-045`.

## Purpose

This Skill ensures audience-facing English is precise, idiomatic, reader-oriented, rhythmically controlled, and native to the intended locale.

It is not literal translation, generic proofreading, or visual typography. It works on language before final typesetting and returns to Editorial Director.

## Inputs

- Greenlit Treatment;
- Content Architecture and Frame Scripts;
- complete English Copywriting or Copy Editing draft;
- speaker and reality position;
- claim, evidence, attribution, and disclosure requirements;
- locale, audience, platform, voice, and house style;
- terminology record;
- Editorial Director assignment.

## Method

### 1. Establish locale and house style

Record:

- en-US, en-GB, or intentionally global English;
- spelling, punctuation, quotation, capitalization, date, number, and unit conventions;
- serial-comma decision;
- formality and contraction policy;
- terminology and proper-noun rules.

Apply the selected convention consistently.

### 2. Check sentence integrity

Inspect:

- independent and dependent clauses;
- conditionals and results;
- comparisons and their terms;
- subject–verb agreement;
- transitive verbs and objects;
- fragments, run-ons, and comma splices;
- punctuation in relation to syntax.

A display fragment is valid only when its relation is unmistakable in the page system.

### 3. Clarify agents and actions

Make the grammatical spine easy to locate.

Prefer visible subjects and active verbs when they clarify responsibility, cause, or movement. Use passive voice when the receiver or result is genuinely more important than the actor.

Do not allow nominalization or abstract noun chains to hide the main action.

### 4. Check idiom and collocation

Review:

- verb–noun combinations;
- prepositions;
- articles;
- count and mass nouns;
- phrasal verbs;
- adjective order;
- compound forms;
- conventional idioms and their implied meaning.

Grammatical acceptability is not sufficient when a native editor would naturally choose different wording.

### 5. Check pronouns and reference

Every pronoun, demonstrative, relative clause, and elliptical reference must have a stable antecedent in the actual page or caption context.

A social card may require a repeated noun that a long paragraph could omit.

### 6. Check modifier placement and scope

Place modifiers next to what they modify.

Inspect introductory phrases, restrictive terms, temporal phrases, stacked relative clauses, and modifiers that could attach to more than one noun or action.

### 7. Use parallelism deliberately

Use compatible grammatical forms for genuinely parallel ideas. Do not force symmetry across concepts that require different syntax or emphasis.

### 8. Control voice and register

Preserve:

- person and point of view;
- social distance;
- emotional temperature;
- certainty;
- formality;
- sentence length and contraction use;
- degree of rhetorical compression.

Natural English is not synonymous with casual English.

### 9. Control sentence stress and rhythm

Use word order, sentence length, clause structure, and endings to control emphasis.

Read high-impact lines aloud and inspect:

- stress placement;
- breath and clause length;
- one-hearing comprehension;
- function-word or consonant congestion;
- whether the ending lands on the intended idea;
- whether the rhythm sounds translated rather than native.

### 10. Divide copy-layer responsibilities

Confirm distinct functions for:

- headline;
- core line or deck;
- support;
- evidence, source, limitation, or attribution;
- body copy and closing prompt.

The headline need not carry the entire explanation. Repetition among layers signals weak hierarchy.

### 11. Run the translation-smell test

When a source language exists, check whether English inherited:

- source-language word order;
- missing or overused articles;
- topic–comment structure that obscures the English subject;
- repetitive parallel syntax;
- abstract nouns where English would prefer verbs;
- idioms chosen for lexical similarity rather than function;
- unnatural certainty or politeness.

When translation smell remains, return to the shared semantic brief and rewrite natively.

### 12. Audit the full sequence

Inspect:

- repeated openings and sentence frames;
- repeated rhetorical contrasts;
- keyword and adjective saturation;
- tonal shifts;
- metaphor drift;
- inconsistent capitalization and mechanics;
- several pages making the same proposition;
- relationship between card copy and publication copy.

### 13. Check mixed scripts and terminology

Verify product names, acronyms, code, numerals, units, non-English terms, and proper nouns for spelling, capitalization, spacing, punctuation, and semantic consistency.

Visual mixed-script behavior remains a Typography responsibility.

## Output

```markdown
# English Copy Craft Return

Project:
Locale / house style:
Draft reviewed:
Authoritative meaning and speaker position:

Sentence-integrity findings:
Agency and action findings:
Idiom / collocation findings:
Article / countability findings:
Reference / modifier findings:
Parallelism findings:
Voice / register findings:
Rhythm / read-aloud findings:
Translation-smell findings:
Cross-page findings:
Mechanics / terminology findings:

Material edit comparison:
Complete revised English copy:
Terminology decisions:
Issues returned upstream:
Known limitations:
Self-check:
Recommended Editorial Director disposition:
```

## Self-check

- Are grammar and punctuation structurally sound?
- Are agents, actions, comparisons, and references clear?
- Are idiom, collocation, articles, and prepositions native to the locale?
- Does modifier placement preserve meaning?
- Are voice, certainty, and speaker position faithful?
- Does the copy read naturally aloud?
- Has translation smell been removed?
- Are mechanics and terminology consistent across the sequence?
- Is the language specific to this project rather than generic marketing English?

## Failure routing

- accepted meaning or sequence is wrong → Content Architecture or Development through Editorial Director;
- Frame Script cannot support the wording → Frame Script;
- fact, speaker, or claim boundary is unresolved → Copy Editing / Development Research or Claims Rights;
- exact typo-only issue → Proofreading;
- visual line geometry or mixed-script optics → Typography after Script Alignment.
