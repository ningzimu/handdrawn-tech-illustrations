# Prompt Patterns

Use one image generation call per final image.

## Friendly Style Lock

```text
Friendly Chinese handdrawn technical article illustration.
Very light near-white warm paper around #FBFAF5, no full-page border, no frame.
Rounded, friendly dark graphite ink and pencil linework, slightly playful but controlled, soft hatching.
Article-style technical explainer composition: one clear visual idea plus purposeful annotations, callouts, micro-panels, or comparison zones.
Warm pastel marker accents: pale blue, sage green, pale peach, soft lavender, light yellow when useful.
Clear Chinese handwritten labels, short notes, and normal small annotations.
Approachable technical article feeling, slightly cartoon-like, richer than a single doodle, lighter than a standalone information poster, not a dense whiteboard or generic business infographic.
Avoid shadows, gradients, neon, sticker decorations, SaaS cards, editorial card layout, large mascot characters, watermark, fake English, filler text, invented labels.
```

## 16:9 Body Illustration Prompt

```text
Generate one standalone 16:9 Chinese technical article body illustration.
Preferred final size: 1920x1080 if supported.

Visual mode: Friendly Handdrawn Tech.
Core idea: <one sentence>
Main point: <what the reader should understand>
Visual approach: <scene | annotated diagram | workflow | comparison | evidence view | layered model | route map | metaphor | summary>
Information density: medium-rich article explainer, not a sparse decorative doodle and not a standalone information poster.

Style lock:
<paste the chosen style lock>

Composition:
<specific scene, diagram, comparison, evidence view, or metaphor. Include one main visual focus plus purposeful supporting annotations, micro-panels, callouts, or comparison zones.>

Suggested visible text:
- <label 1>
- <label 2>
- <label 3>
- <label 4>
- <optional small note>

Constraints:
One image explains only one core idea.
The image must make the main point legible, not become passive decoration.
Keep visible Chinese text readable, relevant, and grounded in the article.
Preserve generous whitespace.
Use the canvas purposefully; avoid one tiny central object floating in empty space.
Vary composition by semantic role across a multi-image article package.
Do not write the structure type on the image.
Do not add meaningless filler labels, fake English, URLs, watermark, or decorative stickers.
```

## 21:9 Cover Prompt

```text
Generate one 21:9 Chinese technical article/WeChat wide cover illustration.
Preferred final size: 2520x1080 for article cover or 2100x900 for WeChat if supported.

Visual mode: Friendly Handdrawn Tech.
Suggested cover text: <main cover copy>
Suggested secondary text: <optional short line or omit>
Core idea: <one sentence>

Style lock:
<paste Friendly Style Lock>

Composition:
One memorable handdrawn technical visual hook occupying about 50-55% of the width.
Keep visible text readable and restrained, not oversized poster text.
Use wide clean margins and no full-page border.

Suggested visible text:
- <main cover copy>
- <optional short line or 1-3 labels>

Avoid:
crowded composition, dense bullet text, heavy bottom banner, fake labels, random English, watermark.
```

## 1:1 WeChat Square Prompt

```text
Generate one 1:1 WeChat square cover illustration in the same visual identity as the wide cover.
Preferred final size: 1080x1080 if supported.

Suggested square text: <4-10 Chinese characters or two short lines>
Core idea: <one sentence>

Style lock:
<paste the same chosen style lock>

Composition:
Square text is the main readable element.
Add only one tiny handdrawn technical motif or simple visual object.
No long secondary line.
No crop from the wide cover; compose this square separately.

Suggested visible text:
- <square text>
```

## 3:4 Xiaohongshu Cover Prompt

```text
Generate one 3:4 Xiaohongshu/Rednote technical cover illustration.
Preferred final size: 1080x1440 if supported.

Visual mode: Friendly Handdrawn Tech.
Suggested cover text: <sharp Chinese hook>
Core idea: <one sentence>

Style lock:
<paste chosen style lock>

Composition:
Portrait cover with one strong handdrawn technical visual hook.
Fill the canvas with clear top text, central visual focus, and a small bottom takeaway strip or 2-3 labels.
Keep safe margins.

Suggested visible text:
- <cover text>
- <label 1>
- <label 2>
- <label 3>

Avoid:
large empty vertical bands, long paragraphs, tiny text, decorative card shapes, sticker look, fake labels, watermark.
```
