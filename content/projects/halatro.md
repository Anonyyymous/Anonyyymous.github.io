+++
title = "CS141 coursework 1 - Halatro"
description = "My submission for my module CS141 - coursework 1"
[extra]
status = ""
languages = "Haskell"
technologies = ""
image_url = "images/halatro.png"
image_alt = "halatro-alt"
link = ""
+++
The first coursework for my module CS141 - Functional Programming, was inspired by the hit gambling roguelike Balatro. The coursework involved programming a simplified* backend for such a game, which must take a possible hand of cards, and calculate the score associated with any poker hand within that set of cards.

Finally, we used this information to create a bot to play the game, trying to maximise the score. Since the player can choose to play or discard a hand of up to 5 cards, I chose to hunt for flushes, due to their high score yet simplicity to optimise for.

It is worth noting that extra credit was given for any fun/unique ideas that involved playing around with the pre-written code. In my case, I gained 2 marks for adding a specific card to the default deck, in reference to a meme from the original Balatro.

Funnily enough, the presence 161 of clubs made flushes on average 110 points more valuable, with a normal run netting around 411 points.


*I say simplified, because the original game has many card modifiers/effects, that this coursework entirely ignored.
