# All DrillUp prompts (recreated) – one file

79 prompts recreated from the public example videos on drillup.io. Each section below is one complete prompt: copy everything from its heading to the next horizontal rule and paste it into Claude.

## Contents

- Amazed
- Beacon
- Brewst
- Brightcoat Painting
- Burnlo
- Chirpa
- Claude Agents
- Clinqa
- Cumulo
- Cutloop
- Docketa
- Doughly
- Dropla
- Fablo
- Fennel
- Fitlane
- Flagwise
- Greenstripe Lawns
- Gymlo
- Habita
- Harbora
- Heartbeat
- Hoplo
- Jobbo
- Kitebase
- Leafnook
- Lettra
- Liftlab
- Linto
- Mapleo
- Mathloop
- Mendly
- Mowdoc
- Murmo
- Nestwell
- Nightscan
- Nimbo
- Nodra
- Northvale Wealth
- Oakyard Sheds
- One Prompt
- Orbita
- Parcelo
- Pawpath
- Peak
- Penvia
- Podara
- Praiso
- Quiet Nights
- Quillo
- Reelo
- Rellio
- Routa
- Schemata
- Scouta
- Seatlo
- Sendra
- Sharlo
- Shopfly
- Sift
- Solidbase Concrete
- Stoka
- Streako
- Summit Movers
- Tallyo
- Tandem
- Tidy Ledger
- Tippa
- Titlo
- Tokari
- Tonic
- Trim
- Vantro
- Verdo
- Vocado
- Votely
- Wattlo
- Willow Creek Farm
- Yieldo

---

# Amazed – 10-second 3D zoom-chain spec ad for an online store, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A 10-second horizontal (1920×1080, 30 fps) 3D commercial for **"amazed"**, an invented online store (a playful nod to a big marketplace). The whole film is ONE continuous camera take through a bright, warm, soft-shadowed clay studio. Every new world lives inside an object of the previous one: phone → box → delivery van street → doorstep → cardboard logo. Build it in code (Three.js / React Three Fiber in Remotion) and render to MP4 with voice and SFX.

## 1. Look
- Off-white seamless studio (#ECEAE6), very soft ambient occlusion, matte clay materials, one soft key light top-left.
- Brand orange #F27B21, dark text #2A2725, kraft cardboard #C9A57A.
- Type: clean geometric sans (Inter/Hanken Grotesk Semibold), dark grey; the last word of each line in orange with a little orange full stop.
- Props on the table: a white phone on a stand showing a product page (black game controller, price "$69", orange "Buy now" button), a milk bottle labelled "Cola", a white jar, a small e-reader, a white "STRYDO" sneaker box, Lego-like white bricks.

## 2. Voiceover (friendly, upbeat, warm)
"Everything you want is one tap away, packed in minutes, on its way tonight, at your door by morning. Pay less, grin more." (0.1–9.6 s)

## 3. Scenes
1. **0.0–2.5 s – The shelf.** Camera drifts slowly toward the phone among the props. Headline builds word by word above it: "Everything you / is one tap **away**." Each word rises 18 px with a soft overshoot.
2. **2.5–3.3 s – Dive into the phone.** Camera pushes into the phone screen; the 3D controller lifts out of the screen and drops down.
3. **3.3–5.0 s – Packed.** The controller lands in an open kraft box seen from above; flaps fold shut, orange tape strip and a shipping label slap on. Text: "Packed" → "Packed in **minutes**."
4. **5.0–6.6 s – Night street.** The camera follows the box into a dark navy delivery van with an orange-lit rear and flies over it down a stylised night street: clay houses with warm lit windows, round globe street lamps. Text: "On its way" … "At".
5. **6.6–7.5 s – Doorstep.** Morning light; the box sits on a doormat in front of a sage-green door. Text: "At your door by **morning**."
6. **7.5–10.0 s – Logo on cardboard.** Camera dives into the box's surface, which fills the frame as a kraft background. Logotype "amazed" types on in dark brown bold with an orange smile arrow underneath. Tagline types beneath: "Pay less. Grin more."

## 4. Rules
One continuous camera path, no cuts, gentle constant motion. Each transition goes *through* an object (screen, box flap, van, box surface).

## 5. Sound
Light ukulele/marimba bed. SFX: tap, cardboard fold and tape rip, van whoosh with soft engine, door chime, a "ding" on the logo.

## 6. Make it yours
Swap brand, product on the phone, props, the four delivery steps and the tagline. Keep the object-inside-object chain.

---

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

---

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

---

# Brightcoat Painting – 10-second talking head ad for a local house-painting service, 16:9

> Recreated from the public example video. Film your own clip (person speaking to camera), then paste this prompt into Claude together with the clip and ask it to add the captions, overlays and motion design.

## 0. What you are building
A 10-second horizontal (1920×1080) talking head video for **Brightcoat Painting**, a local painter. The painter, in paint-splattered white overalls, stands in a half-painted room and speaks to camera. Claude adds animated paint-swatch overlays, kinetic captions and a quote card. Build the overlays in code (Remotion) on top of the clip.

## 1. Look
- Paper-white background (#F3F0EA) for the intro, warm-red brand colour #D9483B, cream tape #EFE3B5, dark text #1F1F1F.
- Type: bold sans (Hanken Grotesk Bold) for captions; brand accents in a bold italic serif (Newsreader Italic) in red.
- Overlays look like paint swatches and painter's tape: cards with a red top band, tape strips at the corners, slight drop shadow.

## 2. Script (spoken by the painter)
"Want your walls to look brand new? I'm Ben from Brightcoat Painting. Clean lines, zero mess, and a free quote within 24 hours."

## 3. Scenes
1. **0.0–2.5 s – Taped photo.** The clip starts small, like a photo taped to a white wall with four strips of masking tape. Behind the painter, a red paint roller stroke wipes across the wall inside the photo. Caption builds to the right: "Want your walls / to look / ***brand new?***" (last words in red serif italic).
2. **2.5–3.3 s – Full frame.** The photo grows to full frame. A red paint-swatch fan card ("BC-024") slides in on the right.
3. **3.3–5.0 s – Name card.** A swatch card with red top: small "I'm" on a tape label, big white serif "*Ben.*", bottom white area "from Brightcoat Paint**ing**" (typed on, last letters red).
4. **5.0–5.8 s – Wipe.** A full red roller stroke wipes over the frame with the word "*Clean*" in white serif, then a cream stripe underneath.
5. **5.8–7.5 s – Zero mess.** Back on Ben. A red vertical tape line wipes down; "zero" in black and "*mess*" in red italic gets struck through by the tape.
6. **7.5–8.3 s – Quote card.** "and a" tape label; a blank swatch card slides in.
7. **8.3–10.0 s – Free quote.** Card fills: "Free quote · Living room walls 2 coats · Colour BC-024 · Furniture covered yes" and a red stamp "FREE" thumps on. A round timer badge counts "4h → 24h". Tape label: "within 24 hours." A final tape strip at the bottom with "brightcoat…" typed in red.

## 4. Rules
Captions are word-synced to the speech. Every overlay enters with a soft overshoot (scale 0.9 → 1.0) and a tiny rotation like tape being stuck on. Keep the speaker's face clear.

## 5. Sound
Keep the original voice. Add a light acoustic bed, a roller "swish" on wipes, tape tear sounds, a stamp thud on "FREE".

## 6. Make it yours
Swap name, company, three promises, quote details and colour. Use your own clip.

---

# Burnlo – 11-second product film for a cash-runway forecasting tool, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A calm, editorial 2.5D product film (1920×1080, 30 fps) for **Burnlo**, an invented tool that connects to a business bank account, forecasts scenarios and shows exactly when the money runs out ("runway"). The visual metaphor is an airport **runway**: the cash runway becomes a 3D strip with a landing marker. Build in code (Remotion/React + a little Three.js for the runway) and render to MP4.

## 1. Look
- Background: warm paper off-white #EEECE6 with faint grid lines.
- Type: big high-contrast serif (Bodoni Moda / Newsreader) in near-black #111; key words in electric blue #3B3BF5. Small UI labels in a monospace.
- UI: one dark app panel (#131313) with blue line charts. Bank cards: white, thin border.
- Logo: three black vertical bars of decreasing height plus one small blue bar, then "Burnlo" in serif.

## 2. Voiceover (calm, confident)
"Your bank balance looks fine today, but how many months do you really have? Burnlo connects to your account, forecasts every scenario, and shows exactly when the money runs out. Burnlo. See further ahead."

## 3. Scenes
1. **0.0–1.8 s – Balance.** Huge serif "$482,310" header "MERIDIAN BUSINESS · ••4471 AVAILABLE BALANCE"; the number ticks down to $481,335 while small transactions appear on the right (Adobe Creative −$640, Notion Teams −$89, Figma −$511). Caption: "Your bank balance / looks fine".
2. **1.8–3.6 s – Months.** Number shrinks to the corner ($481,070). A big serif "06" appears with a row of month dashes beneath, then turns into a blue "?". Caption: "But how many **months** / do you really have?"
3. **3.6–4.5 s – Connect.** Three white account cards (Meridian Business $481,070, Payroll & Vendors −$103,200, Card Payments +$38,200) connect with thin blue lines to a dark "Runway" app panel. Caption: "Burnlo **connects**".
4. **4.5–6.3 s – Forecast.** The panel fills: "$481,070 · −$65,000 / mo", toggles for scenarios, a blue area chart descending; a dashed second scenario line appears. Caption: "forecasts / **every** / **scenario,**".
5. **6.3–8.2 s – Runway.** The chart tilts into a black 3D airport runway with white dashed centre line, piano-key threshold stripes and a big "07". A blue dot travels along the dashed line; a counter "7.4 → 0.0 months left"; a dark tag "25 May 2027". Caption: "and shows **exactly** / when the money / runs".
6. **8.2–11.0 s – End card.** Logo bars + "Burnlo". "See **further** ahead." A thin runway timeline "SEEING 01 → 20 MONTHS AHEAD" with a blue dot. Small "BURNLO.APP".

## 4. Rules
One continuous camera drift. Words build one by one with blur-in and 18 px rise. Blue only on key words.

## 5. Sound
Minimal piano + soft synth pulse, cash-counter ticks, a low jet-engine swell on the runway, a clean "ding" on the logo.

## 6. Make it yours
Swap brand, bank name, figures, the run-out date and the metaphor object if you like. Keep "fine today → how long really → exact date".

---

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

---

# Claude Agents – 25-second 3D film about AI agents working overnight, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A 25-second vertical (1080×1920, 30 fps) cinematic 3D film. It's 3:47 a.m.; a small blocky terracotta character ("Claude") still has six tasks left on a retro CRT. He types one last prompt and falls asleep. While he sleeps, a hundred agents (copies of him) wake up and do everything at once. By morning, it's done. One continuous camera flight with warm, moody light. Build in code (Three.js / React Three Fiber in Remotion) and render to MP4.

## 1. Look
- Night room: almost black with warm amber/orange light (#E07A4F character, #F0B070 highlights), floating dust particles and bokeh sparks.
- CRT monitor: black shell, curved glass with scratches and starfield, amber monospace text; a small clock "03 47" in the corner.
- Character: cube-shaped terracotta body (#D9714E), two black square eyes, stubby arms/legs, low-poly but softly bevelled.
- Claude-style starburst logo in pale cream-orange.
- Captions: white bold sans (Inter Bold) with an orange full stop.

## 2. Voiceover (narrator, quiet storyteller)
| Time | Line |
|---|---|
| 0.0–4.3 s | "3:47 a.m. Claude still has six tasks left." |
| 4.3–7.5 s | "He types one last prompt and falls asleep." |
| 7.5–10.4 s | "What he doesn't know: his agents just woke up." |
| 10.4–11.8 s | "A hundred of them." |
| 11.8–19.5 s | "Code. … Research. … Design. … All at once." |
| 20.7–22.5 s | "By morning, it's done." |
| 22.5–25.1 s | "Claude Agents. Work while you sleep." |

## 3. Scenes
1. **0.0–4.2 s – The screen.** Extreme close-up on the CRT glass; a cursor dot glows. Pull back: "claude ~/launch-day — 6 tasks left" with checkboxes: code, design, emails, research, video, numbers.
2. **4.2–6.3 s – Last prompt.** Character at the keyboard types "> just do all…", then slumps; pixel "Z z" letters float up.
3. **6.3–8.4 s – Wake-up.** The camera dives past the sleeping character into darkness; the starburst logo ignites with volumetric light rays and a reflection on a glossy floor.
4. **8.4–11.8 s – The army.** A huge grid of identical terracotta agents fills the floor; counter "64 → 100 agents" above.
5. **11.8–14.0 s – Code.** Caption "Code." A glowing terminal card "deploy.yml: deploy: region: eu, replicas: 3, status: live" with a yellow "✓ deployed" pill, agents carrying it.
6. **14.0–16.1 s – Research.** "Research." Agents stack into a tower holding papers and charts.
7. **16.1–18.3 s – Design.** "Design." Agents hold up a landing page panel "Ship it today. Get started · Simple · Yours".
8. **18.3–20.7 s – All at once.** "All at once." The grid explodes into a swirling cloud of flying agents.
9. **20.7–25.2 s – Morning.** Back at the desk with dawn light stripes through blinds. Sticky note "DEADLINE 9:00". Screen: "0 tasks left", all boxes ticked, "6/6 done ✓ · launched". Final: screen shows the starburst + "Claude Agents" in a cream serif and "Work while you sleep"; the character wakes up beside the keyboard.

## 4. Rules
One continuous camera path; slow, floating moves; heavy depth of field; light flares and particles everywhere.

## 5. Sound
Quiet room tone, clock tick, keyboard clicks, a snore, then a rising cinematic pulse when the agents wake, whooshes per task, a soft morning bird and warm chord at the end.

## 6. Make it yours
Swap the character, task list, deadline, and the three showcase tasks. Keep "night struggle → sleep → army → morning done".

---

# Clinqa – 12.3-second product film for clinic appointment reminders, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A clean, calm 2.5D product film (1920×1080, 30 fps) for **Clinqa**, an invented tool for medical practices: it reminds every patient at the right moment, lets them confirm with one tap, and fills cancellations from the waiting list. One day-schedule board carries the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: soft mint-grey #E3EEEA with a fine dot grid.
- Cards: white, 12 px radius; headers in deep teal #1F4A4A. Booked slots: mint pills #CFE8DD with dark teal avatar initials.
- Accent: raspberry red #E0365A for empty slots, underlines and the heartbeat line.
- Type: geometric sans (Hanken Grotesk / Plus Jakarta Sans) in deep teal; key words in raspberry with a hand-drawn underline.
- Logo: teal rounded-square with a raspberry ECG pulse line + "Clinqa".

## 2. Voiceover (calm, professional, kind)
"Three empty slots today, because patients simply forgot. Clinqa reminds every patient at the right moment, lets them confirm with one tap, and fills cancellations from your waiting list. Clinqa. A full day, every day."

## 3. Scenes
1. **0.0–3.0 s – Empty slots.** Schedule card "Tuesday, 14 Oct" with two columns, Dr. Okafor and Dr. Lindqvist, times 08:00–15:00, patient pills (Aiko Tanaka, Ben Okoro, Jonas Weber, Mara Lind, Nia Patel, Omar Haddad, Eva Novak, Sam Carter, Ida Berg, Leo Martin, Ruth Klein, Finn Olsen, Zoe Abbas, Paul Dietz). Three pills turn into raspberry striped "No-show" slots; counter "16/16 → 13/16". Caption: "Three **empty** / slots today," → "because / patients / simply".
2. **3.0–5.1 s – Reminder plan.** A "Reminder plan" card: three patient rows with timelines; small chips "Text", "Push" slide along each line to the right moment before "09:30 / 09:00 / 10:30 Appointment". Caption: "Clinqa reminds every patient / at".
3. **5.1–7.2 s – One tap.** A phone-style push card: "Bright Street Clinic — Hi Mara, see you today at 10:30 with Dr. Okafor. Can you make it?" chip "TUE 14 OCT · 10:30 · ROOM 2", buttons "Confirm" (teal, gets tapped) and "Reschedule". Caption: "lets them / confirm".
4. **7.2–9.2 s – Waiting list.** "Today" grid with a "WAITING LIST" bar below; when a slot shows "CANCELLED", waiting-list pills (Rosa Diaz, Yusuf Ali, Otto Brandt) fly up into it; counter "14/16 → 16/16". Caption: "and fills cancellations / from".
5. **9.2–12.3 s – End card.** Logo assembles; the pulse line draws in. "A **full** day, every day." A small heartbeat line "NO-SHOWS 18% → 6%". "CLINQA.HEALTH".

## 4. Rules
Slow continuous camera drift with depth (cards at different z). Words rise 18 px with blur-in. Raspberry only on key words.

## 5. Sound
Gentle piano/marimba, a soft heartbeat-like pulse, notification ping, confirm "tick", slot-fill pops.

## 6. Make it yours
Swap clinic, doctors, patients, reminder channels and figures. Keep one schedule board from gaps to full.

---

# Cumulo – 14-second product film for a video-meeting app, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A light, airy 2.5D product film (1920×1080, 30 fps) for **Cumulo**, an invented video-meeting app: join in one click, see everyone clearly, notes write themselves. Story: from a cluttered calendar of meetings to floating among clouds. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Opening: off-white #F4F3F7 with a dense wall of colourful calendar event cards on the right, a soft red glow bottom-left.
- Main world: bright sky-blue gradient (#6FA8E0 → #D6E8F7) with soft photoreal clouds drifting.
- Accent: indigo-violet #5B4BF0. Participant tiles: vivid gradients (blue, orange-red, teal-green, purple-pink).
- Type: modern grotesk (Inter / Hanken Grotesk) in navy #141A33; key words in indigo, with a hand-drawn indigo underline on the tagline.
- Logo: indigo rounded square with a white cloud + "Cumulo".

## 2. Voiceover (relaxed, friendly)
"Meetings shouldn't feel like work. With Cumulo, you join in one click, see everyone clearly, and your notes write themselves. So you can just talk. Cumulo. Meetings, light as air."

## 3. Scenes
1. **0.0–2.3 s – Calendar overload.** Huge blurred red word "Meetings" passes, then "Meetings shouldn't / feel like work" with a wall of tiny calendar cards scrolling on the right.
2. **2.3–4.5 s – Up into the sky.** The camera rises through the white into the cloud sky; a small indigo dot becomes the logo. "With / Cumulo, / you join in one click" and an indigo "▶ Join now" pill gets clicked by a cursor.
3. **4.5–7.3 s – The call.** A white "Weekly sync · ● REC" window with four gradient tiles (AM, JK, RS, LT) fills in one by one. "see **everyone** clearly". Then a "✦ Notes" card slides in and ticks items: "Launch moves to May 12", "Anna owns the deck", "Budget is approved". Caption: "and your notes **write themselves.**"
4. **7.3–9.3 s – Just talk.** Soft lilac/blue glow, "So you can / **just** talk." with a colourful voice waveform pulsing.
5. **9.3–14.0 s – End card.** Back to clouds; indigo dot grows into the logo. "Meetings, **light as air.**" with an underline drawn in.

## 4. Rules
Floaty, slow camera, parallax clouds, nothing snappy. Words fade/blur in with 18 px rise.

## 5. Sound
Airy pads, soft wind, a gentle click on "Join now", a chime per note tick, light chord on the logo.

## 6. Make it yours
Swap brand, participants, note items. Keep "heavy → light" as the arc.

---

# Cutloop – 10-second talking head ad for a short-form video editing studio, 16:9

> Recreated from the public example video. Film your own talking head clip, then paste this prompt with it into Claude to add the motion design.

## 0. What you are building
A 10-second horizontal (1920×1080) talking head video for **Cutloop**, an invented editing studio that cuts creators' footage into reels people actually finish. A young man in a dark hoodie speaks to camera in a cosy home studio (shelves, warm bulbs, monitor in the foreground). Overlays look like editing-software UI. Build overlays in code (Remotion).

## 1. Look
- Dark UI: near-black #141217 panels, hot pink accent #FF2E7E.
- Type: bold sans (Inter Bold) in white; accent words in pink serif italic (Playfair Display Italic); small labels in pink rounded pills.

## 2. Script
"You film it. We cut it into reels people actually finish. Send us your clips at cutloop.studio."

## 3. Scenes
1. **0.0–2.3 s – Timeline.** The clip sits small in a video editor: preview window top-left with a timecode, below a timeline with track V1 (thumbnail strip) and A1 (pink waveform), a pink playhead moving. Caption: "You *film* it." A pink "cutloop" clip tag is dragged into the timeline.
2. **2.3–3.7 s – Retention bar.** Full-frame speaker. A pink progress bar across the top fills "25% → 100%"; caption: pink pill "people", white italic "*actually*", big pink "finish."
3. **3.7–5.5 s – Reels.** Three vertical reel cards fan out on a dark pink-lit floor (with like/comment/share icons, "@cutloop"); an "Average watch time" card counts 31% → 94% with a line chart.
4. **5.5–6.5 s – Send clips.** Back on the speaker; a grey pill "Send us" and pink italic "*your clips*"; three clip thumbnails ("clip_01.mov…") in a dashed pink box.
5. **6.5–10.0 s – Export.** An "Export" dialog at the bottom: thumbnail, "Save as…" field types "cutloop.studio" (".studio" in pink), pink "at" bubble on the left, progress "Exporting… 33%" → "✓ Exported", pink "Export" button clicked by a cursor.

## 4. Rules
Captions word-synced; UI elements slide up with soft overshoot; keep the face clear.

## 5. Sound
Original voice + punchy lo-fi beat, timeline scrub sounds, click, export "whoosh-ding".

## 6. Make it yours
Swap studio name, domain and stats; use your own clip.

---

# Docketa – 10.8-second product film for an AI contract-review tool, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A calm, editorial 2.5D product film (1920×1080, 30 fps) for **Docketa**, an invented AI contract reviewer: it reads every clause, marks risk and suggests wording a lawyer would approve. A stack of contract pages and a highlighter-yellow marker carry the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: sage-grey #DCE3D6 with large faint "§" symbols.
- Paper: cream pages #F4F1E6 with grey text lines and serif headings.
- Brand: deep forest green #1F4A33 panels; highlighter yellow #F2D23C.
- Type: bold serif (Newsreader / Source Serif Bold) in forest green; key words highlighted with a yellow marker swipe.
- Logo: a document icon with a yellow highlight stroke + "Docketa".

## 2. Voiceover (calm, assured)
"Forty pages of contract, and the risk hides in one sentence. Docketa reads every clause, marks what could hurt you, and suggests wording your lawyer would approve. Docketa. Sign with confidence."

## 3. Scenes
1. **0.0–1.8 s – The pile.** Pages fan out in a row; a chip "MSA_Northwind_v4.pdf · 31 → 40 pages". Caption: "**Forty** pages of contract,".
2. **1.8–3.6 s – One sentence.** One page lifts: "MASTER SERVICES AGREEMENT" with headings 12 Term and renewal, 13 Fees and payment, 14 Limitation of liability, 15 Restrictive covenants. A line pulls out as a strip: "§ 14.2 The Supplier's liability shall be unlimited in amount." Caption: "and the risk hides / in **one sentence.**"
3. **3.6–6.3 s – Reading.** A green Docketa panel next to the page: "CLAUSES READ 6 → 62 / 62" with a progress row of ticks; on the page, lines highlight yellow as they're read. Then the panel lists flagged clauses: "Auto-renewal · Unlimited liability (HIGH, yellow) · Non-compete". Caption: "Docketa reads / **every clause,**" → "marks what / could **hurt** you,".
4. **6.3–8.1 s – Suggestion.** A cream suggestion card: "Unlimited liability · HIGH"; text "The Supplier's liability under this Agreement shall be ~~unlimited~~ limited to the fees paid in the twelve months before the claim." (new text highlighted yellow), buttons "Dismiss" / "Accept" (clicked). Caption: "and suggests wording / your lawyer would approve."
5. **8.1–10.8 s – End card.** Logo; "Sign with **confidence.**" A "RISK SCORE" slider slides 76 → 27. "DOCKETA.COM".

## 4. Rules
Slow continuous camera drift; paper has subtle 3D tilt and shadow; highlighter swipes left-to-right over 0.3 s.

## 5. Sound
Soft piano, paper rustle, highlighter squeak, a click on Accept, warm chord at the end.

## 6. Make it yours
Swap brand, document type, clause and risk score.

---

# Doughly – 11-second product film for a bakery pre-order tool, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A warm, cosy 2.5D product film, square (1080×1080, 30 fps), for **Doughly**, an invented tool that collects bakery pre-orders and tells the baker exactly what to bake tonight. One dark baking tray with 12 round bread rolls carries the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: warm cream #F3EEE6 with soft vignette.
- Tray: dark chocolate brown #3A2A24, rounded, with 12 circular slots; rolls are golden-brown with a white score line, soft shadows.
- Accent: raspberry #C8285A for key words (with an underline) and badges.
- Type: friendly bold serif (Recoleta / Fraunces) in espresso #3A2A24. UI in Inter.
- Logo: "Doughly" where the "o" is a golden roll with a raspberry check mark.

## 2. Voiceover (warm baker voice)
"Baking too much means waste. Baking too little means empty shelves by nine. Doughly collects every pre-order and tells you exactly what goes in the oven tonight. Doughly. Bake what sells."

## 3. Scenes
1. **0.0–1.8 s – Too much.** Full tray, clock chip "8:45 Mon" → "18:00 Mon": most rolls are still there and one goes pale/stale. Caption: "Baking too much / means waste".
2. **1.8–4.2 s – Too little.** "7:00 Tue" tray with only 6 rolls; they vanish one by one until empty at "8:30 Tue" / "9:00 Tue". Speech bubbles pop: "Any sourdough left?", "Croissants?", "Sold out already?". Caption: "Baking too little / means **empty** shelves / by nine."
3. **4.2–6.4 s – Pre-orders.** A white "Pre-orders · for Thu 15 Oct" card fills rows: Maya R. (pickup 7:30, Web) Sourdough ×2, Jonas K. (Phone) Croissants ×6, Café Alba (Web) Croissants ×24, Tom B. (Counter) Cinnamon buns ×4, Ines O. (Web) Sourdough ×1; badge "3 → 23 orders". Caption: "Doughly collects / every **pre-order,**".
4. **6.4–8.2 s – Tonight's bake.** "Tonight's bake" card: Cinnamon buns 12 (1 tray), Sourdough 14 (2 trays), Croissants 36 (3 trays). Raw dough balls fill the tray "4 of 12 → 12 of 12 on the tray", then a chip "220° Oven 1 · 4:30 am". Caption: "tells you **exactly** / what goes in / the oven".
5. **8.2–11.0 s – End card.** Logo forms; "Bake what **sells.**" A row of 12 roll dots fills: "8 of 12 sold · 0 left over". "DOUGHLY.APP".

## 4. Rules
Camera gently pushes in; rolls pop in/out with squash-and-stretch. Words rise 18 px with soft overshoot.

## 5. Sound
Morning bakery ambience, oven door, soft "pop" per roll, chat bubble blips, cheerful guitar resolve.

## 6. Make it yours
Swap bakery items, names, numbers. Keep one tray going from waste → empty → just right.

---

# Dropla – 11.2-second product film for a link-in-bio shop, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A bold, playful vertical product film (1080×1920, 30 fps) for **Dropla**, an invented tool that turns a creator's single bio link into a tiny shop, takes payment in two taps and shows what sells. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: butter yellow #F6E9B8 with big soft darker-yellow drop shapes and a faint "+" grid.
- Accent: hot pink #EE3E95; black #141414 pills and cards.
- Type: extra-bold rounded grotesk (Archivo Black / Satoshi Black) in black; key words in a pink tilted label with black script italic (e.g. Pacifico).
- Logo: pink water-drop with a smile + "Dropla".

## 2. Voiceover (energetic creator vibe)
"Your audience is ready to buy. Your bio has one link. Dropla turns it into a tiny shop, takes payments in two taps, and shows what sells. Dropla. Sell from your bio."

## 3. Scenes
1. **0.0–1.6 s – Comments.** Avatar "@miakoro · 48,188 → 48,236 followers · Creator" surrounded by popping comment bubbles: "link??", "price??", "where can I buy?", "need it!", "take my money", "link please!", "is it in your bio?". Caption: "Your audience / is *ready to buy.*"
2. **1.6–3.0 s – One link.** A black bio-link pill "miakoro.me ↗" with a pink "99+" badge, a row of tiny avatars. Caption: "Your bio has one link."
3. **3.0–4.6 s – Tiny shop.** The pill grows into a black-header card "Mia's shop 🛍 3" with product tiles: Golden Hour Presets $19, Reel Templates $29, Sticker Pack $8, 1:1 Feed Review. Caption: "Dropla turns it / into a *tiny shop,*"
4. **4.6–6.4 s – Two taps.** Zoom into "Golden Hour Presets · 12 presets · Digital · $19" with a black "Buy now" button; it turns into a pink slider "Paid ✓" with taps "1", "2". Caption: "takes payments / in *two taps,*"
5. **6.4–7.8 s – What sells.** A black dashboard card "Today · Live · $1,180 (+$19) → $1,228", "TOP SELLERS: Golden Hour Presets 41, Reel Templates 23". Caption: "and shows / *what sells.*"
6. **7.8–11.2 s – End card.** The pink drop falls and lands; "Dropla", "Sell from your *bio.*", a black link pill "dropla.shop/mia →" and floating "+$29", "+$19" stickers.

## 4. Rules
Bouncy springs, slight sticker rotations, pop-ins with overshoot.

## 5. Sound
Upbeat pop beat, bubble pops for comments, cash-register "ka-ching" on Paid, drop "bloop" on the logo.

## 6. Make it yours
Swap creator handle, products and prices.

---

# Fablo – 10.5-second product film for an AI product-photo studio, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A sleek 2.5D product film (1920×1080, 30 fps) for **Fablo**, an invented AI tool that turns a quick phone photo of a product into studio shots: cut-out, studio scene, 12 ready images in a minute. Hero product: an amber perfume bottle "Amber No. 4". Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: soft mid-grey studio gradient #5C5C5C → #8A8A8A with a floor horizon.
- Accent: warm orange #F08A2C. App UI: dark charcoal panels.
- Type: clean sans (Inter Medium) in white; key words in orange italic serif.
- Logo: orange circle with a white starburst/aperture + "Fablo" in white.
- Recurring motif: a camera exposure scale "EXPOSURE −2 … +2 EV" under the end card.

## 2. Voiceover (cool, confident)
"One quick phone photo, and your product still looks like a phone photo. Fablo cuts it out, builds the studio scene around it, and delivers twelve ready shots in a minute. Fablo. Studio quality, no studio."

## 3. Scenes
1. **0.0–1.7 s – Phone photo.** A camera viewfinder frame (corner brackets, focus square) over a mediocre photo of the bottle on a wooden table next to a mug, with a cable. Caption: "One quick phone photo,".
2. **1.7–3.4 s – Online shop.** The photo sits in a white shop page "orla.store · Amber No. 4 · Eau de parfum 50 ml · $68.00 · Add to bag"; stats "Views 201/214 · Conversion 2.0% → 0.3% · Sales 0". Caption: "and your product / still looks like / *a phone photo.*"
3. **3.4–4.4 s – Cut out.** The dark Fablo editor: the photo, a marching-ants mask, then the background disappears. Caption: "Fablo / *cuts it*".
4. **4.4–6.0 s – Studio scene.** The bottle now on a white plinth, softboxes appear left and right, colour swatches and sliders (Key light, Fill light, Soft shadow) adjust; orange "Render 12 shots" button. Caption: "builds the / *studio scene* / around it,".
5. **6.0–7.8 s – Twelve shots.** A 4×3 grid of different studio shots (pastel backdrops, stone, dark), counter "12/12 · 0:32 → 0:58". Caption: "and delivers / *twelve* ready shots / in *a minute.*"
6. **7.8–10.5 s – End card.** Logo; "Studio quality, *no studio.*"; exposure scale needle moving −1.7 → −0.1 EV; "FABLO.STUDIO".

## 4. Rules
Continuous slow camera drift; panels slide with depth; shutter-flash on each finished shot.

## 5. Sound
Minimal electronic beat, camera shutter clicks, softbox "thunk", ding at 12/12.

## 6. Make it yours
Swap product, shop and stats.

---

# Fennel – 10.8-second product film for restaurant recipe costing, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A warm, trattoria-style 2.5D product film, square (1080×1080, 30 fps), for **Fennel**, an invented tool that costs every recipe down to the gram and warns when a dish stops making money. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: dark green gingham tablecloth (#3E5A2C / #4E6B38 checks) with soft vignette.
- Cards: cream paper #F2EBD3 with thin borders, like menu cards and market price tags hanging on string.
- Accent: tomato red #D9362B for rising prices, warnings and key words.
- Type: elegant serif (Newsreader / EB Garamond) in cream on green and espresso on paper; prices in a bold serif.
- Logo: cream circle with a fennel-bulb line icon + "Fennel" in bold serif.

## 2. Voiceover (calm chef/owner)
"Prices at the market change every week. Your menu doesn't. Fennel costs each recipe down to the gram, and warns you the moment a dish stops making money. Fennel. Know your margins."

## 3. Scenes
1. **0.0–2.6 s – Market tags.** Three tags on a string: FENNEL per kg €2.40 → €3.40 (+42%), SEA BREAM €19.50 → €26.80 (+37%), OLIVE OIL per litre €9.80 → €12.38 (+27%). Mini bar charts (W14–W19) grow with a red last bar. Caption: "Prices at the market / **change** every week."
2. **2.6–3.4 s – Menu.** Tags shrink up; a "Lunch · printed in March" menu card: Sea bream, shaved fennel 18.00; Burrata, charred leeks 13.00; Rigatoni al limone 17.50. Caption: "Your menu **doesn't.**"
3. **3.4–5.4 s – Costing.** The sea bream line becomes the header. A plate with fish, fennel, lemon, capers sits on a kitchen scale (readout 91 g → 10 g); a recipe card fills: Sea bream 180 g €3.51, Fennel 150 g €0.36, Lemon 40 g €0.14, Olive oil 20 ml €0.19 → "Plate cost €4.18 · food cost 23.2%". Caption: "Fennel costs each recipe / down to the gram".
4. **5.4–8.0 s – Warning.** Prices update in red: Sea bream €4.82, Fennel €0.51, Olive oil €0.25, plus Capers €0.19 → "Plate cost €5.91". A round gauge "MARGIN 75.6% → 67.2%" turns red against "TARGET 70%". A red alert card: "⚠ MARGIN ALERT · Below your 70% target · Raise to €20.00 →". Caption: "and warns you the moment / a dish **stops** making money."
5. **8.0–10.8 s – End card.** Logo; "Know your **margins.**" A ruler scale 60%–80% with a red marker 67.2% → 69.8%. "FENNEL.KITCHEN".

## 4. Rules
Tags sway gently on the string; cards slide with depth; numbers tick; words fade-rise.

## 5. Sound
Market chatter, a soft accordion/guitar bed, scale beep, warning bell, warm resolve.

## 6. Make it yours
Swap ingredients, dish, prices, target margin.

---

# Fitlane – 10.6-second product film for a personal-trainer app, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A sporty, dynamic vertical product film (1080×1920, 30 fps) for **Fitlane**, an invented coaching app: it sends each workout to clients' phones, counts every rep, and shows the coach who needs a push. Visual motif: running-track lanes (lines across the frame with lane numbers 1–7). Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: dark slate #1C1F26 with thin diagonal speed lines and a ruler/track tick strip at the bottom.
- Accent: electric blue #2F5BFF; text white.
- Type: ultra-condensed heavy italic sans (Druk Wide Italic / Anton Italic / Bebas Neue italic) for headlines; key words in blue with underline. UI in Inter.
- Logo: blue rounded square with a white "F" + dot, "Fitlane" in huge condensed italic.

## 2. Voiceover (motivating coach)
"Your clients train alone six days a week. Fitlane sends each workout to their phone, counts every rep, and shows you who needs a push. Fitlane. Coach beyond the hour."

## 3. Scenes
1. **0.0–2.6 s – The week.** "Jonas R. · Week 12 · His plan" with 7 lanes MON–SUN (italic lane numerals). Only THU has a blue "1:1 with you · 60 min". Other days show dashed "Solo" pills; badge "SOLO DAYS 6". Then they fill: Upper body 40 min, Mobility 20 min, Intervals 30 min, Lower body 35 min, Core 15 min. Caption: "Your clients train / **alone** six days a week."
2. **2.6–4.4 s – Phone.** A phone slides up: "Today · from Coach Alex", week strip 13–19 with 17 selected, "Lower body 35 min" with Goblet squat 3×12, Romanian deadlift 3×10, Walking lunge 3×12, "+2 more exercises", blue "Start workout →" button (tapped), "Tomorrow: Core 15 min". Caption: "Fitlane sends each / **workout** to their phone,"
3. **4.4–5.3 s – Rep counter.** Phone shows "Goblet squat · Set 2 of 3 · 12 reps", a motion waveform, huge "8" "OF 12 REPS", segmented blue progress, set chips "12✓ · 8 · –", "Next: Romanian deadlift · rest 0:45". Caption: "counts every **rep,**"
4. **5.3–7.0 s – Coach view.** "This week · 4 clients" card with lanes: Ines B. 5/5, Jonas R. 4/5, Mara K. 1/5 (highlighted, "last trained Mon", with a blue "Send push" button tapped), Tom S. 4/5. Caption: "and shows you / who needs a **push.**"
5. **7.0–10.6 s – End card.** Logo; "Coach **beyond** the hour." A 7-segment blue week bar MON–SUN fills. "FITLANE.APP".

## 4. Rules
Fast but smooth: whip-pans along the lanes, slight motion blur, everything skewed ~8° like italic type.

## 5. Sound
Driving electronic beat, sneaker squeaks, rep "beep" per count, whoosh on push.

## 6. Make it yours
Swap client names, exercises, coach name.

---

# Flagwise – 10.2-second product film for feature flags, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A developer-flavoured 2.5D product film (1920×1080, 30 fps) for **Flagwise**, an invented feature-flag tool: switch a feature on for 1%, watch the numbers, roll back with one click. Headlines are typed like a terminal with a block cursor. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: dark graphite #1E2127 with soft vignette.
- Panels: #2A2E36 with 1 px border, 10 px radius.
- Accents: signal green #3BE37F (safe), alert red #F0545A (risk).
- Type: monospace throughout (JetBrains Mono / IBM Plex Mono), white; key words green or red; a green block cursor "█" after typed text.
- Logo: green toggle switch (knob with a flag) + "flagwise" in bold mono.

## 2. Voiceover (dry, confident engineer)
"Shipping a feature to everyone at once is a gamble. Flagwise lets you switch it on for one percent, watch the numbers, and roll back with a single click. Flagwise. Release without the risk."

## 3. Scenes
1. **0.0–2.5 s – Gamble.** Terminal line "$ deploy new-checkout --all-users" with a progress line. Next to it a "users.live" grid of 10×10 dots; percentage 0% → 83% → 100% as all dots light white; then a cluster turns red and "errors 0 → 14". Typed caption: "Shipping a / feature to / everyone / at once is / a **gamble.**"
2. **2.5–4.2 s – The flag.** Panel "⚑ new-checkout · production" with a toggle (off), round gauge 0%, rollout slider 0–1–10–50–100%, "exposing 0 of 100 users", "↺ instant rollback". The toggle flips green; slider snaps to 1%; one dot lights. Caption: "Flagwise lets you / switch it on for **1%**".
3. **4.2–6.8 s – Watch.** Panel tilts to an "error_rate" chart: flat green line at 0.4%, then it spikes red to 2.9% → 4.7%; metric chips "p95_latency 182 → 628 → 928 ms", "checkout_rate 3.1 → 2.0 → 1.2%", "exposed_users 1%". The cursor clicks the toggle off. Caption: "watch the / **numbers,** / and roll / back with / a single click."
4. **6.8–10.2 s – End card.** Toggle + "flagwise"; "Release without the **risk.**" A rollout slider glides 1% → 35% → 96% with a dotted bar filling green. "flagwise.dev".

## 4. Rules
Typing at ~25 chars/s with a blinking cursor; panels glide with slight perspective; numbers tick.

## 5. Sound
Minimal techno pulse, keyboard typing, toggle click, error buzz, a calm "click" on rollback, success chime at the end.

## 6. Make it yours
Swap flag name, metrics and URL.

---

# Greenstripe Lawns – 10-second talking head ad for a lawn-care service, 9:16

> Recreated from the public example video. Film your own selfie clip in a garden, then paste this prompt with it into Claude to add the motion design.

## 0. What you are building
A 10-second vertical (1080×1920) talking head ad for **Greenstripe**, a local weekly lawn-care service. A woman films herself selfie-style in a back garden and speaks to camera. Claude adds kinetic captions, a lawn-health meter, a checklist card and a striped-lawn end card with a lawn sign. Build overlays in code (Remotion).

## 1. Look
- Brand greens: #3DBE5C (light stripe) / #2EA64C (dark stripe) like a freshly mown lawn; white cards; dark text #1D1D1D.
- Type: bold sans (Inter Bold) white with soft shadow; emphasis words in white serif italic (Playfair Display Italic) inside a green box.
- Logo: green circle with three white grass blades + "Greenstripe", tagline "Lawn care, every week".

## 2. Script
"Patchy, tired lawn? We fix that. Mowing, feeding, edging, every week. greenstripelawns.com"

## 3. Scenes
1. **0.0–1.7 s – Hook.** Caption builds letter by letter "Patchy," then "*tired*" (serif italic) then "lawn?". A small white "Lawn" card with a circular meter at 34% (brownish arc) pops in top-right.
2. **1.7–2.5 s – Mower wipe.** A cartoon push-mower icon drives down the frame, leaving vertical green stripes that wipe over the video.
3. **2.5–3.3 s – We fix that.** Clip framed between green stripes; meter rises 34% → 49%. Caption: "We fix / *that!*" (green box).
4. **3.3–6.5 s – Checklist.** White card with green header "Greenstripe": circles tick one by one with the speech: ✓ Mowing, ✓ Feeding, ✓ Edging, then "↻ every week." in green.
5. **6.5–10.0 s – End card.** Full-frame lawn stripes. A white lawn sign on a post slides up from the ground: logo, "Greenstripe · Lawn care, every week" and a pill where "greenstripelawns.com" types out. The mower crosses behind the sign.

## 4. Rules
Captions word-synced; overlays pop with spring; stripes always vertical and alternating.

## 5. Sound
Original voice, light upbeat acoustic bed, mower buzz on the wipe, tick sounds for the checklist.

## 6. Make it yours
Swap business, services and URL; use your own clip.

---

# Gymlo – 10-second product film for fitness-class booking, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A bold, graphic 2.5D product film, square (1080×1080, 30 fps), for **Gymlo**, an invented class-booking tool for gyms: it handles bookings, moves the waitlist up automatically and checks members in at the door. One HIIT class roster (16 spots) carries the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: light concrete grey #E6E6E4 with faint circular gauge lines/text around the edges.
- Paper booking list on a black clipboard clip; app UI in black #151515 panels.
- Accent: coral red #F2474A.
- Type: condensed heavy sans in all caps (Bebas Neue / Oswald Bold) in black; key words in red.
- Logo: "GYMLO" in heavy caps with the "O" as a red progress ring.

## 2. Voiceover (energetic instructor)
"Classes are full on paper, and half empty in real life. Gymlo handles bookings, moves the waitlist up automatically, and checks members in at the door. Gymlo. A full class, every time."

## 3. Scenes
1. **0.0–2.5 s – Paper vs room.** Clipboard "BOOKING LIST · Tue 13 Oct": "HIIT 45 · 18:00 · Studio 1 · Coach Dana · 45 min", grid of 16 black avatar circles (MA, JO, LI, TK, SR, EV, PB, HN, CD, AW, RF, YS, NO, GM, DT, UL). "BOOKED ON PAPER 14 → 16/16 · FULL · Waitlist: 3 people". Then "IN THE ROOM 10/16": six circles become dashed empty, chip "6 NO-SHOWS", "Nobody moved up". Caption: "CLASSES ARE FULL ON PAPER, / AND **HALF EMPTY**".
2. **2.5–3.3 s – App.** A black Gymlo dashboard flies in: tabs Schedule / Members / Check-in, a week grid with a red slot, stats.
3. **3.3–5.6 s – Waitlist.** "HIIT 45 · 18:00 16/16 FULL", stats "Bookings 48 · Classes 5 · No-shows 0". One spot shows "CANCELLED"; the waitlist column (#1 NK Noa, #2 BT Ben, #3 IM Ida) — NK slides into the free spot; toast "Auto-move: Noa K. moved up from the waitlist". Caption: "GYMLO HANDLES **BOOKINGS,** / MOVES THE WAITLIST UP / **AUTOMATICALLY,**"
4. **5.6–7.4 s – Door check-in.** A door-tablet card "STUDIO 1 · DOOR · 17:54": big circle "NK", "NOA KELLER · HIIT 45 · 18:00 · Spot 7", "SCANNING PASS" → red "✓ CHECKED IN"; "IN THE ROOM 12/16 → 16/16". Avatars "NEXT IN LINE" queue up. Caption: "AND CHECKS MEMBERS / IN AT THE **DOOR.**"
5. **7.4–10.0 s – End card.** Logo with the O ring filling; "A **FULL** CLASS, EVERY TIME." A MON–SUN row of red bars each "16/16". "GYMLO.APP".

## 4. Rules
Punchy but clean: cards slam in with a slight bounce, avatars pop, counters tick.

## 5. Sound
Gym beat with heavy kick, whistle on the hook, NFC beep on check-in, crowd-cheer sting at the end.

## 6. Make it yours
Swap class, coach, names and numbers.

---

# Habita – 10.8-second product film for small landlords, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A soft, friendly 2.5D product film, square (1080×1080, 30 fps), for **Habita**, an invented app for small landlords: tracks every rent payment, sends reminders, builds the yearly statement by itself. A little house with six arched apartment windows carries the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: dusty rose/blush #EBCFC4 with faint arch shapes.
- House: cream #F6EEDF outline drawing with six arched door-windows (1A, 1B, 2A, 2B, 3A, 3B), chimney, a number badge on the roof.
- Accents: teal #1E7A6E (paid / brand), coral red #D9534F (late).
- Type: chunky slab/typewriter serif (Clarendon / Cooper / "Rockwell"-like) in espresso #3A2620; highlighted words inside a white outlined pill with a small teal dot.
- Logo: teal arched door icon + "Habita".

## 2. Voiceover (calm, relieved landlord)
"Six apartments, six spreadsheets, and one rent that's late again. Habita tracks every payment, sends the reminder for you, and builds the yearly statement by itself. Habita. Renting made simple."

## 3. Scenes
1. **0.0–1.8 s – Chaos.** The house draws in (badge 3 → 6 as windows fill). Little spreadsheet cards ("rent_2A.xlsx", "rent_1B.xlsx"…) fly around it. Caption: "Six apartments, / six spreadsheets,".
2. **1.8–3.5 s – Late.** Windows turn teal with ✓ amounts: 3A €880, 3B €1,020, 2A €910, 1A €820, 1B €760; 2B stays dashed red "LATE" with a tag "7 days late". Caption: "and one rent / that's **• late** again."
3. **3.5–6.2 s – Payments.** A "Payments · October 2025" card: A. Brandt €820, L. Moreau €760, S. Jensen €910, M. Okafor €940 (Late · 12 days), T. Novak €880, R. Castell €1,020; counter "1/6 → 5/6 → 6/6 paid". A "Rent reminder" popup sends; Okafor flips to "✓ Paid". Caption: "Habita tracks every payment, / sends the **• reminder** for you,"
4. **6.2–8.0 s – Statement.** "Yearly statement · 2025 · Lindenweg 14 · 6 apartments" with a teal 12-month bar chart; "Rent received €63,960 · Running costs −€9,480 · Net income €54,480", a round teal stamp "✓ AUTO-BUILT", "Ready for your tax advisor". Caption: "and builds the yearly / statement by **• itself.**"
5. **8.0–10.8 s – End card.** Door icon swings open; "Habita"; "Renting made **• simple.**" Six small arches fill teal with ticks. "habita.app".

## 4. Rules
Gentle springs, soft shadows, camera slowly pushes in.

## 5. Sound
Light pizzicato strings, paper flutter, notification ping, stamp thud, door creak + chime on the logo.

## 6. Make it yours
Swap tenant names, amounts, address and units.

---

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

---

# Heartbeat – 22-second 3D explainer film: how a smartwatch measures your pulse, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A 22-second horizontal (1920×1080, 30 fps) cinematic 3D explainer: how a smartwatch's optical sensor (PPG) reads your heartbeat. The camera starts on a smartwatch on a wrist, dives under the watch into the skin, flies along a blood vessel, and comes back out to the screen. One continuous camera move. Ends with a social call to action ("Comment WATCH for the link"). Build in code (Three.js / React Three Fiber in Remotion) and render to MP4.

## 1. Look
- Warm, dark, moody lighting; skin tones in warm peach/terracotta, deep blacks.
- Watch: black aluminium case, dark screen with a red heart-rate UI: big "148 BPM", heart glow, "2 Minute History" dotted chart.
- Inside: layered skin (pinkish-tan tissue), a translucent capillary network, a blood vessel full of red blood cells (instanced discs), green LED light beams and concentric green light rings from the sensor.
- Labels: dark pill with a dot, white caps "GREEN LED", "BLOOD VESSEL", with a thin leader line.
- Captions: white bold sans (Inter Bold), centred lower third, key words in green #4CE38A on the CTA.

## 2. Voiceover (curious explainer tone)
| Time | Line |
|---|---|
| 0.0–3.0 s | "Your watch doesn't actually feel your heartbeat." |
| 3.0–4.5 s | "It watches your blood." |
| 4.5–8.5 s | "Underneath, green lights flash hundreds of times every second." |
| 8.5–10.5 s | "Your blood absorbs that light." |
| 10.5–14.5 s | "Every heartbeat pushes more blood through, so less light comes back." |
| 14.5–17.5 s | "The watch reads that rhythm, filters out your motion…" |
| 17.5–19.5 s | "…and turns it into your heart rate." |
| 19.5–21.9 s | "Comment WATCH for the link." |

## 3. Scenes
1. **0.0–3.0 s – Wrist.** A wrist with a smartwatch showing 148 BPM; slow push-in with bokeh lights.
2. **3.0–4.5 s – Under the watch.** The camera slips under the case: the sensor back of the watch above, the skin surface below.
3. **4.5–8.5 s – Green LEDs.** Two green LEDs fire pulsing beams down into the skin; label "GREEN LED"; capillaries glow.
4. **8.5–12.5 s – Blood vessel.** Fly along a vessel filled with red blood cells; label "BLOOD VESSEL"; green light is absorbed (beams fade in the blood). A pulse wave pushes a denser surge of cells.
5. **12.5–14.5 s – Less light back.** Concentric green rings at the sensor shrink/dim with each pulse ("so less light comes back").
6. **14.5–17.5 s – The signal.** Back out to the screen: a messy orange waveform "Heart Rate 10:09" is cleaned into a neat red ECG-like line.
7. **17.5–21.9 s – Result + CTA.** Screen: big heart glow "148 BPM" with the 2-minute dotted history. Caption "Comment **WATCH** for the link".

## 4. Rules
One unbroken camera path; slow and smooth; depth of field always on; light particles float in the air.

## 5. Sound
Deep ambient score, a steady heartbeat thump that syncs with the blood pulses, soft electronic hum for the LEDs, a bright UI blip on the final reading.

## 6. Make it yours
Use the same structure to explain any device ("it doesn't X, it Y"). Swap the CTA keyword.

---

# Hoplo – 10.1-second product film for event ticketing and door check-in, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A nightlife-styled vertical product film (1080×1920, 30 fps) for **Hoplo**, an invented ticketing app for venues: it sells tickets, scans each guest in a second and shows who's inside. A queue of dots, a door card and a ticket carry the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: deep violet-purple #2A1648 with a darker bottom; a faint pixel/LED dot-matrix pattern at the bottom.
- Accent: ticket yellow #F5B82E; cards in dark purple #3A2560; tickets in off-white #F1ECEF.
- Type: heavy geometric sans (Sora / Clash Display Bold) white; key words yellow with a dotted underline. Labels in monospace.
- Logo: yellow ticket stub with a dotted "H" + white ticket body with "Hoplo".

## 2. Voiceover (club promoter, upbeat)
"The doors open at eight, and the queue is already around the block. Hoplo sells the tickets, scans each guest in a second, and shows who's inside. Hoplo. Doors open, no queue."

## 3. Scenes
1. **0.0–3.4 s – Queue.** Door card "LANTERN HALL · CAP. 480 · DOORS 19:59 · CLOSED" flips to yellow "20:00 · OPEN"; a light cone spills from the door. A line of white dots (the queue) loops around the card; counter "IN LINE 131 → 163 → 196 · 47 MIN WAIT". Caption: "The doors open / at **eight,** / the queue is already around / the **block.**"
2. **3.4–4.2 s – Ticket.** A ticket slides in: "HOPLO · ADMIT ONE · NIGHT SHIFT · Live at Lantern Hall · Sat 24 Oct · Doors 20:00 · Price €24.00", yellow "PAID" stamp, perforation, QR code, "Guest Mia Kowalski · GA · No. 0312 · Order #HP-48213"; pill "Tickets sold 471 / 480". Caption: "Hoplo sells / the **tickets,**"
3. **4.2–5.9 s – Scan.** The ticket stub alone; a yellow scanner frame snaps on the QR, check mark, "● VALID · 0.8 s". A "LAST SCANS · DOOR A" log scrolls: 20:01:07 ✓ 0312 M. Kowalski GA, 0311 J. Okafor GA, 0310 S. Lindqvist VIP, 0309 T. Brandt GA… Caption: "scans each guest / in a **second,**"
4. **5.9–7.5 s – Inside.** Dashboard "Night Shift · Lantern Hall · Door A · ● LIVE 20:01": "INSIDE NOW 311 → 317 / 480 · ↑31/min", a yellow progress bar, a dot grid (1 dot = 4 guests) filling, recent check-ins list. Caption: "and shows / who's **inside.**"
5. **7.5–10.1 s – End card.** Logo ticket; "Doors open, / **no queue.**" Queue dots disappear: "IN LINE 195 → 76 → 0". "HOPLO.EVENTS".

## 4. Rules
Smooth vertical camera slide, neon glow on yellow elements, bass-synced pulses.

## 5. Sound
Club bass muffled behind a door, crowd murmur, door unlock clunk, scanner beep per guest, music fully opens on the end card.

## 6. Make it yours
Swap venue, event, price and numbers.

---

# Jobbo – 10-second product film for tradesperson quoting, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A vertical product film (1080×1920, 30 fps) for **Jobbo**, an invented app for contractors: it measures a room from a photo, lists every item and sends the quote before you leave the driveway. A yellow tape measure runs along the bottom of the frame the whole time, and a little contractor van drives along it. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: denim/navy blue gradient #2B4170 → #1C2C50 with faint blueprint grid.
- Accent: tape-measure yellow #F5C623; cards white; text navy.
- Type: rounded bold sans (Nunito Black / Gilroy) in white; key words yellow with underline.
- Logo: "Jobbo" in heavy white where the "J" is a yellow tape-measure hook.

## 2. Voiceover (friendly tradesperson)
"You're on site all day and write quotes at midnight. Jobbo measures from a photo, lists every item, and sends the quote before you leave the driveway. Jobbo. Quote on the spot."

## 3. Scenes
1. **0.0–2.5 s – The day.** A vertical day timeline 7 AM → 12 PM → 5 PM → 12 AM with a yellow dot moving down. Job cards: "Bathroom refit · Dana Miller, 8:20 AM", "Kitchen tiling · Sam Ortiz, 11:40 AM", "Hallway floor · Lin Chen, 3:00 PM", each with "NO QUOTE". At midnight a "TONIGHT" card: "☾ Quotes to write · 3 OPEN · NOW 12:00 AM · 0 OF 3 SENT" with scribbles and a pencil. Caption: "You're on site all day / and write quotes / at **midnight.**"
2. **2.5–4.2 s – Measure.** A tablet frame shows an isometric bathroom (tub, window, mirror, door); yellow dimension lines snap on: 10.5 ft, 8.0 ft, 5.0 ft, 7.0 ft; chips "FLOOR 73.5 sq ft · WALL TILE 84.0 sq ft". Caption: "Jobbo measures / from a **photo,**"
3. **4.2–5.0 s – Items.** "Quote #214 · FROM 1 PHOTO · Bathroom refit": 01 Demo & haul-away $450, 02 Floor tile 73.5 sq ft × $12 $882, 03 Wall tile 84 sq ft × $14 $1,176, 04 Tub install $640, 05 Labor 16 h × $65 $1,040 → "TOTAL 5 items $3,085 → $4,188". Caption: "lists every item,"
4. **5.0–7.5 s – Send.** A client card "DM Dana Miller · Homeowner, bathroom refit · CLIENT" receives "Quote #214 · $4,188", "Delivered 8:26 AM ✓✓", she types "Looks great. Let's do it". A chip "PHOTO TO QUOTE 0:53 → 2:48 min". The van drives along the tape. Caption: "and sends the quote / before you leave / the **driveway.**"
5. **7.5–10.0 s – End card.** Logo; "Quote on the **spot.**" Three job chips 8:26 AM ✓, 11:47 AM ✓, 3:08 PM (pending); "2 of 3 quotes sent on site". "JOBBO.APP".

## 4. Rules
The tape measure scrolls with the camera (numbers 40 → 300), acting as a progress bar. Cards slide with a soft bounce.

## 5. Sound
Upbeat acoustic/whistle bed, tape-measure zip on measurements, cash-register ding on total, van horn beep at the end.

## 6. Make it yours
Swap trade, jobs, line items and prices.

---

# Kitebase – 12-second product film for a customer data platform, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A soft, editorial 2.5D product film (1920×1080, 30 fps) for **Kitebase**, an invented customer-data tool: it pulls one customer from five tools into a clean table, merges duplicates and syncs the right segment back. The visual motif is a kite: a red diamond with strings to five tool cards. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: sky gradient from pale blue #DCE6F2 at top to peach #F4D9C7 at bottom.
- Cards: white, small icons; table panel deep navy #1C2550.
- Accent: kite red #E0302F, with hand-drawn red underlines.
- Type: bold serif (Newsreader / Source Serif Semibold) in navy for headlines; key words red italic with underline. UI in Inter.
- Logo: red diamond kite + "Kitebase" in big navy serif.

## 2. Voiceover (calm, smart)
"Your customer lives in five different tools under five different names. Kitebase pulls everything into one clean table, merges the duplicates, and sends the right segment back to every tool. Kitebase. One customer, one truth."

## 3. Scenes
1. **0.0–3.0 s – Five names.** Five white cards float like kites: HELPDESK "@mia_ok", NEWSLETTER "mia.o@nordlicht.de", CRM "Mia Okafor", BILLING "M. Okafor", SHOP "OKAFOR, MIA". A red diamond kite rises below; strings connect it to each card and the names get red outlines. Caption: "Your customer lives / in five different tools, / under five different names."
2. **3.0–5.5 s – One table.** The strings pull the cards into a navy table "Kitebase · Customers · Segments · Sync · 2 → 5 sources", columns NAME / EMAIL / SOURCE / SEGMENT, five rows. Caption: "Kitebase pulls everything / into ***one*** clean table,"
3. **5.5–7.0 s – Merge.** Rows collapse into one record card "MO Mia Okafor · nordlicht GmbH · Berlin · 1 record" with sub-chips; segment chip "♦ VIP · Berlin". Caption: "***merges*** the duplicates,"
4. **7.0–9.0 s – Sync back.** The record sends red dotted lines up to five diamond icons (helpdesk, newsletter, CRM, billing, shop), each receiving a "VIP · Berlin" chip. Caption: "and sends the right ***segment*** / back to every tool."
5. **9.0–12.0 s – End card.** The chip turns into the kite; "Kitebase"; "One customer, ***one truth.***" A string of five dots "2 → 5 of 5 tools in sync". "KITEBASE.IO".

## 4. Rules
Cards sway like kites on a breeze; the camera drifts upward slightly; words build with blur-in.

## 5. Sound
Breezy acoustic/pad, wind flutter, string "twang" when connecting, merge "whoomp", resolve chime.

## 6. Make it yours
Swap customer, tools, segment.

---

# Leafnook – 10-second talking head ad for a balcony garden design service, 1:1

> Recreated from the public example video. Film your own selfie clip on a balcony, then paste this prompt with it into Claude to add the motion design.

## 0. What you are building
A square (1080×1080) talking head ad for **Leafnook Balcony Gardens**, a service that plans tiny balconies into green escapes. A woman in a mustard cardigan films herself on a city balcony with pots and herbs. Claude adds kinetic captions, a top-down balcony floor plan, growing vines, a checklist and a seed-packet end card. Build overlays in code (Remotion).

## 1. Look
- Brand: terracotta coral #E07563, leaf green #4CAF50, wood beige #E8C9A0, cream #F6F0E4, espresso text.
- Type: white sans (Inter) for small words; key words in big coral serif italic (Playfair Display Italic).
- Illustration style: flat, top-down, simple (wood planks, round pots with green leaves, string lights).

## 2. Script
"Tiny balcony? We turn it into a green escape. Plants, pots and lights, planned for you. leafnook.garden"

## 3. Scenes
1. **0.0–1.7 s – Hook.** A small flat floor plan of an empty balcony (beige rectangle with railing) is measured with a dotted line; caption "Tiny" (white) + "*balcony?*" (coral italic).
2. **1.7–2.5 s – Plan.** Full-frame top-down illustration: wooden deck planks, windows, four round coral pots with green succulents popping in. Caption "We turn it into".
3. **2.5–4.2 s – Escape.** Back to her; big green leaves grow in from the corners and vines climb the sides. Caption: "a green / *escape.*"
4. **4.2–5.8 s – Checklist.** White card "Balcony · 3": ✓ Plants, (sprout icon) ✓ pots, ✓ and lights, with a tiny row of glowing string-light bulbs.
5. **5.8–7.5 s – Before/After.** A before/after slider card over the empty and the planted balcony plan; caption "*planned* for you."
6. **7.5–10.0 s – End card.** Coral background; a seed-packet card with a zigzag top: the planted balcony plan, "leafnook" in espresso serif italic, "BALCONY GARDENS", coral pill "leafnook.garden" typed in; a sprout pops out of the top; fine print "Sow: any season · Grows: on any balcony".

## 4. Rules
Captions word-synced; leaves and vines grow with organic easing; keep her face clear.

## 5. Sound
Original voice, soft acoustic guitar, birdsong, rustling leaves, a "pop" for each checklist item.

## 6. Make it yours
Swap business, offers and URL; use your own clip.

---

# Lettra – 9.7-second product film for an AI newsletter tool, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A cosy, editorial 2.5D product film, square (1080×1080, 30 fps), for **Lettra**, an invented newsletter assistant: it drafts the issue from your week, picks the best subject line and sends it when readers open. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: plum/aubergine #3A1E3F with a faint "+" grid and soft top glow.
- Cards: warm cream paper #F2E8D9, typewriter-ish UI. Accent: salmon coral #F08A72.
- Type: bold slab serif (Clarendon / Roboto Slab Bold) in cream; key words coral. UI labels in monospace.
- Logo: "Lettra" in heavy cream slab serif between two thin rules, followed by a blinking coral text cursor.

## 2. Voiceover (warm writer voice)
"Your newsletter takes all Sunday. Lettra drafts it from your week, picks the best subject line, and sends it when readers open. Write less. Get read. Lettra."

## 3. Scenes
1. **0.0–2.4 s – Sunday.** An editor card "ISSUE № 48 · Untitled" where text is typed and deleted ("Hey ever…", "So…"), word count 2 → 1 → 0 words. Beside it a "SUNDAY" clock card 11:15 → 16:05 with a coral bar filling. Caption: "Your newsletter / takes all **Sunday.**"
2. **2.4–3.2 s – Draft.** A coral tag "● Lettra is drafting"; the card fills: "The week at Juno · MON We shipped v2.4…" 470 words; on the right week chips get checked: MON v2.4 live, TUE 3 user calls, WED New pricing, THU Podcast, FRI 1.2k signups — each flies into the draft. Caption: "Lettra drafts it / from your week,"
3. **3.2–4.8 s – Subject lines.** Three option cards stacked: A "Our week in review" 33%, B "We shipped it. Here's why." 16%→58%, C "5 things from this week" 22%; B pops forward with a coral "✓ Best" tag, "predicted opens". Caption: "picks the **best** / subject line,"
4. **4.8–6.5 s – Send time.** Below, a bar chart "WHEN YOUR READERS OPEN · last 12 issues" with a coral marker at "08:05" → "07:20"; a chip "Sent 07:20" and little envelopes fly out. Caption: "and sends it when / **readers open.**"
5. **6.5–7.3 s – Write less.** "Write **less.**" with a slim progress bar "TIME TO WRITE 17 min" and a row of envelopes.
6. **7.3–9.7 s – End card.** A coral cursor types "Lettra"; tagline "Write less. Get read." and "lettra.email" in coral mono.

## 4. Rules
Typewriter rhythm for text, cards with paper shadows, slow push-in.

## 5. Sound
Lo-fi jazzy beat, typewriter keys, paper slide, envelope whooshes, a small bell on the logo.

## 6. Make it yours
Swap brand, week items and subject lines.

---

# Liftlab – 10-second talking head ad for an online personal-training service, 16:9

> Recreated from the public example video. Film your own clip talking to camera, then paste this prompt with it into Claude to add the motion design.

## 0. What you are building
A horizontal (1920×1080) talking head ad for **Liftlab**, an online coach offering 20-minute home workouts and weekly check-ins. A young, curly-haired coach in a white tee talks to camera in a bedroom with purple LED strip light. Claude adds a workout UI, captions and a smartwatch end card. Build overlays in code (Remotion).

## 1. Look
- Dark UI: near-black #111 panels, lime green #C6F432 accent rings, check marks and buttons.
- Type: white bold sans (Inter Bold); key words in lime serif italic (Playfair Display Italic) inside dark pills.

## 2. Script
"No gym? No problem. 20-minute home workouts, built just for you, and I check in every single week. Start today at liftlab.fit."

## 3. Scenes
1. **0.0–1.6 s – Hook.** The clip sits in a dark video-player card "Liftlab · Full body at home" with a timer ring "00:00 → 00:01", controls and a scrub bar. On the right: a dumbbell icon, "No gym?", and "TODAY'S WORKOUT: Squats 3×12 (highlighted), Push-ups 3×10, Plank 45 s". The dumbbell gets a lime slash.
2. **1.6–3.3 s – No problem.** The clip goes full-frame. Pill caption "No *problem.*" A small timer card "HOME WORKOUT 00:02 → 20:00". Caption: "20-minute / home".
3. **3.3–5.0 s – Plan.** A dark plan card: "20:00 · Alex's plan · Week 1: MON Legs & glutes 20 min, WED Upper body 20 min, FRI Core & cardio 20 min", each ticks lime. Caption: "built just / for *you.*"
4. **5.0–6.6 s – Check-in.** A chat bubble "How did week one go?" pops beside the coach. Caption: "And I / check in / every single week".
5. **6.6–10.0 s – CTA.** A smartwatch slides in on the left: lime ring, "liftlab.fit" typing in, lime "Start workout" button. Caption: "Start / *today*".

## 4. Rules
Captions word-synced; cards slide in with spring; keep the face clear.

## 5. Sound
Original voice, upbeat gym beat, a timer beep, check-mark ticks, a watch "buzz" on the CTA.

## 6. Make it yours
Swap coach name, plan, URL; use your own clip.

---

# Linto – 10.1-second product film for AI code review, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A clean, light 2.5D product film (1920×1080, 30 fps) for **Linto**, an invented AI code reviewer: it reviews every line of a pull request, flags risky ones and suggests the fix, so teams can ship on Friday without fear. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: very light lavender-grey #EEEEF3 with a subtle floor reflection.
- Code panels: dark #1E1E2A with syntax highlighting; PR cards white.
- Accent: violet #6B4EF6 for highlights, flags and buttons.
- Type: grotesk (Inter Semibold) in near-black, key words violet, followed by a violet blinking text cursor "|".
- Logo: violet rounded square with a white check-mark wave + "Linto".

## 2. Voiceover (calm engineer)
"Pull requests pile up for days. Linto reviews every line, flags the risky ones and suggests the fix. Ship on Friday, without the fear. Linto."

## 3. Scenes
1. **0.0–1.7 s – Pile.** PR cards stack up: "#482 Refactor billing webhooks · Needs review · +128 −42", "#480 Add retry to sync job", "#481 Bump auth middleware", "#479 Fix cart rounding", "#478 Migrate users table", "#477 New export endpoint"; badge "Open pull requests 6". Caption: "Pull requests / pile **up**".
2. **1.7–3.4 s – Review.** The #482 card opens into a dark code view "billing/webhooks.ts · TypeScript"; a violet scan bar sweeps down the lines; badge "● 87/128 lines". Caption: "Linto reviews **every** line,"
3. **3.4–5.0 s – Flags.** Three lines get violet flag markers and labels: line 40 `SELECT * FROM users WHERE id = ${id}` (SQL injection), line 41 `log.info("stripe", req.headers)` → "Secrets in logs", line 43 `await billing.markPaid(user.id)` → "user may be null"; badge "3 risky lines". Caption: "flags the **risky** ones,"
4. **5.0–5.9 s – Fix.** A Linto suggestion card "Suggested fix · risk high": diff `- "SELECT * FROM users WHERE id = ${id}"` / `+ "SELECT * FROM users WHERE id = $1", [id]`, note "Use a parameterised query. id comes straight from the request.", buttons "Apply fix" (clicked) / "Dismiss". Caption: "and suggests **the fix.**"
5. **5.9–7.5 s – Ship.** A checks card "#482 · FRI 16:40": ✓ Linto review (0 risky lines), ✓ Tests (214 passed), ✓ Build; "Rollback risk 42% → 11%", a violet "Shipping…" button. Caption: "Ship on **Friday,** / without the fear."
6. **7.5–10.1 s – End card.** Logo; "Code review, before the merge."; "linto.dev".

## 4. Rules
Soft, slow camera drift with reflections under the cards; every caption ends with a blinking cursor.

## 5. Sound
Minimal electronic ambience, keyboard ticks, flag "blips", a satisfying click on Apply fix, rocket-ish whoosh on Shipping.

## 6. Make it yours
Swap repo, code issues and figures.

---

# Mapleo – 9.8-second product film for a budgeting app, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A warm, autumnal vertical product film (1080×1920, 30 fps) for **Mapleo**, an invented budgeting app: it splits income into jars the moment it lands and shows how close your next goal is. Glass jars filling with colour carry the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: warm cream-to-peach #F6E7CF with faint maple-leaf shapes and thin branch lines.
- Bank card: dark espresso #2E1B16. Accent: maple red #C4161C.
- Jar fills: chocolate brown (Fixed), caramel (Living), maple red (Saving).
- Type: elegant serif (Newsreader / Lora) in espresso; key words in red italic with a hand-drawn underline.
- Logo: red maple leaf + "Mapleo".

## 2. Voiceover (friendly, calm)
"Payday feels great, until the last week of the month. Mapleo splits your income the moment it lands, and shows how close your next goal is. Mapleo. Money with a plan."

## 3. Scenes
1. **0.0–2.4 s – Payday drain.** Dark "Checking · Main account 4821" card: red chip "↓ Paycheck +$3,200", balance $2,318 → $3,412 (↑ +$3,200 today), then a staircase line falls week by week to $525, week 4 hatched red. Chips fall out: Rent −$1,400, Groceries −$310, Takeout −$86. Caption: "Payday feels great, / until the *last week*".
2. **2.4–4.8 s – Split.** The paycheck chip drops onto a shelf; three red branch lines split it into three jars: Fixed $909 → $1,500, Living $564 → $1,196, Saving $157 → $487; a tiny chip "0.2 s". Small jars on a lower shelf. Caption: "Mapleo *splits* your income / the moment it lands,"
3. **4.8–6.5 s – Goal.** Camera pushes into the Saving jar: fill rises "$1,500 → $3,469 saved so far" toward a dashed goal line with a red flag "Japan $6,000"; a branch below sprouts red leaves; "5 months to go". Caption: "and shows how close / your *next goal* is."
4. **6.5–9.8 s – End card.** Logo; "Money with a *plan.*" Three small jars fill; "$1,140 → $3,187 of $3,200 planned"; the branch fills with red leaves. "MAPLEO.APP".

## 4. Rules
Liquid fills with a gentle slosh; leaves drift; slow vertical camera.

## 5. Sound
Soft acoustic guitar, coin clink on payday, liquid pour, leaf rustle, warm chord.

## 6. Make it yours
Swap amounts, jars and goal.

---

# Mathloop – 10-second talking head ad for online maths tutoring, 16:9

> Recreated from the public example video. Film your own clip talking to camera, then paste this prompt with it into Claude to add the motion design. (The spoken lines below are reconstructed from a noisy audio track; adjust them to what you actually say.)

## 0. What you are building
A horizontal (1920×1080) talking head ad for **Mathloop**, an online one-on-one maths tutor. A tutor with glasses in a black tee sits at home (bookshelves, plant, guitar) and speaks to camera. Claude adds a video-call frame, a big "1:1" graphic, an algebra animation and a progress chart. Build overlays in code (Remotion).

## 1. Look
- Accent: bright cobalt blue #2F6BF0; dark navy #121A33 for the call UI; white cards.
- Type: white bold sans (Inter Bold); key words in white serif italic (Playfair Display Italic) inside a blue box.

## 2. Script (approximate)
"Maths doesn't have to feel impossible. One-on-one lessons, online. Start at mathloop.io. You'll get there, promise."

## 3. Scenes
1. **0.0–1.6 s – Call.** The clip sits inside a video-call window on navy: name tag "● Jonas · Maths tutor", a student tile "MK", call controls with a red hang-up. Caption on the right: "Maths / doesn't / have to feel".
2. **1.6–3.3 s – One-on-one.** Full-frame; two big blue gradient "1" glyphs appear either side of his head; caption "One-on-one / *lesson*".
3. **3.3–4.8 s – Algebra.** Full blue screen: "2x + 6 = 14", "−6" drops under both sides and the equation simplifies; then an oval video portrait pops in; "online".
4. **4.8–6.7 s – Start.** Back to him; label "Start at"; a white "Your progress · Maths" card with a rising blue S-curve Week 1 → Week 4 → Week 8; "mathloop.io" is typed below.
5. **6.7–10.0 s – Promise.** Blue pill "🤝 *Promise.*"; the curve's end dot becomes a blue grade badge "A".

## 4. Rules
Captions word-synced; blue panels wipe in from the side; keep the face clear.

## 5. Sound
Original voice, light piano/pluck beat, chalk-tap sounds on the equation, a "ding" on the A badge.

## 6. Make it yours
Swap subject, name, URL; use your own clip.

---

# Mendly – 9.9-second product film for IT asset management, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A cool, techy 2.5D product film, square (1080×1080, 30 fps), for **Mendly**, an invented IT tool for small companies: it knows every device, who uses it, its warranty, and what needs fixing next. A barcode asset tag "MND-014" carries the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: slate blue-grey #2E3A4A with a soft vignette.
- Cards: #3A4759 with lighter borders; asset tags: light grey aluminium labels with a barcode.
- Accent: sky blue #5CC2F2; highlighted words sit in a light-blue box with a tiny barcode stripe before them.
- Type: grotesk (Inter Bold) in white; UI labels in monospace.
- Logo: light-blue rounded rectangle with a barcode/bar-chart glyph + "Mendly".

## 2. Voiceover (dry, efficient)
"Who has the spare laptop, and when does its warranty end? Mendly knows every device, who uses it, and what needs fixing next. Mendly. IT that runs itself."

## 3. Scenes
1. **0.0–1.6 s – Shelf.** A 4×3 grid of device tiles (laptops, monitors, phones) with asset tags MND-002 … MND-031 and user avatars (JW, AM, RK, LS…). One tile "SPARE" (dashed) is empty; then shows "LS". Caption: "Who has the / spare laptop?"
2. **1.6–3.3 s – Warranty.** The MND-014 tag ("MACBOOK PRO 14" · SPARE") zooms big; below, a card "ASSIGNED TO ?" and "WARRANTY ENDS 30.06.20??" with a timeline 2024–2028 and a "?" marker. Caption: "And when does its **warranty** end?"
3. **3.3–4.9 s – Knows every device.** A Mendly dashboard "ALL DEVICES 9 → 48 tracked" with a device list; the MND-014 tag becomes "TRACKED". Caption: "Mendly knows / every **device,**"
4. **4.9–5.8 s – Who uses it.** Detail: "ASSIGNED TO JW Jonas Weber · Design · since 02 Oct · IN USE", "WARRANTY ends 14 Mar 2027 · 152 days left", "HEALTH · BATTERY 61%", a blue chip "Battery low". Caption: "**who** uses it,"
5. **5.8–7.4 s – Fix next.** "Fix next · 3 open" list sorted by urgency: 1 Battery low (MND-014 · Spare MND-040 held · Swap booked Thu 09:30), 2 Warranty ends in 30 days (MND-027 Dell 27" monitor · Renewal quote requested), 3 Screen cracked (MND-031 iPhone 15 · Repair slot offered Fri 14:00); footer "SORTED BY URGENCY · ASSIGNED AUTOMATICALLY". Caption: "and what needs / fixing **next.**"
6. **7.4–9.9 s – End card.** Logo; "IT that runs **itself.**" A row of 12 barcode chips lights up "40 → 46 of 48 devices tracked". "MENDLY.APP".

## 4. Rules
Smooth zooms between tag and dashboard; barcode scan line sweeps across tags as they become tracked.

## 5. Sound
Minimal techy pulse, barcode-scanner beeps, soft UI clicks, resolve chime.

## 6. Make it yours
Swap devices, people and dates.

---

# Mowdoc – 10-second talking head ad for a lawn-mower repair shop, 1:1

> Recreated from the public example video. Film your own clip talking to camera, then paste this prompt with it into Claude to add the motion design.

## 0. What you are building
A square (1080×1080) talking head ad for **Mowdoc**, a local lawn-mower repair shop run by an experienced mechanic. A friendly older man with white hair in a navy fleece vest stands in front of his garage (bikes, shelves, mowers) and speaks to camera. Claude adds flat mower icons, an app-style error dialog, a repair checklist, a "40 years" flip counter and a job-card end. Build overlays in code (Remotion).

## 1. Look
- Brand: signal red #D9302C, white, charcoal text. Flat white line icons of a push mower with a red engine.
- Type: white bold sans (Inter Bold) + white serif italic (Playfair Display Italic) for emphasis; red pill labels.

## 2. Script
"Mower won't start? Don't throw it out. Forty years I've fixed them. Bring it to mowdoc.shop."

## 3. Scenes
1. **0.0–1.7 s – Hook.** A white mower icon (red engine) sputters on his chest with little smoke puffs. Caption: "Mower won't / *start?*"
2. **1.7–3.3 s – Dialog.** An iOS-style alert card: red app icon with mower, "Engine won't start · 3 pulls · no spark", buttons "Retry" / "Throw out" (red). A cursor hovers "Retry".
3. **3.3–4.1 s – Don't.** The red mower app icon is dragged toward a trash-can icon; red pill "Don't" + "throw it **out.**"
4. **4.1–5.8 s – Repair.** Full red background: the mower icon explodes into parts (engine, handle, spark plug, battery), checklist pills tick: ✓ Spark plug new, ✓ Air filter cleaned, ✓ Blade sharpened. The mower reassembles and drives off with speed lines.
5. **5.8–7.4 s – Experience.** Back on him; a black split-flap counter flips to "4 0", serif italic "*years*", "I've…".
6. **7.4–10.0 s – Job card.** A white "JOB CARD · No. 0417" slides up: Machine Lawn mower, Fault Won't start, Status ✓ Fixed, "Drop off at" field typing "mowdoc.shop" (".shop" in red). Caption: "*Bring* it to".

## 4. Rules
Captions word-synced; flat icons with springy motion; keep his face clear.

## 5. Sound
Original voice, mower pull-cord sputter, wrench clinks, engine roar when fixed, flip-counter clicks.

## 6. Make it yours
Swap trade, repairs, years, URL; use your own clip.

---

# Murmo – 13.8-second product film for an AI meeting notetaker, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A modern 2.5D product film (1920×1080, 30 fps) for **Murmo**, an invented AI notetaker: it listens, writes the summary and assigns every task, so the team just talks. Participant avatar bubbles (J, A, L, M) orbit a central element. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: deep indigo/violet #1C1550 with a radial glow #3A2C9A in the centre.
- Accent: acid lime #C8F23A for highlights (lime box behind key words), waveform and checks.
- Avatars: white circles with initials; the "taking notes" person shows a "•••" typing bubble.
- Type: grotesk (Inter Semibold) in white; highlighted words get a lime rounded box with dark text.
- Logo: dark navy circle with a lime waveform + "Murmo" in black on the lime end card.

## 2. Voiceover (light, friendly)
"Another meeting. Who's taking notes? Murmo listens, writes the summary and assigns every task. So your team just talks. Murmo. Meetings that write themselves."

## 3. Scenes
1. **0.0–3.4 s – Who takes notes?** A small dark "Notes · 0 words · Start typing…" card in the centre; four avatars orbit; the typing bubble jumps from one avatar to another. Caption: "Another meeting. / Who's taking **notes?**"
2. **3.4–4.6 s – Listens.** The card morphs into a dark circle with a lime waveform reacting to voices. Caption: "Murmo **listens,**"
3. **4.6–5.8 s – Summary.** A dark app panel "● REC 00:43 · Product sync" with a summary typing in lime/grey lines. Caption: "writes the summary".
4. **5.8–8.0 s – Tasks.** "Summary": ☐ Launch moves to Nov 12, ☐ Pricing page needs new copy, ☐ Beta opens to 200 users; each line turns lime and drops a tag "Launch ✓", "Pricing ✓", "Beta ✓" to an avatar (M, J, A, L). Caption: "and assigns every **task.**"
5. **8.0–9.2 s – Just talks.** Avatars orbit the waveform again; chips "6 min saved", "Notes · 61 words". Caption: "So your team just talks."
6. **9.2–13.8 s – End card.** A lime circle wipes from the left across the whole frame; logo; "Meetings that **write themselves.**" and an outlined pill "murmo.app".

## 4. Rules
Orbiting motion is slow and constant; waveform reacts to voice; lime wipe is a big radial reveal.

## 5. Sound
Soft synth groove, overlapping murmured voices at the start, typing ticks, task "pops", a bright chord on the lime wipe.

## 6. Make it yours
Swap names, tasks, durations.

---

# Nestwell – 10.8-second product film for a daycare parent app, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A gentle, sky-themed 2.5D product film, square (1080×1080, 30 fps), for **Nestwell**, an invented daycare app: it shares the day in small moments, handles sign-in and pick-up, and keeps notes out of backpacks. The sun travels an arc over a small house from 8 AM to 4 PM. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: soft sky blue #CFE3F5 → #E8F1FA with puffy white clouds at the bottom and small clouds drifting.
- Navy #1F2D52 for house, text and backpack; sun orange #F59A1E for accents (key words in an orange pill on white).
- Type: rounded geometric sans (Nunito Bold / Poppins Semibold) in navy.
- Logo: an orange sun rising out of a navy nest/bowl + "Nestwell".

## 2. Voiceover (warm parent voice)
"What did my child do today? Every parent asks. Nestwell shares the day in small moments, handles sign-in and pick-up, and keeps notes out of backpacks. Nestwell. Closer to their day."

## 3. Scenes
1. **0.0–2.7 s – The question.** A dotted arc from "8 AM" to "4 PM" over a navy house on clouds; dashed circles with "?" along the arc; the sun moves along it; speech bubbles "?" pop over the house. Caption: "What did my child / do **today?** / Every parent asks."
2. **2.7–4.5 s – Moments.** The arc fills orange; the "?" circles become moment icons: ✓ "8:02 Arrived", 🍽 "11:40 Lunch", ☾ "1:10 Nap"; a photo card "Mila R. · Painting · 3:15 PM ♡" with a child's painting of flowers and a sun. Caption: "Nestwell shares the day / in small moments,"
3. **4.5–6.2 s – Sign-in.** A white "Robin Room · Wed, Oct 14 · 4 children · 4 of 4 signed in" card: Mila R. 8:02 AM, Noah K. 8:15 AM, Ivy T. 8:31 AM, Leo M. 8:47 AM (orange check chips), an empty PICKUP column with a sun slider. Caption: "handles sign-in / and **pick-up,**"
4. **6.2–8.1 s – Notes.** A navy backpack tagged "Mila" with paper notes sticking out ("2 loose notes"); the notes fly into a "Notes · from Robin Room · 3 new" card: Field trip Friday · Permission slip (orange "Sign" button), Bring rain boots · Tomorrow (Seen), Photo day Tuesday · Wear a smile (Seen); backpack chip "✓ 0 loose notes". Caption: "and keeps notes / out of **backpacks.**"
5. **8.1–10.8 s – End card.** Sun rises into the nest; "Nestwell"; "Closer to their **day.**" "3 → 6 moments shared today". "nestwell.app".

## 4. Rules
Soft springs, clouds parallax, sun glow pulses gently.

## 5. Sound
Music box / soft xylophone, children's distant laughter, gentle pops for moments, paper rustle, sunrise chime.

## 6. Make it yours
Swap room name, children, moments and notes.

---

# Nightscan – 31-second 3D explainer film: how Face ID works in the dark, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A 31-second vertical (1080×1920, 30 fps) cinematic 3D explainer about how a phone's face unlock works in the dark: a flood illuminator lights the face with infrared, a dot projector sprays tens of thousands of dots, and a camera reads their spacing to build a 3D depth map. Setting: a dim bedroom at night, a woman lying in bed looking up at her phone. One continuous camera flight. Ends with a social CTA ("Comment FACE for the link"). Build in code (Three.js / React Three Fiber in Remotion) and render to MP4.

## 1. Look
- Night bedroom: deep blue-grey shadows, a warm bedside lamp bokeh in the background.
- Phone: black glass, titanium edge, the sensor pill (flood illuminator, dot projector, IR camera) clearly modelled. Green Face ID glyph on the screen.
- Infrared dots: glowing pink-magenta particles (#FF6FA3) forming a cone from the projector and covering the face like a point cloud.
- Labels: dark pills with a pink dot and white caps text ("INFRARED DOTS · invisible to your eyes", "MEASURING", "FLOOD ILLUMINATOR · infrared lamp", "DOT PROJECTOR", "CLOSER", "FARTHER", "DEPTH MAP", "PHOTO · no depth"), with thin leader lines.
- Captions: white bold sans (Inter Bold) lower third; numbers and key words in pink.

## 2. Voiceover (curious explainer)
| Time | Line |
|---|---|
| 0.0–3.7 s | "Your iPhone sprays 30,000 invisible dots on your face." |
| 3.7–6.5 s | "It isn't looking at your face. It's measuring it." |
| 6.5–8.1 s | "But how? In the dark?" |
| 8.1–12.3 s | "A tiny lamp floods your face with infrared. Light your eyes can't see." |
| 12.3–14.9 s | "Next to it, a dot projector fires the dots." |
| 14.9–19.3 s | "But here's where it gets clever: dots on your nose land closer than dots on your cheeks." |
| 19.3–22.7 s | "A camera reads every dot and builds a 3D map of you." |
| 22.7–25.0 s | "That's also why a photo can't fool it." |
| 25.0–28.9 s | "So your iPhone never sees your face. It feels its shape with light." |
| 28.9–31.0 s | "Comment FACE for the link." |

## 3. Scenes
1. **0–3.7 s – Spray.** Close on the phone's top edge; a pink cone of dots sprays out; a counter caption "Your phone sprays **16,400 → 30,000**" ticks up; label "INFRARED DOTS".
2. **3.7–8 s – Measuring.** Camera follows the cone to her face; dots land on her skin; label "MEASURING" on the nose tip.
3. **8–10.3 s – Flood illuminator.** Back to the sensor pill; label "FLOOD ILLUMINATOR · infrared lamp"; a soft invisible-light wash glows.
4. **10.3–12.3 s – Eye.** Extreme close-up of her blue eye: "Light your eyes **can't** see."
5. **12.3–14.9 s – Dot projector.** Label "DOT PROJECTOR"; a dense pink beam fires.
6. **14.9–19.3 s – Closer/farther.** Profile of her face covered in dots; labels "CLOSER" (nose) and "FARTHER" (cheek), dots visibly denser/sparser.
7. **19.3–22.7 s – Depth map.** Her face lifts off as a pure point-cloud mask, label "DEPTH MAP".
8. **22.7–25 s – Photo.** A flat printed photo of her with dots on it, label "PHOTO · no depth"; it fails (dots stay flat).
9. **25–28.9 s – Unlock.** The phone screen shows the blue Face ID frame animating to a check.
10. **28.9–31 s – CTA.** Green Face ID glyph; caption "Comment **FACE** for the link".

## 4. Rules
One unbroken camera path; slow, floating moves; heavy depth of field; dots twinkle subtly.

## 5. Sound
Quiet night ambience, low cinematic drone, sparkly particle shimmer for the dots, a soft unlock click and chime.

## 6. Make it yours
Use the same structure to explain any hidden tech. Swap the CTA keyword. (Don't use real brand logos.)

---

# Nimbo – 14.2-second product film for automated invoicing, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A clean, light 2.5D product film (1920×1080, 30 fps) for **Nimbo**, an invented invoicing tool: it creates invoices, sends them and follows up so you get paid on time. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: off-white #F2F3F2 with soft mint-green glows #9FE3B5 in the corners and a faint dot grid.
- Cards: white, soft shadow; text near-black; accent green #22B35E; overdue red #E5484D.
- Type: grotesk (Inter Semibold); key words green.
- Logo: green rounded square with a white arch/cloud "n" + "Nimbo".

## 2. Voiceover (relaxed freelancer)
"Still chasing invoices? Nimbo creates them, sends them and follows up for you. So you get paid. On time. Nimbo. Invoicing on autopilot."

## 3. Scenes
1. **0.0–2.3 s – Chasing.** Three invoice cards: "INV-1038 · Atelier Kreis $1,250 · Overdue 21 days", "INV-1042 · Studio Brandt $4,800", "INV-1040 · Mono Lab $960 · Overdue 33 days"; red "!" badges pop; a cursor hovers. Caption: "Still chasing invoices?"
2. **2.3–4.7 s – Create & send.** The $4,800 card turns into a full invoice document that builds itself (lines fill in green), then folds to a small envelope card and flies off. Caption: "Nimbo creates them, sends them,"
3. **4.7–7.0 s – Follow-up.** A curved line flies to a client avatar "SB · Studio Brandt"; then a timeline: "Invoice sent · Today" → "Friendly reminder · Day 3" → "Second reminder · Day 7" → (paid). Caption: "and **follows up** for you."
4. **7.0–10.6 s – Paid.** Two cards: "INV-1042 · Studio Brandt · $4,800 · Sent → Paid ✓ · Due Oct 31 · Paid Oct 29" and a "2 days early" green tag; "Balance $12,350 → $16,366 → $17,150" with a bar chart whose last bar shoots up green. Caption: "So you get paid. **On time.**"
5. **10.6–14.2 s – End card.** Logo; "Invoicing on autopilot."; step chips above "Create ✓ · Send ✓ · Follow up ✓ · Get paid ✓"; a green "Start free" button is clicked.

## 4. Rules
Calm, slow camera; cards float with depth blur; numbers tick.

## 5. Sound
Breezy lo-fi beat, paper fold, email whoosh, soft reminder pings, cash "ding".

## 6. Make it yours
Swap clients, amounts and reminder timing.

---

# Nodra – 10-second product film for a sleep-tracking app, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A dreamy vertical product film (1080×1920, 30 fps) for **Nodra**, an invented sleep app: it reads your night, shows when you truly rested and gives one small tip for tomorrow. The moon travels an arc across the night. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: dusky lavender-grey #5A5478 → #6E6890 with layered dark hills at the bottom and a tiny house.
- Moon: soft cream, cratered, with glow. Accent: mint teal #6FE3C8.
- Cards: translucent lavender #6E6890 with soft borders.
- Type: rounded geometric sans (Nunito Black / Quicksand Bold) in white; key words mint.
- Logo: crescent moon above a mint hill-curve + "Nodra".

## 2. Voiceover (soft, sleepy)
"Eight hours in bed, and you still wake up tired. Nodra reads your night, shows when you truly rested, and gives one small tip for tomorrow. Nodra. Better mornings."

## 3. Scenes
1. **0.0–2.5 s – In bed.** An arc from 23:10 to 07:10; the moon travels along it; "IN BED 5h09m → 7h58m → 8h00m". Then an alarm card "07:10 · Snoozed ×2 · MORNING ENERGY 26%". Caption: "Eight hours in bed, / and you still wake up tired."
2. **2.5–4.2 s – Reads your night.** "Last night · 8h00m in bed · Tue 13 → Wed 14 Oct" with chips Heart 58 bpm, Breath 14/min, Moves 23 turns; a sleep-stage wave chart (Awake/Light/Deep) draws from 23:10 to 07:10. Caption: "Nodra reads / your night,"
3. **4.2–5.8 s – Truly rested.** Only one peak fills mint (deep sleep) around 00:30; "TRULY RESTED 0h 13m of 8h". The moon pulses. Caption: "shows when you / **truly rested,**"
4. **5.8–7.5 s – Tip.** A score ring "SLEEP SCORE 59 → 61 of 100"; a card "TIP FOR TOMORROW · Lights out 20 min earlier" with a slider from 22:30 to 22:10 "−20 min", "FORECAST 61 → 70". Caption: "gives one **small tip** / for tomorrow."
5. **7.5–10.0 s – End card.** Logo; "Better **mornings.**" A row of moon phases WED–TUE filling with scores 61, 70, 74, 77, 80, 83, 86. "NODRA.APP".

## 4. Rules
Very slow, floaty camera; stars twinkle; everything eases gently.

## 5. Sound
Ambient pad, crickets, soft alarm snooze beep, gentle chime per score step, morning birds at the end.

## 6. Make it yours
Swap metrics, tip and scores.

---

# Northvale Wealth – 10-second talking head ad for a wealth adviser, 9:16

> Recreated from the public example video. Film your own clip talking to camera, then paste this prompt with it into Claude to add the motion design.

## 0. What you are building
A vertical (1080×1920) talking head ad for **Northvale Wealth**, a financial adviser offering a free call. A red-haired, bearded man in a teal tee sits in a moody room with tropical plants and a warm Edison bulb. Claude adds a gold growth chart, a comparison graphic and a booking sheet. Build overlays in code (Remotion).

## 1. Look
- Accent: warm gold #D9B45A; navy #13203B panels; off-white #F4F1EA comparison card.
- Type: white bold sans (Inter Bold) + gold serif italic (Playfair Display Italic) for key words.

## 2. Script
"Your money should work harder. Not just sit in your account. Book a free call at northvalewealth.com."

## 3. Scenes
1. **0.0–2.5 s – Growth line.** A thin gold line chart grows across the frame behind him, label "● Portfolio", ending in a dot with a chip "▲ 7% / yr". Caption: "Your money / should *work* / **harder.**"
2. **2.5–3.3 s – Portfolio card.** Navy card: "work harder." / "Portfolio $17,250" with a gold line chart 2026 → 2036.
3. **3.3–5.0 s – Not just sit.** Back on him: "Not just / *sit* / in…" with a blinking cursor.
4. **5.0–6.6 s – Comparison.** Off-white card: "Checking account $10,000.00" with a flat grey line; then a gold curve rises from the same start to "$19,670 · Invested · 7%", while the grey line ends at "$10,010 · Account 0.01%", 2026 → 2036.
5. **6.6–10.0 s – Booking sheet.** A white bottom sheet slides up: "Book a *free* call · 20 min · Video call · Tuesday, 27 October", time chips 9:30 / 11:00 / 14:30 (11:00 tapped, turns gold), a URL field "at 🔒 northvalewealth.com" typing, navy "Book free call" → "✓ Booked".

## 4. Rules
Captions word-synced; charts draw smoothly; keep his face clear above the sheet.

## 5. Sound
Original voice, calm piano/strings bed, soft chart "whoosh", tap sound on time slot, confirmation chime.

## 6. Make it yours
Swap name, figures, URL; use your own clip. (Avoid making specific return promises in a real ad.)

---

# Oakyard Sheds – 10-second talking head ad for a handmade garden-shed builder, 9:16

> Recreated from the public example video. Film your own clip talking to camera, then paste this prompt with it into Claude to add the motion design.

## 0. What you are building
A vertical (1080×1920) talking head ad for **Oakyard**, a carpenter who builds sheds, fences and gates by hand. A grey-haired man in a navy quarter-zip stands in front of a weathered timber shed under a blue sky. Claude adds a line-drawing shed that builds itself, a three-step progress line, service icons and a quote sheet. Build overlays in code (Remotion).

## 1. Look
- Brand: warm oak #C98A4B, espresso lines #3A2A20, cream paper #F5F0E6.
- Type: white bold sans (Inter Bold) + oak serif italic (Playfair Display Italic) for key words; oak label box for "by hand".

## 2. Script
"Every shed we build is cut, fitted and finished by hand. Garden sheds, fences, gates. Get a free quote at oakyardsheds.com."

## 3. Scenes
1. **0.0–1.6 s – Outline.** A white pencil draws a big shed outline (gable roof) around him. Caption: "Every *shed* / we build".
2. **1.6–4.1 s – Build.** Cut to a cream paper background: a line drawing of a shed (window, door). Three steps on a line tick oak one by one: "cut," → planks appear; "fitted," → boards fitted; "and finished" → the shed fills with oak colour. Oak label: "*by hand.*"
3. **4.1–5.0 s – Door.** The camera pushes into the shed door, which swings open and reveals the clip again.
4. **5.0–7.4 s – Services.** White rounded icon tiles pop on his chest with a segmented pill underneath: "Sheds" (house icon) → "Sheds | Fences" (fence icon) → gates.
5. **7.4–10.0 s – Quote sheet.** A white bottom sheet slides up: "Get a *free* quote · Project Garden shed · 3 × 2 m · Finish ● Oak, oiled", URL field "at oakyardsheds.com" typing, oak "Send" button tapped.

## 4. Rules
Line drawing animates with a stroke-draw effect; captions word-synced; keep his face clear.

## 5. Sound
Original voice, acoustic guitar, saw and hammer taps on each step, door creak, send "whoosh".

## 6. Make it yours
Swap craft, steps, services and URL; use your own clip.

---

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

---

# Orbita – 9.8-second product film for a social-media scheduler, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A dreamy pastel 2.5D product film, square (1080×1080, 30 fps), for **Orbita**, an invented social scheduler: it plans your whole month, picks the best time and publishes everywhere. Post tiles orbit a central "day" planet on elliptical rings. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: soft pink-lilac gradient #F4D9E8 → #D9C6EC with thin white orbit ellipses.
- Post tiles: rounded squares in pastels (lilac, pink, peach, blue) with icons (image, video ▶, text lines).
- Accent: coral-pink #F0506E; dark aubergine #2A1745 for text and check dots.
- Type: rounded humanist sans (Nunito Bold / Mulish Bold) in aubergine; key words get a hand-drawn coral circle/underline.
- Logo: "Orbita" in heavy aubergine with an orbit ring around it and a coral planet dot travelling on it.

## 2. Voiceover (light, relatable)
"Posting every day sounds easy, until it's nine p.m. and you have nothing ready. Orbita plans your whole month, picks the best time, and publishes everywhere for you. Orbita. Always on schedule."

## 3. Scenes
1. **0.0–1.6 s – Orbit.** A white planet "TODAY MON → FRI" in the centre; post tiles orbit it; a M–S row of seven circles below fills with aubergine checks. Caption: "Posting every day / sounds easy,"
2. **1.6–3.3 s – 9 PM.** The planet becomes "SUNDAY 9:00 PM" with a coral ring; orbiting tiles fade into empty dashed outlines; a dashed "+" tile and chip "Nothing ready"; Sunday's circle stays empty (dashed coral). Caption: "until it's nine p.m. and / you have nothing ready."
3. **3.3–4.9 s – Month.** An empty calendar grid slides in and fills: "November 2026 · 27 → 30/30 planned", each day a pastel tile. Caption: "Orbita plans your *month,*"
4. **4.9–5.7 s – Best time.** "REACH BY HOUR" bar chart (6 AM–11 PM); the tallest bar highlights "BEST TIME 7:00 PM"; a coral image tile drops onto it. Caption: "picks the best time,"
5. **5.7–7.4 s – Publish.** The tile (studio.nova · Sun, Nov 1 · 7:00 PM) sends dotted lines to three cards: Photo feed, Short video, Stories, each "Published · 7:00 PM ✓"; pill "3 of 3 published". Caption: "and publishes / *everywhere* for you."
6. **7.4–9.8 s – End card.** Logo with orbit; "Always on *schedule.*"; "22 of 30 posts out on time"; "ORBITA.APP".

## 4. Rules
Constant slow orbital motion; tiles tilt in 3D as they pass; soft bloom.

## 5. Sound
Dreamy synth arps, soft whooshes as tiles orbit, a tick per published channel.

## 6. Make it yours
Swap account, channels, month.

---

# Parcelo – 10.8-second product film for e-commerce returns, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A tactile 2.5D/3D product film, square (1080×1080, 30 fps), for **Parcelo**, an invented returns tool for online shops: customers start a return themselves, it prints the label and refunds on arrival. A kraft cardboard box carries the story. Build in code (Remotion + Three.js for the box) and render to MP4.

## 1. Look
- Background: kraft-paper beige #E7D8BF with faint packing-tape grid lines.
- Box: realistic kraft cardboard with fragile/up arrows and a shipping label.
- Accent: royal blue #2F55E0 — key words sit on a torn blue packing-tape strip with white text. Dark ink #1E1A16.
- Type: grotesk (Inter Semibold) in ink; small labels in a typewriter monospace.
- Logo: blue/ink "P" with a return arrow + "Parcelo"; a blue tape strip "PARCELO · EASY RETURNS" runs across the bottom.

## 2. Voiceover (calm, helpful)
"Returns are part of selling online. The email ping-pong doesn't have to be. Parcelo lets customers start a return themselves, prints the label, and refunds on arrival. Parcelo. Easy returns."

## 3. Scenes
1. **0.0–1.7 s – Return.** An open box with a shirt card inside; tag "ORDER #4812 · ● Delivered" → "● Return"; a blue circular arrow spins around the shirt tag "€64.00". Caption: "**Returns** are part / of selling online."
2. **1.7–3.4 s – Ping-pong.** Customer "MK" on the left, "Shop support" on the right; an envelope bounces between them; counters "EMAILS 1 → 4 · DAYS 1 → 5"; the box waits with a chip "● WAITING FOR A LABEL"; blue tape "PARCELO" strips appear. Caption: "The email **ping-pong** / doesn't have to be."
3. **3.4–6.2 s – Self-service.** A return form "parcelo · 1 ITEM · 2 REASON · 3 LABEL": "Linen shirt · Size M · Sand · €64.00 · Order #4812 · Delivered 9 Oct" with a checkbox ticked; "Why are you returning it?" chips "Too small" (selected), "Changed my mind", "Arrived damaged"; "Start return" clicked → "RETURN STARTED · LABEL IS PRINTING". Caption: "Parcelo lets customers start / a return **themselves.**"
4. **6.2–8.1 s – Label & refund.** The box closes; a "RETURN" label with barcode slaps on; blue tape seals it; the box slides along a dashed line; a "REFUND · ON ARRIVAL" card counts "€0.00 → €64.00 · Back to M. Keller · Card ••42". Caption: "prints the **label,** / and **refunds** on arrival."
5. **8.1–10.8 s – End card.** Logo; "Easy **returns.**"; "PARCELO.APP"; tape strip slides across.

## 4. Rules
Physical feel: box flaps with spring, tape strips tear on with slight rotation.

## 5. Sound
Cardboard rustle, tape rip, printer whirr, cash "ding" on refund, friendly pluck melody.

## 6. Make it yours
Swap product, order and reasons.

---

# Pawpath – 10-second talking head ad for a dog-walking service, 1:1

> Recreated from the public example video. Film your own selfie clip outdoors, then paste this prompt with it into Claude to add the motion design.

## 0. What you are building
A square (1080×1080) talking head ad for **Pawpath**, a daily dog-walking service. A young woman in a mustard beanie, green scarf and parka films herself in an autumn park. Claude adds phone-style notifications, a walk route map, a rainy weather card, a weekly paw tracker and a dog-bone end card. Build overlays in code (Remotion).

## 1. Look
- Brand: golden yellow #F5B324, white, charcoal; dark glass notification cards.
- Type: white bold sans (Inter Bold) + charcoal serif italic (Playfair Display Italic) on a yellow box for emphasis.

## 2. Script
"Busy day? We'll walk your dog. Rain or shine. Every single day. pawpath.co"

## 3. Scenes
1. **0.0–1.6 s – Busy.** iOS-style notifications drop in: "Mail · 14 unread emails", then "pawpath · Bella's walk is overdue". Caption: "Busy" → "We'll".
2. **1.6–2.5 s – Route.** Full-frame flat map: streets, a green park "Riverside Park", river; a yellow paw-print trail draws from Home to the park; card "Bella's walk · 45 min · 3.2 km"; route label "Home → Riverside Park". Caption: "We'll *walk* / your *dog.*"
3. **2.5–4.2 s – Rain.** Dark rainy background with falling streaks: weather card "Riverside Park 12° 🌧 H:14° L:9°", serif "*Rain*", pill "Walk in progress · Bella · with Sam · 18 min" ring; caption "or (shine)".
4. **4.2–7.4 s – Every day.** Back on her smiling; a dark tracker "M T W T F S S" whose circles fill with yellow paw icons one by one; chip "7 walks this week". Caption: "Every single *day.*"
5. **7.4–10.0 s – End card.** Yellow background; a white dog-bone tag with a paw print swings in; "pawpath" → "pawpath.co" typed in serif italic. Final beat: the bone sticker sits at the bottom of her clip.

## 4. Rules
Captions word-synced; overlays bounce in; rain is a quick full-frame cutaway.

## 5. Sound
Original voice, happy ukulele, notification dings, rain patter, a little bark on the end card.

## 6. Make it yours
Swap dog name, walker, park, URL; use your own clip.

---

# Peak – 14-second product film for a business metrics dashboard, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A calm, premium 2.5D product film (1920×1080, 30 fps) for **Peak**, an invented metrics dashboard: it pulls numbers from five tools into one, showing revenue, churn and growth live every morning. Background is a soft dawn sky over hazy hills. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: pastel dawn gradient — periwinkle #C9D0EA top, peach/sunrise glow #F6D7B8 at the horizon, soft blue hill silhouettes.
- Cards: white glass with soft shadow. Accent: indigo #4F5BE8 for revenue/growth; coral #E86A5A for churn.
- Type: grotesk (Inter Semibold) for UI; the spoken key words appear as large italic serif (Newsreader Italic) in navy.
- Logo: indigo rounded square with a white zig-zag up-arrow + "Peak".

## 2. Voiceover (calm, assured)
"Your numbers live in five tools. Peak pulls them into one. Revenue. Churn. Growth. Live, every morning. Peak. Know your numbers."

## 3. Scenes
1. **0.0–2.3 s – Five tools.** Small floating cards with conflicting numbers: Billing $48,210 → $48,905, CRM "$47K?" → "$46K?", Ads $53.4K → $54.1K, Bank $51,930, Sheets $50,112, each with a tiny sparkline. Caption: "Your numbers live in *five* tools."
2. **2.3–4.6 s – Into one.** An indigo Peak icon appears; lines connect all five cards into it and out to one card "Monthly recurring revenue $52,477 · Synced · 5 sources". Caption: "Peak pulls them into *one.*"
3. **4.6–5.8 s – Revenue.** "*Revenue.*" Card "Revenue $52,461 ↑ 4.2% vs last month" with an indigo area line and a tooltip "$52,104".
4. **5.8–7.0 s – Churn.** "*Churn.*" Card "Churn 1.8% ↓ 0.3 pts" with coral bars declining and reasons: Too expensive 38%, Missing a feature 27%, Switched tools 19%.
5. **7.0–8.2 s – Growth.** "*Growth.*" Card "+12%" with stacked indigo bars and "New $4,120 · Expansion $1,870 · Reactivation $640".
6. **8.2–10.5 s – Morning.** All three combine into a full dashboard "Peak · Overview · Revenue · Customers · Reports · Live 07:00" ($52,480 → $52,611); a notification "Morning digest · MRR +$150 since yesterday". Caption: "*Live,* every morning."
7. **10.5–14.0 s – End card.** Dashboard blurs behind; floating chips MRR $52,611, Churn 1.8%, Growth +12%; logo; "Know your *numbers.*"; pill "peakhq.app".

## 4. Rules
Slow drifting camera with depth of field; numbers tick; the sun rises subtly over the film.

## 5. Sound
Soft ambient piano, gentle swells, tick sounds on numbers, a morning bird chirp with the digest.

## 6. Make it yours
Swap tools, metrics and figures.

---

# Penvia – 11.4-second product film for e-signatures, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
An elegant 2.5D product film, square (1080×1080, 30 fps), for **Penvia**, an invented e-signature tool: it sends a document to everyone at once and collects each signature in order. A cream "Service Agreement" document and a red wax seal carry the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: deep navy #13205A with a soft radial glow.
- Paper: cream #F2EBDC with grey text lines; handwritten signatures in navy ink.
- Accent: wax-seal red #D8343A.
- Type: classic serif (Libre Caslon / Newsreader Semibold) in cream; key words red with a small hand-drawn underline and an "×" mark. UI labels in a small monospace.
- Logo: red wax seal with a "P" + "Penvia" in large cream serif.

## 2. Voiceover (calm, slightly wry)
"Print, sign, scan, send back. It's still how most contracts get done. Penvia sends the document to everyone at once, and collects each signature in order. Penvia. Signed in minutes."

## 3. Scenes
1. **0.0–2.8 s – Old way.** A document "AGREEMENT · Service Agreement" slides out of a printer slot; a vertical step list on the right: Day 1 Mon 09:10 (printer icon), Day 2 Tue 14:40 (pen), Day 2 Tue 16:55 (scan), Day 3 Wed 08:20 (envelope). The paper gets signed "Jo Hale", a scan line passes, it folds into an envelope. Caption: "Print, sign, / scan, send back."
2. **2.8–4.0 s – Day 5.** "Day 5 · ONE CONTRACT · THREE SIGNATURES": the envelope travels an arc between three signers J Jo Hale (✓ Signed · day 3), A Ana Ruiz (Waiting), T Tim Berg (Waiting). Caption: "It's **still** how most / contracts get done."
3. **4.0–6.4 s – Send to all.** A dark Penvia app: "Service Agreement.pdf" preview with three signature boxes; "Signers": Jo Hale (Client), Ana Ruiz (Legal), Tim Berg (Finance), "0 → 3 of 3 sent"; red "→ Send to all" button; each signer gets "✓ Sent 09:02". "SIGNING ORDER · 1 · 2 · 3". Caption: "sends the document / to **everyone** at once,"
4. **6.4–8.5 s – Signatures.** A cream "Signatures · Service Agreement · Page 3 of 3" card: a red numbered timeline 1–2–3; signatures write on in order: Jo Hale (Signed 09:03), Ana Ruiz (Signed 09:05), Tim Berg (Signed 09:06); counter "1 → 3 of 3 signed". Caption: "and collects each / **signature** in order."
5. **8.5–11.4 s – End card.** The red wax seal stamps down; "Penvia"; "Signed in **minutes.**"; three red checks and a timer "01:00 → 03:50 FROM SENT TO SIGNED"; "PENVIA.COM".

## 4. Rules
Slow camera drift; signatures animate as handwriting strokes; the seal lands with a squash and a little drip.

## 5. Sound
Printer whirr, pen scratch, scanner beam, envelope slide, soft string bed, a deep wax-stamp thud at the end.

## 6. Make it yours
Swap document, signers and times.

---

# Podara – 10.2-second product film for AI podcast editing, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A rich 2.5D product film, square (1080×1080, 30 fps), for **Podara**, an invented podcast editor: it removes every "um" and pause, cleans the sound and writes chapters. A big audio waveform carries the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: deep emerald green #0F4A3A with soft flowing wave shapes and a ruler tick strip at the bottom.
- Waveform: mint #9FE8C8 bars on a near-black rounded panel.
- Accent: coral red #F05A4F for "um", pauses, cuts and key words (with a dotted underline).
- Type: bold humanist sans (Source Sans Bold / Nunito Sans) in white; labels in monospace.
- Logo: a mint "P" with a coral dot + "Podara".

## 2. Voiceover (podcaster, friendly)
"An hour of recording means four hours of editing. Podara removes every um and pause, cleans the sound, and writes the chapters for you. Podara. Record, then publish."

## 3. Scenes
1. **0.0–2.5 s – Editing by hand.** A waveform card "● REC · EP 42 · 0:41:19 → 1:00:00". Below, "EDITING BY HAND 0:24:43 → 3:40:24" with four bars HOUR 1–4 filling slowly with manual cut marks. Caption: "An **hour** of recording / means **four hours**".
2. **2.5–4.9 s – Auto-cut.** "● AUTO-CUT": coral tags "um", "pause 2.4 s", "um" appear on the waveform; red cut lines slice them out and the waveform closes the gaps (1:00:00 → 0:51:13). A "REMOVED" counter: "0 → 149 UMS · 0 → 38 PAUSES". Caption: "Podara removes / every **um** and **pause,**"
3. **4.9–5.9 s – Clean.** Full Podara app "Cut · Clean · Chapters · Publish · EP 42 – The first client": "MAIN TRACK 0:48:20"; toggles ✓ Hiss, ✓ Room echo, ✓ Hum; "NOISE FLOOR −48 dB → −62 dB"; the waveform gets crisper. Caption: "**cleans** the sound,"
4. **5.9–7.6 s – Chapters.** Numbered markers 1–4 drop onto the waveform; "CHAPTERS · 0 → 4 OF 4 WRITTEN": 00:00 Cold open, 06:40 The first client, 21:15 Pricing without fear, 39:50 Listener questions (typed). Caption: "and writes the / **chapters** for you."
5. **7.6–10.2 s – End card.** Logo; "Record, then **publish.**"; a mini player "EP 42 · The first client · 48:20 · 4 chapters · clean sound" with a "● Publishing" chip → "● Published". "PODARA.FM".

## 4. Rules
Waveform always animating subtly; cuts snap with satisfying closes; slow camera push.

## 5. Sound
Short snippets of spoken audio with "um"s that get cut out (audible!), hiss that disappears, then a clean podcast intro jingle.

## 6. Make it yours
Swap episode, chapters and numbers.

---

# Praiso – 11-second product film for team recognition, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A warm, celebratory 2.5D product film, square (1080×1080, 30 fps), for **Praiso**, an invented team-recognition tool: it makes saying thanks easy, shares it with the team and shows what the culture really values. Hexagon badges stack up like a honeycomb. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: honey yellow #F6E2A0 → #F9EDC4 with soft light spots.
- Cards: white with soft shadow; avatars in warm browns/oranges with initials.
- Accent: crimson #C8102E; honey gold #F0B532 for badges.
- Type: rounded grotesk (Nunito Bold / Plus Jakarta Sans) in espresso #3A2A20; key words crimson.
- Logo: crimson hexagon with a white sparkle + "Praiso".

## 2. Voiceover (warm team lead)
"Good work happens every day, and most of it goes unnoticed. Praiso makes it easy to say thanks, shares it with the team, and shows what your culture really values. Praiso. Make it count."

## 3. Scenes
1. **0.0–3.6 s – Unnoticed.** Day cards MON–FRI: Mia "Fixed the checkout bug", Jonas "Covered the late shift", Noor "Shipped the release early", Ana "Onboarded three new hires", Theo "Cleared the whole backlog", each "✓ Done" with an empty dashed circle; footer "3 → 5 wins this week · ♡ 0 thanks". Then all fade to faint outlines except Noor, whose empty circle turns into a crimson hexagon outline. Caption: "Good work happens / every day, and most / of it goes **unnoticed.**"
2. **3.6–5.4 s – Say thanks.** A card "To NH Noor Haddad · Shipped the release early · Wed · SAY THANKS": message types "Thank you for shipping early – you saved the launch!"; "ADD A BADGE": Teamwork, Ownership (selected by cursor), Craft, Kindness (honey hexagons); toggle "Share on the team wall"; crimson "♥ Send thanks". Caption: "Praiso makes it easy / to say **thanks,**"
3. **5.4–6.4 s – Team wall.** Thank-you cards appear on a wall: Noor (from Mia, Ownership), Jonas (from Ana, "Covered my shift. Legend", Teamwork), Ana (from Jonas, "Always has our back", Teamwork), with heart counts. Caption: "shares it with / the team,"
4. **6.4–8.3 s – Culture.** Hexagon badges fly together into honeycomb columns: Teamwork 5, Ownership 7 (one crimson), Craft 3, Kindness 4. Caption: "and shows what your / culture really values."
5. **8.3–11.0 s – End card.** Confetti (crimson/gold shapes) bursts; logo; "Make it **count.**"; a row of hexagon dots filling; "1,251 → 1,274 thank-yous this year"; "praiso.team".

## 4. Rules
Bouncy, cheerful springs; hexagons snap like magnets; confetti only at the end.

## 5. Sound
Happy marimba/claps, pop per hexagon, a soft "aww" chime on send, confetti burst.

## 6. Make it yours
Swap names, wins, badges.

---

# Quiet Nights – 10-second talking head ad for an evening wind-down app, 1:1

> Recreated from the public example video. Film your own clip talking to camera at home in the evening, then paste this prompt with it into Claude to add the motion design.

## 0. What you are building
A square (1080×1080) talking head ad for **Quiet Nights**, an app with a 6-minute evening routine. A young woman with red hair in a cosy knit sweater sits on a sofa at night (warm floor lamp) and speaks to camera. Claude adds sleep-mode chips, a wind-down timer, a starry "mind" cutaway with a calming waveform and an app card. Build overlays in code (Remotion).

## 1. Look
- Brand: lavender violet #8A6CF0, deep night indigo #2A1E6B, white.
- Type: white sans (Inter Semibold) + white serif italic (Playfair Display Italic); key words in a violet rounded box.

## 2. Script
"Can't switch off at night? Six calm minutes before bed, and your mind finally slows down. Try the free evening routine at quietnights.app."

## 3. Scenes
1. **0.0–1.6 s – Hook.** A dark iOS-style focus pill "☾ Focus · Off" flips to "☾ Sleep · On". Caption: "Can't switch off / at *night?*"
2. **1.6–4.1 s – Timer.** Caption "Six *calm*"; a pill "◯ Timer · Wind down 6:00 → 5:59" counting. Caption: "before / *bed,*"
3. **4.1–5.8 s – Mind.** Cut to a starry indigo background: big white "mind", a violet pill "and your", an agitated violet waveform calms into a smooth line; then the clip returns in the lower half with a circle and "mind *finally*".
4. **5.8–6.6 s – Slows down.** Spaced-out letters "s l o w s" and "*down.*" over the clip with the calm waveform.
5. **6.6–8.3 s – Routine.** Caption "Try the *free* / *evening* routine"; a white card "TONIGHT · 6 MIN": ✓ Slow breathing 2 min, ✓ Body scan 2 min, ✓ Lights down 2 min.
6. **8.3–10.0 s – App card.** A white card over the blurred clip: violet app icon with a crescent moon, "Quiet Nights · Your 6-minute evening routine", field "at quietnights.app" typing, violet "Try free" button.

## 4. Rules
Slow, soft easing everywhere; captions word-synced; everything breathes.

## 5. Sound
Original voice, soft ambient pad, a slow breath sound, gentle chime on the card.

## 6. Make it yours
Swap app, routine steps and URL; use your own clip.

---

# Quillo – 11.4-second product film for AI proposal writing, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
An elegant, paper-like 2.5D product film (1920×1080, 30 fps) for **Quillo**, an invented tool for agencies: it listens to the sales call, drafts every section of the proposal, prices it from your rate card and sends it out for signature. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: warm ivory paper #F2ECE2 with faint horizontal ruled lines and one red vertical margin line on the left.
- Cards: white/cream documents with thin borders; dark ink #1E2235.
- Accent: ink red #C8322E for key words (italic) and buttons.
- Type: refined serif (Cormorant Garamond / Newsreader) for headlines; key words in red italic. UI in a small grotesk.
- Logo: "Quillo" in large high-contrast serif with a quill-stroke red underline.

## 2. Voiceover (calm, confident)
"You finish the call, and the proposal still isn't written. Quillo listens in, drafts every section, prices it from your rate card, and sends it out for signature. Quillo. Proposals that write themselves."

## 3. Scenes
1. **0.0–2.8 s – Call ends.** A video-call card "Discovery call · Northpeak Coffee · ● 32:13": tiles "MO Maya Okafor · Northpeak" and "You · Fernhill Studio", red "End call"; chip "Call ended · 32:14". An empty document "Proposal for Northpeak · Not started · 0 words · Due tomorrow 9:00". Caption: "You finish the call, / and the proposal still isn't written."
2. **2.8–4.7 s – Listens.** A "Quillo · listening" waveform card next to the document; highlights from the call become chips: "three landing pages", "live before summer", "around twelve thousand". Caption: "Quillo *listens* in,"
3. **4.7–5.7 s – Drafts.** The document fills: "Website relaunch · Proposal for Northpeak Coffee · 14 May"; sections 1 Summary, 2 Scope (Three landing pages and the shop; New subscription checkout; CMS training for the team), 3 Timeline (Kick-off 19 May · design 3 weeks · build 6 weeks · Live by 1 July). Caption: "drafts every section,"
4. **5.7–6.6 s – Prices.** A "Rate card": Discovery workshop $1,800/day, Design $140/hour, Development $160/hour; lines fly into "4 Pricing … Total $5,104 → $11,560". Caption: "prices it from / your rate card,"
5. **6.6–8.5 s – Signature.** The proposal folds into a signing card "Maya Okafor · Northpeak Coffee · Website relaunch $11,560"; a handwritten signature writes on; badge "✓ Signed". Caption: "and sends it out for *signature.*"
6. **8.5–11.4 s – End card.** Logo; "Proposals that *write themselves.*"; "QUILLO.APP".

## 4. Rules
Paper physics: slight curl and soft shadows; text writes on line by line; slow lateral camera drift.

## 5. Sound
Soft piano, a muffled call fading out, pen scratches, paper slides, a fountain-pen flourish on the signature.

## 6. Make it yours
Swap client, scope, rate card and total.

---

# Reelo – 10.5-second product film for AI clip extraction, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A vertical product film (1080×1920, 30 fps) for **Reelo**, an invented tool that watches a long video, cuts the best clips and frames them for every feed. A long film strip receding into perspective carries the story. Build in code (Remotion/React + a bit of 3D perspective) and render to MP4.

## 1. Look
- Background: dark teal-black #12201F with subtle sprocket-hole film edges.
- Film strip: dark frames with simple flat-illustrated people (talking heads) in muted blue/green/purple backgrounds.
- Accent: electric violet/magenta #C04CFD — selection brackets "[ ]", progress, highlighted words in brackets.
- Type: condensed bold sans (Barlow Condensed ExtraBold / Oswald) in white; key words wrapped in violet square brackets "[ten]". Labels in monospace.
- Logo: violet brackets around a white ▶ "[▶] Reelo".

## 2. Voiceover (energetic creator)
"One long video holds ten great moments. Finding them takes all day. Reelo watches it for you, cuts the best clips, and frames them for every feed. Reelo. One video, ten posts."

## 3. Scenes
1. **0.0–2.6 s – Film strip.** A film strip recedes into the distance; a playhead line moves along it; frames light up with violet borders; chip "▶ founder-interview.mp4 · 00:18:37 → 00:58:29" and "3 → 8 → 10 MOMENTS". Caption: "One long video holds / [ten] great moments."
2. **2.6–3.5 s – Manual.** The strip turns vertical on the left; a "Manual review · SCRUBBING" card: ring "TIME SPENT 6h 15m by hand", "Moments found 0/10", "Your workday 8H GONE". A cursor scrubs. Caption: "Finding them / takes all day."
3. **3.5–5.2 s – Reelo scan.** "Reelo scan · WATCHING → DONE": ring "0h 26m → 0h 04m with Reelo", "Moments found 3/10 → 10/10" violet segments; frames on the strip get violet brackets; "Your workday 7H 56M FREE". Caption: "Reelo watches it for you,"
4. **5.2–7.0 s – Cut & frame.** Three clips pop out as cards; then reframed into 9:16, 1:1 and 16:9 with violet face-tracking brackets; a bar "▭▭▭ 3 formats · captions on · RENDERING 0% → 57%", queue "+7 MORE CLIPS IN THE QUEUE". Caption: "cuts the [best clips,] / and frames them / for every feed."
5. **7.0–10.5 s – End card.** Brackets snap around ▶; "Reelo"; "One video, [ten] posts."; a row of clip thumbnails fills "2 → 6 → 10 / 10 POSTS READY"; "reelo.app".

## 4. Rules
Film-strip parallax; bracket snaps with a tiny overshoot; fast but readable.

## 5. Sound
Punchy beat, film-projector clatter, scrub sounds, snap per bracket, render "whoosh".

## 6. Make it yours
Swap video name, counts, formats.

---

# Rellio – 9-second product film for AI customer support, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A warm 2.5D product film (1920×1080, 30 fps) for **Rellio**, an invented AI support tool: it reads each ticket, drafts the answer and sends it in your voice, so support replies in seconds. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: peach/salmon #F2D3C2 with soft diagonal light stripes.
- Cards: cream-white #FBF4EE; accent orange-red #E8532F for highlights, checks and a blinking text cursor.
- Type: chunky slab serif (Roboto Slab Bold / Clarendon) in dark brown #2B1810 for headlines, followed by an orange cursor "|". UI in Inter + monospace labels.
- Logo: "Rellio" in heavy dark-brown slab serif with an orange square dot over the "i".

## 2. Voiceover (calm, efficient)
"Two hundred tickets before lunch. Rellio reads each one, drafts the answer and sends it in your voice. Support that replies in seconds. Rellio."

## 3. Scenes
1. **0.0–1.5 s – Pile.** A stack of ticket cards; chips "🕐 10:08 → 11:36 · ✉ 86 → 193 open". Top ticket: "#4821 · Email · Waiting 2h 14m · SW Sam Whitfield · Where is my order? · Hi, I ordered the oak desk lamp on May 2 and it still hasn't arrived. Order #4821 says shipped since last week. Can you check or refund me?" tags Shipping, Lamps. Caption: "Two hundred / tickets / before lunch."
2. **1.5–3.0 s – Reads.** Key phrases highlight orange; side tags pop: "INTENT Late delivery", "ORDER #4821", "ASK Refund". Caption: "Rellio reads each one,"
3. **3.0–3.8 s – Drafts.** A "Reply to Sam" card types: "Hi Sam, thanks for your patience. Your lamp was held at the depot, so I have re-sent it today with express delivery, at no extra cost. It arrives on Thursday. Tracking: RL-4821-X. Cheers, Maya" with buttons Edit / Send. Caption: "drafts the answer,"
4. **3.8–5.2 s – Your voice.** The ticket thread "✓ Solved": customer bubble and the reply bubble "Maya · Olive & Co. · Delivered in 4 s"; "YOUR VOICE · Learned from 1,240 replies": ✓ Warm, ✓ Brief, ✓ Signs off as Maya; "Voice match 96%". Caption: "and sends it / in your voice."
5. **5.2–6.7 s – Queue.** A "Today's queue" grid of 200 squares fills with orange check marks in a wave; "3 → 185 of 200 answered · 0.2 s → 4.0 s avg. reply". Caption: "Support that replies in seconds."
6. **6.7–9.0 s – End card.** Logo with the orange dot dropping in; chips "✓ 200 of 200 answered · 11:41 → 11:42".

## 4. Rules
Typing with a blinking cursor; cards slide on diagonals; camera slowly pans.

## 5. Sound
Lo-fi beat, email pings piling up, keyboard typing, a satisfying "whoosh" on send, tick wave sound in the queue.

## 6. Make it yours
Swap ticket, product, agent name and numbers.

---

# Routa – 13.6-second product film for delivery route planning, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A bold, editorial 2D product film (1920×1080, 30 fps) for **Routa**, an invented route planner for delivery vans: it maps the fastest route, texts every customer and reroutes when traffic hits. A flat city street map with 12 numbered stops carries the story; a black side panel holds the text. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Map: cream #F1EADC base, white streets in a grid, grey hatched blocks; a "● LIVE 07:42" chip top-right.
- Panel: black #161414 on the left (or bottom) with huge thin outlined numerals in the background.
- Accent: signal red #E23B2E for the route, van and key words. Checks: red circles with white ticks.
- Type: classic serif (Newsreader / Source Serif Bold) in cream; key words red italic. Data labels in monospace caps.
- Logo: red circle with a white S-route + "Routa" in italic serif.

## 2. Voiceover (punchy narrator)
"Twelve stops. One van. No plan? Routa maps the fastest route, texts every customer, and reroutes when traffic hits. Routa. Every delivery, on time."

## 3. Scenes
1. **0.0–3.4 s – Chaos.** Map with white numbered stops 1–12 and a "DEPOT"; a red van. Big words in the black panel: "Twelve" (outlined "6"), "One *van.*" (outlined "1"), "No *plan?*" (outlined "?"); messy grey lines criss-cross between stops.
2. **3.4–5.6 s – Route.** "Routa" bar; a clean red route draws through stops in order from the depot; stats "TOTAL DRIVE TIME 3 H 05". Caption: "Routa maps the / ***fastest route,***"
3. **5.6–6.8 s – Texts.** ETA tags pop at each stop ("ETA 08:31", "ETA 09:14"…); "CUSTOMERS TEXTED 12 / 12". Caption: "texts every / ***customer,***"
4. **6.8–9.0 s – Reroute.** A red hatched "TRAFFIC +14 MIN" block appears on the route; the route snaps around it; "TRAFFIC AHEAD +14 MIN" → "REROUTED · STILL ON TIME". Stops tick red as the van passes ("● LIVE 09:46"). Caption: "and reroutes when / ***traffic hits.***"
5. **9.0–13.6 s – End card.** Black panel: logo; "Every delivery, *on time.*"; red pill "routa.app"; the map shows the finished route with a chip "12 / 12 DELIVERED · ON TIME" and "● LIVE 10:37"; coordinates in tiny mono.

## 4. Rules
Flat, graphic; route draws with a pen-like stroke; van icon moves smoothly along the path.

## 5. Sound
Driving funk-ish beat, van engine hum, SMS "ding" per customer, traffic horn on the reroute, final stamp.

## 6. Make it yours
Swap stop count, times, URL.

---

# Schemata – 11-second product film for a no-code internal-tool builder, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A crisp, design-tool-styled 2.5D product film (1920×1080, 30 fps) for **Schemata**, an invented builder for internal tools: drag in a table, connect your database and publish a working admin panel in an afternoon. Selection boxes with handles (like Figma) frame the key words. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: pale lilac-grey #ECEAF2 with faint wireframe UI.
- UI: white panels, black headers #121018; accent magenta #E0177A (selection boxes with square corner handles, cursors labelled "You").
- Type: grotesk (Inter Bold) in near-black; key words inside a magenta selection rectangle with handles. UI labels in monospace.
- Logo: "Schemata" in heavy black inside a magenta selection box with a tiny tag "schemata.build".

## 2. Voiceover (wry, upbeat)
"Your team needs an admin panel, and engineering says next quarter. With Schemata, you drag in a table, connect your database, and publish a working tool in an afternoon. Schemata. Build it yourself."

## 3. Scenes
1. **0.0–3.4 s – Next quarter.** A roadmap board: columns "Q4 2026 · NOW" (Billing v2, SSO rollout), "Q1 2027 · NEXT" (Mobile app, API v3). A card "REQ-284 · INTERNAL TOOL · Admin panel · Refunds, order edits, user lookup · 5 → 12 requests" is dragged by a cursor labelled "Engineering" into Q1 2027; tag "Q1 2027". Caption: "Your team needs an admin panel, / engineering says [next quarter.]"
2. **3.4–5.5 s – Drag a table.** A component sidebar (Table, Button, Chart, Form, Text); the "You" cursor drags "Table" onto an empty "Admin panel" canvas; magenta guides snap it. Caption: "With Schemata, / you drag in a [table,]"
3. **5.5–6.4 s – Database.** A "Postgres · CONNECTED" card with tables ✓ orders, customers, refunds; a magenta wire connects to the table, which fills with rows (Maya Lindqvist $129.00 Paid, Tomás Rey $64.50 Refunded, Aiko Tanabe $310.00, Jonas Weber $18.40, Priya Nair $245.00). Caption: "connect your [database,]"
4. **6.4–8.3 s – Working tool.** Stats cards "1,284" orders, "37" refunds, a magenta bar chart; a "+ New refund" button; multiple cursors (Support, Ops, Finance) use it; chip "3 teams using it now"; a time card "13:05 → 16:40". Caption: "a working tool in an [afternoon.]"
5. **8.3–11.0 s – End card.** Logo; "Build it [yourself.]"; a row of tiny tool icons fills "00 → 05 → 10 TOOLS BUILT THIS QUARTER".

## 4. Rules
Design-tool feel: crisp snapping, selection handles, smooth cursors with name tags.

## 5. Sound
Clean electronic beat, mouse clicks, snap sounds, a "publish" whoosh, final pop.

## 6. Make it yours
Swap tool, data and teams.

---

# Scouta – 9.6-second product film for AI recruiting, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A clean, airy 2.5D product film (1920×1080, 30 fps) for **Scouta**, an invented hiring tool: it reads every résumé, ranks the best fits and books interviews, so you hire in days, not months. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: very light blue-grey #EEF2F6 with a faint dot grid.
- Cards: white résumés; app panels in deep navy #1E2B45. Accent: cyan #29B6E8 — key words wrapped in thin cyan square brackets "[ ]".
- Type: condensed humanist sans (Barlow Semi Condensed SemiBold / Oswald) in navy.
- Logo: cyan rounded square inside navy corner brackets (a viewfinder) + "Scouta".

## 2. Voiceover (brisk)
"Three hundred applicants, one opening. Scouta reads every résumé, ranks the best fits, and books the interviews. Hire in days, not months. Scouta."

## 3. Scenes
1. **0.0–1.6 s – 300.** Hundreds of tiny résumé cards form the giant number "300". Caption: "Three hundred applicants,"
2. **1.6–2.4 s – Funnel.** The résumés pour into a funnel shape toward a navy card "OPEN ROLE · Product Designer · Berlin · Hybrid · Full-time · APPLICANTS 296". Caption: "[one] opening."
3. **2.4–4.0 s – Reading.** A résumé "LO Lena Okafor · Product Designer · Berlin" (experience 2021–24 Senior Designer, Fiora; 2018–21 Product Designer, Lexis; 2016–18 UX Designer, Nord Studio; skills Figma, Prototyping, User research; BA Interaction Design) with cyan corner brackets scanning; navy card "READING RÉSUMÉS 1 → 300 / 300" with a progress bar, current "NH Noor Haddad · 78% match" and tags. Caption: "Scouta reads / [every résumé,]"
4. **4.0–4.8 s – Ranking.** Initial chips (HL, SR, TM, PN, RC, JW, EB, NH, DK, AS, MT, LO) slide along an axis "MATCH WITH THE ROLE %" 50–100; the top three (AS, MT, LO) land in a highlighted "BEST FITS" zone. Caption: "ranks the best fits,"
5. **4.8–6.4 s – Interviews.** Three navy interview cards with cyan checks: "LO Lena Okafor · Video interview · 45 min · TUE 10:00", "MT Marek Tomasz · TUE 14:30", "AS Aiko Sato · WED 09:15"; pill "3 interviews booked". Caption: "and books / the [interviews.]"
6. **6.4–8.0 s – Days.** A pipeline Applied → Screened → Interview → Offer → Hired with the LO chip moving; "TIME TO HIRE 5 → 6 days" vs struck-out "44 days without Scouta". Caption: "Hire in [days,] not ~~months.~~"
7. **8.0–9.6 s – End card.** Logo; "300 APPLICANTS → 3 INTERVIEWS → 1 HIRE"; "scouta.io".

## 4. Rules
Clean, fast transitions; brackets snap around words; smooth counting.

## 5. Sound
Upbeat minimal beat, paper flutter, scanning beeps, calendar "pops", success chime.

## 6. Make it yours
Swap role, names, counts.

---

# Seatlo – 10.8-second product film for restaurant reservations, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A stylish vertical 2.5D product film (1080×1920, 30 fps) for **Seatlo**, an invented restaurant booking tool: it takes bookings online, reminds every guest and seats the room twice. A top-down floor plan of black tables with chairs carries the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: warm stone/linen #E6E3DA with faint floor-plan lines ("ENTRANCE", "BAR").
- Tables: glossy black #161616 with light-grey chairs; seated chairs turn olive green #7FA33A. Reservation cards: cream with handwritten names.
- Accent: lime/olive green #A9C94A for buttons and key words.
- Type: classic serif (Newsreader) in black; key words in olive green handwritten script (Caveat / Homemade Apple).
- Logo: black table-shaped pill with a lime card icon + "Seatlo" in cream serif, surrounded by chairs.

## 2. Voiceover (restaurant owner)
"Friday night, the phone rings nonstop, and a table of six doesn't show. Seatlo takes bookings online, reminds every guest, and seats the room twice. Seatlo. A full house, every night."

## 3. Scenes
1. **0.0–1.8 s – Phone.** A paper booking book "Friday · 16 Oct" with handwritten entries 18:30 Okafor (4), 19:00 Ana (2), 19:30 Laurent (6), 20:00 Kim (2), 20:15 Mori; a black phone "INCOMING CALL · CALLS TONIGHT 12 → 14"; chips "Missed call 19:02 / 19:03 / 19:05". Caption: "Friday night, / the phone rings / *nonstop,*"
2. **1.8–3.6 s – No-show.** A big table for six "Laurent · 6 guests · 19:30" with empty chairs; clock "19:40 → 20:15 · 45 min late"; a stamp "NO-SHOW". Caption: "and a table of six / *doesn't show.*"
3. **3.6–5.0 s – Online.** A black app bar "Book · Remind · Seat · ● Fri 16 Oct · Seatlo" with "Fri 16 Oct · 19:30 · 2 guests · Book table", "BOOKED ONLINE 1 → 5"; the floor plan (T1–T5) gets reservation cards Ana, Okafor, Kim, Laurent, Mori. Caption: "Seatlo takes / bookings *online,*"
4. **5.0–5.9 s – Remind.** "Remind" tab: a message "Hi Ana, see you Friday at 19:00? Reply YES to keep your table." "CONFIRMED 2/5"; bell icons on tables turn to checks. Caption: "reminds *every* guest,"
5. **5.9–8.1 s – Seat twice.** "Seat" tab with a timeline 17:00–23:00: "1st 18:00" and "2nd 20:30" seatings; chairs turn green; each table gets a "×2" badge; "COVERS TONIGHT 18 → 36". Caption: "and seats the / room *twice.*"
6. **8.1–10.8 s – End card.** Logo table with chairs filling green; "A *full house,* / every night."; a row of seven dots filling; "SEATLO.APP".

## 4. Rules
Top-down camera with slight tilt; cards drop in with soft shadows; chairs pop green.

## 5. Sound
Restaurant buzz and phone rings at the start, then a smooth jazz bed, notification pings, chair-scrape "pops".

## 6. Make it yours
Swap names, times and covers.

---

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

---

# Sharlo – 9.6-second product film for bill splitting, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A bright, playful vertical product film (1080×1920, 30 fps) for **Sharlo**, an invented bill-splitting app: it reads the receipt, assigns each item and everyone pays their share in a tap. A round restaurant table seen from above carries the story, turning into a donut chart. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: fresh mint #BFEBD9 → #DDF5EA with large faint pie-slice shapes.
- Diners: coloured circles with names — Mia (teal #1F8A7A), Jonas (navy #1B2A4A), Ada (white), You (tomato red #E8432F).
- Accent: tomato red for key words, with a tiny red tick mark above.
- Type: bold rounded grotesk (Manrope ExtraBold / Plus Jakarta Sans) in navy.
- Logo: a circle split into four quadrants (red, navy, navy, navy) + "Sharlo" in navy.

## 2. Voiceover (friendly, a bit funny)
"Dinner was great. Then the bill arrives, and the math begins. Sharlo reads the receipt, assigns each item, and everyone pays their share in a tap. Sharlo. Fair and square."

## 3. Scenes
1. **0.0–0.8 s – Dinner.** Top-down white table with a navy pizza in the middle and plates; four diners around; chip "Trattoria Nonna · Table 12 · 21:40". Caption: "Dinner was great."
2. **0.8–3.2 s – The bill.** The pizza turns into a receipt card counting up to "TOTAL $145.20"; speech bubbles: "Who had the wine?", "Just ÷ 4?", "I only had a salad…", "Plus service?"; a struck-out "÷ 4 = $36.30 each". Caption: "Then the bill arrives, / and the **math** begins."
3. **3.2–4.0 s – Reads.** Receipt "Trattoria Nonna · Reading 1/7" with a red scan line; toggle "Evenly | By item". Caption: "Sharlo reads the receipt,"
4. **4.0–5.6 s – Assign.** Lines: 1× Margherita 16.00, 1× Truffle tagliatelle 24.00, 1× Burrata salad 13.00, 1× Lasagne 19.00, 1× Red wine bottle 36.00, 2× Tiramisu 16.00, 1× Sparkling water 8.00, Service 10% 13.20 → Total $145.20; "7 items read". Coloured dots assign items to diners; totals beside avatars: Mia $30.00, Jonas $38.00, Ada $23.00, You $41.00; toggle switches to "By item". Caption: "**assigns** each item,"
5. **5.6–7.2 s – Pay.** A donut chart "TABLE 12 $145.20" with segments Ada $25.28, You $45.07, Jonas $41.77, Mia $32.97; red button "Pay my share $45.10" → navy "✓ Paid", options "Apple Pay · Card · Bank"; avatars get red checks. Caption: "and everyone pays / their share in a **tap.**"
6. **7.2–9.6 s – End card.** Logo; "Fair and **square.**"; four avatar dots M, J, A, Y each getting a check; "SHARLO.APP".

## 4. Rules
Top-down, playful springs; donut segments sweep in; slow camera rotation of the table.

## 5. Sound
Restaurant ambience, plate clinks, receipt printer, pops per item, cash "ka-ching" on paid.

## 6. Make it yours
Swap restaurant, items, diners.

---

# Shopfly – 14-second 3D ad film for an e-commerce platform, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A 14-second horizontal (1920×1080, 30 fps) cinematic 3D ad for **Shopfly**, an invented store builder: every brand starts with one product; Shopfly builds the store around it; sell online, on social, in person; every order lands in one place. A lime shopping bag and a small terracotta pixel mascot appear throughout. One continuous camera move in a dark studio. Build in code (Three.js / React Three Fiber in Remotion) and render to MP4.

## 1. Look
- Dark studio: near-black #0B0B0B background, glossy floor, glowing lime #A6E05A ring lines on the floor.
- Hero bag: lime green shopping bag with a white paper-plane logo.
- Products (invented brands): "Henley's" milk bottle, "Red Bolt" can, "kiki cosmetics" box, white earbuds, and the hero "GYMWHALE" white training shaker with a black whale-tail logo.
- Mascot: small blocky terracotta character with two eyes (cube body, stubby legs).
- Devices: silver laptop, phone on a dock, card terminal.
- Type: white bold sans (Inter Bold), centred.
- Logo: lime bag + "shopfly" in white rounded bold.

## 2. Voiceover (warm, inspiring)
"Every brand you love started with one product. Shopfly builds the store around it. Sell online, on social, in person. Every order lands in one place. Start selling today."

## 3. Scenes
1. **0.0–2.3 s – Brands.** Products orbit the lime bag; the mascot peeks out of the bag. Caption: "Every brand you love / started with one product."
2. **2.3–3.5 s – One product.** Everything else drops away; the GYMWHALE shaker rises out of the bag.
3. **3.5–4.7 s – Store builds.** The camera dives toward the shaker as white store panels assemble around it (colour swatches, capacity options).
4. **4.7–5.8 s – Product page.** A laptop shows "Training Shaker" with colour dots, size "500 ml / 750 ml", lime "Add to cart" clicked by a cursor.
5. **5.8–8.2 s – Channels.** Camera pulls back: laptop (online), phone (social shop), card terminal (in person, check mark) on the lime-ring floor; the mascot walks between them. Caption: "Sell online, on social, in person."
6. **8.2–10.5 s – Orders.** Push in on the phone: "Orders · 10 → 128 orders" list of #1047 Training Shaker…; mascot beside it. Caption: "Every order / lands in / one place."
7. **10.5–14.0 s – End card.** Lime bag with the mascot on top + "shopfly"; "Start selling today."

## 4. Rules
One continuous camera path, no cuts; slow, premium moves; soft rim lights and reflections.

## 5. Sound
Modern upbeat electronic bed, product "pops", cart click, terminal beep, order notification pings.

## 6. Make it yours
Swap hero product, brand, channels and mascot.

---

# Sift – 8.8-second product film for customer-feedback analysis, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A minimal 2.5D product film (1920×1080, 30 fps) for **Sift**, an invented tool that gathers every piece of customer feedback, sorts it by topic in seconds and shows what to build next. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: warm off-white #F1EEEA with soft vignette.
- Cards: white feedback chips with small source icons; text near-black.
- Accent: signal red #E8392C (ring, top topic bar, key words).
- Type: humanist sans (Source Sans / Inter Semibold) in near-black; key words red.
- Logo: red magnifier/pin icon + "Sift" in heavy black.

## 2. Voiceover (calm product voice)
"Feedback everywhere? Sift gathers every comment, sorts them by topic in seconds, and shows what to build next. Sift. Hear what matters."

## 3. Scenes
1. **0.0–1.4 s – Everywhere.** Feedback chips float around with source labels (App Store, Support, Live chat, Sales call): "Checkout keeps freezing", "Can't export to CSV", "Dark mode, please!", "Checkout failed twice", "Where is the export?", "Payment page is so slow", "Onboarding is confusing". Caption: "Feedback **everywhere?**"
2. **1.4–2.9 s – Gather.** Chips get pulled into a red ring counter "0 → 1,074 COMMENTS". Caption: "Sift gathers every **comment,**"
3. **2.9–4.4 s – Sort.** The ring shrinks left; horizontal topic bars grow: Checkout 512 (red), Export 318, Dark mode 204, Onboarding 96. Caption: "sorts them by **topic** in seconds,"
4. **4.4–6.0 s – Build next.** The Checkout bar becomes a card "ROADMAP · Fix checkout freezes · 512 mentions · ▲ 38% this week" with a red stamp "BUILD NEXT"; below "2 Export to CSV 318 · 3 Dark mode 204". Caption: "and shows what to **build** next."
5. **6.0–8.8 s – End card.** Logo; "Hear what **matters.**"; topic chips float around (Checkout 512, Export 318, Dark mode 204, Onboarding 96); a black pill "getsift.app".

## 4. Rules
Very clean; chips drift slowly, then snap; bars grow with ease-out.

## 5. Sound
Soft murmur of many voices that resolves into silence, tick sounds while sorting, a stamp thud, light piano.

## 6. Make it yours
Swap topics, counts and URL.

---

# Solidbase Concrete – 10-second talking head ad for a concrete foundations contractor, 16:9

> Recreated from the public example video. Film your own clip on a building site, then paste this prompt with it into Claude to add the motion design.

## 0. What you are building
A horizontal (1920×1080) talking head ad for **Solidbase Concrete**, a foundations contractor. A builder in a hi-vis vest and dark hoodie, holding a white hard hat, speaks on a construction site (formwork, rebar, a loader). Claude adds line-drawn houses, a cutaway animation of concrete being poured and levelled, and a branded end card. Build overlays in code (Remotion).

## 1. Look
- Brand: safety yellow #F5D30F, charcoal #2B2B2B, white; yellow/black hazard stripes.
- Type: white bold sans (Inter Bold); key words in yellow serif italic (Playfair Display Italic) on a hazard-stripe label or boxed with a yellow outline.

## 2. Script
"A house is only as good as its foundation. We pour it right. The first time. solidbaseconcrete.co"

## 3. Scenes
1. **0.0–2.5 s – Hook.** A white line drawing of a house builds itself next to him ("A house"); caption "is only as [good] as its" with "good" in a yellow outline box; a hazard-stripe label "*foundation.*" slides under the house.
2. **2.5–5.0 s – Pour.** Charcoal full-frame cutaway: wooden formwork on gravel with rebar; a chute pours grey concrete that fills the form; a screed bar levels it; chip "LEVEL —" → "LEVEL 0.0°" with a yellow spirit level. Caption: "We pour it / *right.*"
3. **5.0–7.5 s – First time.** Back on him; a yellow line sweeps across; "The first time." Small card: a corner bracket + level line "0.0° ✓", then a yellow house on a striped foundation.
4. **7.5–10.0 s – End card.** A charcoal panel rises with hazard stripes along the bottom: yellow house logo "SOLIDBASE CONCRETE", URL typing "solidbaseconcrete.co", "FOUNDATIONS · SLABS · DRIVEWAYS".

## 4. Rules
Captions word-synced; technical, line-drawing feel; keep his face clear.

## 5. Sound
Original voice, site ambience, concrete mixer rumble on the pour, level "click", a solid drum hit on the logo.

## 6. Make it yours
Swap trade, steps, URL; use your own clip.

---

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

---

# Streako – 10.9-second product film for a habit tracker, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A warm, moody vertical product film (1080×1920, 30 fps) for **Streako**, an invented habit app: it keeps your streak visible, nudges you at the right moment and celebrates every single day. A 21-day calendar of circles turns into a chain of dots. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: dark espresso-brown #2A1E18 with a warm radial glow and a dot-matrix texture at the bottom.
- Circles: cream #F1E7DA outlines/fills; accent lavender #A98BF5 for today, nudges and key words.
- Type: classic serif (Newsreader / Source Serif Semibold) in cream; key words lavender italic with a dotted underline. Big dot-matrix numerals for streak counts.
- Logo: "Streako" in cream serif inside a ring of cream dots with one lavender dot travelling around it.

## 2. Voiceover (gentle, motivating)
"Day one is easy. Day twelve is where habits quietly die. Streako keeps your streak visible, nudges you at the right moment, and celebrates every single day. Streako. Don't break the chain."

## 3. Scenes
1. **0.0–1.8 s – Day one.** "Morning run" pill and "STREAK 0 → 1"; a 3-week grid (M–S, 1–21) of circles; day 1 gets a check; "21-DAY GOAL 1/21". Caption: "Day one is *easy.*"
2. **1.8–3.6 s – Day twelve.** Days connect into a chain up to 8; then 8–11 go grey/faded while 12 glows lavender (dashed); "STREAK 11"; "21-DAY GOAL 11/21". Caption: "Day twelve is where / habits quietly die."
3. **3.6–5.4 s – Visible.** A "Today · Wed 14 Oct" card: "MORNING RUN" big dot-matrix "11 day streak", dashed lavender ring "12 TODAY"; a 2026 year dot-grid "234 of 287 days"; other habits "Read 20 pages 34", "Stretch 9". Caption: "Streako keeps / your streak *visible,*"
4. **5.4–6.4 s – Nudge.** "YOUR USUAL TIME around 7:10 PM" timeline with a stack of dots at 7:02 PM; a notification "🔔 Time to run. 10 minutes keep day 12 alive · Log run". Caption: "nudges you at / the right moment,"
5. **6.4–8.1 s – Celebrate.** Big lavender check; the streak flips to "12 · DAY 12 DONE"; then a ring of cream dots with "16 DAY STREAK" in dot-matrix and milestone chips "● 7 days ● 14 days ○ 21 days". Caption: "and celebrates every / single day."
6. **8.1–10.9 s – End card.** The dot ring rotates around "Streako"; "DAY 22 → 23"; "Don't break the *chain.*"; "streako.app".

## 4. Rules
Soft and steady; dots pop in sequence like a chain; slow camera push.

## 5. Sound
Warm lo-fi beat, soft "tick" per day, a phone buzz for the nudge, celebratory chime and light claps at 12.

## 6. Make it yours
Swap habit, numbers and nudge text.

---

# Summit Movers – 10-second talking head hiring ad for a moving company, 9:16

> Recreated from the public example video. Film your own selfie clip, then paste this prompt with it into Claude to add the motion design.

## 0. What you are building
A vertical (1080×1920) talking head recruiting ad for **Summit Movers**, a moving company hiring two crew members. A young man in an olive hoodie films himself on the steps outside a house. Claude adds a rotating "We're hiring" badge, typed name chips, a crew-avatar row, b-roll photo cards, a perks checklist and an "Apply" link button. Build overlays in code (Remotion).

## 1. Look
- Brand: royal blue #2F5BEA, white pills, light periwinkle gradient panels #E6ECFF.
- Type: white/black bold sans (Inter Bold); key words in blue; one serif italic accent ("*crew.*").

## 2. Script
"We're hiring! I'm Kai from Summit Movers, and we need two more people on the crew. Weekly pay, free lunch, and no more leg day. Apply through the link!"

## 3. Scenes
1. **0.0–0.8 s – Badge.** A circular text ring "WE'RE HIRING • WE'RE HIRING" rotates around his head with a blue glow; a white pill types "● We're **hiring**".
2. **0.8–2.5 s – Name.** "I'm" with a blue cursor tag "K" (like a collaborator cursor), then "from" and a white pill "🧊 Summit Movers" typed.
3. **2.5–4.2 s – Two more.** The clip shrinks into a browser-window card "Summit Movers" on a periwinkle panel; "we need / **2 more** / people"; a pill of six avatars where the last two are dashed "+" slots; "on the *crew.*" A b-roll photo card (two movers carrying a sofa up the steps to a white truck) slides over.
4. **4.2–6.2 s – Perks.** A second photo card (the crew eating lunch on the truck's tailgate); a white checklist: ✓ Weekly pay, ✓ Free lunch.
5. **6.2–7.8 s – Joke.** Back on him; caption "no more" + "~~leg day.~~" with a blue strike and little blue squares bursting.
6. **7.8–10.0 s – CTA.** Blue pill "Apply" + "through the" + a blue link pill "🔗 link." that gets clicked with a check.

## 4. Rules
Captions word-synced and typed; overlays spring in; keep his face clear.

## 5. Sound
Original voice, upbeat indie beat, keyboard typing for the pills, camera-shutter for photo cards, click on the link.

## 6. Make it yours
Swap name, company, perks, roles; use your own clip.

---

# Tallyo – 10.8-second product film for company spend cards, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A premium, dark 2.5D product film, square (1080×1080, 30 fps), for **Tallyo**, an invented corporate card platform: it gives everyone their own card, sets a limit for each and matches every receipt automatically. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: deep forest green #0E2A20 with a soft vignette and a faint ornamental guilloche ring (like banknote engraving).
- Cards: dark green metallic cards with chip, "TALLYO" wordmark, contactless icon, holder name and last four digits.
- Accent: copper/terracotta #D9875A for key words, sliders and tally-mark logo.
- Type: elegant serif (Newsreader / EB Garamond) in cream; key words copper italic. UI labels in small caps.
- Logo: copper tally-marks "𝍸" inside an outlined rectangle + "Tallyo" in cream serif.

## 2. Voiceover (calm, assured CFO tone)
"One company card, passed around the whole team. Tallyo gives everyone their own card, sets a limit for each, and matches every receipt on its own. Tallyo. Spending under control."

## 3. Scenes
1. **0.0–2.7 s – Passed around.** A grey "COMPANY CARD •••• 4471 · SHARED · 4 USERS" orbits inside the guilloche ring between four avatars M Maya, J Jonas, T Tom, I Ines (each with a "•••" bubble). Caption: "One company card, / passed around the *team.*"
2. **2.7–4.5 s – Own cards.** Four green Tallyo cards deal out: •••• 2041 Maya Lindqvist (Marketing), •••• 7718 Jonas Weber (Sales), •••• 5126 Tom Brandt (Operations), •••• 3390 Ines Okafor (Design). Caption: "Tallyo gives everyone / their *own* card,"
3. **4.5–5.4 s – Limits.** "Card limits · MONTHLY": copper sliders slide to Maya €1,200, Jonas €800, Ines €490, Tom €1,791 "per month". Caption: "sets a *limit* for each,"
4. **5.4–7.2 s – Receipts.** Maya's card above a "Transactions · 2 of 3 matched" list: Pixelbay (Design tools) €45.00 ✓ Matched, Nordair (Flight BER–ARN) €312.40 ✓ Matched, Café Lumen (Team lunch) €86.20 "Matching…"; little receipt thumbnails fly in and attach. Caption: "and matches every / *receipt* on its own."
5. **7.2–10.8 s – End card.** The guilloche ring draws around the logo; "Spending under *control.*"; "TALLYO.COM" between thin rules.

## 4. Rules
Luxurious, slow motion; cards have subtle metallic reflections; sliders ease.

## 5. Sound
Low cello/piano bed, card "flick" sounds, slider ticks, receipt paper whoosh, soft chime.

## 6. Make it yours
Swap people, limits and merchants.

---

# Tandem – 14.4-second product film for staff shift scheduling, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A friendly 2.5D product film (1920×1080, 30 fps) for **Tandem**, an invented shift-scheduling app: it builds a schedule in seconds, lets the team swap shifts and keeps hours on budget. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: soft lilac-pink #EFE6F2 with a gentle gradient.
- Shift chips: pastel colour per person — Mia coral #F28B82, Ben blue #8AB6F2, Ida green #8ED1A0, Tom yellow #F2D06B.
- Accent: magenta-pink #E0247A for highlights (pink marker highlight behind key words), donut chart and buttons.
- Type: grotesk (Inter Bold) in deep navy #1E1B3A.
- Logo: magenta "T" glyph + "Tandem" in navy.

## 2. Voiceover (warm manager)
"Who's working Saturday? Nobody knows. Tandem builds a schedule in seconds, lets your team swap shifts, and keeps hours on budget. Tandem. Shifts that sort themselves."

## 3. Scenes
1. **0.0–2.4 s – Who?** A calendar tile "SAT ?" with chat bubbles from avatars: M "Who's in on Saturday?", B "Not me, sorry!", I "I thought Tom was?", T "Wait, what?". Caption: "Who's working **Saturday?**"
2. **2.4–3.8 s – Nobody knows.** An empty "Week 42 · Café Lumen · 4 people" grid (Mon–Sun × Mia, Ben, Ida, Tom); the Saturday column fills with pink "?" boxes; button "Auto-schedule". Caption: "**Nobody knows.**"
3. **3.8–6.0 s – Build.** "Building…" chip; shifts drop into the grid in colour: Mia 9–5, Ben 5–11, Ida 12–8, Tom 9–5 etc., each with a role (Bar, Floor, Kitchen). Caption: "Tandem builds a schedule / in **seconds,**"
4. **6.0–8.4 s – Swap.** Two shift cards for Mia "Sat 9–5 · Bar" and Ben "Sun 12–8 · Floor" swap places with a pink "Swapped" chip. Caption: "lets your team / **swap shifts,**"
5. **8.4–10.8 s – Budget.** A pink donut "69% → 92% of this week's budget"; rows "Hours planned 121 → 148 / 160 h · Labour cost $2,439 → $4,120 · Overtime 0 h"; pill "On budget ✓". Caption: "and keeps hours / **on budget.**"
6. **10.8–14.4 s – End card.** Logo; "Shifts that **sort themselves.**"; floating pastel shift chips drift around; navy pill "tandem.team".

## 4. Rules
Soft springs, grid cells pop; gentle camera tilt on the schedule.

## 5. Sound
Light bouncy pop beat, chat pops, card shuffles on swap, a check chime on budget.

## 6. Make it yours
Swap venue, names, hours, budget.

---

# Tidy Ledger – 10-second talking head ad for a freelance bookkeeper, 9:16

> Recreated from the public example video. Film your own clip talking to camera, then paste this prompt with it into Claude to add the motion design.

## 0. What you are building
A vertical (1080×1920) talking head ad for **Tidy Ledger**, a bookkeeper who handles receipts, invoices and taxes. A woman in a cream cable-knit sweater sits in a bright home office (shelves, plants, coffee cups) and speaks to camera. Claude adds flying paper receipts, a green folder, stacked green cards, a "Filed." cutaway, a big clock and an incoming-call CTA. Build overlays in code (Remotion).

## 1. Look
- Brand: fresh green #1FA45A → teal #2A9D8F gradient cards, white, charcoal text.
- Receipts: white thermal-paper receipts with zigzag edges in monospace ("CAFE LUNA", "OFFICE PLUS", "FUEL 24", "HARDWARE", "TRAIN", "POST").
- Type: dark/white sans (Inter Medium); key words in big green serif italic (Playfair Display Italic).

## 2. Script
"Still doing your own books? I'm Emma. I take care of your receipts, invoices and taxes, so you get your evenings back. Book your free call today."

## 3. Scenes
1. **0.0–1.6 s – Receipts.** Paper receipts slide in and pile up at the bottom of the frame. Caption: "Still doing / your" (own books?).
2. **1.6–2.5 s – Folder.** A green folder pops up and the receipts get sucked into it; chip "Sorted". Caption: "I'm *bookkeeper*…" (her name/role in green serif).
3. **2.5–5.6 s – Cards.** Green cards stack up from the bottom: "Receipts · sorted · 128 matched to your bank", "Invoices · sent · 12 paid on time", "and taxes · 2026". Caption: "I take care of your".
4. **5.6–6.6 s – Filed.** Full green cutaway: a white document "Tax return 2026 · Prepared by Tidy Ledger" gets a green stamp; "*Filed.*"
5. **6.6–8.2 s – Evenings.** A huge green clock "6:00" with "Friday, October 23" behind her head. Caption: "so you get your / *evenings* / back."
6. **8.2–10.0 s – Call.** An iOS incoming-call banner "TL Tidy Ledger · tidyledger.co · free call" with red/green buttons. Caption: "Book your / *free call* / today."

## 4. Rules
Captions word-synced; paper physics for receipts; keep her face clear.

## 5. Sound
Original voice, light acoustic bed, paper rustle, folder "whoomp", stamp, phone ring.

## 6. Make it yours
Swap name, numbers, URL; use your own clip.

---

# Tippa – 10.1-second product film for cashless restaurant tipping, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A warm, upscale vertical product film (1080×1920, 30 fps) for **Tippa**, an invented tipping app for restaurants: a QR code on every table lets guests tip by phone, and tips are split fairly at the end of the night. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: deep burgundy/wine #3A1420 with a soft warm glow and faint coin-edge ring patterns.
- Accent: gold #E0B44A (coins, rings, key words in gold italic).
- Paper receipt: cream #F2EAD8 with monospace text.
- Type: elegant serif (Newsreader / Lora) in cream; key words gold italic.
- Logo: a gold coin with a dash + "Tippa" in cream serif.

## 2. Voiceover (restaurant owner)
"Nobody carries cash anymore, and your team feels it in their tips. Tippa puts a code on every table, and splits each tip fairly at the end of the night. Tippa. Tips, without cash."

## 3. Scenes
1. **0.0–3.3 s – No cash.** A receipt "LA TAVOLA · Table 7 · 22:41 · 2× Tagliatelle 32.00 · Chianti, glass 16.00 · TOTAL €48.00 · TIP ____" gets a stamp "PAID BY CARD"; a card terminal shows "€48.00 ✓ Approved"; a gold coin ring below reads "CASH TIPS €0.00"; staff avatars M, J, L, S appear sadly. Caption: "Nobody carries / cash anymore, / and your team / feels it in their tips."
2. **3.3–5.0 s – Code.** A table tent "Tip the team · SCAN · TABLE 7 · powered by Tippa" whose QR code assembles pixel by pixel with gold corner brackets. Caption: "Tippa puts a code / on *every table,*"
3. **5.0–6.7 s – Tip.** A phone: "Tippa · Table 7 ✓ · Tip the team · LA TAVOLA · €48.00 PAID", gold ring "TONIGHT €179.00 → €184.00 team pot", chips €3 / **€5** / €10, "Pay €5". Caption: "and splits each tip / *fairly*".
4. **6.7–7.6 s – Split.** Phone shows "TONIGHT €184.00 · split by hours · 23:00 Night closed": Mara 6 h €55.20, Jonas 6 h €55.20, Lea 4 h €36.80, Sam 4 h €36.80. Caption: "at the end / of the night."
5. **7.6–10.1 s – End card.** Gold coin spins into the logo; "*Tips,* without cash."; "TIPPA.APP"; the staff avatars become gold coins one by one.

## 4. Rules
Slow, warm, cinematic; coins have metallic shine; QR builds pixel by pixel.

## 5. Sound
Restaurant ambience, soft jazz piano, card-terminal beep, coin clinks, a warm chime.

## 6. Make it yours
Swap restaurant, staff, amounts.

---

# Titlo – 9.5-second product film for AI video captions, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A bold, high-contrast product film, square (1080×1080, 30 fps), for **Titlo**, an invented captioning tool: it hears every word, sets captions in your style and translates them into 30 languages. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: near-black #0E0E0E with faint technical labels and a fine grid.
- Accent: highlighter yellow #F2F23A — key words get a yellow box behind black text.
- Phone mockup: grey-scale flat illustration of a person in a beanie (video "@maya.films"), waveform at the bottom.
- Type: heavy grotesk (Inter Black / Archivo Black) in white; labels in monospace.
- Logo: "Titlo" in black on a yellow rounded rectangle.

## 2. Voiceover (punchy)
"Most people watch your video with the sound off. Titlo hears every word, sets captions in your style, and translates them into thirty languages. Titlo. Words that keep them watching."

## 3. Scenes
1. **0.0–2.4 s – Sound off.** A phone with a video and a waveform; a dashed "NO CAPTIONS" box; a mute icon appears over the face and the waveform flattens. Caption: "Most people / watch your [video] / with the [sound] / [off.]"
2. **2.4–3.2 s – Hears.** A "TRANSCRIPT · EN · auto" panel with timecodes: 00:03.12 Nobody, 00:03.46 tells, 00:03.71 you…; on the phone "Nobody tells" appears; the waveform turns yellow "LISTENING". Caption: "Titlo [hears] every word,"
3. **3.2–4.7 s – Style.** A big caption "Nobody tells / you this." cycles through three styles in a "STYLE · 2/3 · PAPER" picker: Clean, Paper (selected ✓), Brand Kit (yellow highlight). Caption: "[sets] captions / in [your] style,"
4. **4.7–6.7 s – Translate.** A "LANGUAGES 00 → 28 / 30" grid of chips (EN, ES, DE, FR, IT, PT, NL, SV, PL, DA, FI, CS, HU, RO, EL, TR, UK, AR, HE, JA, ZH, KO…) lighting yellow; the caption morphs: "Nobody tells you [this.]" → "Das sagt dir [keiner.]" → "[誰も]教えてくれないこと。". Caption: "and [translates] / them into [thirty] languages."
5. **6.7–9.5 s – End card.** Logo; "Words [that] keep / them [watching.]"; a timeline scrubber with a yellow waveform "00:00:00:00 → 00:00:01:02"; "titlo.app".

## 4. Rules
Snappy cuts between panels; highlight boxes wipe in left-to-right; very readable.

## 5. Sound
Muted start (just a ticking clock), then a punchy beat kicks in with the captions, typewriter-like clicks for words, a shimmer per language.

## 6. Make it yours
Swap the sample sentence, languages and handle.

---

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

---

# Tonic – 15-second cinematic product film for a music-streaming app (no voiceover), 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film. This one has no voiceover: the story is told by on-screen text over moody scenery and music.

## 0. What you are building
A cinematic, mood-driven film (1920×1080, 30 fps) for **Tonic**, an invented music app. Glassy player UI cards float over atmospheric photographic backdrops: a coastal road at sunset, a rainy neon city at night, a sunny green hill. Captions appear in thin white type, typed word by word. Build in code (Remotion/React) with AI-generated or stock-style backdrop images, and render to MP4.

## 1. Look
- Backdrops: (1) cliffside coastal road at golden hour; (2) rainy neon city street at night, wet reflections; (3) green meadow under a blue sky with clouds. Slow push-ins, slight blur behind UI.
- UI: frosted-glass dark cards (#1A1A1A at 60%, blur 30 px), white text, coral-red accent #E8463A for progress and highlights.
- Type: light/regular grotesk (Inter Light) in white; one key word per line in coral.
- Logo: coral equaliser bars + "Tonic" in white on black.

## 2. On-screen text (no voiceover; music carries it)
"press play" → "we drive until the sky turns" → "a soundtrack for late night" → "every song you love" → "playlists that build themselves" → "Tonic · All your music. One tap."

## 3. Scenes
1. **0.0–3.7 s – Press play.** Coastal road at sunset. A small glass pill player in the centre; a cursor presses ▶; caption "press **play**"; the pill expands to "Coast Road · Mara Vale" with an equaliser.
2. **3.7–6.2 s – The drive.** Background blurs; a glass "now playing" card (album art of the road, "Coast Road · Mara Vale", red progress 1:21 / 3:48). Caption: "we drive until the sky turns".
3. **6.2–7.5 s – Late night.** Hard cut to the rainy neon street. A vertical list of moods scrolls: Rainy, Road trip, **Late night**, Sunday morning, Workout; "Late night" locks in with "Neon Rain" playing. Caption: "a soundtrack for".
4. **7.5–10.0 s – Every song.** A stack of album covers fans out, then two rows of colourful album covers stream across the screen (abstract art, a yellow ball, vinyl, forest, a vintage car, a sunset, a silhouette, pool water, gradients). Caption: "every song you love".
5. **10.0–12.5 s – Playlists.** The green meadow. A glass "Made for you · ▶ Play all" playlist fills: Paper Sun, Poolside, Red Line, Soft Orbit, Fog Season, Checkmate, Lemon…; counter "5 songs · 19 min → 24 songs · 92 min". Caption: "playlists that / build **themselves**".
6. **12.5–15.0 s – End card.** Black screen; coral equaliser icon + "Tonic"; "All your music. One tap."

## 4. Rules
Cinematic pacing; slow parallax; UI cards with real glass blur; text fades and types gently.

## 5. Sound
A licensed or original lo-fi/indie track that shifts mood with each scene: sunset guitar → rainy synthwave → bright acoustic; rain and car ambience under the scenes.

## 6. Make it yours
Swap song titles, artists, moods and backdrops.

---

# Trim – 11.3-second product film for subscription management, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A crisp 2.5D product film (1920×1080, 30 fps) for **Trim**, an invented app that finds every subscription, cancels the forgotten ones in one tap and shows what you saved. A long paper bank statement carries the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: deep bottle green #123A2B with soft vignette.
- Statement: cream receipt paper #F2EBDD hanging from a black bar, monospace lines.
- Accent: apricot orange #F5A54A for highlights, buttons and key words (italic).
- Type: geometric sans (Futura / Jost Medium) in cream; key words apricot italic.
- Logo: cream rounded square with a green "T" + "Trim" in cream.

## 2. Voiceover (friendly, smart)
"Paying for things you never use? Trim finds every subscription, cancels the forgotten ones in one tap, and shows what you saved. Trim. Keep what you love."

## 3. Scenes
1. **0.0–1.9 s – Subscriptions.** Little cream tags float: STREAMFLIX 12.99, GYMPASS 39.00, CLOUDBOX 9.99, NEWSLY 7.50, MUSICO 10.99, FONTLAB PRO 9.99, PHOTOSTASH 2.99, VPN SHIELD 11.95 (monthly). Caption: "Paying for things you never use?"
2. **1.9–4.7 s – Statement.** A statement "STATEMENT · CARD •••• 4821 · RECURRING · SEP 2026" prints down; each line gets a usage tag: Watched yesterday, Last visit: 8 months ago (orange), Used today, Never opened (orange), Played today, Unused for 14 months (orange), Used this week, Always on; total "$105.40"; chip "8 subscriptions · 3 forgotten". Caption: "Trim finds every *subscription,*"
3. **4.7–6.6 s – Cancel.** The three forgotten lines (GYMPASS, NEWSLY, FONTLAB PRO) pop out in orange; an orange button "Cancel 3 forgotten" is tapped. Caption: "cancels the *forgotten* ones / in one tap,"
4. **6.6–8.5 s – Saved.** The three tags get struck through; a big counter "$17.90 → $56.49 saved every month · That's $677.88 a year"; two bars "BEFORE $105.40" vs "NOW $48.91". Caption: "and shows / what you *save.*"
5. **8.5–11.3 s – End card.** Logo; "Keep what you *love.*"; the kept subscriptions float around as chips with a heart (STREAMFLIX ♥, MUSICO ♥, CLOUDBOX ♥, PHOTOSTASH ♥); orange pill "trim.money".

## 4. Rules
Paper physics on the statement; snappy strike-throughs; number ticker.

## 5. Sound
Upbeat minimal beat, receipt printer, highlighter swipes, a "cha-ching" on savings.

## 6. Make it yours
Swap services, prices and savings.

---

# Vantro – 12-second product film for van fleet maintenance, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A rugged, graphic 2.5D product film (1920×1080, 30 fps) for **Vantro**, an invented fleet tool: it tracks every mile, books the workshop ahead of time and shows what each van really costs. Top-down white vans on a dark road carry the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: asphalt charcoal #2A2A2A with white lane lines.
- Vans: small top-down white vans with number plates 01–12.
- Accent: high-vis yellow #F5D000 for alerts, highlights and key words.
- Type: condensed bold caps (Barlow Condensed SemiBold / Oswald) in white; key words yellow. Mechanical odometer digits for mileage.
- Logo: yellow "V" check-mark + "VANTRO" in white condensed caps.

## 2. Voiceover (no-nonsense fleet manager)
"Twelve vans on the road, and nobody knows which one is due for service. Vantro tracks every mile, books the workshop ahead of time, and shows what each van really costs. Vantro. Keep the fleet moving."

## 3. Scenes
1. **0.0–3.0 s – Fleet.** Twelve vans drive in lanes; a "FLEET STATUS" chip "On the road 7 → 12 · Service due ?". Then all vans grey out except 07, which gets yellow corner brackets and a tag "⚠ SERVICE DUE"; "Service due 1". Caption: "TWELVE VANS ON THE ROAD. / NOBODY KNOWS WHICH ONE / IS **DUE FOR SERVICE.**"
2. **3.0–5.0 s – Mileage.** A card "V-07 · Transit": a rolling odometer "048,21x mi", "NEXT SERVICE 48,240 mi", a fuel gauge, "23 days". A curved road timeline with mile ticks, a marker "SERVICE DUE" and van 07 driving toward a wrench icon. Caption: "VANTRO **TRACKS** EVERY MILE,"
3. **5.0–7.0 s – Workshop.** A "Workshop · North Depot · Week 42" calendar: slots V-02 Tires, V-12 Inspection, V-06 Oil change, **V-07 Oil + brakes** (yellow, booked ✓), V-09 Brake pads, V-11 Tires; chips "$240" and "4 DAYS EARLY"; badge "✓ BOOKED · THU 08:00". Caption: "BOOKS THE WORKSHOP **AHEAD OF TIME.**"
4. **7.0–9.0 s – Cost.** "Cost per mile · October · ■ FUEL ■ SERVICE": V-03 $0.35, V-12 $0.38, **V-07 $0.52** (highlighted), V-05 $0.36, V-09 $0.34; "FLEET AVERAGE $0.39". Caption: "AND SHOWS WHAT EACH VAN / **REALLY COSTS.**"
5. **9.0–12.0 s – End card.** Logo; "KEEP THE FLEET **MOVING.**"; a row of 12 tiny vans; "● 11 → 12 / 12 VANS ON SCHEDULE"; "vantro.app".

## 4. Rules
Top-down camera with smooth tracking; odometer digits roll mechanically; alerts pulse.

## 5. Sound
Engine hum and road noise, odometer clicks, a warning beep, a wrench "clink", driving rock beat.

## 6. Make it yours
Swap fleet size, van IDs, costs.

---

# Verdo – 10-second product film for a plant-care app, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A soft, illustrated vertical product film (1080×1920, 30 fps) for **Verdo**, an invented plant-care app: it identifies a plant from a photo and reminds you when to water, feed and move it. A potted plant on a windowsill carries the story. Build in code (Remotion/React) with flat vector illustrations, and render to MP4.

## 1. Look
- Background: pale sage-mint #E2EDE6 window with white glazing bars and soft sunlight streaks.
- Plants: flat vector, terracotta pots #C9573E; healthy leaves deep green #2F7A4A, wilting leaves olive #A8A65A.
- Tools below on a rail: watering can, trowel, fork, spray bottle (pale outlines).
- Accent: terracotta red for key words (italic) and reminder icons.
- Type: elegant serif (Newsreader / DM Serif Display) in deep green #1E4A33; key words terracotta italic.
- Logo: a sprouting pot icon + "Verdo" in big deep-green serif.

## 2. Voiceover (gentle, a little wry)
"Another plant, another slow goodbye on the windowsill. Verdo identifies it from a photo, and reminds you when to water, feed and move it. Verdo. Keep them alive."

## 3. Scenes
1. **0.0–3.2 s – Wilting.** Three pots on the sill (small "Basil" and "Fern" tags); the big plant droops as a calendar card flips "DAY 3 → 9 → 15 → 19 · WITHOUT WATER", torn pages falling. Leaves fade from green to olive. Caption: "Another plant, / another slow *goodbye* / on the windowsill."
2. **3.2–5.0 s – Identify.** Green camera corner brackets frame the plant; a card "● IDENTIFIED FROM 1 PHOTO · Flamingo flower · *Anthurium andraeanum* · 96% MATCH" with chips "☀ Bright shade · 💧 Water weekly · Feed monthly"; a tag "Flamingo flower" hangs on the pot. Caption: "Verdo identifies it / from a photo,"
3. **5.0–7.5 s – Reminders.** A dotted arc around the plant with three terracotta icons: WATER (drop), FEED (bottle), LIGHT (sun). Notifications pop: "💧 Water today · 250 ml · every 7 days", then "☀ Move to the light · East window · bright shade". A water drop falls; the plant perks up and turns green. Caption: "and reminds you when to / *water, feed* and *move* it."
4. **7.5–10.0 s – End card.** A healthy sprout in a pot above "Verdo"; "Keep them *alive.*"; three small healthy pots; "214 → 347 days · 0 goodbyes"; "VERDO APP".

## 4. Rules
Organic, springy leaf motion; slow light shift from cool to warm as the plant recovers.

## 5. Sound
Soft acoustic guitar, a sad little "droop" sound, camera shutter, water drip, a bright chime as it revives.

## 6. Make it yours
Swap plant species, reminders and counts.

---

# Vocado – 10.2-second product film for a conversation-practice language app, 9:16

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A bright vertical product film (1080×1920, 30 fps) for **Vocado**, an invented language app: you practise real conversations with an AI partner and it corrects you gently as you speak. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: butter yellow #F7EBB0 with huge faint letterforms (¿, ñ, é, ¡) in a slightly darker yellow, and a grid of yellow squares (like a streak calendar).
- Accent: cobalt blue #2C3FD8 for chat bubbles, highlighted words, accents and mic UI.
- Cards: white with soft shadows; flashcards stacked with year tabs.
- Type: grotesk (Inter Bold) in navy #1C1F3A; key words cobalt with an accent mark on top ("fréeze", "réal", "géntly", "sóoner").
- Logo: "Vocado" in heavy navy with a cobalt accent stroke above the "a".

## 2. Voiceover (friendly learner)
"You studied Spanish for years, and still freeze when someone talks to you. Vocado lets you practise real conversations, and corrects you gently as you speak. Vocado. Speak sooner."

## 3. Scenes
1. **0.0–1.7 s – Years of study.** A flashcard stack with tabs 2022, 2023, 2024, 2025: "Spanish · B1 · Card 2,140 · **hablar** · to speak · hablo / hablas / habla ✓". Stats: LESSONS 543 → 624, WORDS 1,864 → 2,140, CONVERSATIONS 0 (dashed). Caption: "You studied / Spanish for years,"
2. **1.7–3.4 s – Freeze.** A dark speech bubble "M Marta · at a café in Madrid 🇪🇸 · ¡Hola! ¿Qué tal todo?", then "¿Me entiendes?"; your reply bubble is just "• • •" with a chip "⏸ Silence 0:05". Caption: "and still **fréeze** / when someone talks to you."
3. **3.4–5.9 s – Practice.** A chat card "Lucía · AI partner · Café in Madrid · ● 02:16": "¡Hola! ¿Qué te pongo? (Hi! What can I get you?)"; your bubble fills as you speak: "Un café con leche, por favor." with "✓ Sounds natural"; "¡Claro! ¿Algo más?". A mic bar "LISTENING" with waveform and a "PRONUNCIATION 0 → 50 → 94" ring; scenario chips "At the café · Job interview · In a taxi · First date". Caption: "Vocado lets you / practise **réal** conversations,"
4. **5.9–7.6 s – Correction.** A "You · speaking" card: "Ayer **hablo** con mi jefa" with a squiggly underline → corrected to "Ayer **hablé** con mi jefa y le dije que…"; chip "✎ hablé · ayer → past tense". Caption: "and corrects you **géntly** / as you speak."
5. **7.6–10.2 s – End card.** Logo; "Speak **sóoner.**"; a greeting bubble cycles "🇪🇸 ¡Hola!" → "🇫🇷 Bonjour!" → "🇩🇪 Hallo!"; a waveform at the bottom; "VOCADO.APP".

## 4. Rules
Bouncy chat bubbles, typing effect for speech, accents drop onto letters with a little bounce.

## 5. Sound
Café ambience, light Latin guitar, chat pops, a soft "ding" for corrections, cheerful resolve.

## 6. Make it yours
Swap language, phrases and scenarios.

---

# Votely – 10.3-second product film for board meetings and voting, 1:1

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A stately, boardroom-styled 2.5D product film, square (1080×1080, 30 fps), for **Votely**, an invented meeting tool: it runs the agenda, counts each vote live and has the signed minutes ready when you leave the room. An oval boardroom table seen from above carries the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: deep burgundy/oxblood #4A1428 with a soft vignette.
- Table: dark oval with a thin gold rim; members as circles with initials (L, O, P, J, A, S, E, T) and cream name cards (Lena, Omar, Priya, Jonas, Aiko, Samir, Elia, Theo).
- Accent: antique gold #D9B25A for key words (italic), "Yes" vote cards and the seal.
- Paper: cream minutes document #F2EAD8.
- Type: classic serif (Newsreader / Libre Caslon) in cream; key words gold italic.
- Logo: gold oval seal with a check and dots (like a table with seats) + "Votely" in cream serif.

## 2. Voiceover (measured chairperson)
"The meeting ends, and the minutes take another week. Votely runs the agenda, counts each vote live, and has the signed minutes ready when you leave the room. Votely. Decisions on record."

## 3. Scenes
1. **0.0–2.5 s – Slow minutes.** Members around the table; in the centre a "MINUTES · DRAFT · Meeting ended 16:00" card with empty boxes and a counter "+0 days → +7 days"; members fade out one by one. Caption: "The meeting ends, / and the minutes / take another *week.*"
2. **2.5–4.2 s – Agenda.** The centre card becomes a dark "AGENDA · 14 OCT · Item 4 of 5": ✓ Previous minutes, ✓ Q3 report, ✓ Hiring plan, ▸ 2027 budget (highlighted, "VOTING NOW"), Any other business. Caption: "Votely runs / the *agenda,*"
3. **4.2–5.1 s – Live votes.** Each member flips a cream vote card; "Yes" cards turn gold; the budget row counts "2 → 6 yes · 0 → 2 no" with a gold bar; a dial in the centre. Caption: "counts each / vote live,"
4. **5.1–7.7 s – Signed minutes.** A "CARRIED 6–2" stamp lands on the agenda; a cream "Minutes · Board meeting · 14 Oct 2026 · 5 of 5 approved" sheet slides up: Previous minutes approved 16:02, Q3 report received 15:31, Hiring plan approved 15:44, "Resolution 4 · 2027 budget approved" with a mini of the vote card; a signature writes on. Caption: "and has the *signed* / minutes ready when / you leave the room."
5. **7.7–10.3 s – End card.** The seal draws; "Votely"; "Decisions on *record.*"; eight dots filling "3 → 7 of 8 votes on record"; "VOTELY.APP" between gold rules.

## 4. Rules
Slow, dignified camera; cards flip with weight; gold glints.

## 5. Sound
Chamber strings/piano, paper shuffles, card flips, gavel tap on "CARRIED", pen flourish.

## 6. Make it yours
Swap members, agenda items and result.

---

# Wattlo – 11.3-second product film for EV charger monitoring, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
An electric, dark-teal 2.5D product film (1920×1080, 30 fps) for **Wattlo**, an invented platform for EV charging operators: it watches every station, restarts it remotely and shows which locations really earn money. A row of charging pillars carries the story. Build in code (Remotion/React) and render to MP4.

## 1. Look
- Background: deep teal #0C2E35 with a soft glow and floor reflection.
- Chargers: dark teal pillars with round displays showing kW (22, 50, 11, 150) and lime rings, labelled "Bay 01–06" with big numbers 01–06.
- Accent: electric lime #C6F23A (online, key words underlined); offline grey with a dashed ring.
- Type: rounded techno sans (Exo 2 Bold / Rajdhani) in white; key words lime with an underline.
- Logo: lime ring with a plug cable sweeping under "Wattlo" in white.

## 2. Voiceover (calm operator)
"A charger goes offline, and you only hear about it from an angry driver. Wattlo watches every station, restarts it remotely, and shows which locations really earn money. Wattlo. Chargers that stay online."

## 3. Scenes
1. **0.0–2.8 s – Offline.** Six pillars "CHARGING" with lime rings; Bay 04 flips to a dashed grey "OFF · OFFLINE · 2 h 08 m → 2 h 14 m". A review bubble: "Dana K. ★☆☆☆☆ · Bay 04 · 'Charger's dead. Again.'" Caption: "A charger goes offline, / and you only hear about it / from an angry driver."
2. **2.8–4.7 s – Watches.** A dashboard "Wattlo · Stations · Sessions · Revenue · ● 23 / 24 online · 23:41": rows Harbor Garage, Mill St. Lot, Airport P2, Old Depot, each with six charger rings; a lime scan line sweeps; one ring has a "!" alert. Caption: "Wattlo watches every station,"
3. **4.7–6.6 s – Restart.** Side panel "Mill St. Lot · Bay 04 · OFFLINE · OFF no link · Detected in 4 s · Drivers affected 0"; a lime "↻ Restart remotely" button is clicked; the ring powers back up to "22 kW · ONLINE", "✓ Back online in 9 s"; "24 / 24 online". Caption: "restarts it **remotely,**"
4. **6.6–8.5 s – Revenue.** "Revenue by location · this month": Harbor Garage $4,442 → $4,820 (TOP EARNER), Mill St. Lot $2,533 → $3,140, Airport P2 $774 → $1,260, Old Depot $100 → $310; "TOTAL THIS MONTH $7,849 → $9,530". Caption: "and shows which locations / really **earn** money."
5. **8.5–11.3 s – End card.** Logo; "Chargers that stay **online.**"; a strip "●●●●●● 24 / 24 online · 1,285.0 → 1,286.9 kWh delivered today"; "WATTLO.IO".

## 4. Rules
Glowing rings pulse with charge; smooth parallax on the pillars; UI slides in with depth.

## 5. Sound
Electric hum, a power-down "whine" for the offline charger, a restart "boot" sound, a synth pulse groove.

## 6. Make it yours
Swap locations, kW, revenue.

---

# Willow Creek Farm – 10-second talking head ad for a family farm with weekend visits, 9:16

> Recreated from the public example video. Film your own selfie clip on the farm, then paste this prompt with it into Claude to add the motion design.

## 0. What you are building
A vertical (1080×1920) talking head ad for **Willow Creek Farm**, a farm open to visitors on weekends. A woman with silver-blonde hair in a quilted green gilet films herself at golden hour in front of a paddock, horses and a stable. Claude adds kinetic captions, a name tag cursor, a weekend calendar, photo cards (riding lesson, pony ride, fresh eggs) and a booking-link button. Build overlays in code (Remotion).

## 1. Look
- Brand: warm golden yellow #F2B21B, cream #FBF5E6, white; soft golden-hour glow.
- Type: white sans (Inter Medium) + gold serif italic (Playfair Display Bold Italic) for the farm name and "visit"; a gold selection box with corner handles around "Willow Creek".

## 2. Script
"Hi, I'm Claire from Willow Creek Farm. Every weekend we open our gates. Riding lessons, pony rides, fresh eggs. Come say hello — book your visit online."

## 3. Scenes
1. **0.0–2.5 s – Intro.** Big white "Hi," then "I'm" with a cursor and a gold name tag "Claire"; "from" + "*Willow Creek*" in gold serif inside a selection box with handles.
2. **2.5–4.2 s – Weekends.** Caption "Every weekend / we open"; a white calendar card "OCTOBER 2026 · M T W T F S S · 13 14 15 16 17 **18 19**" with Saturday and Sunday circled gold.
3. **4.2–6.6 s – Activities.** A vertical wipe reveals a cream panel with photo cards stacking: a rider on a chestnut horse in an arena ("Riding lessons"), a child on a white pony at sunset ("Pony rides"), hands holding a wire basket of brown eggs ("Fresh eggs"); the calendar stays at the bottom.
4. **6.6–7.4 s – Come.** Back on her; a gold pill "Come" (say hello) with little gold squares.
5. **7.4–10.0 s – Book.** "book your / ***visit***" (gold serif with glow) and a white URL pill typing "willowcreek.farm" that turns gold with a check when clicked.

## 4. Rules
Captions word-synced; warm, friendly springs; keep her face clear.

## 5. Sound
Original voice, gentle acoustic folk guitar, birdsong, a horse whinny, clucking hens on the eggs card, click on the link.

## 6. Make it yours
Swap farm, name, activities, dates, URL; use your own clip.

---

# Yieldo – 11.2-second product film for satellite crop monitoring, 16:9

> Recreated from the public example video. Paste into Claude and ask it to build and render the film.

## 0. What you are building
A warm, agricultural 2.5D product film (1920×1080, 30 fps) for **Yieldo**, an invented farm tool: it reads satellite images each morning, shows which field is ready and plans the harvest around the weather. A patchwork of wheat fields in perspective, each with a ripeness percentage pin, carries the story. Build in code (Remotion + Three.js or a tilted 2D grid) and render to MP4.

## 1. Look
- Fields: patchwork of wheat/straw tones #E8D8A8 → #C99A3A with crop-row stripes; seen from a low aerial angle with haze.
- Pins: white flag labels with ripeness % (or "?").
- UI: dark espresso panels #2A2018. Accent: farm green #2E9E48 for "ready" and key words (with underline).
- Type: chunky slab serif (Roboto Slab Bold) in espresso; key words green.
- Logo: green tilted square with a white "Y" + "Yieldo" in espresso slab serif.

## 2. Voiceover (calm farmer)
"Every field ripens at its own pace, and you can't walk them all. Yieldo reads satellite images each morning, shows which field is ready, and plans the harvest around the weather. Yieldo. Harvest at the right moment."

## 3. Scenes
1. **0.0–2.8 s – Pace.** The field patchwork with pins changing: 77%, 43%, 71%, 81%, 52%, 61%, 74%, 44%, 59% → 63%, 49%, 73%, 87%… each field's colour deepens. Caption: "Every field ripens / at its own pace,"
2. **2.8–3.7 s – Can't walk them all.** Most pins turn to "?"; a dotted walking path crosses only a few fields; chip "3 of 18 WALKED". Caption: "and you can't / walk them **all.**"
3. **3.7–5.6 s – Satellite.** A green scan line sweeps across the fields from a satellite icon ("Morning pass · Mon 11 Aug · 06:12"); "?" pins resolve into %s; a dark side list "FIELDS · 18 MORNING": 07 North Ridge 96%, 12 Mill Lane 88%, 03 Low Meadow 81%, 15 Creek Side 74%, 09 Old Orchard 63%; "18 of 18 fields read". Caption: "Yieldo reads satellite images / **each morning,**"
4. **5.6–6.5 s – Ready.** North Ridge lifts with a green outline "96%"; dark card: ring "61% → 96%", "26.4 ha", "Moisture 5.6%". Caption: "shows which field is **ready,**"
5. **6.5–8.4 s – Weather.** A "Harvest plan · Week 33 · Aug 11–17" card: weather row MON 24° ☀, TUE 27° ☀ (BEST WINDOW), WED 26° ☀, THU 19° 🌧, FRI 18° 🌧, SAT 22° ⛅, SUN 25° ☀; North Ridge is slotted into Tue–Wed, Mill Lane and Low Meadow after; "209 t · 8.1 t/ha". Caption: "and plans the harvest / around the **weather.**"
6. **8.4–11.2 s – End card.** Logo; "Harvest at the **right moment.**"; a ripeness bell curve "TOO EARLY → TOO LATE" with a green "harvest window Tue 12 Aug – Wed 13" and a marker sliding "79% → 88% ripe"; "YIELDO.FARM".

## 4. Rules
Slow aerial drift over the fields; wheat stripes shimmer; numbers tick up.

## 5. Sound
Wind over wheat, larks, a soft satellite "ping", a gentle country guitar bed, a warm resolve.

## 6. Make it yours
Swap field names, percentages, weather and crop.

