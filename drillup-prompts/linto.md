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
