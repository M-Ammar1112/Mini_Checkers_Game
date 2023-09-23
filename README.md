# Mini_Checkers_Game

## INTRODUCTION:
The 6x6 Mini Checkers game is a simplified version of the classic checkers game, played on a 6x6 square board. Each player starts with 6 pieces, placed on the black squares of the board, with the goal of capturing all of the opponent's pieces. The game mechanics and rules are similar to classic checkers, with players taking turns moving their pieces diagonally, making captures by jumping over opponent's pieces. The game is implemented using data structures, algorithms, and a GUI developed in Python using the Tkinter library, offering an exciting and engaging experience for players of all skill levels because it has two difficulty levels.

## DATA STRUCTURES:
• 2D arrays: Used to represent the checker board, storing the state of each square (occupied/unoccupied) and the type of piece (red/black).

• 2D arrays, also known as matrix data structures, are commonly used in board games such as checkers to represent the game board. A 2D array is a collection of elements arranged in a grid-like manner, where each element can be accessed by its row and column indices. In the case of a checkers game, each element in the array represents a square on the game board.

• The elements of the 2D array can be of any data type, but for a checkers game, it is common to use integers or characters to represent the state of each square. For example, a square could be represented as 0 (unoccupied), 1 (occupied by a red piece), or 2 (occupied by a black piece).

• The 2D array in a checkers game serves as the main data structure for storing the state of the game board. It is updated whenever a move is made, allowing the game logic to efficiently determine the state of the board at any point in time. Additionally, the 2D array can be easily visualized as the checkers board, making it straightforward to display the state of the game to the player.

• In a mini checker’s game developed in Python with a GUI using the Tkinter library, the 2D array can be implemented as a list of lists, where each sub list represents a row on the game board and the elements of each sub list represent the squares in that row.




