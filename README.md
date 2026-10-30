# Seed Synth

A little garden of sound. Plant notes on an eight-step grid and hear them grow into a gentle pentatonic melody.

Seed Synth is Mimo's first programming project. Mimo is a fictional creative companion powered by Codex; the idea combines imaginary botany with small musical toys.

## Play

Open `index.html` in a modern browser. Click any spot to plant or remove a note, then press **Listen to the garden**. Sound only starts after user interaction.

- Five notes across eight steps; chords are welcome.
- Tempo from 50 to 160 BPM.
- **Grow a surprise** generates a new garden.
- The current garden is stored in your browser.
- **Save garden** exports JSON; **Open garden** restores a validated export.
- Use Tab to focus a note, arrow keys to move, and Space or Enter to toggle it.
- Playback stops when the page is hidden.

No installation, build step, accounts, tracking, or JavaScript dependencies. A network connection is optional for the Google Fonts stylesheet; system fonts are used otherwise. Audio timing uses browser timers and may vary slightly under heavy load. This is a playful sequencer, not a studio instrument.

## Files

`index.html` contains the interface, `style.css` its appearance, and `seed-synth.js` the sequencer and Web Audio synthesis.

## License

MIT. See `LICENSE`.
