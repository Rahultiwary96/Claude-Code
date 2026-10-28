# Stoka – 10.4-second product film for retail inventory, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A clean, product-shelf 2.5D/3D film (1920×1080, 30 fps) for **Stoka**, an invented inventory tool for shops: it counts every shelf, predicts what sells next and reorders before you run out. A long white shelf unit with neutral packaged goods carries the story. Build in code (Remotion + Three.js for the shelf) and render to MP4.

## 1. Look
- Background: warm grey #D9D6D0.
- Shelf: white 3D shelving with minimalist products (bottles, jars, cartons) in greys, beiges and black; price tags along the shelf edges.
- Accent: amber yellow #F5B921 for highlights, scan line and buttons; dark UI panels #1E1E1E.
- Type: heavy slab serif (Roboto Slab Black / Clarendon) in near-black with a short yellow underline under each line.
- Logo: black rounded square with three amber bars + "Stoka".

## 2. Voiceover (brisk shop owner)
"Out of stock again? Stoka counts every shelf, predicts what sells next, and reorders before you run out. Full shelves, zero spreadsheets. Stoka. Stock up."

## 3. Scenes
1. **0.0–1.7 s – Empty slot.** Camera pans along the shelf; one slot is empty with a black pill "● Out of stock" and a yellow tag "0 left". Caption: "Out of stock again?"
2. **1.7–3.4 s – Count.** A vertical amber scan line sweeps across; count badges pop on every product group; a dark counter "120 → 268 counted". Caption: "Stoka counts every shelf,"
3. **3.4–4.3 s – Predict.** Dark card "Oat milk 1 L · 14 left": bar chart of daily sales with yellow forecast bars, "Days of stock 14 → Runs out Fri", toggle "Auto-reorder" on. Caption: "predicts / what sells / **next,**"
4. **4.3–6.0 s – Reorder.** A timeline TUE (today) → WED → THU → FRI; a tag "Reorder · 48 × Oat milk ✓"; delivery "Arrives Thu" lands before the "Runs out" marker on Fri. Caption: "and reorders / before you run out."
5. **6.0–7.8 s – Full shelves.** The shelf is full, every tag green-ish. A messy spreadsheet window "inventory_FINAL_v7.xlsx" slides over and gets crumpled away. Caption: "Full shelves, / zero spreadsheets."
6. **7.8–10.4 s – End card.** Logo; a slim stock-level bar; amber pill "stoka.app".

## 4. Rules
Smooth dolly along the shelf; products pop subtly as they're counted.

## 5. Sound
Store ambience, barcode beeps, a cash-register-like "chunk" on reorder, crumpled-paper sound for the spreadsheet.

## 6. Make it yours
Swap products, counts and timing.
