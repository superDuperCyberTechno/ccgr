## Ello
*v0.10.0*

Highly experimental. Originally based on *Oh Hell!*, but tweaked heavily into something completely different. Most notably this game features an extra participant represented by the stock (to make it viable as a 2-player game), fixed hand size, simpler scoring and a can-follow mechanic ([read this](?p=articles-core_values)).

### Requirements
2-6 players. A standard deck of 52 cards.

### Goal
Accrue most points.

### Setup
All players receive 7 cards. The rest of the cards are put aside as stock (placed between 2 players) with the top card flipped and put below the stock to denote the trump suit.

### Play
Clockwise, one at a time, each participant plays 1 card. The winner of the trick is determined as follows: Highest card of the trump suit wins the trick or if no trump suited card was played, highest card of the leading suit wins the trick.

If any player can't or won't play a card that will win the current state, a card is chosen at random from their hand and played face down. Any card played like this cannot win the trick. I.e., the last played face-up card wins the trick.

All face-down cards played *after* the last face-up card, will be awarded to the winner as points, 1 point per card. E.g., if the second player wins the trick in a 5-player game, they get 3 face-down cards which will count as points (3 cards were played after the last winning card). If the last player won the trick, they get 0 points (no face-down cards played afterwards).

When play passes the stock, play the top card as if it were played by a human participant. Make sure to check if the revealed card is winning the trick and play the card face-down if not. Any points won by the stock are discarded. If the stock is leading a trick, simply play the top card face-up.
