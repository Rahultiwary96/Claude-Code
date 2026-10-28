# Sendra – 10.2-second product film for same-day courier delivery, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A sleek vertical 2.5D product film (1080×1920, 30 fps) for **Sendra**, an invented same-day courier platform: it finds the nearest rider, tracks the parcel street by street and gets the signature on delivery. A light-grey city map carries the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Map: pale grey #E9ECEF streets on white blocks, faint street names in monospace caps (FOUNDRY RD, WEIR ST, HARBOR ROW, LINDEN AVE, CANAL ST…).
- Cards: black #121418 UI panels. Accent: bright blue #1E6BEB — route line, rider arrow pin, speed-line motif "≡" before key words.
- Type: heavy italic sans (Archivo Black Italic / Gilroy Black Italic) for key words in blue; bold sans for the rest in black.
- Logo: blue location pin with a stopwatch face + "Sendra" in black heavy italic.

## 2. Voiceover (urgent but calm)
"It has to be there today, not tomorrow. Sendra finds the nearest rider, tracks the parcel street by street, and gets the signature on delivery. Sendra. Across town, within the hour."

## 3. Scenes
1. **0.0–2.4 s – Today.** A black card "New order · SD-2048 · 1 parcel · 2.4 kg · ● Unassigned → Same day": "○ Atelier Nord · 14 Weir St → ● L. Moreau · 9 Harbor Row"; DELIVER toggle "Tomorrow | Today" switches to blue "Today", "by 17:00" with a countdown "59:59.64". "Tomorrow" gets struck through. Caption: "It has to be there / ≡ ***today.*** / Not ~~tomorrow.~~"
2. **2.4–3.4 s – Nearest rider.** Concentric search rings expand from the parcel pin; rider arrows around at 1.2 km and 1.1 km; the closest blue rider is picked and a line connects; chip "SD-2048 Today". Caption: "Sendra finds the / ≡ ***nearest*** rider,"
3. **3.4–5.9 s – Tracking.** The blue route draws street by street from Weir St to Harbor Row; a black "● LIVE · Arrives in 3 min · 600 m · Harbor Row" card with a progress bar; destination tag "L. Moreau · No. 9". Caption: "tracks the parcel / ≡ ***street*** by street,"
4. **5.9–6.8 s – Signature.** A black "Proof of delivery · SD-2048 · 9 Harbor Row · 🕐 16:42" card: a white signature box where "L. Moreau" signs; "Recipient · Awaiting signature → Signed". Caption: "and gets the / ≡ ***signature*** on delivery."
5. **6.8–10.2 s – End card.** Logo; "Across town, / within the ≡ ***hour.***"; a progress line with a blue arrow "door to door in 18 → 37 → 46 min"; "SENDRA.APP".

## 4. Rules
Map camera pans and zooms smoothly; route draws like a GPS trace; speed lines on key words.

## 5. Sound
Urban ambience, scooter whoosh, ping when the rider is found, GPS ticks, pen scribble, success chime.

## 6. Make it yours
Swap addresses, times and parcel.
