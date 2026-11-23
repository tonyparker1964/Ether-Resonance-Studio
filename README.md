# Ether Resonance Studio

A standalone browser app for keeping a local session journal across three independent systems:

- **Spooky2 + Scalar:** log GeneratorX, mode, preset, Scalar setup, duration, and notes.
- **Muse:** log headset, practice type, app, duration, and optional self-reported rating.
- **FlameInSound:** log mobile device, session name, any frequency shown, playback setup, duration, and notes.

## Use

Open `index.html` in a modern browser. The app works without a build step or external libraries. Session history is saved to that browser's local storage on that device. Use **Export CSV** for a spreadsheet or **Backup JSON** to move a journal to another device.

## Integration status

This version is a recorder and session journal. It does not control Spooky2 hardware, connect to Muse, read live EEG, control FlameInSound, or synchronize signals between devices. Spooky2 + Scalar, Muse, and FlameInSound sessions are kept as independent records.
