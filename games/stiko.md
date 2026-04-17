## Stiko
*v0.9.2*

Trick-taking game with an inverse trump mechanic that enables clever plays. Modified version of the commercial game *Stick 'Em* (AKA. *Sticheln*).

### Requirements
3-7 players. A standard deck of 52 cards. If you include jokers, never include more than 1 less the total amount of players, i.e.: a 3 player game should include no more than 2 jokers.

### How to Play
Deal each player 7 cards. Put the rest of the deck aside - face down - to form the stock. Each player plays one card face up, its suit dictating the player's *bad suit*.

In a clockwise fashion, each player plays one card from their hand. Depending on the card played, a winner is determined...
- If **all** cards **did** follow the lead suit, the last played, highest card wins the trick.
- If **any** card did **not** follow the lead suit, the highest card **not** in the lead suit wins the trick.

The winner of the trick collects all the played card, leads the next trick. When all tricks have been played, tally up points: All bad-suited cards each yield -1 point, all other cards yield 1 point.

### Notes
* Cards are ranked 2-K (lowest to highest).
* Aces beat all face cards but are beaten by all number cards.
* Jokers always lose and are suitless (cannot by played as a bad suit).
