# Production Workflow

This is an image-generation-first skill.

## Output Location

Do not require a fixed output folder.

- If the user provides a target folder or filename, save or copy final images there.
- If the image generation tool returns a usable local path, leaving the image there is acceptable.
- Create a task folder only when it helps organize a multi-image delivery, source assets, or contact sheet.

## Generate

1. Plan each image with role, ratio, mode, core idea, visual approach, and visible text guidance.
2. Use the built-in image generation model for each final image.
3. Keep selected images at their generated paths or copy them to the user-requested location.
4. Do not make a multi-image collage unless the user asks for a contact sheet.

## Delivery Helpers

Allowed after generation:

- Crop or resize to the requested ratio.
- Create contact sheets.

Not allowed as primary style generation:

- Building the illustration with HTML/CSS.
- Drawing the whole image with SVG, canvas, Pillow, or local rendering libraries.
- Copying unrelated card templates or editorial page systems.

## Contact Sheet

For 2+ images, make a contact sheet when feasible:

- Preserve aspect ratios.
- Add small filename labels outside or below the image tiles when needed.
- Use it only for review; do not treat it as a final illustration.

## Source Assets

When screenshots or product images are supplied:

- Preserve readability.
- Do not redraw or fake UI.
- Avoid cropping important UI, code, charts, or hardware details.
- If the screenshot is the evidence layer, make it large enough and reduce nearby text.

## Optional Filenames

Use clear filenames when copying or organizing files:

```text
article-21x9-cover.png
wechat-21x9-cover.png
wechat-1x1-cover.png
xhs-01-cover.png
body-01-<topic>.png
body-02-<topic>.png
contact-sheet.png
```
