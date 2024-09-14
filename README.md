Tic-Tac-Toe Game.
This is a C++ implementation of the classic Tic-Tac-Toe game where you can play against the computer. The computer uses the Minimax algorithm to make optimal moves.


The game board is a 3x3 grid, and the cells are numbered from 1 to 9 as shown below:
markdown

 1 | 2 | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9
You will be asked if you want to play first (as "X") or let the computer start (as "O").
Take turns placing your mark (X for Human, O for Computer) in an empty cell.
The first player to align 3 of their marks horizontally, vertically, or diagonally wins.
If the grid is full and no player has aligned their marks, the game is a draw.
How to Run the Code
Prerequisites
You need a C++ compiler (e.g., g++) installed on your machine.
Steps
Clone the repository or download the code.

bash
Copy code
git clone https://github.com/Anubhav1Shukla/Tic-Toe-Game.git
cd Tic-Toe-Game
Compile the program:

bash
Copy code
g++ TicTacToe.cpp -o TicTacToe
Run the executable:

bash
Copy code
./TicTacToe
Playing the Game
Follow the instructions on the screen.
You can choose to play first or let the computer start.
Enter the position number (1-9) where you want to place your mark when it's your turn.
Game Features
AI Opponent: The computer uses the Minimax algorithm to choose the best possible move.
Interactive: Prompts you to choose your move and displays the current state of the board after each turn.
Winning Logic: The game checks if a player has won after every move.
Files
TicTacToe.cpp: The main game implementation.
Example Gameplay
bash
Copy code
------------------------------------------------------------------------------------

                Tic-Tac-Toe

-------------------------------------------------------------------------------------

Do you want to start first? (y/n): y
Choose a cell numbered from 1 to 9 as below and play

 1 | 2 | 3 
-----------
 4 | 5 | 6 
-----------
 7 | 8 | 9 

You can insert in the following positions: 1 2 3 4 5 6 7 8 9 
Enter the position = 1

HUMAN has put X in cell 1

 X | * | * 
-----------
 * | * | * 
-----------
 * | * | * 

...
Future Enhancements
Add a GUI version of the game.
Add more difficulty levels for the AI.
