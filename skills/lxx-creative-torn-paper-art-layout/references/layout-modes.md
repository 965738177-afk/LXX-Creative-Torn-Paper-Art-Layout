# Layout Modes and Prompt Compiler

Use this reference after reading the source image. Replace every brace-delimited field with observed facts. Never leave placeholders in a generation prompt.

## Source card

Record these facts in one compact note:

```text
SUBJECTS: exact count, identity cues, age presentation, relationship
GESTURE: pose, gaze, expression, hand positions, interaction
WARDROBE: silhouettes, colors, embroidery, veil, suit, jewelry
PROPS: bouquet, umbrella, car, dog, décor, architecture, written marks
SCENE: location type, light direction, dominant materials, depth
QUIET ZONE: the safest area for paper field or microtype
ACCENT: one source-derived high-chroma hue
MUST KEEP: details whose loss would change the factual photograph
```

## Common prompt compiler

Write the final image-edit prompt as four short paragraphs in this order.

### 1. Task and composition

```text
Edit the supplied original photograph into a premium vertical 3:5 torn-paper editorial zine poster. Use {MODE MODULE}. Keep the photograph as truthful photographic evidence inside the paper composition; the surrounding illustration should reorganize the source rather than replace it.
```

### 2. Preservation contract

```text
Preserve exactly {SUBJECTS AND MUST-KEEP FACTS}. Keep the same recognizable faces, expressions, gaze, pose, anatomy, hand positions, body proportions, clothing, jewelry, bouquet, props, person count, and location cues. Do not add, remove, merge, duplicate, restage, or redesign any person. Do not alter ethnic appearance, age presentation, or facial structure.
```

### 3. Material translation

```text
Translate only selected source elements into a few large quiet abstract fields: {SOURCE-DERIVED FORMS}. Use {ACCENT} as the single structural high-chroma accent. Create an unmistakable hand-torn fibrous deckled photo-to-paper edge with irregular fibers and shallow paper depth. Add restrained graphite or ink contour lines, sparse dry-brush or botanical impressions, and generous active negative space. {TEXT INSTRUCTION}
```

### 4. Finish and hard avoids

```text
Finish as a flat scanned art print on tactile warm fibrous paper with subtle natural grain. Keep the photograph crisp where retained and the illustration quiet at thumbnail size. No frame mockup, phone interface, glossy 3D paper, smooth vector clipping path, burnt edge, scrapbook clutter, excessive flowers, random symbols, extra limbs, extra people, face changes, false studio credit, invented watermark, or unrelated logo.
```

## Mode A — Airy Cream Window

Best for a single portrait or intimate couple when the subject can sit inside one irregular opening.

```text
an airy warm-cream paper field with one asymmetric torn photographic window placed off center; preserve a large calm paper area around it; let one thin hand-drawn line travel from the photograph into the negative space; use two or three oversized translucent source-derived botanical or fabric forms at most; keep the composition lyrical, light, and editorial
```

Suggested micro-copy, only when useful:

```text
Set the exact handwritten line to “A quiet light between us.” and a tiny uppercase microtype block to “SOMETHING GENTLE, STAYING.” Keep both subtle and secondary.
```

## Mode B — Linear Magazine

Best for architecture, corridors, windows, stairs, motion, or a full-length subject.

```text
a cream editorial magazine field where the main photograph enters from one side through a long irregular torn boundary; extend the source architecture, veil, foliage, or gesture into a few very fine graphite construction lines and translucent washes across the paper; keep the subject grounded and photographic; reserve at least half the canvas as quiet negative space; use one faint oversized outline word only if it remains subordinate
```

Suggested micro-copy:

```text
Set the exact handwritten line to “Love, in motion.” and a tiny microtype block to “A MOMENT HELD LIGHTLY.” Do not generate any other text.
```

## Mode C — Dark Fissure

Best for dramatic portraits, black suits, crystalline light, long gowns, night scenes, and cinematic reveals.

```text
a deep charcoal-black fibrous paper field split by one narrow irregular vertical or diagonal torn fissure that reveals the unchanged photograph; allow the gown, veil, light beam, or architectural line to flow slightly beyond the opening as a restrained source-derived ink gesture; use one warm gold, electric blue, or source-red accent as a structural stroke; keep the darkness spacious, refined, and print-like
```

Suggested text:

```text
Use no headline. If text is needed, add only the tiny exact line “WITHIN THE QUIET, LIGHT REMAINS.” in a low-contrast corner.
```

## Mode D — Bold Group Collage

Best for groups, bridal parties, festive red rooms, ceremonies, and scenes with strong social energy.

```text
a bold but disciplined torn-paper collage built from two or three broad cream, charcoal, and source-accent paper shapes; keep every person together inside one continuous truthful photographic island so nobody is cut apart or duplicated; use overlapping tears to frame the group hierarchy, not to fragment faces; convert décor and flowers into large screen-printed masses and sparse contour marks; retain clear breathing room around the group
```

Suggested text:

```text
Use no decorative quotation. Add only a small exact microtype label supplied by the user, or omit text entirely.
```

## Batch-cohesion module

Append this paragraph when processing a set:

```text
Match the companion series through the same warm-paper temperature, fiber scale, graphite density, microtype size, and accent saturation. Choose tear geometry from this photograph's composition rather than copying another image's mask. Keep this poster distinct but visibly part of one editorial series.
```

## 4K delivery

Prefer generation at the highest supported native resolution. For a 3:5 vertical deliverable, export at no less than 3840 × 6400 pixels when the workflow supports a resize or upscale step. Preserve aspect ratio and use high-quality resampling; do not stretch. A resized file is a 4K canvas, not proof of newly generated photographic detail.

## Targeted correction prompts

Use only the relevant correction instead of rewriting the whole art direction.

```text
Identity correction: Restore the exact source faces, expressions, gaze, pose, hands, and person count. Change no decorative elements except where necessary to recover source fidelity.

Tear correction: Replace the smooth digital cutout with an irregular hand-torn fibrous deckled edge. Keep the photographic region and all people unchanged.

Density correction: Remove half of the decorative micro-detail. Consolidate it into two or three large source-derived shapes and restore active negative space.

Typography correction: Remove all misspelled or invented text. Retain only the exact quoted line at a small editorial scale, away from faces and hands.
```
