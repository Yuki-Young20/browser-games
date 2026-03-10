# Claude Coding — Project Progress

## GitHub Repository
- **URL:** https://github.com/Yuki-Young20/browser-games
- **Account:** Yuki-Young20
- **Visibility:** Public
- **Remote:** origin (https)

---

## Projects

### 1. Tic Tac Toe (`tictactoe.html`)
- **Status:** Complete
- 2-player local multiplayer (X vs O)
- Winning cell highlight animation
- Score tracker across games
- "New Game" reset button
- Dark neon theme

### 2. Pixel Fighter (`fighter.html`)
- **Status:** Complete
- Anime-style pixelated 2D fighting game (Tekken-inspired)
- Two fighters: RYU-KEN (P1, red) vs SHADOW (P2, blue)
- Pixel art sprites drawn on HTML5 Canvas (programmatic, no image files)
- Health bars at top with color-drain animation (green → yellow → red)
- 60-second round timer with flashing warning at ≤10s
- Best of 3 rounds system
- KO / Round / FIGHT! / TIME! announcements
- Hit particles and special move screen flash
- Web Audio API sound effects (hits, blocks, KO, special)
- On-screen click/touch buttons for both players
- Keyboard controls:
  - P1: WASD (move) + U/I (punch) + J/K (kick) + L (special) + O (block)
  - P2: Arrows (move) + Numpad 1/2 (punch) + 4/5 (kick) + 6 (special) + 0 (block)

---

## Tech Stack
- Vanilla HTML/CSS/JavaScript (no frameworks, no build tools)
- HTML5 Canvas for fighter game rendering
- Web Audio API for sound
- Google Fonts: "Press Start 2P" (pixel font)
- All games are single self-contained `.html` files

---

## Workflow Notes
- All files committed and pushed to GitHub after completion
- Git user configured locally: Yuki-Young20
- Open files with: `start "filename.html"` in bash

---

## Next Steps / Ideas
- Add AI opponent to Pixel Fighter
- Add more characters / stages
- Add combo system / move list UI
- Mobile touch improvements
- Host on GitHub Pages
