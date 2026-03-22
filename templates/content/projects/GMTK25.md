+++
title = "GMTK25 - Loops"
description = "My submission for the GMTK25 game jam, and first time using Godot"
[extra]
status = ""
languages = "GDscript"
technologies = "Godot"
image_url = "images/magical-girl-vs-the-horros.png"
image_alt = "gmtk25-game-jam-alt"
link = "https://anonyym0us.itch.io/magical-girl-vs-the-horrors"
+++

## The Premise

The theme for the 4-day GMTK25 game jam was one simple word - Loops.
In a mix of my own curiosity, and preparaton for a university module I would be taking the next year, I endeavored to learn I needed about Godot and gdscript - while the jam was going.

A questionable choice, and one that led to a lot of intentionally this-is-such-an-awful-way-of-doing-this-but-it-just-needs-to-work decisions, more than usual in a game jam.

The game idea had to be kept relatively simple, so I teamed up with the same artist friend as in GMTK24, and we set out to create something once again a little silly.
We arrived at the idea of a vampire survivors clone, where the player projectiles **loop**ed. We agreed that the idea of a magical girl, who's attack animations are just vogue-like poses, fighting eldrich horrors beyond our comprehension would be both fun for her to draw, and for me to bang my head against when the bugs reared their ugly heads.

Overall, it was definitely an interesting way to get to grips with Godot, so I can't say I regret it.

## Gameplay

I haven't played vampire survivors, so I can't really comment on how close we got - though one not-at-all-biased comment on the itch page suggests that we far surpassed the original.

At the end of each wave of enemies, the player can get a new weapon. Each weapon has its own trajectory (either a <9 sided polygon, a line, or a circle), damage, speed, and recharge time. Additionally, weapons can have extra features, such as destroying enemy projectiles, or being cast over your cursor, instead of originating from the player.

When a weapon is 'cast', the projectile enacts it's trajectory. The distance of the player's cursor can be used to decrease the range of the weapon, making aiming a little easier. This also decreases the cooldown, though this means some high-damage weapons can be spammed at close range, and if one of them happens to destroy enemy projectiles on hit, gg you win.