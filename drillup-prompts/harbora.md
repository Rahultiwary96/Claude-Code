# Harbora – 11.8-second product film for live shipment tracking, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A clean, light 2.5D/3D product film (1920×1080, 30 fps) for **Harbora**, an invented freight-tracking tool: it tracks every shipment live, flags delays before they hit and tells customers the real arrival date. One bright orange shipping container ("HBRU 482915 7") carries the story along a dashed route line. Build in code (Remotion + Three.js for the containers) and render to MP4.

## 1. Look
- Background: misty pale sea-green/grey #E4ECEA with soft horizon haze.
- Hero container: safety orange #F0532D, corrugated, white stencil "HBRU 482915 7". Other containers: slate teal/grey.
- Text: deep navy #1E2B45; accent orange-red #F0532D on key words. UI cards: white with soft shadow; monospace labels.
- Logo: an orange sun over two navy wave lines + "Harbora" in navy semibold sans.

## 2. Voiceover (calm logistics narrator)
"Your container left Shanghai three weeks ago. Where is it now? Harbora tracks every shipment live, flags delays before they hit you, and tells your customers the real arrival date. Harbora. Know before it docks."

## 3. Scenes
1. **0.0–2.0 s – Departure.** The orange container floats in 3D; a line drops to a chip "● SHANGHAI · DEPARTED OCT 05". The container flies off along a dashed route with day ticks; chip "DAY 17 → DAY 21". Caption: "Your container / left Shanghai / three weeks ago."
2. **2.0–3.0 s – Unknown.** A grey "Carrier portal" card: "Status: In transit · Last update: 9 days ago · Position: Unknown · ETA: To be confirmed". A "?" bubble on the route. Caption fades: "Where is it now?"
3. **3.0–4.9 s – Tracking.** The container lands in a 3D stack on a ship deck; floating tags "HBRU 482915 7 · DELAY", "TGHU 518977 0 · ON TIME". A "Shipments · 14 live" list: HBRU 482915 7 Shanghai → Rotterdam, MSKU 771204 3 Ningbo → Hamburg, TGHU 518977 0 Busan → Antwerp, CMAU 205618 4 Shenzhen → Felixstowe, OOLU 664812 9 Qingdao → Gdańsk, each with progress bars. Caption: "Harbora tracks / every **shipment**".
4. **4.9–6.8 s – Delay flag.** The container gets a little red flag "DELAY" planted on top. A "Voyage HBRU 482915 7" timeline: SHANGHAI → SUEZ · DAY 11 (red congestion block) → ROTTERDAM, chips "+3 DAYS", old ETA "NOV 16" struck, new "ETA NOV 19". Caption: "flags **delays** / before they hit".
5. **6.8–8.8 s – Customers.** Three white emails/cards fan out: "Nordhaus Living · Your order #2291 has a new delivery date · Oak dining table · ~~Mon, Nov 16~~ Thu, Nov 19 · +3 DAYS · ✓ Sent automatically · 3 of 3 customers notified"; side cards Order #2304 Fri, Nov 20 and #2317. Caption: "and tells your customers / the **real arrival**".
6. **8.8–11.8 s – End card.** Logo; "Know **before** it docks." A mini route line with an orange marker "DAY 21", "ROTTERDAM · NOV 19". "HARBORA.IO".

## 4. Rules
Continuous camera drift; containers have soft shadows and gentle bobbing; route lines draw dashed.

## 5. Sound
Low ambient sea and gull, ship horn on the departure, metal clank on the stack, alert ping on the flag, soft email whooshes, warm chord.

## 6. Make it yours
Swap ports, container number, customer and dates.
