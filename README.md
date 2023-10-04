# TIC-TAC-TOE Game in C++

This C++ project implements a simple TIC-TAC-TOE game for two players. Players take turns to mark 'X' or 'O' on a 3x3 game board until one of them wins or the game ends in a draw. Here's a brief overview of the project:

## Project Structure

- The game uses standard C++ libraries and functions.
- The game board is represented as a 3x3 array of characters called `Board`.
- State variables are used to keep track of the current player's turn, choice of position to mark, and whether the game has ended in a draw.

## Main Components

1. **display_board()**: Displays the current game board with player symbols ('X' and 'O').

2. **player_turn()**: Allows players to take their turns, input their choice of position, and updates the game board accordingly. It also handles invalid inputs.

3. **gameover()**: Checks for win conditions, including rows, columns, and diagonals. It also checks if the game is still in progress or has ended in a draw.

4. **main()**: The main program loop that repeatedly calls `player_turn()` until the game is over. After the game ends, it announces the winner or declares a draw.

## Usage

To play the game:
1. Players take turns to input their choice of position (1-9) on the game board.
2. The game checks for wins or draws after each move.
3. If a player wins, the game announces the winner ('X' or 'O').
4. If the game ends in a draw, it announces a draw.

This TIC-TAC-TOE game provides a simple console-based multiplayer experience. Players can enjoy taking turns to compete against each other until there is a winner or a draw.
