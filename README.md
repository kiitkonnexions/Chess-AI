# Chess-AI

## Description
This is a chess AI that uses the minimax algorithm with alpha-beta pruning to determine the best move to make written using vanilla Javascript.

## How to use
1. Clone the repository
2. Open the index.html file in your browser
3. Drag and drop the pieces to make your move
4. AI will make its move after you make yours

## How it works
The AI uses the minimax algorithm with alpha-beta pruning to determine the best move to make. The minimax algorithm is a recursive algorithm that will simulate every possible move that can be made from the current board state and will determine the best move to make based on the evaluation function. The evaluation function is a function that will evaluate the current board state and return a score based on how good the board state is for the AI. The higher the score, the better the board state is for the AI. The evaluation function will evaluate the board state based on the following:
- Piece value
- Piece position
- Piece mobility
- Piece protection
- Piece attack
- Piece defense
- Piece development
- Piece center control
- Piece pawn structure
- Piece king safety


## How to change the difficulty
The difficulty of the AI can be changed by changing the depth of the minimax algorithm. The higher the depth, the more moves the AI will simulate and the better the AI will be. The depth can be changed by changing in the GUI `depth` in the file `js/ai.js` on line 3. The default value is 3.