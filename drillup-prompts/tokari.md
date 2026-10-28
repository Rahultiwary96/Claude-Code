# Tokari – 12-second product film for design tokens, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A techy 2.5D product film (1920×1080, 30 fps) for **Tokari**, an invented design-token tool: it keeps every token in one source and pushes each change to web, iOS and Android at once. A grid of colour tiles carries the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: deep green-black #10201A with a subtle grid.
- Tiles: rounded squares in sage greens #5FAF8A, pale greens and cream #EDE6D0.
- Accent: hot pink #FF2E93 — the new brand colour and highlighted words (pink box behind white text).
- Type: grotesk (Inter Bold) in white; monospace labels.
- Logo: four pink rounded squares in a 2×2 offset pattern + "tokari" in cream lowercase bold.

## 2. Voiceover (calm developer voice)
"Design changes one color, and developers update it in forty places. Tokari keeps every token in one source and pushes each change to web, iOS and Android at once. Tokari. One change, everywhere."

## 3. Scenes
1. **0.0–2.0 s – One colour.** A grid of sage tiles; a colour-picker popover "brand/primary" opens on one tile; the hue slider drags to pink "#FF3D9A"; the tile turns pink. Caption: "Design changes [one color,]"
2. **2.0–4.0 s – Forty places.** Tiles across the grid flip one by one and get pink outline marks with little code-file icons; counter "13/40 → 40/40 FILES TO EDIT BY HAND". Caption: "developers update it / in [forty places.]"
3. **4.0–6.0 s – One source.** A dark "tokens.json" panel: rows color.brand.primary #FF3D9A (40 places), color.surface.base #0E1712, color.text.default #F5F0E6, radius.md 12px, space.4 16px, font.body 15/24. Caption: "Tokari keeps every token / in [one source,]"
4. **6.0–9.0 s – Push.** Lines branch from the tokens panel to three empty device outlines labelled web, iOS, Android; they fill with app UIs (dashboard on web, phone screens) that all adopt the pink accent at once. Caption: "pushes each change to / web, iOS and Android at once."
5. **9.0–12.0 s – End card.** Pink tiles assemble into the logo; "One change, [everywhere.]"; mono "1 source · 3 platforms · 40 places in sync"; "TOKARI.DEV"; a pink tile grid glows at the edges.

## 4. Rules
Grid tiles flip with 3D rotation; lines draw like circuit traces; steady camera drift.

## 5. Sound
Minimal electronic pulse, click per tile, a rising arpeggio as platforms sync, satisfying "snap" on the logo.

## 6. Make it yours
Swap token names, values and platforms.
