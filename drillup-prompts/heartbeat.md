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
