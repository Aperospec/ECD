# Capability Registry — V3.1

This file is the only authority for what professional capabilities exist in the V3 runtime.

A Director may not claim that a Skill was used unless its path is listed here as `Implemented`, the Skill was available in the installed runtime, and an inspectable Specialist Return was produced.

## Core / orchestration

| Capability | Registered name | Path | Status |
|---|---|---|---|
| Creative Producer | `ecd-creative-producer` | `core/creative-producer/SKILL.md` | Implemented |

## Development Department

| Capability | Registered name | Path | Status |
|---|---|---|---|
| Development Director | `ecd-development-director` | `departments/development/SKILL.md` | Implemented |
| Creative Strategy | `ecd-creative-strategy` | `departments/development/skills/creative-strategy/SKILL.md` | Implemented |
| Concept Development | `ecd-concept-development` | `departments/development/skills/concept-development/SKILL.md` | Implemented |
| Research Verification | `ecd-research-verification` | `departments/development/skills/research-verification/SKILL.md` | Implemented |
| Claims and Rights Review | `ecd-claims-rights` | `departments/development/skills/claims-rights/SKILL.md` | Implemented |

## Editorial Department

| Capability | Registered name | Path | Status |
|---|---|---|---|
| Editorial Director | `ecd-editorial-director` | `departments/editorial/SKILL.md` | Implemented |
| Content Architecture | `ecd-content-architecture` | `departments/editorial/skills/content-architecture/SKILL.md` | Implemented |
| Frame Script | `ecd-frame-script` | `departments/editorial/skills/frame-script/SKILL.md` | Implemented |
| Copywriting | `ecd-copywriting` | `departments/editorial/skills/copywriting/SKILL.md` | Implemented |
| Copy Editing | `ecd-copy-editing` | `departments/editorial/skills/copy-editing/SKILL.md` | Implemented |
| Chinese Copy Craft | `ecd-chinese-copy-craft` | `departments/editorial/skills/chinese-copy-craft/SKILL.md` | Implemented |
| English Copy Craft | `ecd-english-copy-craft` | `departments/editorial/skills/english-copy-craft/SKILL.md` | Implemented |
| Bilingual Transcreation | `ecd-bilingual-transcreation` | `departments/editorial/skills/bilingual-transcreation/SKILL.md` | Implemented |
| Proofreading | `ecd-proofreading` | `departments/editorial/skills/proofreading/SKILL.md` | Implemented |

## Visual Department

| Capability | Registered name | Path | Status |
|---|---|---|---|
| Art Director | `ecd-art-director` | `departments/visual/SKILL.md` | Implemented |
| Visual Concept | `ecd-visual-concept` | `departments/visual/skills/visual-concept/SKILL.md` | Implemented |
| Storyboard / Sequence | `ecd-storyboard-sequence` | `departments/visual/skills/storyboard-sequence/SKILL.md` | Implemented |
| Editorial Design | `ecd-editorial-design` | `departments/visual/skills/editorial-design/SKILL.md` | Implemented |
| Typography | `ecd-typography` | `departments/visual/skills/typography/SKILL.md` | Implemented |
| Image Direction | `ecd-image-direction` | `departments/visual/skills/image-direction/SKILL.md` | Implemented |
| Design Critique | `ecd-design-critique` | `departments/visual/skills/design-critique/SKILL.md` | Implemented |

## Production Department

| Capability | Registered name | Path | Status |
|---|---|---|---|
| Production Director | `ecd-production-director` | `departments/production/SKILL.md` | Implemented |
| Image Production | `ecd-image-production` | `departments/production/skills/image-production/SKILL.md` | Implemented |
| Finished Art | `ecd-finished-art` | `departments/production/skills/finished-art/SKILL.md` | Implemented |
| Production Typesetting | `ecd-production-typesetting` | `departments/production/skills/production-typesetting/SKILL.md` | Implemented |
| Technical QA | `ecd-technical-qa` | `departments/production/skills/technical-qa/SKILL.md` | Implemented |

## Not implemented

The following capabilities are not part of V3.1 and must not be claimed as used:

- dedicated Information Design Skill;
- dedicated Motion / Interaction Direction Skill;
- dedicated Photography Direction Skill;
- dedicated Illustration Direction Skill;
- dedicated Retouch-only Skill;
- dedicated Asset Management Skill;
- native-language craft Skills beyond the registered Chinese and English capabilities.

When one of these is materially required, Producer must either:

1. route the problem through the closest implemented Skill and disclose the limitation; or
2. stop at a genuine capability blocker rather than pretending the capability exists.

## Capability selection rule

Registration makes a method available. It does not make the method mandatory for every project.

Creative Producer and Department Directors must apply `core/ADAPTIVE_ROUTING.md`:

- route active professional questions before named Skills;
- reuse authority-complete evidence;
- omit irrelevant methods;
- record why a Skill was selected, combined, or omitted;
- preserve required review and authority even when execution seats are combined.

## Capability-use record

Every Department Cleared package includes:

```markdown
Registered Skills used:
- name:
  version:
  professional question:
  task:
  artifact:
  method evidence:
  self-check result:

Skills considered but omitted:
- name:
  professional question absent or already resolved:
  reason omitted:

Combined execution seats:
- methods combined:
  evidence kept distinct:

Missing capability or limitation:
```

## Registration check

After installation, the root Skill must verify that every `Implemented` entry is discoverable. If one is not registered or readable, mark it `Unavailable in runtime` for that project and do not claim it was used.
