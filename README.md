# 🃏 Memory Match Game

A fun and interactive **memory matching game** built with Pygame where players must find sets of **three matching cards** instead of pairs. Test your memory and concentration skills against friends or a smart AI opponent!

---

## 🎮 Game Description

Memory Match Game takes the classic card-matching gameplay to the next level. Instead of matching pairs, your goal is to find **triplets** — three cards with the same value! Play against a friend or challenge a memory-sharpened AI in turn-based, score-tracking gameplay.

---

## ⚡ Features

### Game Modes
- 🔥 **Player vs AI** — Challenge a smart AI opponent.
- 🧑‍🤝‍🧑 **Player vs Player** — Compete against a friend on the same device.

### Game Mechanics
- 🃏 **Triple Card Matching** — Match three identical cards.
- 🔄 **Turn-Based Gameplay** — Keep flipping until you miss!
- 📊 **Score Tracking** — See who’s ahead at all times.
- 👉 **Turn Indicator** — Know whose move it is.

### User Interface
- 💻 **Clean & Modern Design** — Dark theme with bright cards.
- 🎯 **Interactive Menu** — Select game modes smoothly.
- 🖱️ **Mouse-Driven Controls** — Simple, intuitive clicks.
- 📋 **Score Panel** — Real-time score & turn display.

### Card Layout
- 🧩 **6x6 Grid** — 36 cards, 12 unique triplets.
- ⚡ **Well-Spaced Layout** — Easy and precise selection.

### Animations
- 💫 **Card Flip Animation** — Smooth and polished reveals.
- 🧨 **Match Fade Animation** — Cards fade away when matched.
- ⏲️ **Timing Tweaks** — Balanced delays for satisfying flow.

### AI Opponent
- 🧠 **Smart Memory AI** — Learns and adapts as it plays.
- 🤖 **Simulated Thinking** — AI waits before each move.
- 🚀 **Adaptive Difficulty** — Gets smarter with more knowledge.

### Game States
- 📋 **Start Menu** — Easy game mode selection.
- 🕹️ **Playing State** — Dynamic and fun gameplay.
- 🏆 **Game Over Screen** — Displays winner and play-again option.

### Visual Elements
- 🎨 **Card Styling** — Clear color separation.
- 🖱️ **Interactive Buttons** — Smooth hover effects.
- 💡 **Overlay Screens** — Transparent game-over overlays.

---

## 🧠 How to Play

1. **Starting the Game**
    - Launch the game.
    - Choose: `Play vs AI` or `Play vs Friend`.

2. **Gameplay Rules**
    - Click to flip cards.
    - Match three cards with the same number.
    - Score 1 point for every triplet.
    - Keep playing until you miss, then it's the other player's turn.

3. **Winning**
    - When all triplets are matched, the player with the highest score wins.

---

## 💻 Controls

| Action            | Control           |
|-------------------|--------------------|
| Select Cards      | `Mouse Click`      |
| Exit on Game Over | `ESC Key`          |

---

## ⚙️ Technical Details

- Written in **Python 3.x**
- Built using **Pygame**.
- Smooth animations with progressive rendering.
- Intelligent AI with memory-based decision-making.
- State management for clear transitions.

---

## 🚀 Installation

1. Ensure Python 3.x is installed on your machine.
2. Install `pygame`:

```bash
pip install pygame

git clone https://github.com/yourusername/memory-match-game.git
cd memory-match-game

python memory_match_game.py
