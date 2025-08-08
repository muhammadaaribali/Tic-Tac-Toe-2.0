Tic-Tac-Toe Game: Player vs Computer

Demo: 
This is a simple Tic-Tac-Toe game built with HTML, CSS, and JavaScript, where a human player (X) plays against the computer (O). The computer makes random valid moves. The game automatically detects wins, ties, and disables moves accordingly.

Features
Player plays as X and clicks on empty boxes to make a move.

Computer plays as O and makes random valid moves after the player.

Win detection for rows, columns, and diagonals for both player and computer.

Detects draw condition when all boxes are filled without a winner.

Disables further moves after the game ends.

Reset button to start a new game anytime.

Simple and intuitive UI with clear markings.

How to Use
Click on any empty box to place your X.

Wait for the computer to place its O automatically.

The game will alert when X or O wins or if it's a draw.

Click the Reset button to clear the board and play again.

Technologies Used
HTML — Game board structure.

CSS — Styling and layout of the game board.

JavaScript — Game logic including player moves, computer moves, win detection, and reset functionality.

Project Structure
index.html — Contains the game board and reset button.

styles.css — Styling for the game board and elements.

script.js — JavaScript logic for game play and interactivity.

How It Works
The game board consists of 9 clickable boxes.

Player clicks a box to place X if it's empty.

After the player's move, the computer picks a random empty box to place O.

After each move, the game checks for a winner or a draw.

When the game ends, further moves are disabled until the board is reset.

Future Improvements
Implement smarter computer AI using Minimax algorithm.

Add animations and sounds for better user experience.

Improve UI responsiveness for mobile devices.

Track and display the score between player and computer.
