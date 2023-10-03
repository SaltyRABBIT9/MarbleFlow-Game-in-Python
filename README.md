# MarbleFlow-Game-in-Python
A simple yet engaging implementation of the MarbleFlow Game in Python. Its a two player boardgame. Play againsts my AI opponent. The game is built using Python and agent determines the next move through minimax and alpha beta pruning.

<h1>Game Rules:</h1>
<br>
Place the board horizontally between the two players. Each player controls the six pits closest to them and the score pocket on their right. Place an equal number of marbles (usually 3-4) in each of the 12 small pits.
The goal of the game is to capture more marbles than your opponent. The game ends when one player cannot make a move.
Players take turns. On a player's turn, they choose one of their pits containing marble and distribute the marble in a counter-clockwise direction, placing one marble in each pit, including their own score pocket but skipping the opponent's score pocket. If the last marble lands in the player's score pocket, they get another turn. If the last marble lands in an empty pit on the player's side, and the opposite pit from the opponent's side has marble, the player captures both the last marble and the marbles in the opposite pit, placing them in their score pocket. The game continues until one player's side is empty. The winner is the one with the most marble in their score pocket.
