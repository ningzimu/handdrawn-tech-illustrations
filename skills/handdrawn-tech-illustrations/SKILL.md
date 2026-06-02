---
name: handdrawn-tech-illustrations
description: Use when the user asks for Chinese handdrawn technical article illustrations, body images, WeChat covers, Xiaohongshu/Rednote covers, or technical explainer visuals from articles, notes, screenshots, outlines, or rough ideas.
---

# Handdrawn Tech Illustrations

Create final illustrations for Chinese technical articles and social covers: article body illustrations, concept visuals, WeChat covers, and Xiaohongshu/Rednote covers.

Default production uses the built-in image generation model. Crop, resize, and contact-sheet creation are only delivery helpers after the final image is generated.

## Reference Map

Load only what the task needs:

- `references/style-dna.md`: read before choosing a visual mode or writing prompts.
- `references/content-planning.md`: read when turning articles or outlines into a shot list.
- `references/prompt-patterns.md`: read before image generation.
- `references/platform-specs.md`: read when covers or fixed ratios are requested.
- `references/production-workflow.md`: read before saving outputs, resizing, or contact sheets.

Use `assets/theme-tokens.json` as the compact palette/style token file when prompt writing needs exact colors.

## Output Modes

- **Body illustration**: 16:9 Chinese article illustration. Default for 正文配图.
- **Article/WeChat wide cover**: 21:9 cover. Use for 公众号主封面 or blog/article hero.
- **WeChat square cover**: 1:1 companion cover. Compose separately for the square surface.
- **Xiaohongshu/Rednote cover**: 3:4 cover illustration. Fill the portrait canvas with one strong visual hook.
- **Shot list only**: planning output with where each image goes, core idea, visual approach, text, and ratio.

Do not create editable document packages, reusable layout templates, or generated card systems inside this skill.

## Workflow

1. **Compress the request**
   - Decide the output mode, ratio, core idea, useful visible text, and any source assets.
   - For articles or multi-image sets, pick only the few points that deserve images.
   - If the user asks only for planning, return a shot list and stop.

2. **Generate the image**
   - Use **Friendly Handdrawn Tech**.
   - Read `style-dna.md` and `prompt-patterns.md` before generation.
   - Use one image generation call per final image. Put the ratio, main point, visual approach, composition, and Chinese visible text directly in the prompt.

3. **Deliver**
   - Use the user-requested output path when one is provided; otherwise keep the generated image at the model-provided path and report it clearly.
   - Copy or organize files only when useful for delivery.
   - Resize or create a contact sheet only when useful for delivery.

## Defaults

- Language: Simplified Chinese.
- Body illustration ratio: 16:9.
- Article/WeChat wide cover ratio: 21:9.
- WeChat square cover: 1:1, composed separately.
- Xiaohongshu/Rednote cover: 3:4.
- Body illustration text density: 3-6 short labels, notes, or short phrases when needed for clarity.
- Cover text density: concise main text plus 0-3 short labels.
- Background: near-white warm paper.

## Non-Negotiables

- Do not copy unrelated card templates, editorial page systems, generated layout frameworks, or nested-card visual language.
- Do not package outputs into editable documents or multi-image deliverable bundles.
- Do not create dense whiteboards, business templates, SaaS dashboards, sticker decorations, random blobs, gradients, or heavy shadows.
- Do not invent facts, product details, metrics, release dates, or percentages.
- Do not let Chinese text become long, wrong, cramped, or unreadable.
- Do not crop supplied screenshots, product UI, code, or hardware details in a way that hides the evidence.

## Final Response

Report image paths, image count, and ratios/dimensions when available. Show main images inline with absolute paths when useful.
