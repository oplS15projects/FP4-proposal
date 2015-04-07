
# Project Title: 2D Side-scrolling Game in Racket (maybe think of a better name?)
### Problem Statement
* An attempt to create a 2 D Side Scrolling game with the 2htdp/universe library. When using the 2htdp/univese library we manipulate what are called “WorldState”s; These “WorldState”s represent the current state of the program and in our program also choose which maps are to be drawn on the screen. The “big-bang” procedure drives the entire program around so that we can have an interactive product; “big-bang” expects us to hand procedures to it that will handle creating new “WorldState”s, key-handlers, and draw procedures. 
* Therefore, we need to handle drawing the map, player movement, collisions, etc. so that "big-bang" will know what to do with it when it comes to the next state, every "tick" we have to update all the sprites and map.

### Problem Analysis
For this project we will have to make use of higher order procedures such as foldr, map, filter, etc. for when we transition between world states and when we are redrawing the map/level. We will also have to seperate our code into sprites, entities, maps, and our procedures which we hand to "big-bang"; therefore we are building an abstraction barrier between our helper procedures and all of our game data.

### Data set or other source materials
All of our sprites will have to come from another image file which will be saved locally within the game directory.

We plan to have a feature which will allow a user to save their current status in the game to a file which they can later read from to resume their progress.

### Deliverable and Demonstration
At the end we should have a fully functional side-scrolling game that will be interactive via keyboard controls. It should allow the user to either start a new game or continue an old one. The user can then play through the various levels of the game in order to beat it.

### Evaluation of Results
We are successful if our game has fully functional user interactivity so they can play the game from start to finish, the map and sprites are drawn successfully throughout the entire game, all the sprites and entities are handled correctly regarding collisions and state, the map is drawn in a way that allows side-scrolling, and we have a functional save/resume system.

## Work Plan and Schedule

The general plan is to first construct the framework for the game so that we can have key-strokes made in a way that feels comfortable to the user, the side-scrolling feature implemented, handling the state of sprites so we know when they are colliding with something else (wall or enemy), and the effective drawing of the map, player, and enemy.

### First Milestone (04-13)
I think for the first milestone we should at least have all the basic things accomplished

### Second Milestone (04-21)
What exactly will be turned in on this day? 

## Group Responsibilities

### Patrick Lehane
Factoring in momentum on the main character can be something

3. There's also enemy patterns to program. Like, we could have it like in Mario where  some enemies walk off ledges and some enemies don't.
4. I also think we should have some sort of experience and leveling up system if only to further justify having a save system.

### Andrew Gabriel

1. I would like to have the screen actually scroll properly (like, not just going to the next part when you reach the side of the screen).
2. Programing the jumping might also prove to be difficult.

5. Programming a pause menu is another big thing. In the pause menu could be weapons and an option to save.

## Proposal Presentation Link
insert your google presentation public link here, so with one click it will open up in the browser and you can present.

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/
