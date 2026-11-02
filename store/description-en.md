# Block Fall — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Guide falling blocks with move, rotate and drop controls, fill complete
rows to clear them, and climb levels as the stack speeds up. A clean,
polished take on the classic falling-block puzzle.

(192 characters)

## Details

- Genre: Puzzle / Casual / Arcade
- Controls: Keyboard — ←/→ move, ↑/X rotate, Z counter-rotate, ↓ soft drop,
  Space hard drop, P pause. Mobile — five on-screen touch buttons
  (◀ ▶ ⟳ ▼ ⤓) with hold-to-repeat, shown automatically on touch devices.
- Features: 10×20 board, 7 tetromino pieces with 7-bag randomizer, simple
  wall kicks, ghost landing preview, next-piece preview, line-clear scoring
  (1/2/3/4 lines = 100/300/500/800 × level), level up every 10 lines with
  rising speed, best score saved locally, mute toggle, pause on tab switch.
- Tech: Single-file HTML5 (about 30 KB), vanilla JavaScript, Canvas
  graphics, WebAudio synthesized sounds. No external assets, no frameworks,
  no tracking, no external links. Works offline once loaded.

## Tags
falling blocks, tetromino, puzzle, arcade, casual, retro, brain, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames / gamedistribution domains)
- [x] gameplayStart / gameplayStop / happytime events wired (loadingStart/loadingStop in SDK loader)
- [x] Responsive (canvas scales to fit portrait mobile and desktop, keyboard + touch controls)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## GameDistribution
- Upload block-fall-gd.zip (contains only index.html)
- Game starts on load; no site integration needed beyond the GD SDK loader

## itch.io
- Upload zip (rename to block-fall.zip), mark "This file is playable in browser",
  entry file: index.html, viewport 440×680, kind: html
- Pricing: $0 (donations optional)
