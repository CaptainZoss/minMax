# minMax

Simple demonstration of the minMax Algorithm with pruning in the form of a game of Koanne.

The rules can be found here https://en.wikipedia.org/wiki/K%C5%8Dnane but simply, the goal of the game is to avoid being the first player without a valid move. A move can be made by hoping over the opponents pieces which captures them (removes them from the board). The first player without valid moves is the loser.

To play the game, simply run game.py. You will see a grid of B and W representing the Black and White pieces on the board. Before making a move, all viable moves are persented below the player. To make a move, simply write the coordinates of your piece(separated by a coma) then space and then the coordinates of your pieces destination. 

For example, to go from 8,8 to 6,8 simply input 8,8 6,8. At the beginning of the game, certain pieces have to be removed from the board and this is done by setting the destination coordinate to simply 0 (8,8 0).

Good luck!
