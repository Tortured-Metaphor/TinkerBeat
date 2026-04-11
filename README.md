# TinkerBeat

**Make beats in your browser.**

[Live Demo](https://tortured-metaphor.github.io/TinkerBeat)

## Features

- **16-step drum machine** with kick, snare, hi-hat, and clap — all synthesized from scratch via Web Audio API
- **Bass synth** row with note cycling (C3–C4), sawtooth oscillator through lowpass filter with ADSR envelope
- **Sample-accurate timing** using the Web Audio API clock with lookahead scheduling
- **Swing** control (0–100%) for shuffle feel
- **Tap tempo** and BPM slider (60–200)
- **16 or 32 step** modes
- **Pattern bank** — 8 slots (A–H) with auto-save, JSON export/import
- **Pattern chaining** — queue patterns for automatic playback sequencing
- **Effects** — filter (LP/HP), delay with feedback, reverb with generated impulse response
- **Waveform display** — real-time audio visualization via AnalyserNode
- **Keyboard mode** — play drums (A/S/D/F) and bass (Z–M) in real time
- **Live recording** — overdub keyboard and pad hits into the pattern during playback
- **Preset patterns** — Rock, Four on the Floor, Hip Hop, Bossa Nova
- **URL sharing** — encode a pattern as a link, no backend needed
- **Per-row volume** sliders and double-click to clear

## Controls

| Control | Action |
|---------|--------|
| Play / Stop | Toggle sequencer playback |
| REC | Arm recording — captures keyboard/pad hits during next loop |
| KEYS | Toggle keyboard mode for live playing |
| BPM | Adjust tempo with slider or TAP button |
| SWING | Delay every other step for groove |
| 16 / 32 | Toggle step count |
| BANK A–H | Switch between 8 pattern slots |
| CHAIN | Build a sequence of patterns for auto-switching |
| FX | Open effects panel (filter, delay, reverb) |
| PRESETS | Load built-in patterns |
| EXPORT / IMPORT | Save or load the full pattern bank as JSON |
| SHARE | Copy a URL containing the current pattern |

## Keyboard Mapping

**Drums:** A = kick, S = snare, D = hi-hat, F = clap

**Bass:** Z = C3, X = D3, C = E3, V = F3, B = G3, N = A3, M = B3, , = C4

## License

MIT
