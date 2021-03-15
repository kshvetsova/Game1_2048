### Game 2048

Implemented the 2048 game like in [this reference](https://play2048.co/)

Some rules:
1) The game field is 4 x 4
2) Each cell can be empty or contain one of number: 2, 4, 8 ... 2^n
3) The player can move cells with keyboard arrows
4) All the numbers should be moved in the selected direction as much as possible
   - 2 equal cells should be merged into a doubled number
   - The merged cell can’t be merged twice during one move
5) The move is possible if something will be changed after that
6) After move 2 or 4 appears in a random empty cell. 4 probability is 10%
7) When 2048 collected should be shown win message.
8) The `game over` message should be shown if there are no more available moves.
9) Hide start message after begin.
10) Change the `Start` button to `Restart` after begin.
11) Increase score with each move. The score should be increased by the sum of all merged cells.

Tech stack:
- HTML
- SCSS
- JavaScript

![Preview](./src/images/reference.png)

  [DEMO LINK](https://kshvetsova.github.io/Game_2048/)