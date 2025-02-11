# Connect 4 AI

**Connect 4 Game with Implementation of Minimax Algorithm**

## 📖 Overview

This repository contains a **Connect 4 game** where a player can compete against an AI. The AI uses the **Minimax Algorithm** with alpha-beta pruning to make intelligent moves. The game is built using **Python** and features a graphical user interface created with **Pygame**.

---

## ✨ Features

- 🎮 **Player vs. AI**: Play against an AI opponent.
- 🧠 **AI Intelligence**: Uses the Minimax algorithm to determine optimal moves.
- 🖱️ **Clickable Interface**: A Pygame-based UI for an interactive experience.
- 🏆 **Winning Detection**: Automatically detects winning moves for both the player and AI.

---

## 🛠️ Installation

### Prerequisites

Ensure you have the following installed:
- **Python** (version 3.8 or higher)
- **Pygame** and **Numpy** libraries

### Steps to Run the Game

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/connect4-ai.git
   cd connect4-ai
   ```

2. Install the required dependencies:
   ```bash
   pip install pygame numpy
   ```

3. Run the game:
   ```bash
   python connect4-with-ai.py
   ```

---

## 🎮 How to Play

1. **Start the game**: Run the script and wait for the window to open.
2. **Make your move**: Click on a column in the board to drop your piece.
3. **Compete against the AI**: The AI will automatically calculate and make its move.
4. **Win the game**: Connect 4 pieces horizontally, vertically, or diagonally to win!

---

## 🤖 How It Works

### Minimax Algorithm

The AI uses the **Minimax Algorithm** with **alpha-beta pruning** to:
- Simulate all possible moves up to a depth limit.
- Evaluate the best move to maximize its chances of winning or minimize the player's chances.

### Evaluation Function

The evaluation function calculates scores for board states by:
- Favoring moves that bring the AI closer to connecting 4.
- Blocking the player’s opportunities to connect 4.

---

## 🚀 Future Improvements

- Add **difficulty levels** for the AI.
- Implement **sound effects** for a better user experience.
- Add **multiplayer mode** for two players.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
