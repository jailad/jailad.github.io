# Count & Play

A tiny, playful counting-and-shapes game for a 4-year-old — built for Arjun.

Tap each picture and count out loud as the numbers (and the musical notes!) climb,
find the shape, and find the colour. No timers, no pressure, no losing — right
answers earn a star and a happy tune, wrong answers just get a gentle
"try again."

**Live app:** https://jailad.github.io/count-and-play/

## How to play

- **🔢 Count It!** — tap every picture, one by one. The counter grows and each
  tap plays the next note up a musical scale (tap 1 = Do, tap 2 = Re …).
- **🔷 Shapes** — find the circle, square, triangle, star, heart, or diamond.
- **🎨 Colours** — find the red, blue, green, yellow, orange, or purple.
- **Levels** — Level 1 counts 1–5, Level 2 counts 1–10 (unlocks at 3 ⭐),
  Level 3 counts 1–20 (unlocks at 7 ⭐).
- **🔊 Sound on/off** — a big toggle at the top, for quiet play.

## Good to know

- One self-contained `index.html` — no build step, no dependencies, works
  fully offline once loaded. Great on a phone or an iPad browser; big tap
  targets throughout.
- Sounds are synthesized live with the Web Audio API — there are no audio
  files. On iPhone/iPad, sound starts with the first tap (as iOS requires).
- Stars and progress are **session-only**: nothing is recorded, stored, or
  sent anywhere. Reloading the page starts fresh.

## License

MIT — see `LICENSE`.
