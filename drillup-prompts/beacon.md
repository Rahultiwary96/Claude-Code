# Beacon – 8.6-second product film for an uptime-monitoring service, 16:9, one camera flight across a board from night to dawn

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A short, calm, cinematic 2.5D product film (1920×1080, 30 fps) for **Beacon**, an invented uptime-monitoring service. It checks your site every 30 seconds from several regions, wakes the right on-call person and shows exactly what broke. The camera glides across one big dark board of UI cards while the sky slowly moves from deep night to a warm dawn. Build in code (Remotion + React, or HTML/GSAP) and render to MP4.

## 1. Look
- Background: night gradient #1C1D4A → #2A2660 with a faint starfield; it warms over the film to dusk peach #E9A27A at the bottom by the end.
- Cards: frosted dark navy panels (#2B2B55 at 80%), 1 px lighter border, 12 px radius, soft shadow.
- Accent lime #C8F25A for "ok", alarm coral #F2575A for "down".
- Type: headlines in a serif (Newsreader / Libre Caslon), white, with the key words in *italic lime*. UI text in a monospace (JetBrains Mono).

## 2. Voiceover (calm, low, reassuring)
"Site down at three. Beacon checks it every thirty seconds, wakes the right person, and shows exactly what broke. Beacon. Sleep well."

## 3. Scenes
1. **0.0–1.4 s – Clock card.** "STATUS · SHOP.ACME.IO" card with a big mono clock "03:11" ticking to "03:12", green dot "Operational", a lime bar sparkline "LAST 60 MINUTES" whose last bars turn coral. Headline: "Site down / at *three*".
2. **1.4–3.5 s – Radar.** Camera slides right. A coral pulsing dot in the centre with concentric rings and a lime sweep arc counting "00:10 … 00:30". Four region chips around it: Frankfurt 41 ms, Singapore 163 ms, Virginia 88 ms, São Paulo 120 ms; three flip to coral "timeout". Headline: "Beacon checks it every *thirty seconds,*"
3. **3.5–4.3 s – On-call.** "ON CALL · TONIGHT" list: Jonas Keller, Priya Nair, Mara Okafor (highlighted with a lime border, "on-call · phone"). A white push notification slides in: red dot, "shop.acme.io is down · 3 regions · since 03:12 · tap to open". Headline: "wakes the *right person,*"
4. **4.3–6.4 s – Trace.** A trace card "TRACE · POST /CHECKOUT": rows edge 12 ms, api / checkout 30.1 s (long bar), auth 5 ms, db.orders (coral bar with chip "connection pool exhausted"), cache 3 ms. Then the coral chip turns into a lime "rolled back · resolved 03:21". Headline: "and shows exactly *what broke.*"
5. **6.4–8.6 s – End card at dawn.** Lime ring icon + "Beacon" in large serif; below, "Sleep *well.*" A full lime uptime bar "99.98 % uptime · last 90 days" and a lime pill button "beacon.watch".

## 4. Rules
One continuous horizontal camera drift with slight parallax. Words build one at a time, rising 18 px with a soft overshoot; accent colour only on the key words.

## 5. Sound
Low ambient pad, soft heartbeat-like tick for the 30-second checks, a sharp alert ping on the notification, then a warm resolve chord with birdsong-like shimmer at dawn.

## 6. Make it yours
Swap brand, domain, regions, names, error message and URL. Keep night → dawn as the emotional arc (problem → calm).
