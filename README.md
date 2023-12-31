## 2048 game
2048 is a single-player sliding block puzzle game. The game’s objective is to slide numbered tiles on a grid to combine them to create a tile with the number 2048.

# [DEMO LINK](https://romasheva1987.github.io/2048-game-js/)

# Technologies used
- HTML5
- CSS3
- Saas (SCSS)
- JavaScript

## Rules of 2048 game
- The game field is 4 x 4
- Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
- The game starts with 2 cells filled with 2 or 4 (push Start/Restart button).
- The player can move cells with keyboard arrows
- All the numbers should be moved in the selected direction until all empty cells are filled in
  - 2 equal cells should be merged into a doubled number
  - The merged cell can’t be merged twice during one move
- The move is possible if at least one cell is changed after the move
- After move 2 or 4 appears in a random empty cell. 4 probability is 10%
- When 2048 value is displayed in any cell, win message will be shown.
- The game over message will be shown if there are no more available moves.
- Score is increased by the sum of all merged cells.

## Installing and running the project
- Fork and clone this repository
- Run npm install
- Run npm start
