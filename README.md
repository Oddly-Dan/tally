# Voice Tally

Count out loud in your browser. Pick a start number, a target and a step, and Voice Tally speaks every number in between using the Web Speech API. It shows the count on an odometer as it goes.

## Use

Open `index.html` in a browser, or serve the folder with GitHub Pages. There is no build step and nothing to install. Fonts (Space Mono, IBM Plex Sans) are self-hosted in `fonts/`, so the page makes no third-party requests.

- **Start at / Count to / Step by:** whole numbers of any size (BigInt), so commas, spaces and underscores are ignored. The direction comes from start and target, so the sign of the step doesn't matter.
- **Pace (ms):** the gap after each number finishes being spoken.
- **Voice / Speed / Pitch:** these use the voices your browser and OS provide.

## Notes

- You need a browser with `speechSynthesis` support (current Chrome, Edge, Safari, Firefox).
- Browsers throttle background tabs. Keep the tab in the foreground for a steady pace.

## Licence

[GPL-3.0](LICENSE). The fonts in `fonts/` are under the SIL Open Font License 1.1 ([fonts/OFL.txt](fonts/OFL.txt)).
