# TTTAi

## Overview

This project is a Tic Tac Toe game implemented in Python with an AI opponent powered by the **Minimax algorithm**. The AI plays optimally, making it challenging to beat.

The game supports:
- Human vs AI play
- Valid move enforcement
- Win/draw detection
- Minimax-based AI decision making for unbeatable gameplay

---

## Features

- **Simple board representation:** 3x3 grid with `X`, `O`, or empty cells.
- **Turn-based play:** Alternates between human player and AI.
- **Optimal AI:** Uses Minimax to evaluate all possible moves and select the best outcome.
- **Game status:** Detects wins, losses, and draws accurately.
- **Clear input validation:** Prevents invalid or occupied moves.
- **Pure Python implementation:** No external dependencies required.

---

## How It Works

1. The board is represented as a 2D list of 3 rows and 3 columns.
2. The current player is determined by counting existing moves.
3. The AI uses the Minimax algorithm to recursively evaluate future game states, maximizing its chances of winning or minimizing losing chances.
4. The game checks for terminal states (win/draw) after each move.
5. The AI selects the move with the best minimax score.

---