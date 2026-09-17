# Jukebox audio assets — NEEDED

The on-site player ("The Jukebox") in `index.html` is seeded with a
placeholder playlist. It will stay silent until the real MP3s below are
placed in THIS folder (`audio/` next to `index.html`).

## Required files (exact filenames)

| # | File | Track |
|---|------|-------|
| 1 | `flash.mp3` | FLASH (pop single, 2025) |
| 2 | `the-barrel.mp3` | The Barrel (Markiplier × Schmoyoho collab, 2020) |
| 3 | `girl-named-nova-remix.mp3` | Until I See You Again (Girl Named Nova · Tokens Misplaced remix — remix contest winner) |
| 4 | `psychic.mp3` | Psychic (alternative pop single) |
| 5 | `violets-smile.mp3` | Violet's Smile (cinematic pop, 2022) |
| 6 | `zenith.mp3` | ZENITH (cinematic electronic single) |
| 7 | `blue-flowers.mp3` | Blue Flowers (from the *Blue Flowers* lo-fi EP, 2020) |
| 8 | `legato.mp3` | A Winding Valley (from the *Legato* orchestral album, 2026) |
| 9 | `beneath-the-moon.mp3` | Beneath the Moon (bossa nova / salsa single) |

## Notes

- Export as MP3 (320 kbps recommended). The player reads real durations
  from file metadata automatically; the `duration` strings in the
  playlist are placeholders and update themselves once files exist.
- Until the files are added, the player shows a graceful
  "Fresh from the studio soon" note instead of erroring.
- Keep filenames lowercase with hyphens exactly as listed — the playlist
  in `index.html` references them verbatim.
- To swap, add, or rename tracks, edit the `TRACKS` array at the top of
  the jukebox `<script>` block in `index.html` (clearly commented).
