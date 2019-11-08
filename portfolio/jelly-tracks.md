---
layout: portfolio
title:  "Jelly Tracks"
type: portfolio
priority: front-page
excerpt: "A rhythm puzzle game prototype created as an exploration of the rhythm game genre."
video-url: "Z2Q3fOFJJh4"
thumbnail-url: "portfolio/jelly_thumbnail.gif"
tags: [school, game]

---

**Role:** Designer, Programmer  
**Duration:** 3 weeks  
**Platform:** PC  
**Tools:** Unity   

<hr />

## Contributions
* Designed and documented game over multiple iterations
* Designed puzzle levels
* Programmed main gameplay mechanics and beatmapping system for designers
* Conducted playtesting, crafting and implementing gameplay changes based on playtest feedback

Jelly Tracks is a rhythm puzzle game, developed as part of the [Jam Session](https://etc.cmu.edu/projects/jam-session) project at the ETC. You can play it [here](https://jamsession.itch.io/jelly-tracks).

---

## Game Rules
Players fire red projectiles from the left and blue projectiles from the right.
Enemies can only be destroyed by the appropriately colored projectiles.
Purple enemies can only be destroyed by being hit by both a red AND a blue projectile on the same beat.
Some enemies move after being hit.

If all enemies aren’t destroyed within the time limit, the enemies respawn and the time limit resets.
Players are scored by how many projectiles they take to complete the puzzle. The fewer projectiles, the better.

---

## Design Challenges  
The biggest challenge we had over the course of developing Jelly Tracks was trying to identify what kind of game it wanted to be.

Originally, it was a cooperative puzzle game with no time limit, where one player controlled the red projectiles while the other controlled the blue ones. However, we realized this diminished the puzzle aspect of the game -- instead, it seemed more like a cooperative action game where the main point of the game was to coordinate with your partner, rather than to act according to the rhythm.

Including the timed mode and making the game single-player only was a step in the direction of making it more of a hardcore puzzle. Now, players have to carefully plan and coordinate their actions so they can execute a choreographed solution to the puzzle before the time runs out. To prevent players from just sending out projectiles on every beat, we score players by the number of projectiles they use to complete the level -- the fewer, the better.

An interesting thing to note is that any standard level (without moving enemies) can be completed within an 8-beat time limit, because of the size of the board (8 beats long).

---

## Development Process

I scripted a level editing system that read CSV files to level assets that were loaded into the scene upon level selection.

![](/images/portfolio/JellyTracks_LevelParser.PNG) ![](/images/portfolio/JellyTracks_LevelData.PNG)
