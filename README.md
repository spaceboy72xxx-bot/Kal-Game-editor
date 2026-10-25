# MOBA ni Joy

Laro sa browser na JavaScript ang code (Three.js). Si **Joy** ang hero mo, at mga **skeleton** ang mga kawal. May kasamang editor kung gusto mong baguhin ang laro.

## Laruin
- `index.html` ang mismong laro. Buksan ito sa browser, o i-deploy sa GitHub Pages (tingnan sa baba).
- Joystick (kaliwa-baba) o tap sa lupa para maglakad.
- Mga skill: **⚡ Kidlat**, **★ Starfall**, **+ Heal**.
- Sirain ang mga tower, tapos ang Nexus ng Pula para manalo. Pindutin ang **Ulit** (kanan-taas) para magsimula ulit.
- Pinch (o scroll) para mag-zoom ng camera.

## Editor
Nasa `editor/index.html` ang **Mini Game Editor**. Piliin ang **+ Idagdag > Template: MOBA (Joy)** para makita at mabago ang script ng laro.
Sa Script tab, gamitin ang `Start()` at `Update(dt)`. Mga magagamit: `this`, `Input`, `Time`, `find()`, `Spawn()`, `Kill()`, `Pose()`, `UI`, `Cam`, `THREE`.
Baguhin ang `TYPES` sa taas ng script para sa HP, damage, at bilis.

## I-deploy sa GitHub Pages
1. Gumawa ng bagong repository sa GitHub.
2. I-upload ang lahat ng file at folder dito (`index.html`, `editor/`, `.nojekyll`, `README.md`).
3. Settings > Pages > Source: **Deploy from a branch** > Branch: `main`, folder `/ (root)` > Save.
4. Maghintay ng ilang minuto. Ang laro ay nasa link ng Pages mo, at ang editor ay nasa `/editor/`.

## Paalala
- Kailangan ng internet dahil kinukuha ang Three.js mula sa CDN.
- Naka-embed ang mga 3D model at texture ni Joy at ng skeleton. Auto-rig ang galaw nila (hula batay sa hugis), kaya hindi ito kasing-ayos ng totoong animation.
- Wala pang physics, gold, items, at multiplayer. AI lang ang kalaban.
