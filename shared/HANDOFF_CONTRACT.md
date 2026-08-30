# Studio Handoff Contract

## Principle

Creative Producer coordinates all authoritative transfers between internal professional modes and maintains Project State.

A receiving owner may interpret the accepted upstream artifact inside its craft, but may not silently rewrite its meaning.

Every handoff must answer:

- what artifact and version is authoritative;
- what the receiving owner is being asked to produce;
- what is locked;
- what remains open to professional interpretation;
- what evidence, rights, reference, surface, and technical conditions apply;
- what issue requires return rather than improvisation.

## Common Handoff Envelope

Use at the depth required by project complexity:

```markdown
From:
To:
Project / state reference:
Authoritative input artifact and version:
Requested output artifact:
Deliverable Contract fields that matter:
Active locks:
Open variables:
Evidence / limitation requirements:
Reference intent and prohibited transfer:
Assets and provenance state:
Production tolerances:
Known risks / blockers:
ECD gate expected:
Return conditions:
```

## Development Handoffs

### ECD → Creative Producer

May provide any spark or existing artifact:

- idea, sentence, link, or public post;
- image, screenshot, visual reference, or product;
- notes, rough copy, research, or data;
- existing Treatment, Script, Board, Design Comp, or final asset;
- feedback or correction.

Creative Producer identifies intended use, valid existing work, and the shortest route. It asks only when an unknown materially affects the outcome.

A general request to create the final deliverable is not itself a handoff into Production when the authoritative Treatment and Greenlight are absent.

### Creative Producer → Research / Verification / Validation

Provide:

- intended use and evidence obligation;
- specific publication or commercial claims at issue;
- source material;
- required date, version, region, or availability context;
- relevant rights, attribution, license, or asset questions;
- practical validation scope when applicable.

Research does not choose the editorial premise or create Script / Storyboard content.

### Research Function → Creative Producer

Return a concise Research Result containing only findings that change or constrain Development or Production:

- verified facts and confidence;
- unresolved claims;
- source and recency notes;
- version / date / region limits;
- rights, attribution, and license conditions;
- validation results and failure conditions;
- claim limits and recommended consequences.

### Creative Producer → Editorial Development

Provide:

- aligned intended use;
- relevant research result;
- reality / imagination / claim boundaries;
- reference intent and rights boundaries;
- existing ECD decisions;
- the precise creative question needing development.

### Editorial Development → Creative Producer

May return:

- premise diagnosis;
- insight and audience-relevance assessment;
- materially different angle options;
- recommendation and core proposition;
- Creative Treatment draft or revision;
- recommendation to validate, pause, reframe, or reject.

Creative Producer synthesizes this for ECD alignment rather than exposing raw internal role switching.

## Greenlight Handoff

Apply `GREENLIGHT_RECORD.md`.

### Creative Producer → ECD

For raw or unresolved input, present in a user-visible response:

- the identified proposed Creative Treatment and version;
- material claim, rights, and reference boundaries;
- only unresolved decisions requiring ECD authority;
- the recommended Greenlight decision;
- what Production will be authorized to do if accepted.

Then request Greenlight / revision / pause / rejection and **end the response**.

Do not append a formal Creative Script, final page sequence, Storyboard, Design Comp, visual prompt, generated image, or other Production artifact. Do not invoke deliverable visual-production tools before the ECD responds.

### ECD → Creative Producer

Greenlight means the ECD accepts the identified Treatment as the production premise and authorizes Production.

The response must be interpretable in relation to that Treatment. A concise “可以”, “继续”, or equivalent is sufficient when it directly answers the Greenlight request. The same words do not establish Greenlight when uttered before any Treatment has been presented or identified.

Creative Producer records:

- Treatment version;
- presentation or prior-artifact reference;
- authorization evidence;
- attached conditions or corrections;
- material locks;
- authorized next stage.

A stage-aware supplied-Treatment override or identifiable prior Greenlight may enter Production without a new presentation turn only under the conditions in `GREENLIGHT_RECORD.md`.

Greenlight does not mean later Script, Storyboard, Design Comp, Art Direction, or final assets are automatically accepted.

### Invalid Greenlight Handoff

Reject the transition when:

- the only evidence is “做一个帖子”, “开始吧”, “直接做”, or equivalent generic production language;
- the Treatment had not yet been shown or explicitly identified;
- Creative Producer or another internal role granted authorization on the ECD's behalf;
- Compact complexity is the reason given for bypass;
- Production work already happened and the studio is attempting to legitimize it retroactively.

## Production Handoffs

### Creative Producer → Editorial Director

Transfer:

- Greenlit Creative Treatment and valid Greenlight Record;
- relevant Deliverable Contract;
- exact names, wording, claims, evidence, and limitations;
- content-relevant reference boundaries;
- ECD decisions that constrain communication;
- valid existing sequence or copy work.

Requested output: an accepted-for-handoff **Creative Script**.

Without a valid Greenlight Record, Editorial Director must return the project rather than start scripting.

### Editorial Director → Creative Producer

Return:

- communication strategy;
- minimum viable sequence;
- page / card / beat roles;
- written Visual Beats;
- final or accepted audience-facing copy;
- evidence, attribution, and limitation placement;
- transitions and payoff logic;
- Script-alignment issue, if material.

No actual Storyboard, generated frame, layout, typography system, or final composition is expected.

### Creative Producer → Art Director

Transfer:

- Creative Script accepted for handoff;
- Greenlit Treatment reference;
- relevant Deliverable Contract and viewing conditions;
- reference intent and prohibited transfer;
- locked copy, assets, names, evidence, and limitations;
- established ECD visual preferences;
- expected visual alignment gate.

Requested outputs:

1. Storyboard / Visual Sequence Board;
2. Representative Design Comp when required;
3. Art Direction Package.

### Art Director → Creative Producer — Storyboard / Visual Sequence Board

Return enough low-cost visual material to evaluate:

- fidelity to every Visual Beat;
- visual differentiation and sequence coherence;
- evidence treatment;
- subject, scale, depth, and image–type relationships;
- reference abstraction;
- high-risk visual questions needing a Design Comp.

### Art Director → Creative Producer — Representative Design Comp

Return one or more high-fidelity representative screens using real copy and target geometry.

The Comp must make actual hierarchy, typography, spacing, image–type relationship, body-page readability, and visual-world direction inspectable.

Creative Producer decides whether the Comp can be accepted for handoff professionally or requires ECD Visual Alignment.

### Art Director → Creative Producer — Art Direction Package

Return:

- accepted visual premise and Comp reference;
- shared visual system;
- screen-by-screen direction;
- asset plan;
- crop, safe-area, and small-size intent;
- production tolerances and forbidden drift;
- technical risks and accepted fallbacks.

### Creative Producer → Production Artist

Transfer:

- Creative Script accepted for handoff;
- relevant Board and accepted Design Comp;
- Art Direction Package;
- Deliverable Contract;
- assets, provenance, and transformation permissions;
- exact locked text, evidence, and limitations;
- technical specifications, variants, tolerances, and fallbacks.

Requested output: final assets plus mobile and technical QA record.

### Production Artist → Creative Producer

Return:

- final assets and variants;
- dimensions, formats, and filenames;
- QA results;
- known limitations;
- any authorized deviations;
- unresolved issue requiring upstream action.

## Return Path

When work cannot continue without changing an upstream decision:

- fact, evidence, validation, rights, or reference-boundary failure → Development Research Function;
- premise, angle, proposition, or public-promise failure → reopen Development;
- absent or invalid Greenlight → Creative Producer returns to Treatment presentation / ECD decision;
- sequence, written Visual Beat, copy, or content-progression failure → Editorial Director;
- Storyboard, Design Comp, visual concept, mood, hierarchy, typography, or composition failure → Art Director;
- crop, overflow, exact dimensions, font implementation, export, or file defect → Production Artist;
- state, authority, Greenlight, routing, or lock problem → Creative Producer.

Do not solve upstream problems through downstream distortion.

## Handoff QA

Reject a handoff when:

- the input artifact has no version or authority state;
- Editorial Director is asked to begin without a valid Greenlight Record;
- required copy is still placeholder text;
- the Art Director must invent missing editorial content;
- Production Artist must invent the visual system;
- evidence or limitation obligations are not located;
- reference use is ambiguous;
- output geometry is unknown when it affects design;
- an unresolved ECD decision is hidden as a craft choice;
- an unauthorized pre-Greenlight artifact is presented as authoritative.
