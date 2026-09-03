---
name: ecd-proofreading
description: Internal Editorial specialist skill for final exact-text verification of approved copy, including Chinese punctuation, names, numbers, dates, quotations, terminology, links, disclosures, glyphs, and cross-page consistency before Script Alignment and final release.
version: 3.1-alpha
---

# Proofreading Skill

## Purpose

Proofreading verifies exact text after writing and copy editing. It does not silently rewrite strategy, structure, voice, or claims.

## Inputs

- complete edited page copy and publication copy;
- authoritative names, terms, numbers, dates, quotations, links, sources, disclosures, and qualifiers;
- language and locale;
- Editorial Director assignment.

## Method

### 1. Establish the authoritative text set

Identify the exact version being proofread and the source of every locked name, number, quotation, and qualifier.

### 2. Verify character-level accuracy

Check:

- missing, repeated, or wrong characters;
- simplified / traditional consistency;
- full-width and half-width punctuation;
- quotation marks and nesting;
- dashes, ellipses, colons, semicolons, and parentheses;
- capitalization and spacing for English, code, brands, and acronyms;
- numerals, units, percentages, dates, times, and versions;
- names, handles, titles, products, and URLs;
- hashtags and platform syntax.

### 3. Verify cross-artifact consistency

Compare:

- page copy against Creative Script;
- repeated terms across pages;
- title against publication copy;
- disclosures and limitations across surfaces;
- source labels and attribution;
- sequence numbering.

### 4. Flag, do not silently solve, substantive issues

If proofreading reveals an ambiguous claim, misleading sentence, wrong speaker position, or structural inconsistency, return it to Copy Editing or the responsible upstream Skill.

### 5. Produce exact final text

Return a clean, copyable version and a correction log.

## Output

```markdown
# Proofreading Return

Project:
Text version reviewed:
Authority sources:
Corrections made:
Names / terminology check:
Numbers / dates / units check:
Quotation / attribution check:
Disclosure / qualifier check:
Cross-page consistency check:
Issues returned upstream:
Clean exact text:
Self-check:
Recommended Director disposition:
```

## Self-check

- Was every page and publication field checked?
- Are all names, numbers, punctuation, and qualifiers exact?
- Does the clean text match the intended language and locale?
- Were substantive issues escalated rather than silently rewritten?

## Final-production role

Before Final Acceptance, Proofreading or Editorial Director must compare the actual exported assets against the exact approved text. A correct source document does not prove the final image contains correct text.
