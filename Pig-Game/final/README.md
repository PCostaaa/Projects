# Pig Game 🎲

A simple 2-player dice game. Players take turns rolling a dice, accumulating points, and deciding when to “Hold” to secure their score — but be careful: rolling a 1 resets the current turn score and passes the turn to the other player.

---

## How to Play

- Roll Dice (🎲): adds the dice value (2–6) to your Current score.
- If you roll a 1:
  - your Current score becomes 0
  - the turn switches to the other player
- Hold (📥): adds your Current score to your Total score and ends your turn.
- Win Condition: first player to reach 100 total points wins.
- New Game (🔄): resets everything.

---

## Features

- Turn-based gameplay (Player 1 vs Player 2)
- Dice image updates dynamically (`dice-1.png` … `dice-6.png`)
- Active player highlighting
- Winner state styling
- Reset game button

---

## Tech Stack

- HTML5
- CSS3

- JavaScript (ES6+)

---

## Run Locally

### Option 1 — Open directly
1. Download/clone the repository
2. Open `final/index.html` in your browser

### Option 2 — Using VS Code Live Server (recommended)
1. Open the project folder in VS Code
2. Install **Live Server**
3. Right-click `final/index.html` → **Open with Live Server**

---
![Project Screenshot](Pig-Game/final/pig_game.jpg)
