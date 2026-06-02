# Platform Specs

Use high-resolution exports and stable filenames.

## Article Visuals

### 21:9 Article Cover

- Preferred size: `2520 x 1080`.
- Use for blog/article hero images and wide cover images.
- Filename: `article-21x9-cover.png`.
- Keep concise main text, optional secondary text, and one central handdrawn metaphor.

### 16:9 Body Illustration

- Preferred size: `1920 x 1080`.
- Use for article body images, technical explainers, and concept visuals.
- Filenames:

```text
body-01-<topic>.png
body-02-<topic>.png
```

## WeChat Official Account Cover Pair

Always compose the pair separately:

- `wechat-21x9-cover.png`: `2100 x 900`.
- `wechat-1x1-cover.png`: `1080 x 1080`.
- `wechat-cover-pair-preview.png`: optional review preview, around `2400 x 1180`.

21:9 cover:

- Concise main text.
- Optional secondary text.
- One strong handdrawn technical metaphor or screenshot/evidence object.
- Keep visible text readable in the center-left or another clean safe zone.

1:1 cover:

- Short main text in most cases.
- Compose separately; never crop the 21:9 cover.
- Use simplified text of about 4-10 Chinese characters, or 2 short lines.
- No secondary line unless needed for disambiguation.
- Omit extra imagery unless the image is central to the article identity.

## Xiaohongshu / Rednote

Default size:

- `1080 x 1440`.
- Ratio: `3:4`.

Safe area:

- Side margin: 72-96 px.
- Top margin: 72-112 px.
- Bottom margin: 80-120 px.

Default outputs:

- If the user asks for a cover: produce `xhs-01-cover.png`.
- If the user asks for a carousel: produce one cover plus 4-8 illustration pages.

Names:

```text
xhs-01-cover.png
xhs-02-<topic>.png
xhs-03-<topic>.png
```

3:4 illustration pages must feel filled. Text, diagram, evidence, or functional visual content should cover at least 75% of the canvas height. Do not center a small 16:9 illustration in the middle and leave large empty bands.

## Screenshots And Source Images

- Put originals under `assets/`.
- Preserve the full screenshot when UI, code, dense text, charts, or tables matter.
- Crop only when the important subject remains fully visible.
- If cropping a source image, decide the crop deliberately instead of accepting a default center crop.
- Preserve readability before decoration.

## Cross-Platform Text

Use different text lengths per surface:

- Article/WeChat 21:9: full or near-full main text.
- Xiaohongshu 3:4 cover: sharp 12-30 character hook when possible.
- WeChat 1:1: shortest text, usually 4-10 characters.

Do not squeeze long text into a square. Rewrite it.
