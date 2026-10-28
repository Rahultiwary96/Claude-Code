# Chirpa – 11.6-second product film for an AI review-reply tool, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A friendly 2D/2.5D vertical product film (1080×1920, 30 fps) for **Chirpa**, an invented tool that answers every Google Maps review for restaurants in the owner's own voice within the hour. One review card for "Marta K." carries the whole story from angry 2 stars to happy 5 stars. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: pale pistachio #E8F1D6 with soft light blobs.
- Cards: white, 16 px radius, soft shadow. Owner reply card: deep forest green #1E3B2A with cream text.
- Accent: sunflower yellow #F5C518 (stars, chips, smiley faces).
- Type: chunky slab serif (Roboto Slab Bold / Zilla Slab) in forest green for headlines; highlighted words sit in a dark green rounded pill with cream italic text. UI text in Inter.

## 2. Voiceover (warm, light)
"A bad review sits there for weeks, unanswered. Chirpa replies to every review in your voice, within the hour, and turns unhappy guests around. Chirpa. Every review answered."

## 3. Scenes
1. **0.0–2.9 s – Unanswered.** Review card: frowning avatar, "Marta K. · Dinner for two · Osteria Lume", ★★☆☆☆ "2 of 5", "Waited 40 minutes for a table we had booked. Nobody even said sorry." Footer "No reply for 1 day → 13 days → 21 days". Below it a dashed empty box "No reply yet" and a "Waiting for a reply" calendar of dots that fill in week by week (1 week, 2 weeks, 3 weeks). A row of four mini review chips at the bottom. Headline: "A bad review sits / there for weeks," then the pill "*unanswered.*" stamps onto the dashed box.
2. **2.9–5.8 s – Reply.** A green reply card connects with a line: "★ Osteria Lume · |||· Your voice", text types: "Marta, we're so sorry about the wait. That's not the evening we want for you. Your next aperitivo is on us. — *Gianna, Osteria Lume*", chips "Warm · Personal · Signed" turn yellow, "Replied in 38 min". Mini chips below flip to yellow "Replied ✓". Headline: "Chirpa replies / in *your voice,*" then "within the hour."
3. **5.8–8.7 s – Turnaround.** The review card flips in 3D; it comes back as "Updated review · today" ★★★★★ "5 of 5 · They wrote back within the hour and made it right. We'll be back!" with a yellow "Updated" badge. An "AVERAGE RATING" card counts 4.1 → 4.7 (5 stars 62% → 78%, 1–2 stars 14% → 4%). Row of yellow smileys; the last one turns from sad to happy. Headline: "and turns unhappy / guests *around.*"
4. **8.7–11.6 s – End card.** Green rounded-square app icon with a yellow star, "Chirpa" in big slab serif, "Every review, *answered.*" Stars fill and the counter "44 → 118 of 128 reviews answered". Five yellow smileys bob. Small "CHIRPA.APP".

## 4. Rules
Single continuous vertical layout, camera slowly pushes in. Words rise 18 px with soft overshoot. Typing at ~40 characters/second.

## 5. Sound
Soft ukulele/whistle bed, typing clicks, a bird-chirp "pop" on each reply, a happy chime on the 5-star flip.

## 6. Make it yours
Swap restaurant, reviewer, complaint, reply and stats. Keep one card going from bad to good.
