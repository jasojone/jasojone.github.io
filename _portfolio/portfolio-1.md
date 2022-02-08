---
title: "War the card game in C++"
excerpt: "The objective is simple, win all the cards in the deck at all costs. 1<br/><img src='/images/portfoio-War'>"
collection: portfolio
---

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->
In the basic game there are two players, and you use a standard 52 card pack. Cards rank as usual from high to low: A K Q J T 9 8 7 6 5 4 3 2. Suits are ignored in this game.  
Deal out all the cards, so that each player has 26. Players do not look at their cards but keep them in a packet face down. The object of the game is to win all the cards.  
Both players now turn their top card face up and put them on the table. Whoever turned the higher card takes both cards and adds them (face down) to the bottom of their packet. Then both players turn up their next card and so on.
If the turned-up cards are equal, there is a war. The tied cards stay on the table and both players play the next card of their pile face down and then another card face-up. Whoever has the higher of the new face-up cards wins the war and adds all six cards face-down to the bottom of their packet. If the new face-up cards are equal as well, the war continues: each player puts another card face-down and one face-up. The war goes on like this if the face-up cards continue to be equal. As soon as they are different the player of the higher card wins all the cards in the war.  
The game continues until one player has all the cards and wins. This can take a long time.  
Most descriptions of War are not clear about what happens if a player runs out of cards during a war.   
In the event…  
If you do not have enough cards to complete the war, you lose. If neither player has enough cards, the one who runs out first loses. If both run out simultaneously, it is a draw. Example: Players A and B both play sevens, so there is a war. Each player plays a card face down, but this is player B's last card. Player A wins since player B does not have enough cards to fight the war.
