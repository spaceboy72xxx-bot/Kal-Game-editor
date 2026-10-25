# MOBA ni Joy

Laro sa browser na JavaScript ang code (Three.js). Si **Joy** ang hero mo, at mga **skeleton** ang mga kawal.

## Mga file
- `index.html`: ang mismong laro. May sariling loading screen at wala nang editor.
- `editor.html`: ang Mini Game Editor (opsyonal), para makita at mabago ang script ng laro.

## Laruin
- Hintaying matapos ang loading, tapos pindutin ang **Maglaro**.
- Joystick (kaliwa-baba) o tap sa lupa para maglakad.
- Mga skill: **Kidlat**, **Starfall**, **Heal**.
- Sirain ang mga tower, tapos ang Nexus ng Pula para manalo. Pindutin ang **Ulit** para magsimula ulit.

## I-deploy sa GitHub Pages
1. Gumawa ng bagong repository sa GitHub.
2. Add file > Upload files. I-upload ang `index.html`, `editor.html`, at `README.md`. Commit changes.
3. Settings > Pages > Source: **Deploy from a branch** > Branch: `main`, folder `/ (root)` > Save.
4. Maghintay ng ilang minuto. Ang laro ay nasa link ng Pages mo, at ang editor ay sa dulo ng link na `/editor.html`.

## Para i-upload ang sarili mong laro
1. Buksan ang editor at gawin ang laro. Ilagay ang pangalan ng laro sa kahon sa taas.
2. Pindutin ang **I-export ang Laro**. Makukuha mo ang `laro.html`: may loading screen, pangalan mo, at walang editor.
3. Palitan ang pangalan nito ng `index.html` at i-upload sa GitHub.
4. Hindi kasama sa export ang mga na-import na GLB. Pero pwede mong gamitin sa script ang `Spawn("joy")` at `Spawn("skeleton")`, na naka-embed na.

## Paalala
- Kailangan ng internet dahil kinukuha ang Three.js mula sa CDN.
- Naka-embed ang mga 3D model at texture. Auto-rig ang galaw nila (hula batay sa hugis).
- Wala pang physics, gold, items, at multiplayer.
