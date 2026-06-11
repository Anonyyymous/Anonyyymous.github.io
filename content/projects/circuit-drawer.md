+++
title = "Godot logic gate sim"
description = "A logic gate simulator, made in Godot. Paused to avoid Godot-burnout while doing a module on it"
[extra]
status = "Paused"
languages = "GDscript"
technologies = "Godot"
image_url = "images/circuit-drawer.png"
image_alt = "logic-sim-alt"
link = ""
+++

My 2nd project in Godot, this is a boolean circuit drawer, inspired by <a class="text-1 ul" href="https://sebastian.itch.io/digital-logic-sim">Digital Logic Sim by Sebastian Lague</a>.

<!-- Once it reaches the milestone of stateful components, I aim to try and create a simple computer inside it, as a testiment to it's power. -->

As of writing, it has the capacity for memoized stateless components, meaning a 1-bit adder could be saved and treated as a single component, though a flip flop (or anything that relies on some internal state) would not yet work.


<!-- From that, I will make a simulator for that computer in C++, and attempt to make a low level language out of its base instruction set. -->
