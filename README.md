# TicTacToe-using-Python
❌⭕ Tic-Tac-Toe Game using Python (Console-Based)
This program is a two-player Tic-Tac-Toe game built using Python, played entirely in the console. Players alternate turns, placing X and O on a 3x3 grid. The game checks for a winner after every move and ends with a win or draw.

🔧 Key Features and Functionality:
Console-Based Interface: Displays a 3×3 grid using print statements, showing live updates after each turn.

Two-Player Mode: Accepts input from two players alternately, assigning 'x' and 'o' marks.

Input Validation: Ensures players do not overwrite filled positions by checking if a tile is already occupied.

Winning Logic: Checks all possible winning combinations (rows, columns, diagonals) after each move.

Game End Handling: Announces the winner immediately or ends in a draw after 9 moves if no winner is found.

🧠 How it works:
Initializes a board with 9 '-' characters representing empty tiles.

Displays the board using the dis() function.

Takes user input (1–9) for position selection via inp(), ensuring no overwriting.

Updates the board with 'x' or 'o' based on turn count.

The check() function evaluates win conditions after each move.

If a win is detected, it breaks the loop and displays the winner; otherwise, it proceeds until all 9 moves are done.
