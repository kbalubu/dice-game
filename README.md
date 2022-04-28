# DICE-GAME

## Goal

Creation of a small game on a web browser using the DOM.

## Rules

The game includes 2 players on a single screen. 
Each player has a temporary score (ROUND) and a global score (GLOBAL).
At each turn, the player has his ROUND initialized to 0 and can roll a die as many times as he wants. The result of a roll is added to the ROUND.

During his turn, the player can decide at any time to:
- Click on the "Hold" option, which sends the points from the ROUND to the GLOBAL. It will then be the other player's turn.
- Roll the die. If he rolls a 1, his ROUND score is lost and his turn is over.

The first player to reach 100 points on global wins the game.
