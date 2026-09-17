# Custom UI sound effects

Drop your own click sounds in this folder. The site checks for these files on every page:

| File | Plays on |
|---|---|
| `pop.mp3` (or `pop.wav`) | Buttons and call-to-action links |
| `tick.mp3` (or `tick.wav`) | Text links |
| `knock.mp3` (or `knock.wav`) | Toggles and the music-player controls |

How it works:

- MP3 is tried first, then WAV. Only add the files you want to replace.
- Any sound with no file falls back to the built-in synthesized tone, so nothing ever goes silent.
- Keep clips short. A tenth of a second or so is plenty for a UI click.
- They play quietly by design. To change the volume, edit the `s.volume = 0.4` line in the sound block near the bottom of each page.
- The speaker toggle in the navigation mutes these too, and the visitor's choice is remembered.
