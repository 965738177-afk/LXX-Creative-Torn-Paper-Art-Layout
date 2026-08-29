---
name: lxx-creative-torn-paper-art-layout
description: "Transform user-supplied portraits, wedding photos, and event photographs into source-faithful torn-paper editorial posters using one of four layout grammars: airy cream window, linear magazine, dark fissure, or bold group collage. Use when the user asks for LXX torn-paper art, a paper-zine photo layout, a tactile editorial collage, or a cohesive batch in this style. Do not use for ordinary color correction, beauty retouching, or a fully illustrated replacement of the source photograph."
---

# LXX Creative Torn-Paper Art Layout

Create tactile editorial posters in which the supplied photograph remains truthful and recognizable while torn paper, quiet illustration, and restrained typography reorganize the surrounding space.

## Required companion skill

Use the `imagegen` skill for every raster generation or edit. Read its instructions before invoking image generation. When the source has a local path, inspect and edit that original file rather than a chat-compressed preview.

## Workflow

1. Inspect each original at full available resolution.
2. Make a source card before writing the prompt:
   - subject count and identities;
   - pose, gaze, gesture, and expression;
   - clothing, bouquet, props, architecture, and other invariants;
   - dominant scene colors and one source-derived accent hue;
   - usable quiet zones and the image's natural visual direction.
3. Choose one layout mode from [layout-modes.md](references/layout-modes.md). For a batch, choose per image; do not force every photograph into the same silhouette.
4. Build the edit prompt with the prompt compiler in the reference file. State the preservation constraints before decorative instructions.
5. Generate a vertical 3:5 poster unless the user requests another ratio. Keep the source photograph as the visual evidence, not merely as inspiration.
6. Inspect the result at normal size and thumbnail size. Regenerate once with a targeted correction if a critical check fails.
7. Deliver the image and identify the selected mode. If the requested pixel size is obtained by resizing, say `4K canvas, upscaled from the generated master`; do not imply newly generated optical detail.

## Non-negotiable source fidelity

Preserve the exact number of people, recognizable facial identity, expression, gaze, pose, body proportions, hands, clothing, jewelry, bouquet, important props, and location cues. Do not add, remove, merge, duplicate, beautify into a different person, restage, or replace the people. Do not fabricate a second exposure of a person unless the user explicitly requests a double-exposure composition.

Treat existing logos, watermarks, license plates, and written marks as source content. Do not invent new branding or signatures. Do not remove a photographer's watermark unless the user clearly establishes authorization and asks for removal.

## Visual grammar

- Make the photograph occupy a deliberately torn window, breach, fissure, or paper island.
- Keep the paper field spacious. Convert foliage, walls, shadows, architecture, and fabric into a few large source-derived shapes rather than many decorative fragments.
- Use a visibly irregular fibrous deckled edge. The tear must feel physical and quiet, not like a smooth vector mask, sticker outline, or burnt hole.
- Use one high-chroma accent hue as compositional structure. Derive it from the source when possible.
- Favor warm cream, bone, charcoal, muted ink, graphite lines, sparse botanical impressions, dry brush, translucent washes, and scanned paper grain.
- Keep typography optional and secondary. Use at most one short handwritten line plus one microtype block unless the user supplies exact copy.
- Keep the result flat and print-like: no frame mockup, phone UI, glossy 3D paper, excessive drop shadow, scrapbook clutter, or busy floral borders.

## Mode selection

- **A — Airy Cream Window:** default for single portraits and intimate couples with a clear subject and enough surrounding context.
- **B — Linear Magazine:** use when architecture, corridors, windows, stairs, or strong directional movement can extend into fine editorial lines.
- **C — Dark Fissure:** use for dramatic light, black suits, long gowns, crystalline scenes, night ceremonies, or a cinematic reveal.
- **D — Bold Group Collage:** use for bridal parties, group portraits, festive red rooms, or scenes whose energy benefits from broad torn shapes.

Read [layout-modes.md](references/layout-modes.md) for the exact prompt modules, negative constraints, and batch-cohesion rules.

## Typography rules

Default to no text when accurate text rendering is not important. If text is useful:

- request exact spelling in quotation marks;
- use short English-default, Chinese, or bilingual micro-copy;
- place it in negative space and keep it clear of faces, hands, attire, and the essential tear;
- never let generated text masquerade as a real studio credit, date, place, or quotation that the user did not provide.

## Quality checks

Reject or correct the result when any of these are true:

- the people are not the same recognizable subjects;
- person count, hands, limbs, clothing, bouquet, props, or pose changed;
- the source scene was replaced instead of selectively translated;
- the tear reads as a clean digital mask;
- micro-detail overwhelms the negative space;
- several unrelated accent colors compete;
- text is misspelled, too large, or crosses a face;
- the poster becomes a mockup, scrapbook, fantasy painting, or generic wedding template.

## Batch behavior

Keep the batch coherent through shared paper temperature, grain scale, ink density, typography size, and accent saturation. Vary tear geometry, photo placement, and mode to suit each image. Preserve landscape sources as landscape photographs inside a vertical paper composition unless the user explicitly asks to crop away information.

## Privacy and publishing

Use private source images only to perform the requested edit. Do not place them in a public repository, example folder, README, issue, or release. A reusable public skill should contain only instructions, templates, and synthetic or separately licensed assets.
