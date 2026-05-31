## Tetris

A clean, modern implementation of the classic Tetris game, built entirely with vanilla HTML, CSS, and JavaScript.

### Features

- Full Tetris mechanics (7 tetrominoes, rotation with wall kicks, line clearing)
- Ghost piece (shadow) for easier placement
- Next piece preview
- Progressive difficulty (speed increases with level)
- Scoring system with persistent high score (saved in localStorage)
- **Sound effects** + synthesized **Für Elise** background music (Beethoven, public domain)
- Music enabled by default
- **Mobile-friendly touch controls** arranged in a keyboard-style layout on the right side
- Optimized for vertical (portrait) mobile screens — no scrolling required
- Audio properly unlocked on mobile browsers (iOS Safari, Android Chrome, etc.)
- Pause / Resume support
- Works great on both desktop and mobile

### Controls

**Desktop / Keyboard**
- ← → ↓ — Move left / right / soft drop
- ↑ or X — Rotate
- Space — Hard drop
- P or Esc — Pause / Resume
- R — Restart

**Mobile / Touch**
- Touch buttons appear on the right side of the board in a keyboard-like layout:
  - ↻ — Rotate
  - ← → — Move left/right
  - ↓ — Soft drop
  - ⬇️ — Hard drop

### Running Locally

No installation or build tools required.

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

Just open the file in any modern browser.

### Tech Stack

- Pure HTML5 Canvas + CSS3 + JavaScript (ES6+)
- Web Audio API for sound effects and music (no external audio files)
- Fully responsive design

### Live Demo

https://cashiny.github.io/tetris

### Project Structure

```
tetris/
└── index.html   # Complete self-contained game
```

---

Enjoy the blocks! 🧩

Created by [cashiny](https://github.com/cashiny)