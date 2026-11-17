# Snake3310

Complete, feature-rich retro Nokia 3310 Snake game application in a single file complete with authentic LCD aesthetics, synthetic Web Audio sound effects, particle systems, high score persistence, and responsive controls.

## ▶ Play Now

**[Play Snake3310](https://seanshaffer88.github.io/Snake3310/)**

No install needed — just open the link and press **START GAME** (or any arrow key / WASD).

## How to Play

- **Move:** Arrow Keys, WASD, or the on-screen D-Pad
- **Pause / Resume:** Space, P, or the PAUSE / OK button
- **Start / Restart:** START GAME button, RESET button, or Space
- **Sound:** 🔊 SND toggle button

Eat the food to grow and score points. Special food is worth **30 points** (normal food is 10). Every 50 points you level up — the snake speeds up and obstacles appear from level 3 onward. Don't hit the walls, yourself, or an obstacle!

## Features

- Authentic Nokia 3310 LCD look with scanlines and pixel-grid effects
- Synthetic Web Audio sound effects (eat, move, start, game over) — no audio files needed
- Particle effects when eating food
- High score saved in your browser (localStorage)
- 5 levels with increasing speed and obstacle layouts
- Fully responsive — works on desktop and mobile
- Single-file game (`index.html`), no build step

## Run Locally

Just open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Tech

Single-file HTML + CSS + JavaScript. Uses Tailwind CSS (CDN) and Google Fonts for styling. Hosted on GitHub Pages.
