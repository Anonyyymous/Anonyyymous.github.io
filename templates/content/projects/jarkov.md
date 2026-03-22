+++
title = "C++ markov babble api"
description = "A C++ text-based, markov chain, managed in a terminal, and made public with a custom HTTP server"
[extra]
status = ""
languages = "C++"
technologies = ""
image_url = "images/cpp-markov-chain.png"
image_alt = "markov-chain-output-alt"
link = "https://github.com/Anonyyymous/cpp-markov-chain"
+++

My gateway into C++, in this project I set out to create a terminal-trainable/managable markov babble (exclusively word-based markov chain) generator, and give it the gift of the internet, in the form of a HTTP server. The server uses a pointer to a function that takes a *HTTPRequest* and returns a *HTTPResponse*, so it could in theory be used for something that isnt a markov chain, but doing so would mean separating the scripts (not hard, just a bit of effort), and using it instead of a much better supported option. In short, don't.

I attempted to treat it as an open project, meaning it needed some documentation and testing. Unfortunately it only works on linux, as I chose to familiarise myself with the bare linux sockets api, instead of something like boost. The tests test the program's ability to create a new model, save it, load/host it on the http server, and respond to queries through a python script.

Documentation for using the program yourself (again, only on linux) is on the github page.
