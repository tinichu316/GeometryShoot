# Geometry Shoot
##### A Game by William Wang
## Current State
As of September 2 (BETA 1.5), the game features upgrade saving, 6 unique enemies, and 30 waves.

Future updates include adding the remaining 20 waves along with an ending, implementing the final boss, King Cylinder, fixing some bugs, and adjusting balance with upgrades and enemy stats.

## Introduction
Geometry Shoot is a top down, arcade-style shooter that pits the player against an increasing onslaught of geometric shapes with distinct and unique AI, patterns, and mechanics. In total, there are 7 enemies ranging from the humble triangle to the mighty octagon. The goal is to defeat enough enemies to upgrade your character in order to eventually defeat the 50th wave, consisting of the deadliest shape of all: King Cylinder.

## Inspiration
Undoubtedly, Geometry Shoot takes inspiration from classic arcade games such as Asteroids as well as Geometry wars in both gameplay and theme. It also incorporates minor elements of Edwin Abbott Abbott’s book, Flatland: A romance of many dimensions. In particular, shapes in Geometry Shoot are ranked in increasing order of difficulty by their number of polygonal sides and each shape has distinct mechanics inspired from Geometry Wars. Moreover, the idea of an ever-shrinking arena was adopted in part from Player Unknown’s Battlegrounds to encourage the player to defeat each wave as quickly as possible, rather than kiting the enemies around and using bombs to defeat them all at once. The circle is designed to force the player to either purchase upgrades to increase their wave clearing speed or to improve their own skill to dodge enemies in such a small space.

## Development
The game itself was developed in C# using the Unity Engine over the course of a couple weeks. Although rudimentary, the game serves more as a learning exercise and an exploration into the Engine rather than as a decisively addicting arcade shoot ‘em up. Though developing this game, I have not only gained increased knowledge of the use and application scripting elements such as Quaternions, Coroutines, GUI, C# Dictionaries, and Classes, but I have also practiced game design, balancing, scheduling, and scoping.

## Future Updates
If I were to develop this game further, I would prioritize a true reincarnation system in which, after wave 50, the player continues to wave 51 in which the enemies are considerably tougher. Another possibility is to include a sort of AI director system, in which the enemies in each wave would be spawned randomly by first classifying each enemy’s relative difficulty level, then procedurally selecting groups of enemies based on their total difficulty rating. It would also consider the player’s performance in each wave, and increase or decrease the next wave’s difficulty rating as required. This feature, however, has been cut from the current version of the game as it was too much about wondering whether or not I could program the feature, rather than considering whether or not I should.

## Controls

The controls for Geometry Shoot are relatively simple.
* WASD: Move
* Left click: Shoot
* ‘P’ or ‘G’: Shop
* Space bar for bomb (destroys enemy bullets)
* Upon collision with an enemy, you take damage equal to their current health
* Arena shrinks at a constant rate. The wave automatically advances once all enemies are defeated
* Green and Beige ovals are health and bomb packs.
