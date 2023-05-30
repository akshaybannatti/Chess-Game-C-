# Chess-Game-C++
# Chess Game in C++

This is a simple implementation of a Chess game in C++. It includes the basic rules and logic to play the game, but doesn't include advanced features such as castling, en passant, or pawn promotion.

## Getting Started

To compile and run the Chess game, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-akshay/chess-game.git
  

**Compile the code using a C++ compiler:****
g++ -o chess-game main.cpp

**Run the executable:**
./chess-game

**How to Play**
The Chess game is played on an 8x8 board. The pieces are represented by the following symbols:

P: Pawn
N: Knight
B: Bishop
R: Rook
Q: Queen
K: King
To make a move, specify the source square and the destination square using the algebraic notation. For example, to move a piece from e2 to e4, you would enter e2 e4.

**Example**
Here's an example gameplay session:
$ ./chess-game

Initial Board:
R N B Q K B N R
P P P P P P P P
. . . . . . . .
. . . . . . . .
. . . . . . . .
. . . . . . . .
p p p p p p p p
r n b q k b n r

Enter your move: e2 e4

Updated Board:
R N B Q K B N R
P P P P P P P P
. . . . . . . .
. . . . . . . .
. . . . p . . .
. . . . . . . .
p p p p . p p p
r n b q k b n r


**Contributing**
Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.

License
This Chess game is open source under the MIT License.
