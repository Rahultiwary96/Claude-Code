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
