# LXX-Creative Torn-Paper Art Layout

A reusable Codex skill for turning original portraits, wedding photographs, and event images into source-faithful torn-paper editorial posters.

The style system provides four layout grammars:

- **Airy Cream Window** — warm paper, one asymmetric photo opening, lyrical negative space.
- **Linear Magazine** — architectural graphite lines and a restrained editorial field.
- **Dark Fissure** — deep charcoal paper with a narrow cinematic photographic reveal.
- **Bold Group Collage** — broad torn shapes that preserve group hierarchy and person count.

The skill is designed around photographic truth. It tells the image editor to preserve identity, expression, anatomy, hands, clothing, props, person count, and scene evidence while translating only selected surroundings into paper, ink, and simplified source-derived forms.

## Install

Copy the skill directory into your Codex personal skill library:

```text
skills/lxx-creative-torn-paper-art-layout
```

Target location:

```text
~/.codex/skills/lxx-creative-torn-paper-art-layout
```

Or ask Codex to install the skill from this GitHub repository after it is cloned.

## Example requests

```text
用 $lxx-creative-torn-paper-art-layout 把这张婚礼原图做成 3:5 的奶油色撕纸编辑海报，保留人物与服装，不要改变脸。
```

```text
Use $lxx-creative-torn-paper-art-layout on this folder. Choose the best of the four modes per photo, keep the batch cohesive, and export a 4K canvas.
```

## 4K note

The skill requests the highest available native generation size and supports high-quality export to at least 3840 × 6400 for a vertical 3:5 canvas. Upscaling increases canvas dimensions; it does not recreate optical detail that was absent from the generated master.

## Privacy

This repository contains instructions and prompt templates only. It intentionally contains no wedding photographs, portraits, private source files, or generated client work.

## License

MIT. See [LICENSE](LICENSE).

## Acknowledgement

This is an independently written workflow informed by experiments in tactile editorial collage and by the MIT-licensed Gathered Scenes Zine project. No upstream images or prompt text are bundled here. See [NOTICE](NOTICE).
