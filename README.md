# Project Title: 2D Top-Down Game


### Problem Statement
Idle hands could be considered a "problem" of sorts, and times of leisure are a necessary requirement in life. Therefore, this proposal is for a game. Games are inherently interesting, both from programming and play perspectives. Hopefully, mine will be good enough as to not tarnish this quality.

The game will be two-dimensional, with a top-down perspective. Its genre is a bit hard to pin down, but in broad terms it will have casual action, collection, and maze-like elements. The goal of each level is to collect all the keys. Once all the keys are collected, the door to the next level can be opened. Enemies can be avoided or eliminated.


### Problem Analysis
Layers of abstraction will be a must. Elements of the game will be broken up into a number of structures (classes), with both public and private procedures in order to have some semblance of decent organization and OOP. A number of keywords learned throughout this term will be used. The board will most likely use a list, and in order to handle the elements in that list, keywords such as map and filter will probably be used. Some of the classes will probably inherit from a base class, so creating some general-purpose functions in the base class could prove beneficial in keeping code complexity to a minimum.


### Data set or other source materials
There are no plans to use any source materials outside of Racket libraries and documentation. Any images will be simple and be made specifically for this project. If an audio file is added, it will be something publicly available, but one hasn’t been chosen yet. This program will most likely be reading in level data from a file, but that content will also be created without any currently existing data. It should be noted that some elements of this game are loosely based on my memory of an old MS-DOS game. The name and whereabouts of that game are presently unknown.


### Deliverable and Demonstration
Optimistically, the game should be demonstrable, interactive, and playable at the end of the due date. In order to properly explain what it should be doing come due date, I should explain the game itself. Unfortunately, this game isn't a popular or commonly known game (such as checkers or Risk) so a detailed description of the game is required. A description of each element of the game is as follows:

####Board
First, there is a board. The board consists of a rectangular grid. The size of this grid could potentially change from level to level, but for now it will remain a fixed size for the sake of time. Each cell on the grid can be occupied by any one of six objects - a player, an enemy, a wall, a block, a key, or a door. The outermost cells are always occupied by walls, in order to keep the player contained. The initial contents of the remaining cells are determined from layouts read in from a file (to make level editing easy). A general graphical mockup looks like this:

![board](https://cloud.githubusercontent.com/assets/11641731/7040362/666b2abc-dd9c-11e4-947c-7d2c28ef6cb9.png)

![legend](https://cloud.githubusercontent.com/assets/11641731/7040369/81dd06ee-dd9c-11e4-8177-8e92c1705377.png)

####Player (green) 
A player can move left, right, up, or down. These are its behaviors with other objects:
- Contact with a block (blue) has two cases: 
- If there is empty space, a key, or an enemy on the other side of the block, the block will move, and the player comes to occupy the block’s previous space.
- If that block can’t be moved (i.e. there is a wall or another block on the other side), then the block will break.
- Contact with an enemy (red) kills the player. It resets the level.
- Contact with a wall (gray) stops the player. The player can’t move or occupy the space of the wall.
- Contact with a key (yellow) picks up the key. Key disappears, player occupies the key’s previous space
- Contact with a door (purple) does nothing if all keys haven’t been collected – changes the level if they have.

####Enemy (red)
An enemy can move left, right, up, or down. These are its behaviors with other objects:
- Contact with a stationary block (blue) stops the enemy. The enemy can’t move or occupy the space of the block.
- Contact with a moving block (blue) kills the enemy. The enemy disappears and the block passes through the enemy’s previous space.
- Contact with another enemy (red) stops the enemy. The enemy can’t move or occupy the space of the other enemy.
- Contact with a player (green) kills the player. It resets the level.
- Contact with a wall (gray) stops the enemy. The enemy can’t move or occupy the space of the wall.
- Contact with a key (yellow) does nothing. Enemy occupies the same space as the key, but the key doesn’t go away. 
- Contact with a door (purple) does nothing. Enemy occupies the same space as the door.

####Wall (gray)
A wall can’t move, and can’t be moved. Nothing can occupy the same space as a wall.

####Block (blue)
A block only moves when a player pushes it. It will move in the direction that it is pushed, in a straight line, until it hits a wall (gray) or another block (blue). These are its behaviors with other objects when the block is in motion:
- Contact with another block (blue) stops the block and the block occupies the last space before overlap.
- Contact with a player (green) kills the person. It resets the level.
- Contact with an enemy (red) kills the enemy.
- Contact with a key (yellow) does nothing. Block occupies the same space as the key, but the key doesn’t go away. 
- Contact with a door (purple) does nothing. Block occupies the same space as the door.

####Key (yellow)
A key can’t move, and can’t be moved. Enemies, Players, and Blocks can occupy the same space as the key, but the key can only be picked up by a player.

####Door (purple)
A door can’t move, and can’t be moved. Enemies, Players, and Blocks can occupy the same space as the door, but the door can only be opened by a player. The player can only open the door if it has all the required keys.


### Evaluation of Results
The project will be considered a success if it is playable with most of the goals being met. Levels of success would be something along the lines of:

Minimal Success:
- Menu bar exists but doesn’t do anything
- One level exists
- No sound
- Player works as described
- Enemies exist and can kill player, but don’t move
- Walls work as described
- Blocks don’t exist
- Keys work as described
- Door opens for the correct amount of keys, but doesn’t lead to the next level
- No movement animations

Adequate Success:
- Menu bar exists and works (with possible fullscreen option)
- Simple music only
- Multiple levels exist
- Player works as described
- Enemies work as described, and use rudimentary movement.
- Walls work as described
- Blocks work as described
- Keys work as described
- Door works as described 
- No movement animations

Shocking, Near-Impossible Success:
- Menu bar exists and works
- Varying music and sound effects
- Multiple levels exist
- Multi-player (competitive or co-op) functionality exists and works
- Throw in networked LAN multi-player, just for good measure
- Enemies work as described, and use intelligent pathfinding movement.
- Walls work as described
- Blocks work as described
- Keys work as described
- Door works as described 
- Movement animations work

Ultimately, the final level of success will probably be a mix of the minimal and adequate success levels. Some of the functionality in the third level would be great to implement (like pathfinding movement of enemies), but there probably isn’t time.


## Work Plan and Schedule
Order of implementation will be something along these lines:

1. Window frame
2. Add a canvas to the frame with key listener
3. Add a menu bar to the frame without functionality
4. Make an external level file
5. Add file reading capability
6. Add a player in the proper location that can respond to key commands
7. Add walls
8. Add a perpetually open door that resets the level upon player entering.
9. Add keys, make the player pick up keys, and maintain a key counter.
10. Make the door respond to the key counter accordingly.
11. Add non-moving enemies
12. Add basic music
13. Give enemies rudimentary movement
14. Add sliding blocks
15. Add more levels

This order doesn’t include any of the bigger goals included in the third level of success described previously.


### First Milestone (04-13)
- Window frame
- Add a canvas to the frame with key listener
- Add a menu bar to the frame without functionality
- Make an external level file
- Add file reading capability
- Add a player in the proper location that can respond to key commands
- Add walls


### Second Milestone (04-21)
- Add a perpetually open door that resets the level upon player entering.
- Add keys, make the player pick up keys, and maintain a key counter.
- Make the door respond to the key counter accordingly.
- Add non-moving enemies
- Add basic music
- Give enemies rudimentary movement

Then, for the final turn in, hopefully the sliding blocks and more levels will be added. 


## Proposal Presentation Link
[Click Here For Presentation]: https://docs.google.com/presentation/d/1d_P1R_vQh7qjO16h9aUuUlwRHRxbdTPqipOFfdZUeWE/edit?usp=sharing

