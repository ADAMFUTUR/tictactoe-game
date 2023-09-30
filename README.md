# Tic-Tac-Toe Game

## Introduction

This is a simple console-based implementation of the classic Tic-Tac-Toe game using the C programming language. It allows two players to take turns marking spaces on a 3x3 grid until one player wins or the game ends in a draw.

## Features

- Two players can play the game.
- The game checks for a win or draw condition after each move.
- It displays the game board after every move.
- A player can choose their mark (either 'X' or 'O') at the beginning of the game.

## Getting Started

 **Clone the Repository**:


  $ git clone https://github.com/ADAMFUTUR/tictactoe-game.git
  $ cd tictactoe-game
  $ gcc tictactoe.c -o tictactoe
  $ ./tictactoe

## gameplay
Welcome to Tic-Tac-Toe!

Player 1, choose your mark (X or O): X
Player 2, your mark is O

     1   2   3
   +---+---+---+
1  |   |   |   |
   +---+---+---+
2  |   |   |   |
   +---+---+---+
3  |   |   |   |
   +---+---+---+

Player 1's turn (X):
Enter row (1-3) and column (1-3) separated by a space: 2 2

     1   2   3
   +---+---+---+
1  |   |   |   |
   +---+---+---+
2  |   | X |   |
   +---+---+---+
3  |   |   |   |
   +---+---+---+

Player 2's turn (O):
Enter row (1-3) and column (1-3) separated by a space: 1 2

     1   2   3
   +---+---+---+
1  |   | O |   |
   +---+---+---+
2  |   | X |   |
   +---+---+---+
3  |   |   |   |
   +---+---+---+

...

Player 1 wins! Congratulations!

Do you want to play again? (yes/no): no

Thanks for playing Tic-Tac-Toe!

   

