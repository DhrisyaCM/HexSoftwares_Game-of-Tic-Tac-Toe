Tic-Tac-Toe Game
This script implements a simple Tic-Tac-Toe game where the player competes against the computer.

Description
The script allows a player to play Tic-Tac-Toe against a computer. The player uses 'X', and the computer uses 'O'. The game continues until either the player or the computer wins, or the game ends in a tie.

How It Works
Game Board: A 3x3 grid is used to play the game.
Turns: The player and the computer take alternate turns, starting with the player.
Moves:
The player is prompted to enter their move by specifying the row and column numbers.
The computer randomly selects from available empty positions.
Winning Conditions: The game checks for a win after each turn by examining rows, columns, and diagonals.
End Game: The game ends when either the player or the computer wins, or if all positions are filled, resulting in a tie.
Functions
print_board(board): Prints the current state of the game board.
check_winner(board, mark): Checks if a given mark ('X' or 'O') has won the game.
get_empty_positions(board): Returns a list of empty positions on the board.
player_move(board): Handles the player's move input.
computer_move(board): Handles the computer's move by selecting a random empty position.
tic_tac_toe(): The main function to start and control the game flow.
Example Usage
Run the script to start the game:

bash
Copy code
python tic_tac_toe.py
Sample Gameplay
markdown
Copy code
  |   |  
-----
  |   |  
-----
  |   |  
Your turn:
Enter your move (row and column): 1 1
X |   |  
-----
  |   |  
-----
  |   |  
Computer's turn:
...
Requirements
Python 3.x
