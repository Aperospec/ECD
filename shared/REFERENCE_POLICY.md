# Reference Policy

## Purpose

This is the single authoritative policy for editorial, visual, product, and design references across ECD.

References may supply evidence, context, permissions, or abstractable creative qualities. They do not automatically become content to reproduce.

Reference handling is also **stage-scoped**. A reference may be received during Development while its detailed visual interpretation remains Deferred until Art Director is activated.

Use together with `STAGE_SCOPED_INPUT_REGISTER.md`.

## First Determine Reference Intent

Creative Producer must identify why the reference was supplied. Possible intents include:

- factual source or evidence;
- product / interface / repository being discussed;
- asset authorized for direct use;
- mood or atmosphere reference;
- lighting or color relationship;
- materiality or texture;
- spatial scale or depth;
- camera feeling or composition temperament;
- typography character or image–type relationship;
- workflow or interaction reference;
- quality benchmark;
- negative example.

Do not assume that everything visible in a reference is intended for transfer.

## Stage-Scoped Reference Handling

### During Development

Allowed:

- identify the reference class;
- preserve the ECD's stated intended use;
- determine ownership / rights / attribution / direct-use boundaries;
- record prohibited transfer;
- identify a Development-level semantic consequence when the reference genuinely affects the project premise;
- register later visual interpretation as Deferred.

Do not perform detailed Art Direction extraction merely because the reference is available.

If the ECD says:

> “这张图我喜欢它的色调、画风。”

Development should record:

> Reference intent: color and visual style. Detailed extraction deferred to Art Director.

Development should not silently upgrade that into:

> blue-gray + ivory + warm gold, high cool skylight, hand-painted concept-art grain

unless the ECD explicitly supplied those qualities or Development needs one of them for a material premise decision.

### During Editorial

Editorial Director may use a reference only when:

- it is evidence required by the content;
- its semantic content was explicitly authorized as an Editorial input;
- a Greenlit meaning depends on it.

Editorial Director must not consume Deferred visual attributes to pre-decide palette, camera, lighting, typography, or composition.

### During Art Direction

After the Creative Script is Accepted for Handoff and Visual inputs are activated, Art Director receives:

- the original reference asset;
- the original ECD reference instruction;
- authority class;
- approved reference intent;
- prohibited transfer;
- rights / attribution state.

Art Director may then professionally extract and test the authorized visual attributes.

### During Production

Production Artist uses only assets, transformations, and reference consequences authorized by accepted Art Direction plus Activated Production constraints.

## Reference Classes

### A. Source / Evidence

Use to support factual claims, show observed output, or establish provenance. Preserve date, version, region, and limitation where material.

### B. Authorized Content Asset

A supplied image, screenshot, logo, product rendering, or other asset may be reproduced or transformed only to the extent authorized and legally permitted.

Record:

- ownership or source;
- permitted use;
- permitted transformation;
- attribution requirement;
- prohibited alteration;
- publication or commercial limits.

### C. Creative Attribute Reference

May inform abstract qualities such as:

- mood;
- atmosphere;
- emotional temperature;
- lighting behavior;
- color relationships;
- materiality;
- spatial scale;
- depth;
- grain and surface behavior;
- composition temperament;
- typography compatibility;
- rhythm.

Unless separately authorized as content, it does not authorize transfer of the specific subject, person, character, building, object, product, pose, prop, event, exact camera, exact crop, exact composition, logo, symbol, or distinctive branded device.

The list above defines what may be extracted **after the relevant stage activates**. It is not permission for Development to extract every visible attribute immediately.

### D. Structural / Interaction Reference

May inform information hierarchy, navigation behavior, interaction sequence, or workflow logic. Do not copy proprietary expression, branded interface details, or content beyond what is necessary and permitted.

### E. Negative Reference

Defines what the work must avoid. Record the failure dimension precisely rather than importing unrelated traits.

## Governing Creative Relationship

```text
OUR GREENLIT TREATMENT
→ OUR CREATIVE SCRIPT AND WRITTEN VISUAL BEATS
↓ Script Accepted for Handoff
ACTIVATE AUTHORIZED VISUAL REFERENCE INPUTS
+
ORIGINAL REFERENCE ASSET
→ ORIGINAL STORYBOARD AND DESIGN COMP
```

Not:

```text
RAW REFERENCE
→ DEVELOPMENT-ERA ART DIRECTION
→ RE-SKINNED COPY
```

## Reference Intent Record

Use when references materially affect the project:

```markdown
Reference:
Source / owner:
Original ECD instruction:
Reference class:
Why it was supplied:
Authority class:
Current stage status: [Active Now / Deferred / Activated / Resolved / Superseded / Rejected / Conflict]
Development-level consequence, if any:
Detailed visual extraction status: [not active / active / resolved]
Approved qualities or content after activation:
Specific elements authorized for direct use:
Required attribution:
Prohibited transfer:
Version / date / region limit:
Commercial-use limit:
Open rights question:
Activation condition:
Receiving owner:
```

## Role Responsibilities

### Creative Producer

Clarifies intended use, preserves the original reference instruction, records stage projection and authority, manages activation, and obtains ECD decisions when rights or creative intent are material.

### Research Function

Verifies source, claims, ownership, license, attribution, and practical constraints when required. It does not write the Creative Script or perform Art Direction extraction.

### Editorial Director

Derives content and written Visual Beats from the Greenlit Treatment plus Activated Editorial inputs. It may require evidence from a reference but must not adopt a reference scene or Deferred visual attribute as original content without activation and authorization.

### Art Director

After visual activation, applies only the authorized reference attributes to original visual solutions derived from the Creative Script. It should use the original ECD reference instruction rather than relying on a Development paraphrase.

### Production Artist

Uses only authorized assets and transformations. It must preserve attribution, logos, UI evidence, or exact source behavior when the Deliverable Contract requires them.

## Similarity and Distinctiveness Check

Before accepting a Storyboard or Design Comp influenced by a creative reference, ask:

- Was this reference attribute actually authorized for visual use?
- Would a reasonable viewer recognize the reference's specific scene, character, object arrangement, branded device, or exact composition?
- Did the work abstract qualities, or merely replace surface details?
- Does the original concept still work if the reference is removed?
- Are protected or distinctive elements essential, or were they copied for convenience?

When similarity risk is material, revise the visual concept rather than relying on disclaimers.

## Evidence Integrity

When a screenshot, output, chart, document, or comparison carries proof:

- do not replace it with decorative imagery;
- do not crop away material limitations;
- do not imply independent validation when only a source claim exists;
- preserve source context required for correct interpretation;
- label simulation, reconstruction, or speculative visualization when relevant.

## Reference QA

Before each relevant handoff, confirm:

- intended reference use is explicit;
- original ECD instruction is preserved;
- current-stage status is correct;
- detailed visual extraction did not occur before Visual activation unless explicitly Development-relevant;
- direct-use assets have known permission status;
- prohibited transfer is recorded;
- attribution and license obligations are visible downstream;
- original Visual Beats came from the Treatment and Activated Editorial inputs;
- Art Director received the original visual reference context;
- Storyboard and Design Comp do not reproduce a source scene by cosmetic substitution;
- evidence references remain credible and legible.
