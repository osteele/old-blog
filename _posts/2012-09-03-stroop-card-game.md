---
layout: post
title: "The Stroop Card Game"
description: ""
category : fun
tags : [games]
---
{% include JB/setup %}

Stroop is a card game for two or more players and a dealer. The dealer does not play. The objective is to collect the most cards by calling cards that do not match (that differ in face value and in suit color) the cards that the dealer turns over.

Stroop is played with a shuffled standard 52-card deck face down in a *stock pile*. On each round, the dealer removes the top card (the *top card*) from the stock pile, and places it face up onto the *discard pile* (which is initially empty). No cards are dealt to the players. As soon as the dealer has turned over the card, all players become active. An active player may call out a card name (e.g. “five of spades”). The first active player to call a *qualifying card* wins the round and collects the discard pile.

# Qualified Cards
To qualify, the named card must have a different rank and a different color suit than the top card. If the top card is a face card or an ace, the named card must be a face card or an ace in order to qualify. If the dealt card is a two through ten, the named card must be a two through ten in order to qualify.

Top Card | Qualifying Calls | Non-Qualifying Calls |
:------- | :--------------: | :------------------: |
3♠       | 4♡, 9♧           | 3♡, 4, A♡, J♣        |
6♢       | 2♠, 8♣           | 3♢, 6, J♡            |
Q♡       | K♠, A♦           | 9♦, Q♦, A♢           |
A♣       | J♢, Q♡           | 10♢, 7♣, J♠          |

In a two player game, if one player names a card that doesn't qualify, the other player wins the dealt card. Otherwise, the first player to name a qualifying card wins the card.

# Active Players
When the top card is dealt, all players are active. A player who calls a non-qualifying card becomes inactive, if there are other players who have not yet called a non-qualifying card in this turn. Once all players have called non-qualifying cards, all players become active for the remainder of the round.

Top Card | Player 1 Call | Player 2 Calls | Result |
:------- | :-----------: | :------------: | :----- |
3♠       |               |                | Round starts; both players are active |
3♠       | 2♡            |                | Player 1 wins the round |


Top Card | Player 1 Call | Player 2 Calls | Result |
:------- | :-----------: | :------------: | :----- |
4♢       |               |                | Round starts; both players are active |
4♢       | 2♡            |                | Player 1 miscalls, becomes inactive |
4♢       | 3♣            |                | No effect; player 1 is inactive |
4♢       |               | 3♣             | Player 2 wins the round |


Top Card | Player 1 Call | Player 2 Calls | Result |
:------- | :-----------: | :------------: | :----- |
J♠       |               |                | Round starts; both players are active |
J♣       | 2♡            |                | Player 1 miscalls, becomes inactive |
J♣       |               | Q♠             | Player 2 miscalls; now both players are active again |
J♣       | Q♡            |                | Player 1 wins the round |


# Call Ties
 If two or more active players call a qualifying card simultaneously, the first player to *complete* the call (in the judgement of the dealer) wins the turn. If several active players complete qualified calls simultaneously, the first player to *begin* the call (in the judgement of the dealer) wins the turn. If several active players begin and end qualified calls simultaneously, the round is a draw and the next card is placed on top of it (and the winner of that round wins the entire discard pile).

# Variants
We tried a variant where each player is dealt a “match card”: if the top card matches the match card’s suit, a qualifying card *for that player* must match the suit instead of differ from it’s color; and if the top card matches the match card’s rank, a qualifying for that player must match the top card’s rank instead of differing from it.

For example, if player one’s match card is a 9♠, and a 9♡ is dealt, player one must call a 9♡ or 9♢ to win the round (but player two cannot call a nine, unless player two’s match card is also a nine). If player one’s match card is a 9♠ and a K♠ is dealt, player one must call an A♠, J♠, or Q♠ to win.

This variant was intended to keep the game from getting too easy after we’d played it for a while and therefore presumably gotten better at it. It turned out to be unnecessary. Presumably there’s a [practice effect](http://en.wikipedia.org/wiki/Power_Law_of_Practice) eventually, but in our limited experience the game was actually harder the second time we sat down for it.

# Origin
Stroop is named after the [Stroop Effect](http://en.wikipedia.org/wiki/Stroop_effect). I made it up last weekend after showing the kids [GOPS](http://en.wikipedia.org/wiki/GOPS), and we played it over the weekend.
