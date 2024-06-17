# Tic-Tac-Toe-game

## Tic-Tac-Toe Game

This is a simple Tic-Tac-Toe game implemented using HTML, CSS, and JavaScript.

**Features:**

* Players take turns marking the board with "X" or "O".
* Winner is declared when a player completes a horizontal, vertical, or diagonal row.
* The game detects a draw if all boxes are filled and no winner is found.
* Players can reset the game or start a new game.

**How to Play:**

1. Open the `index.html` file in a web browser.
2. Click on the empty boxes to place your mark ("X" or "O").
3. The game will automatically determine the winner or a draw.
4. Use the "Reset Game" button to clear the board and start over.
5. Use the "New Game" button to start a completely new game (clears winner/draw message).

**Code Structure:**

* `index.html`: This file contains the HTML structure of the game board, buttons, and messages.
* `style.css`: This file defines the styling for the game board and elements.
* `app.js`: This file contains the JavaScript logic for handling player turns, checking winners, and resetting the game.

**Technical Details:**

* The game utilizes an array to store the state of each box on the board.
* Event listeners are used to detect clicks on the boxes and buttons.
* Win patterns are defined in a separate array to check for winning combinations.

**Future Improvements:**

* Implement an AI opponent for single-player mode.
* Add visual effects for winning or drawing the game.
* Enhance the user interface with animations or sound effects.

**Feel free to contribute!**

This code provides a basic foundation for a Tic-Tac-Toe game. You can extend it with additional features and functionalities.
