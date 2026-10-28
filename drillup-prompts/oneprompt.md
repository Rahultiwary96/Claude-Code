# One Prompt – 13.4-second 3D film in one continuous camera take, retro desk look, 9:16

> Recreated from the public example video. Paste into Claude (Claude Code works best) and ask it to build and render the film.

## 0. What you are building
Build a 13.4-second vertical (1080×1920, 30 fps) 3D film for an AI video prompt library called **DrillUp**. A young creator's voice tells a tiny success story: one video, made from one prompt, just landed a client. Everything happens on and around one object: a beige retro CRT computer on a glossy desk. The camera never stops moving and never cuts; it is one continuous flight that pushes in, pulls back to reveal the scene being "built", then pushes back in for the end card.

Build it in code (Three.js or React Three Fiber inside Remotion, or Blender via Python if you prefer), render to MP4, and mix the voice and sound effects in.

## 1. Look
- **Set:** beige 90s CRT monitor with a slightly yellowed plastic shell, two yellow sticky notes with scribbles taped to the top corners, a small green power LED, beige desktop tower underneath with a floppy slot and vent grille, beige mechanical keyboard in the foreground.
- **Room:** deep royal-blue background (#1530B8 to #0B1F8C gradient), soft bloom on highlights, glossy purple-maroon desk surface with reflections.
- **Mascot:** a small, blocky terracotta-red pixel creature (cube body, two black square eyes, four stubby legs) that sits on top of the monitor.
- **Screen:** CRT glass with scanlines, a subtle starfield and dust/scratches, a warm red-orange glow at the bottom of the screen.
- **Film feel:** shallow depth of field, slight film grain, soft warm desk-lamp key light from the left, cool blue fill.
- **Type:** heavy rounded sans (e.g. Hanken Grotesk Black) in white with a soft glow; accent words in hot magenta (#FF3FD0) and yellow (#F5D637).

## 2. Voiceover (young, casual, slightly excited creator)
| Time | Line |
|---|---|
| 0.3–3.0 s | "This video just landed me a client…" |
| 3.0–5.5 s | "…and the crazy part? I made it with one prompt." |
| 5.8–9.0 s | "Claude built the desk, the light, every single frame." |
| 9.0–12.1 s | "Want the prompt behind it? It's on drillup.io." |

Words appear on screen in sync, one or two at a time.

## 3. Scenes (one continuous take)
1. **0.0–1.1 s – Swoop in.** Camera arcs in from the left with motion blur toward the monitor. The screen shows a green, playful video thumbnail with bouncing dots and the words "Keep your…".
2. **1.1–2.3 s – The payment.** A white rounded notification card pops out of the screen toward camera with an overshoot: a green check badge on top, "+$4,999 USD" in big green bold type, small grey line "You received a payment from Client Studio". A white hand cursor taps it.
3. **2.3–4.4 s – Caption on glass.** The card dissolves; on the screen, white glowing words build: "…video call / and the / crazy **magic**" with the key word in magenta.
4. **4.4–5.6 s – "I made it with".** Big white italic words "i made it / with" float in 3D in front of the screen. Behind them the screen shows a prompt editor: "Retro beige PC drops onto a glossy desk, a payment pops out of the screen. Warm lamp, navy room, film grain. 9:16, one take." with a yellow "Generate" button.
5. **5.6–6.7 s – Mascot jump.** The red pixel mascot hops up from behind the monitor; the screen goes to grey static.
6. **6.7–8.0 s – Behind the scenes.** Camera pulls back fast into a grey untextured 3D viewport (grid floor, flat grey light): an empty slab of desk, then the PC, keyboard and an angled desk lamp assemble into place as clay models. The mascot lands on top. This shows "Claude built the desk, the light".
7. **8.0–10.6 s – Back to the finished look.** Materials and blue light snap back on as the camera pushes in again. The screen shows the DrillUp library page: a card titled "Retro PC, one prompt", tag "AI PROMPT", the prompt text, a small thumbnail of the PC, and a yellow "Copy prompt" button that turns green with a check when the hand cursor clicks it.
8. **10.6–13.4 s – End card.** Giant 3D extruded yellow italic logotype "drillup" swings in front of the screen, then ".io" in lilac slides in next to it. Mascot stays on top. Hold.

## 4. Camera and motion rules
- One path, no cuts. Ease in/out on every move; never a full stop.
- Every pop-in (card, words, logo) scales from 0.85 to 1.0 with a soft overshoot (back-out easing, ~0.35 s).
- Light camera shake/handheld drift of ±0.5°.

## 5. Sound
Soft lo-fi beat under the voice. SFX: whoosh on the opening swoop, coin "cha-ching" on the payment card, mouse click on each tap, CRT static crackle at 5.6 s, a short "pop" when the logo lands.

## 6. Make it yours
Swap: brand name and URL, the payment amount and sender, the on-screen prompt text, the mascot, the main object (any retro device works) and the background colour. Keep the structure: hook result → "made with one prompt" → behind-the-scenes pull-back → product page → logo.
