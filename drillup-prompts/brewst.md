# Brewst – 11.8-second product film for a café point of sale, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A short, calm, warm 2.5D product film (1920×1080, 30 fps) for **Brewst**, a point-of-sale and order-flow tool for cafés. Paper order tickets pile up on a steel ticket rail that runs across the whole film; Brewst sorts them, takes payment and restocks. Build in code (Remotion/React or HTML+GSAP) and render to MP4.

## 1. Look
- Background: dark espresso brown #2B1A12 with a subtle vignette and fine paper grain.
- Ticket rail: brushed steel bar with small clips and labels "COUNTER", "BAR", "OVEN" each with a small count badge.
- Tickets: off-white paper (#EDE6D6), slight curl, handwritten-style order numbers (#44, #45, #46, #48), grey lines.
- Accent: honey caramel #E0A64A. Cards: dark brown panels (#3A271C) with a thin lighter border.
- Type: serif headline (Newsreader / Source Serif) in cream, accent words in *italic caramel*. UI in a monospace.
- Logo: round caramel coin with a "B", wordmark "Brewst" in large cream serif.

## 2. Voiceover (warm, calm barista tone)
"The morning rush hits and orders get lost between the counter and the bar. Brewst sends every order straight to the right station, takes payment in seconds and restocks before you run out. Brewst. Smooth service, every cup."

## 3. Scenes
1. **0.0–3.0 s – The rush.** Tickets #45, #46… clip onto the COUNTER rail, piling up; the counter badge climbs. Two tickets (#43, #44) flutter off and fall; empty "?" slots appear on the BAR rail. Headline: "The morning … and orders get *lost*".
2. **3.0–5.9 s – Routing.** A caramel "B" coin slides along the rail; behind it the rail lights caramel and splits into a curved branch down to OVEN. Order #48 card on the left (Flat white $9.00, Oat latte $5.50, Almond croissant $4.25, Total $18.75, "TAP TO PAY"). Small tickets "2× FLAT WHITE", "1× OAT LATTE" fly to BAR, "1× CROISSANT" to OVEN. Headline: "Brewst sends every order / to the *right station,*"
3. **5.9–6.9 s – Payment.** A caramel card taps the order card; a big "0.0 s" timer counts to "2.4 s"; a round "PAID" stamp lands on the card. Headline: "takes payment".
4. **6.9–8.8 s – Stock.** A "Stock" panel slides in: Oat milk bar low with chip "REORDERED · +12 by Thu", Espresso beans 4.1 kg, 12 oz cups 290 pcs. Headline: "and *restocks* before you run *out.*"
5. **8.8–11.8 s – End card.** "B" coin + "Brewst". Line types in: "Smooth service, *every cup.*" Below, a mini ticket rail where tickets flip to caramel check marks, counter "ORDERS SERVED TODAY · 250 → 251", small "BREWST.APP".

## 4. Rules
Camera slowly tracks along the rail the whole time (one continuous take). Words rise 18 px with soft overshoot. Every motion eases, nothing snaps.

## 5. Sound
Café ambience, espresso machine hiss, paper flutter, card-tap chime, rubber-stamp thud, soft acoustic guitar under the end card.

## 6. Make it yours
Swap brand, menu items and prices, stations, stock items. Keep the ticket rail as the single connecting object.
