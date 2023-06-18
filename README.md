# Tictactoe

This is a simple implementation of the Tic-Tac-Toe game in Java using the Swing library. The game allows two players to take turns and compete against each other. It features a graphical user interface with buttons representing the game board.


# Getting Started

To run the game, you need to have Java Development Kit (JDK) installed on your machine.

Copy the code provided into a Java file with the name Tictactoe.java.
Compile the Java file using the following command : javac Tictactoe.java
Run the compiled class file using the following command: java Tictactoe

# Gameplay Instructions

1-When you run the game, a graphical window will appear with a 3x3 grid of buttons representing the game board.
2-The first player's turn is denoted by the "X" symbol, and the second player's turn is denoted by the "O" symbol.
3-Click on any available button to place your symbol on the game board.
4-Players take turns placing their symbols until one of the following conditions is met:
5-One player has three symbols in a horizontal, vertical, or diagonal row.
6-All the buttons on the game board are filled, resulting in a tie.
7-If any of the above conditions is met, a message will be displayed indicating the winner or a tie.
8-To start a new game, close the game window and run the program again.

# Implementation Details

The Tictactoe class implements the ActionListener interface to handle button click events. It creates a graphical window using the Swing library and sets up the necessary components such as buttons, labels, and panels. The game logic is implemented in the actionPerformed method, which determines the current player's turn, updates the game board, and checks for a win or tie condition. The xWins and oWins methods highlight the winning combination of buttons and disable all the buttons once the game is over.

Feel free to modify the code to add new features or customize the game according to your requirements. Enjoy playing Tic-Tac-Toe!
