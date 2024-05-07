# Tic Tac Toe Game

This repository contains a simple Tic Tac Toe game implemented in Python using `tkinter`, providing both single-player and multiplayer modes.

## How to Play

Experience the classic game of Tic Tac Toe with the following steps:

1. **Installation**
   - Clone this repository:
     ```bash
     git clone https://github.com/VipranshOjha/tic-tac-toe.git
     ```
   - Ensure you have Python installed.

2. **Run the Game**
   - Navigate to the project directory.
   - Execute the Python script:
     ```bash
     python tic_tac_toe.py
     ```

3. **Game Rules**
   - Choose a mode (`SinglePlayer` or `Multiplayer`) by clicking the respective buttons.
   - Click on the squares in the 3x3 grid to place your marker (`X` or `O`).
   - The first player to align three of their markers horizontally, vertically, or diagonally wins.
   - Click "Restart Game" to reset the board and start a new game.

## Game Components

- **Graphical User Interface (GUI)**
  - Implemented using `tkinter` for buttons, labels, and game board visualization.
  - Provides a simple yet intuitive interface for playing Tic Tac Toe.

- **Modes**
  - **SinglePlayer**: Play against the computer AI.
  - **Multiplayer**: Play against another player on the same device.

- **Game Logic**
  - Tracks the game state using a dictionary (`board`) to represent the 3x3 grid.
  - Implements logic for checking win conditions (`checkForWin`), draw conditions (`checkForDraw`), and game restart.

- **Computer AI (SinglePlayer)**
  - Utilizes the minimax algorithm to determine the optimal move for the computer player (`O`).

## Repository Structure

- `tic_tac_toe.py`: Main Python script containing the Tic Tac Toe game logic and GUI implementation.
- `README.md`: This document explaining the game and its usage.

## Dependencies

- Python 3.x
- `tkinter` library for GUI development.

## Acknowledgments

This Tic Tac Toe game was developed by Vipransh Ojha as a fun project to practice Python and GUI programming with `tkinter`.

Enjoy playing Tic Tac Toe! Feel free to modify the code and add new features. If you have any feedback or suggestions, please reach out.
