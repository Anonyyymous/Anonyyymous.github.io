+++
title = "CS141 coursework 2 - Gridlock"
description = "My submission for my module CS141 - coursework 2"
[extra]
status = ""
languages = "Haskell"
technologies = ""
image_url = "images/gridlock.png"
image_alt = "gridlock-alt"
link = ""
+++
The second coursework for my module CS141 - Functional Programming, involved a custom game created by the lecturer, and making a parser for specifically formatted records of that game, stored in text files.

A much greater jump in depth from the first coursework, the best solution to this one involved heavy use of monads, functors, and state - through the use of monad transformers. Due to poor timetabling and a poor vsc auto-import, my efforts to follow through with this were hamstrung, and the package I was trying to debug for a week was in fact unable to do what I was expecting it to do.

My initial solution passes all tests, if in a little verbose and more object oriented manner, storing and then evaluating turns of the game, rather than evaluating them as I went with state.
