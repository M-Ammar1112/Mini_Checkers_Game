# Mini_Checkers_Game

## INTRODUCTION:
The 6x6 Mini Checkers game is a simplified version of the classic checkers game, played on a 6x6 square board. Each player starts with 6 pieces, placed on the black squares of the board, with the goal of capturing all of the opponent's pieces. The game mechanics and rules are similar to classic checkers, with players taking turns moving their pieces diagonally, making captures by jumping over opponent's pieces. The game is implemented using data structures, algorithms, and a GUI developed in Python using the Tkinter library, offering an exciting and engaging experience for players of all skill levels because it has two difficulty levels.

## DATA STRUCTURES:
• 2D arrays: Used to represent the checker board, storing the state of each square (occupied/unoccupied) and the type of piece (red/black).

• 2D arrays, also known as matrix data structures, are commonly used in board games such as checkers to represent the game board. A 2D array is a collection of elements arranged in a grid-like manner, where each element can be accessed by its row and column indices. In the case of a checkers game, each element in the array represents a square on the game board.

• The elements of the 2D array can be of any data type, but for a checkers game, it is common to use integers or characters to represent the state of each square. For example, a square could be represented as 0 (unoccupied), 1 (occupied by a red piece), or 2 (occupied by a black piece).

• The 2D array in a checkers game serves as the main data structure for storing the state of the game board. It is updated whenever a move is made, allowing the game logic to efficiently determine the state of the board at any point in time. Additionally, the 2D array can be easily visualized as the checkers board, making it straightforward to display the state of the game to the player.

• In a mini checker’s game developed in Python with a GUI using the Tkinter library, the 2D array can be implemented as a list of lists, where each sub list represents a row on the game board and the elements of each sub list represent the squares in that row.

## ALGORITHMS:
• Minimax: Used to determine the best move for the AI player, considering all possible moves and counter-moves and assigning a score to each position to determine the best outcome.

• Alpha-Beta Pruning: An optimization to the Minimax algorithm, to eliminate branches of the game tree that will not affect the final decision.

• Breadth First Search: Used to generate all possible moves from a given position on the board.

### MINIMAX:
Minimax is a decision-making algorithm that helps the AI player determine the best move to make in a game. It works by evaluating all possible moves and outcomes, considering both the player's and the opponent's moves. The algorithm assigns scores to each possible outcome, with the goal of maximizing the score for the AI player and minimizing the score for the opponent. The AI player chooses the move that results in the highest score for itself.

### ALPHA-BETA PRUNING:
Alpha-Beta pruning is a technique used to optimize the Minimax algorithm. It works by eliminating branches of the game tree that are not relevant to the outcome of the game, allowing for a faster and more efficient evaluation of possible moves. The algorithm uses two values, alpha and beta, to keep track of the best outcome for the AI player and the opponent, respectively. Branches that have values less than alpha or greater than beta are pruned, since they will not affect the outcome of the game.

### BREADTH FIRST SEARCH:
Breadth First Search is a search algorithm used to find the shortest path between two points in a graph. In the context of mini checkers, it can be used to determine the shortest path for a piece to reach the opposite end of the board and become "kinged". The algorithm works by exploring all the neighboring squares of the current square, before moving on to the next set of squares. This ensures that the shortest path is found, as the algorithm will always explore the squares closest to the starting point first.

## CONCLUSION:
In conclusion, the 6x6 Mini Checkers game is a unique and engaging implementation of the classic checkers game, combining traditional game mechanics with modern computer programming techniques. The game is developed using data structures, algorithms, and a GUI in Python using the Tkinter library, offering an interactive and challenging experience for players of all skill levels. The use of algorithms such as Minimax, Alpha-Beta Pruning, and Breadth First Search play a crucial role in the game's implementation, allowing for efficient and effective decision-making by the AI player. This combination of classic game mechanics with advanced computer science techniques results in a thrilling and entertaining experience for players.


