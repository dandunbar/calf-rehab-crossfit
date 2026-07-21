# WOD Rehab — calf-rehab-crossfit

A tolerance-gated recovery tracker for a **grade-1 gastrocnemius strain**, built
for getting back to CrossFit and plyometric work rather than just "walking
without pain."

Progress is gated by tolerance, not by the calendar: you advance a stage only
once the checks for that stage are met.

## The five stages

1. **Protect** — settle the strain, restore pain-free walking and basic ankle motion.
2. **Load tolerance** — reintroduce progressive calf loading (isometrics into slow heel raises).
3. **Strength & squat depth** — build capacity through range, including full-depth squat positions.
4. **Plyometric & impact reintro** — hops, skips, jump rope, and controlled landings.
5. **Return to the WOD** — box jumps, double-unders, running, and full-intensity metcons.

## Live URL

https://dandunbar.github.io/calf-rehab-crossfit/

## Notes

- Self-contained static single page — one `index.html`, no build step, no
  dependencies, no server.
- Progress is stored in the browser via `localStorage`, so it is **per-device**
  and per-browser. Clearing site data wipes it; it does not sync between your
  phone and your laptop.
- Add to an iPhone home screen for an app-like launch (`apple-touch-icon.png`
  supplies the icon).

**Not medical advice.** Impact and explosive work carry the highest re-injury
risk; get a physio to clear you before the plyometric stages if you can.

## License

MIT — see [LICENSE](LICENSE).
