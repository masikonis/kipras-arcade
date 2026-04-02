# 🗣️ How to Talk to Claude Code

## Starting a New Game

Say things like:
- "Create a new game called Dragon Runner where a dragon flies and avoids obstacles"
- "Make a new game in folder 03 where you click on moles that pop up"
- "I want a racing game with a car that drives on a road"

**Tip:** Describe WHAT the game is, not HOW to code it!

## Making Changes

Be specific about what you want:
- ✅ "Make the player bigger"
- ✅ "Add 3 enemies that move left and right"  
- ✅ "When I press space, the character should shoot a fireball"
- ✅ "Change the background to look like space with stars"
- ✅ "Add a game over screen when the player runs out of lives"

## Good Words to Use

- **"Add"** — "Add a score counter in the top corner"
- **"Change"** — "Change the player color to blue"
- **"Make"** — "Make the enemies faster"
- **"When"** — "When the player touches a coin, play a sound"
- **"Remove"** — "Remove the second enemy"
- **"Fix"** — "Fix the bug where the player goes through walls"

## Power Moves 💪

Once you get comfortable, try:
- "Add particle effects when stars are collected"
- "Make a start screen with a play button"
- "Add levels that get harder"
- "Save the high score so it remembers"
- "Add power-ups that fall randomly"
- "Make the camera follow the player"

## Rules for the AI

When creating games in this repo, always:
1. Put each game in `games/XX-game-name/index.html`
2. Use Phaser 3 via CDN: `https://cdn.jsdelivr.net/npm/phaser@3/dist/phaser.min.js`
3. Keep everything in ONE html file (inline CSS, inline JS)
4. Update `games/games.json` when adding a new game
5. Make games work with both keyboard AND touch/mouse
6. Always include: a score, a way to lose, and a restart button
