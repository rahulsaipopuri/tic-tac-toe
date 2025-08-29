Tic Tac Toe Web App
Overview
A simple web-based Tic Tac Toe game built with HTML, CSS, and JavaScript. Players take turns marking X or O on a 3x3 grid, aiming to align three symbols or end in a draw.
Files

index.html: Defines the game interface with a 3x3 grid, status display, and restart button.
style.css: Styles the game with a dark theme, responsive grid, and hover effects.
script.js: Handles game logic, including player moves, win/draw detection, and game reset.

Features

Two players alternate between X and O.
Displays current player's turn and game outcome (win or draw).
Restart button resets the game to start over.
Responsive design with a clean, dark-themed UI and interactive hover effects.

Usage

Open index.html in a web browser.
Click a cell on the 3x3 grid to place X or O (players alternate).
The game ends with a win (three in a row) or a draw (all cells filled).
Click "Restart Game" to start a new game.

Setup

Clone or download the repository.
Ensure index.html, style.css, and script.js are in the same directory.
Open index.html in a web browser.

Notes

The game prevents moves on occupied cells or after the game ends.
Win conditions include horizontal, vertical, and diagonal lines.
The reset function clears the board and restores the initial state, but note that script.js has a bug: currentPlayer = '1' should be currentPlayer = 'X' in resetGame().

