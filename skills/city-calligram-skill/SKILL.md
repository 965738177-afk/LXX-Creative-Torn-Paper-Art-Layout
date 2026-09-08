---
name: city-calligram-skill
description: Transform one or more city photographs into premium 3:4 editorial posters whose lower panel reconstructs the photographed subject from city-led English typography. Use for city calligrams, typographic travel posters, “文字即图像” photo treatments, or requests to reproduce this specific two-panel style.
---

# City Calligram

Create one standalone poster per source photograph. Use image generation or image editing tools that accept reference images; do not substitute a text-only prompt when the user expects finished images.

## Resolve the city first

Use the city explicitly named by the user. If none is given, accept a city only when a legible sign or unmistakable landmark identifies it reliably. Otherwise pause and ask: **“这是哪个城市？”** Never silently guess from architecture, vegetation, filenames, metadata, or general atmosphere.

Convert the confirmed city to its standard English name. Preserve the user's preferred romanization when supplied. Use that city name as the dominant repeated word in the calligram.

## Derive the supporting word set

Inspect each photo independently and identify:

- the main recognizable subject or structure;
- the setting and activity;
- visible natural elements, season, light, color, and mood;
- a small number of location-relevant concepts.

Translate these into 6–12 short, natural English words. Prefer concrete subject words over generic slogans. For example, a lakeside kayak scene may yield `KAYAK`, `WATER`, `RIPPLE`, `SUMMER`, `COLOR`, `WEEKEND`, and `SHORE`; a convention center may yield `ARCHITECTURE`, `CROWN`, `EXPO`, `CITY`, `LIGHT`, and `LANDMARK`.

Do not invent facts, event names, venue names, brands, or sentimental claims not supported by the image or user. Avoid meaningless pseudo-English. Keep all large and medium display words correctly spelled. Dense microtype may repeat the confirmed city and the approved supporting words.

## Build the poster

- Use a 3:4 vertical canvas split into two equal-height 1:1 panels.
- Upper panel: preserve the original photograph's subject, viewpoint, proportions, natural texture, lighting logic, and recognizable details. Allow only restrained editorial color refinement. Do not redraw or replace people, faces, vehicles, architecture, signage, or other important content.
- Lower panel: use a warm off-white paper field with generous negative space. Reconstruct only the photograph's most recognizable subject, outline, perspective, gesture, and material rhythm using typography as the actual drawing medium.
- Use large words for the structural skeleton, medium words for planes and contours, dense small words for shadows and texture, and sparse fading words or particles at edges.
- Make the confirmed city name the visual anchor and roughly 40–60% of readable text. Distribute it through both structural and textural layers without monotonous mechanical repetition.
- Let the derived subject words shape the relevant components. Typography must carry form, not sit on top of a conventional illustration.
- Use two to four colors sampled from the source photo. Keep the paper background warm, clean, and lightly tactile.
- Add only restrained editorial microcopy or a handwritten accent when it improves balance. Do not add Chinese text, logos, app UI, watermarks, borders, or unrelated slogans unless requested.

When processing multiple photos, generate separate outputs and vary the lower composition around each image's subject rather than cloning one layout.

## Image-generation prompt scaffold

Adapt this scaffold to the selected image tool and the actual photo:

```text
Use case: style-transfer
Asset type: standalone premium 3:4 vertical city calligram poster
Input image: source photo to preserve and transform
Confirmed city: <CITY>
Primary subject: <SUBJECT>
Supporting English words: <6–12 IMAGE-DERIVED WORDS>

Create exactly two equal-height square panels stacked vertically. In the upper panel, preserve the source photograph faithfully: the same subject, camera angle, geometry, people, objects, natural texture, lighting logic, and original atmosphere, with only restrained editorial color refinement.

In the lower panel, reconstruct the main subject on warm off-white paper entirely from English typography. Use “<CITY>” as the dominant repeated anchor word. Use the supporting words only where their meanings correspond to visible parts, activity, light, setting, or mood. Larger words define the skeleton and main silhouette; medium words define planes and contours; dense microtype creates shadow and texture; sparse words dissolve at the edges. The lower image must clearly match the upper subject's silhouette, perspective, rhythm, and key features. Typography is the illustration, not decoration over a normal drawing.

Use two to four colors sampled from the photo, intentional negative space, asymmetric editorial balance, crisp display words, subtle paper grain, and a sophisticated independent travel-magazine aesthetic.

Constraints: one source photo per poster; no collage of multiple sources; no Chinese text unless requested; no invented venue or brand names; no meaningless pseudo-English; no UI, logo, border, or watermark; do not alter identity-sensitive or landmark-defining details in the upper panel.
```

## Check before delivery

Confirm that the city is correct, the main city word is spelled correctly, the two panels are equal, the upper photo remains recognizably faithful, the lower silhouette matches the actual subject, and every prominent supporting word is grounded in the image. If a prominent word is malformed or the upper panel changes a defining sign, face, landmark, or object, regenerate with that single failure called out explicitly.
