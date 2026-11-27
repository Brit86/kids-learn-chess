# Kids Learn Chess

A free, offline-capable chess game for young children — built for Charlie, age 6.
One self-contained `index.html`: no ads, no accounts, works in the browser on
iPhone/iPad, Android, Windows, and Amazon Fire (in the Silk browser).

Play it: https://brit86.github.io/kids-learn-chess/

## What it has

- Friendly lessons with Pip and friends — how each piece moves, the pawn race, and more
- Free play, and Play the Computer against Berry (Easy, Medium, Hard)
- Game Theory: the Scholar's Mate lesson — play the trick, learn why it is
  checkmate, then defend against it
- Stars and trophies, saved on the device

## Versioning

Releases use semantic versioning — `vMAJOR.MINOR.PATCH`:

- `MAJOR` — big reworks, or changes old saves cannot carry over
- `MINOR` — new features (a new lesson, a new mode)
- `PATCH` — bug fixes

Dev builds carry the next version with a `-dev` suffix (for example `v1.2.0-dev`)
and are tested first on the dev site before promotion:
https://brit86.github.io/kids-learn-chess-dev/

## Release notes

### v1.1.0 — 27 November 2026

- Game Theory section: Lesson 1, Scholar's Mate — play the four moves with Pip
  guiding, learn what checkmate means and why it is checkmate, then defend it
  as Black by finding …g6. Fork and Pin coming soon.
- Audio rework: sounds are sequenced now, never stacked — fanfare first, then
  the voice — so nothing clips.
- Pawn lesson: new cookie tip with a recorded Pip line.
- Fixed: a pawn that became a queen celebrated "Wow! A new Queen!" on every
  move she made afterwards. She celebrates once now.
- Max stars 8 → 10 (two new stars for Game Theory).

### v1.0.1 — 24 November 2026

- Difficulty levels for Play the Computer: Easy, Medium, Hard.
- A pawn reaching the far end becomes a queen and play carries on —
  promotion no longer ends the game.
- Pawn lesson: the pawn only steps forward, never sideways.
- All robotic voices replaced with recorded Scottish voices (75 clips).

### v1.0.0 — 22 November 2026

- First release: piece lessons, pawn race, free play, Play the Computer.
