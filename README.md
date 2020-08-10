# Tic-Tac-Toe-JavaScript
Build Tic Tac Toe Game With JavaScript

Tic-tac-toe for American English, noughts and crosses for British English, or Xs and Os is a paper-and-pencil game for two players, X and O, who take turns filling the spaces in a 3×3 grid (2D Array in JavaScript). The player who succeeds in placing three of their symbols in a horizontal, vertical, or diagonal row is the winner.

In general in our game.js all what we need to do, is:

1. A 1D Array called "gameData" to store the players moves.
2. Draw the board on the canvas.
3. add Event listener to the CANVAS.
4. Determine which SPACE on THE BOARD the player has clicked on.
5. Update the gameData array. (if the space clicked by the player is empty)
6. Draw the player's move on the board (canvas).
7. check if this player wins. if wins we show the game over message. and stop the game.
8. If it doesn't win, we check for a tie game, if it's a tie we show the game over message. and stop the game.
9. If there is no winner and it's not a tie game, we give the turn to other player.


