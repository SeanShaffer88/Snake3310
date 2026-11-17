# Snake3310

Complete, feature-rich retro Nokia 3310 Snake game application in a single file complete with authentic LCD aesthetics, synthetic Web Audio sound effects, particle systems, high score persistence, and responsive controls.

## ▶ Play it in your browser

**[Play Snake3310 →](https://seanshaffer88.github.io/Snake3310/)**

Nothing to install. Open the link and press **START GAME** (or any arrow key).

## How to play

| Action | Keyboard | On-screen |
| --- | --- | --- |
| Steer | Arrow keys or WASD | D-pad |
| Start | Space or any arrow key | START GAME / OK |
| Pause / resume | Space or P | PAUSE / OK |
| Start over | – | RESET |
| Sound on / off | – | SND |

- Normal food is worth **10 points**. Bonus food (the small hollow square) is worth **30**, but it only stays for 40 moves.
- Every 50 points you go up a level and the snake speeds up, until it reaches top speed at level 6.
- Obstacles appear at level 3, and their layout changes at levels 4 and 5.
- Hitting a wall, an obstacle or your own body ends the game.
- Your high score is saved in your browser.

## Features

- Nokia 3310 style LCD screen with scanlines and a dot-matrix grid
- Sound effects synthesised with the Web Audio API, so there are no audio files
- Particle burst when the snake eats
- High score kept in `localStorage`
- Keyboard, mouse and touch controls
- One `index.html` file with no build step (Tailwind CSS and two Google Fonts load from CDNs)

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

You need to be online, because the styling and fonts load from CDNs.

## Hosting

The playable version is served by GitHub Pages from the `main` branch (repository **Settings → Pages → Deploy from a branch → `main` / root**). Changes merged to `main` go live automatically.
