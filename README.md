# Block Party 🧩

A free, ad-free block puzzle game for phones, tablets and desktops. Drag pieces onto the board, clear rows and columns, and chain combos for a high score.

**[▶ Play now](https://YOUR-USERNAME.github.io/YOUR-REPO/)**

## How to play

1. Drag one of the three pieces from the tray onto the 8×8 board.
2. Fill a complete row or column to clear it.
3. Clear lines on back-to-back moves to build a combo and score more.
4. The game ends when none of your remaining pieces fit. Rows and columns that a move would clear glow as you drag.

## Features

- **No ads, no accounts, no tracking.** Everything stays on your device.
- **Multiple players** on one device, each with their own best score and saved game.
- **Five themes:** Candy, Trail, Barn, Stage and Rink.
- **Calm mode:** the game never ends and clears some space when you get stuck.
- **Parent controls:** a PIN-protected daily play-time limit for each player.
- **Works offline** after the first load.

## Install it like an app

On an iPhone or iPad, open the game in Safari, tap **Share → Add to Home Screen**, and it opens full-screen with its own icon. On Android, use your browser's **Install app** or **Add to Home screen** option.

## Privacy

Block Party collects no data. Scores, settings and saved games are kept in your browser's local storage and never leave your device. Clearing your browser's site data resets everything.

## Run it yourself

It's plain HTML, CSS and JavaScript with no build step.

1. Download or clone this repo.
2. Open `index.html` in a browser, or host the folder anywhere that serves static files.

To publish with GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

## What's in the repo

| File | Purpose |
|---|---|
| `index.html` | The whole game |
| `manifest.webmanifest` | Home-screen app details |
| `sw.js` | Offline support and automatic updates |
| `icon-*.png` | App icons |

## Customizing

- Piece shapes are in the `RAW` array in `index.html`.
- Theme colors and celebration emojis are in the `THEMES` object.
- Starting player names are in the `defaults()` function.

## Credits

An original game built on the classic block-puzzle idea. It isn't affiliated with any other game or company.

## License

MIT. See `LICENSE`.
