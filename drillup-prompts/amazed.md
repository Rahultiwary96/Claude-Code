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
