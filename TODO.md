# TODO

## Slices?
* A game with only 1-cell ships ("Gun Ships")
* A game with a 1x1 board?
* A game with a 2x2 board?
* Place the player's ships at random positions (instead of allowing the user to specify their positions at the start of the game).
* A game with two-players (it's not allowed to add players), no need to model the `addPlayer` command.

## Insights
* There should be a game board for each player (as in the real battleship game)

## Doubts
* Can a single player play a battleships game? Or should we expect two players before allowing the game to start?
* Is it allow to have more than 2 players? If so, how should I decide which one to fire to?
* How to specify the player's ship positions when adding a new player? 
  * e.g. `addPlayer (1,3), (1,4), (1,5)` ??
  * what if I add more ships than the ones allowed by the game? (e.g. 100 destroyers?)
* What if I `fire` more that once before ending my turn? Should this be disallowed somehow?
* 