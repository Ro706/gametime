# Tic-Tac-Toe Game

Welcome to the **Intermediate Level Tic-Tac-Toe Game**! This game is designed to provide a fun and challenging experience for those who enjoy strategic thinking. Do you have what it takes to beat the computer? Let's find out!

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [How to Play](#how-to-play)
- [Code Explanation](#code-explanation)
- [Acknowledgements](#acknowledgements)

## Introduction

This is an intermediate-level Tic-Tac-Toe game where you can play against a computer. The game has a hint feature that provides suggestions for optimal moves if you need help during the game. 

## Features

- Random selection of who plays first (player or computer).
- User-friendly board display.
- Hint feature to help you make better moves.
- Intelligent computer AI to provide a challenging game.
- Option to play again after each game.

## Getting Started

### Prerequisites

- Python 3.x installed on your computer.

### Running the Game

1. Clone or download the repository containing the game script.
2. Open a terminal or command prompt.
3. Navigate to the directory where the script is located.
4. Run the script using Python:

```sh
python tictactoe.py
```

## How to Play

1. When you start the game, a welcome message and game instructions will be displayed.
2. Choose whether you want to be 'X' or 'O'.
3. The game will randomly select who plays first.
4. Enter your moves by typing a number between 1 and 9, corresponding to the position on the board:
   ```
       1 | 2 | 3
      -----------
       4 | 5 | 6
      -----------
       7 | 8 | 9
   ```
5. If you need a hint during the game, type "Hint", "hint", "H", or "h".
6. The game ends when either the player or the computer wins, or the board is full (a tie).

## Code Explanation

The game consists of several functions to handle different aspects of the game:

- `Welcome()`: Displays the welcome message and game instructions.
- `DrawBoard(board, NeedSleep=True)`: Draws the current state of the game board.
- `InputPlayerLetter()`: Asks the player to choose 'X' or 'O'.
- `WhoFirst()`: Randomly selects who plays first.
- `PlayAgain()`: Asks if the player wants to play again.
- `MakeMove(board, letter, move)`: Makes a move on the board.
- `IsWinner(board, letter)`: Checks if there is a winner.
- `GetBoardCopy(board)`: Returns a copy of the board.
- `IsSpaceFree(board, move)`: Checks if a space on the board is free.
- `GetPlayerMove(board)`: Gets the player's move.
- `ChooseRandomFromList(board, MoveList)`: Chooses a random move from a list of possible moves.
- `GetComputerMove(board, ComputerLetter)`: Determines the computer's move using AI logic.
- `IsBoardFull(board)`: Checks if the board is full.
- `FinalBoard(board, NeedSleep=True)`: Displays the final state of the board.

The game loop manages the alternating turns between the player and the computer, checking for a win or tie after each move, and providing hints if requested.

## Acknowledgements

The algorithm used in this game is based on the work by **Albert Sweigart** from his book ["Invent Your Own Computer Games with Python"](http://inventwithpython.com). The original source code has been modified and enhanced to create this version of the Tic-Tac-Toe game. For more details, you can read the relevant chapter online at [Invent with Python](http://inventwithpython.com/invent4thed/chapter10.html).

Enjoy the game, and may the best strategist win! If you like this game, don't forget to give it a star! ⭐
