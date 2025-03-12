A simple Tic Tac Toe game implemented in Java using Object-Oriented Programming (OOP) principles.

Features
Play against another Human or AI opponent.
Uses OOP concepts: Player (abstract class), Human & AI (inheritance), Grid, Cell, and GameLogic.
AI plays automatically using random moves.
Input format: A1, B2, C3 (Grid-based selection).
Detects win conditions and declares the winner.

Compile the Java files:
javac tictactoe/*.java

Run the game:
java tictactoe.GameLogic

Class Summary:

Player (Abstract Class):
Represents a player in the game.
Stores the player's symbol (X or O).
Defines the abstract method makeMove(Grid grid).

Human (Extends Player):
Handles user input for making moves.

AI (Extends Player):
Randomly selects an empty cell to make a move.

Cell:
Represents a single grid cell.
Stores the symbol (X, O, or empty).

Grid:
Manages the 3×3 game board.
Handles symbol placement and checks cell availability.

GameLogic:
Controls the game flow.
Handles turn-based gameplay, win checking, and restarting the game.

How to Play
Choose to play against an AI or another Human.
Player 1 selects their symbol (X or O).
Enter your move using A1, B2, C3 format.
The game will alternate turns and check for a winner.
Play again or exit after a game ends.

Example Gameplay
Do you want to play against AI or another player? (AI/Player): AI
Player 1, choose your symbol (X or O): X

  1   2   3
A   |   |   
 ---+---+---
B   |   |   
 ---+---+---
C   |   |   

Enter your move (e.g., A1, B2): A1

Future Improvements 
Implement a smarter AI strategy.
Add a graphical user interface (GUI).
Improve error handling and input validation.

License
This project is open-source. Feel free to contribute and enhance it!
