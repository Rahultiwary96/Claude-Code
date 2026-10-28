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
