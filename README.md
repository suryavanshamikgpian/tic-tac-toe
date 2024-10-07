# tic-tac-toe
showBoard(char board[][SIDE]):
Displays the current state of the Tic-Tac-Toe board. It prints the board in a 3x3 grid format using the current player moves ('X' or 'O') and empty cells as '*'.
showInstructions():
Displays the numbered layout of the board to help players know which number corresponds to which position on the board.
initialise(char board[][SIDE]):
Initializes the board by filling all the cells with the character '*' to represent empty spaces.
declareWinner(int whoseTurn):
Prints who won the game (either the "HUMAN" or "COMPUTER").
rowCrossed(char board[][SIDE]):
Checks if any row has three identical moves (either 'X' or 'O'). If a row has the same move and is not empty, it returns true, indicating a win.
columnCrossed(char board[][SIDE]):
Similar to rowCrossed(), but it checks columns for a win.
diagonalCrossed(char board[][SIDE]):
Checks both diagonals of the board to see if they contain three identical non-empty moves ('X' or 'O').
gameOver(char board[][SIDE]):
Checks if the game is over by checking rows, columns, and diagonals to see if there's a winner. It returns true if the game is won; otherwise, it returns false.
minimax(char board[][SIDE], int depth, bool isAI):
This is the core of the AI logic. The minimax function uses recursion to simulate all possible moves and assigns a score to each move based on who would win. The AI (computer) tries to maximize its score, while the human tries to minimize it. It considers all future possibilities.
bestMove(char board[][SIDE], int moveIndex):
This function evaluates the best move for the computer using the minimax algorithm. It loops through all possible moves and selects the one that leads to the best outcome for the computer.
playTicTacToe(int whoseTurn):
The main gameplay loop. It alternates turns between the human and the computer, prompting the human for input and using the minimax strategy for the computer's moves. It continues until the game is over (either someone wins or it's a draw).
main():
The entry point of the program. It asks the player whether they want to start first or let the computer go first. It then calls playTicTacToe() and keeps running until the player decides to quit.
