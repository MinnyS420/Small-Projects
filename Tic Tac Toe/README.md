# Tic Tac Toe

Tic Tac Toe is a classic two-player game implemented as a web application. Players take turns marking spaces in a 3x3 grid, aiming to achieve a row, column, or diagonal of their symbol.

## Features

- **Two-Player Gameplay:** Play against another player locally.
- **Interactive Interface:** Clickable grid for selecting game positions.
- **Win Detection:** Automatically detects winning combinations and declares the winner.
- **Reset Functionality:** Allows resetting the game for a new round.

## Usage

1. Clone the repository or download the project files.
2. Open the `index.html` file in a web browser.
3. Players take turns clicking on squares to place their symbol (X or O).
4. The game automatically detects winning combinations or a draw.
5. Click "Reset Game" to start a new round.

## File Structure

- `index.html`: Contains the HTML structure of the Tic Tac Toe game.
- `style.css`: Contains the styles for the game interface.
- `script.js`: Contains the JavaScript code for game logic and functionality.

## How to Play

- The game board is represented by an array of nine empty strings.
- The `currentPlayer` variable stores the player's turn (X or O).
- An event listener is added to each square on the board to handle player clicks.
- When a square is clicked, it checks if the square is already filled. If not, it adds the current player's value to the board array and updates the interface accordingly.
- It checks for a winner after each move and displays a message if there's a winner or a draw.
- The game can be reset using the "Reset Game" button, which resets all variables and enables all squares for clicking again.

## Functions

- `checkForWinner()`: Checks for three of the same values in any row, column, or diagonal on the board.
- `checkForDraw()`: Checks if all squares have been filled with values (X or O).

## Demo

You can view a live demo of the Tic Tac Toe [here](https://minnys420.github.io/Tic%20Tac%20Toe/index.html).

## Credits

This Tic Tac Toe project is created by [Minny'S dev](https://minnys420.github.io/).

## License

This project is licensed under the [MIT License](LICENSE).
