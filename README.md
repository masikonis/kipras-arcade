# 🎮 Game Arcade

A collection of browser games built by Kipras (age 7) with AI-assisted development.

## How It Works

Each game lives in its own folder under `games/`. Every game is a single `index.html` file that runs directly in the browser — no build tools, no installation, no compilation.

The gallery website (`index.html` at the root) automatically discovers and showcases all games.

## Repository Structure

```
game-arcade/
├── index.html              ← Gallery website (play all games here)
├── games/
│   ├── games.json          ← Game registry (title, description, thumbnail)
│   ├── 01-star-collector/
│   │   └── index.html      ← Complete game in one file
│   ├── 02-space-dodge/
│   │   └── index.html
│   └── ...
├── shared/
│   └── phaser.min.js       ← Shared Phaser library (loaded via CDN fallback)
├── docs/
│   └── PROMPTING-GUIDE.md  ← Tips for talking to Claude Code
└── README.md
```

## For Kipras 🧒

1. Open this project in VS Code
2. Open the Claude Code panel
3. Say something like:
   - *"Create a new game where a spaceship dodges asteroids"*
   - *"In game 01, make the player faster"*
   - *"Add a high score to the star collector game"*
4. Watch your game appear in the browser!

## For Nerijus (Dad) 👨‍💻

### Setup
1. Clone this repo
2. Install the **Live Server** VS Code extension
3. Right-click `index.html` → "Open with Live Server"
4. Games auto-reload on save

### Adding a New Game
Claude Code should handle this automatically when asked to "create a new game," but manually:
1. Create a new folder: `games/XX-game-name/`
2. Add an `index.html` inside it
3. Update `games/games.json` with the game's metadata

### Deployment
Push to GitHub and enable GitHub Pages (Settings → Pages → main branch). The gallery and all games will be live at `https://<username>.github.io/game-arcade/`.

## Tech Stack
- **Phaser 3** via CDN — industry-standard 2D game framework
- **Vanilla HTML/CSS/JS** — no build step, no dependencies to install
- **GitHub Pages** — free hosting, automatic deployment
