# TinkerBeat

**Make beats in your browser.**

[Live Demo](https://tortured-metaphor.github.io/TinkerBeat)

## Controls

- **Play / Stop** — Toggle playback with the center button
- **BPM** — Adjust tempo from 60 to 200 BPM with the slider
- **Tap Tempo** — Tap the TAP button rhythmically to set BPM by feel
- **Swing** — Delay every other step for shuffle/groove feel (0–100%)
- **Grid** — Click any drum pad to toggle on/off; click bass pads to cycle through notes
- **Volume** — Per-row volume sliders on the right side of the grid
- **Step Count** — Toggle between 16 and 32 steps
- **Clear Row** — Double-click a row label to clear all pads in that row

## Voices

All sounds are synthesized in real-time using the Web Audio API — no samples or external files.

| Voice | Description |
|-------|-------------|
| KICK  | Sine oscillator with pitch sweep |
| SNARE | Triangle oscillator + filtered noise |
| HIHAT | Highpass-filtered noise burst |
| CLAP  | Double-trigger bandpass noise |
| BASS  | Sawtooth oscillator with lowpass filter and ADSR envelope |

## License

MIT
