---
layout: portfolio
title:  "Gang Beats"
type: portfolio
excerpt: "A rhythm-fighting game prototype created as an exploration of the rhythm game genre."
video-url: "P2qPPJ0Ww-A"
thumbnail-url: "portfolio/gangbeats_thumbnail.gif"
tags: [school, game]
---

**Role:** Designer, Programmer  
**Duration:** 3 weeks  
**Platform:** PC  
**Tools:** Unity   

<hr />

## Contributions
* Programmed beat-matching system, game mechanics, input selection
* Iterated on and documented changes to game design
* Conducted playtesting and data collection

Gang Beats is a competitive multiplayer rhythm fighting game for 2 to 4 players, developed as part of the [Jam Session](https://etc.cmu.edu/projects/jam-session) project at the ETC. You can play it [here](https://jamsession.itch.io/gang-beats).

<hr />

## Design Goals
We realized that there were many multiplayer rhythm games already existing, but few of them involve direct interaction between players, and instead focus on who can get the highest score. In Gang Beats, our goal was to have a player’s rhythmic accuracy negatively impact other players, which would increase their own chance of winning the game.

We determined that the main mechanic of the game would be fighting-game-esque: players would be able to damage other players based on how accurately they were hitting the button to the beat.

## Design Challenges
One of the most pressing issues we noticed was when trying to determine which player is more accurate than the other. We couldn’t resolve multiple players’ relative accuracy to each other at the moment of input, because that privileged early inputs and ignored any late inputs. I decided that the game should resolve conflicts on the next beat instead, which not only eliminated the problem, but also provided an interesting accent to the game’s music track when sound effects were incorporated.
