# Changelog

## v1.6 — first public release

- BPM estimation from local audio files (manual BPM input and tap-tempo
  correction included).
- Key detection with Camelot wheel numbers and relative major/minor hint.
- 8-beat grid visualization on a zoomable / pannable waveform.
- Practice mode: 0.5x / 0.75x / 1x pitch-preserving playback speed,
  A-B loop, current-8-beats loop.
- Fine alignment: manual BPM, tap tempo, millisecond offset, set downbeat,
  grid nudge ±10 ms.
- Metronome toggle.
- Export: beat grid CSV, waveform PNG, time-stretched audio as WAV or MP3
  (music only / music + metronome / click only, optional 4-beat count-in).
- 34-second demo audio support (the `demo.wav` file itself is kept outside this
  repository for now; pending license confirmation).
- Single-file, fully offline web app: no uploads, no telemetry.
