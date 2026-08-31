# Copy Quality Gate

## Purpose

This gate determines whether audience-facing Chinese or English copy is ready to enter an ECD-facing Creative Script Proposal.

A Script may have correct page architecture and still fail because the language is unfinished, unnatural, generic, translated, or unfaithful to the Greenlit Treatment.

Copy quality is therefore a separate professional gate.

## Two-Gate Model

### Gate A — Treatment Fidelity

Before judging style, confirm that the copy still expresses the Greenlit project.

Check:

- governing creative mechanism;
- subject and agency;
- audience takeaway;
- factual / speculative boundary;
- required exclusions;
- relationship among page examples and the core proposition.

If the Script has become another project, stop. Do not polish it.

### Gate B — Language Craft

After fidelity passes, judge the copy in the target language and locale.

A sentence that is technically understandable but not idiomatic, complete, or publishable fails.

## Required Status

Copy may use these states:

- `Semantic Draft`;
- `Candidate Drafts`;
- `Selected Draft`;
- `Copyedited`;
- `Alignment-ready`;
- `Reopened`.

Only `Alignment-ready` copy may be presented as the recommended final wording in a Script Alignment request.

## Hard Failures

Any hard failure blocks Alignment regardless of score.

### Cross-language hard failures

- copy changes the Greenlit Treatment's governing mechanism;
- the main line is grammatically or semantically incomplete by accident;
- audience copy contains internal strategy or workflow language;
- subject, agency, certainty, negation, or limitation is wrong;
- several pages repeat the same proposition with different nouns or examples;
- title and Core Line contradict or merely duplicate each other;
- a governing metaphor collides with another metaphor and changes the concept;
- a key line is generic enough to fit unrelated projects unchanged;
- first-draft wording is submitted without a native-language edit;
- an ECD correction is explained away instead of incorporated into a new Script version;
- the ECD must repair a basic sentence before evaluating the idea.

### Chinese hard failures

- incomplete conditional, comparison, or judgment;
- unnatural collocation or semantic category mismatch;
- unstable pronoun or omitted subject affecting meaning;
- punctuation used to hide malformed syntax;
- forced symmetry producing unnatural Chinese;
- template-like AI phrasing carrying the page's main meaning.

### English hard failures

- unintended fragment, comma splice, malformed conditional, or agreement error;
- clearly non-idiomatic collocation or translationese in a key line;
- unclear pronoun antecedent;
- abstract noun chain replacing the main action;
- mixed locale mechanics;
- generic brand cliché carrying the main idea.

### Bilingual hard failures

- one version changes agency, promise, or certainty;
- required limitation appears in only one language;
- one version is a literal calque rather than idiomatic copy;
- one language is made shorter by deleting necessary meaning;
- layout parity is achieved through unreadable type or semantic loss.

## Scoring Rubric

Score each target-language version out of 100.

| Dimension | Weight | Question |
|---|---:|---|
| Treatment fidelity | 20 | Is this still the Greenlit project, with correct subject, agency, mechanism, and boundary? |
| Semantic precision and completeness | 15 | Does every line say a complete, stable, accurate thing? |
| Grammar, usage, and punctuation | 15 | Is the language mechanically correct for its locale? |
| Idiomaticity and collocation | 15 | Would an experienced native editor accept the wording as natural? |
| Specificity and concreteness | 10 | Does the copy use this project's people, actions, relations, and images rather than generic abstractions? |
| Copy hierarchy | 10 | Do title, Core Line, support, and body copy divide the work effectively? |
| Voice, metaphor, and rhythm | 10 | Is the language coherent, readable aloud, and consistent in emotional temperature and metaphor? |
| Freshness and non-template quality | 5 | Does the wording avoid generic AI, brand, and pseudo-literary patterns? |

Passing threshold:

- overall: **85 / 100**;
- Treatment fidelity: at least **17 / 20**;
- idiomaticity and collocation: at least **12 / 15**;
- no hard failure.

For cover lines, page titles, final payoff lines, and platform titles, target **90 / 100**.

## Evaluation Procedure

### 1. Meaning check

Write the intended meaning in plain internal language.

Compare the audience line against it.

### 2. Native-language edit

Apply the Chinese or English craft protocol.

Do not self-certify based on fluency alone.

### 3. Read-aloud check

Read high-impact lines at natural speed.

Record any hesitation, ambiguity, false stress, or translation rhythm.

### 4. Cross-page pattern scan

Count:

- repeated openings;
- repeated grammatical frames;
- repeated contrast formulas;
- repeated abstract nouns;
- repeated metaphors;
- repeated claims.

### 5. Substitution test

Replace project nouns with unrelated topics.

If the line remains usable without revision, it is likely generic.

### 6. Bilingual parity check

When applicable, compare both versions by function and meaning rather than word count.

### 7. Final selection

Select one coherent copy system. Do not assemble the final Script from individually clever lines that belong to different voices.

## Copy QA Record

Maintain internally:

```markdown
# Copy QA Record

Project:
Script version:
Language / locale:
Copy Brief reference:
Treatment fidelity result:

| Line / section | Status | Main issue | Revision | Score | Hard failure |
|---|---|---|---|---:|---|
| | | | | | |

Cross-page pattern findings:
Metaphor consistency:
Read-aloud result:
Bilingual parity result:
Overall score:
Hard failures remaining:
Copy status:
Ready for Script Alignment: [yes / no]
```

The worksheet normally remains backstage. The ECD-facing Script includes only a concise Copy QA summary.

## ECD-Facing Copy QA Summary

Before Script Alignment, disclose:

```text
Language / locale:
Copy status: Alignment-ready
Native-language copy edit: pass
Treatment fidelity: pass
Cross-page repetition: pass / note
Metaphor and voice consistency: pass / note
Bilingual parity: pass / not applicable
Material copy invention requiring alignment:
```

Do not present a numeric score as proof that weak writing is good. The score is a diagnostic and release threshold.

## Reopening Rules

### Localized line defect

When one line has a grammar, collocation, rhythm, or clarity problem but the page proposition is correct:

- reopen Copy Desk only;
- preserve page architecture and Visual Beat;
- revise related title / Core Line / support as a unit;
- re-run cross-page pattern checks.

### Systemic voice defect

When several lines sound generic, translated, pseudo-literary, or inconsistent:

- reopen the Copy Brief and whole copy system;
- do not patch isolated synonyms;
- generate new candidate directions;
- re-edit the full sequence and body copy.

### Treatment-fidelity defect

When language reveals that the Script is telling the wrong project:

- return to Editorial Director's architecture;
- preserve Greenlit Treatment;
- rebuild the affected beats before writing new copy.

## Release Standard

Creative Producer must not request `Script Alignment` until:

- the Script passes Treatment Fidelity;
- every visible line is Copyedited;
- key lines pass the higher threshold;
- complete body copy passes the same voice and language standard;
- bilingual versions pass independently when required;
- the ECD-facing proposal displays only Alignment-ready recommended copy.
