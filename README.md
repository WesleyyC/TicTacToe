TicTacToe
===========

A perfect Tic Tac Toe player using the strategy in Newell and Simon's 1972 tic-tac-toe program

Win: If the player has two in a row, they can place a third to get three in a row.

Block: If the opponent has two in a row, the player must play the third themselves to block the opponent.

Fork: Create an opportunity where the player has two threats to win (two non-blocked lines of 2).

Blocking an opponent's fork:

    Option 1: The player should create two in a row to force the opponent into defending, as long as it doesn't result in them creating a fork. For example, if "X" has a corner, "O" has the center, and "X" has the opposite corner as well, "O" must not play a corner in order to win. (Playing a corner in this scenario creates a fork for "X" to win.)
    Option 2: If there is a configuration where the opponent can fork, the player should block that fork.

Center: A player marks the center. (If it is the first move of the game, playing on a corner gives "O" more opportunities to make a mistake and may therefore be the better choice; however, it makes no difference between perfect players.)

Opposite corner: If the opponent is in the corner, the player plays the opposite corner.

Empty corner: The player plays in a corner square.

Empty side: The player plays in a middle square on any of the 4 sides.

P.S. Still Under Construction.
