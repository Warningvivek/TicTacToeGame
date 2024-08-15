# TicTacToeGame
# Tic-Tac-Toe Game

Welcome to the Tic-Tac-Toe game! This is a simple command-line implementation of the classic Tic-Tac-Toe game written in C++. The game allows two players to take turns marking spaces in a 3x3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner.

## Features

- **Two-Player Mode**: Play against a friend.
- **Simple and Intuitive Interface**: Easy to understand and play.
- **Winning and Draw Conditions**: Automatically detects when a player has won or if the game ends in a draw.

## How to Play

1. **Players**: The game requires two players.
2. **Turns**: Players take turns to choose a number from 1 to 9 to place their mark (`X` or `O`) on the board.
3. **Winning**: The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins the game.
4. **Draw**: If all nine spaces are filled without any player winning, the game ends in a draw.

## Getting Started

### Prerequisites

To compile and run this project, you need:

- A C++ compiler (e.g., g++, clang++)
- A terminal or command prompt

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/tic-tac-toe.git
    cd tic-tac-toe
    ```

2. **Compile the game**:
    ```bash
    g++ tic-tac-toe.cpp -o tictactoe
    ```

3. **Run the game**:
    ```bash
    ./tictactoe
    ```

## Game Example

```plaintext
        *** TIC-TAC-TOE ***

Enter Player 1 name: Alice
Enter Player 2 name: Bob

 Alice's turn (X). Enter your move: 5

 1 | 2 | 3
---|---|---
 4 | X | 6
---|---|---
 7 | 8 | 9

 Bob's turn (O). Enter your move: 3

 1 | 2 | O
---|---|---
 4 | X | 6
---|---|---
 7 | 8 | 9

...

Alice wins!
