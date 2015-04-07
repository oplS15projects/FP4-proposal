
# Project Title: 2D Side-scrolling Game in Racket (maybe think of a better name?)
### Problem Statement
* An attempt to create a 2 D Side Scrolling game with the 2htdp/universe library. When using the 2htdp/univese library we manipulate what are called “WorldState”s; These “WorldState”s represent the current state of the program and in our program also choose which maps are to be drawn on the screen. The “big-bang” procedure drives the entire program around so that we can have an interactive product; “big-bang” expects us to hand procedures to it that will handle creating new “WorldState”s, key-handlers, and draw procedures. Therefore, we need to handle drawing the map in a way so that our game can perform as a side-scroller.
*  (ALSO collisions!)
* something about tiles 

### Problem Analysis
* We will likely have to create a few wrapper procedures to handle key-handling and world state.
* Make use of higher order procedures from class such as foldr, map, filter, etc.
* ????
* (using state variables to save state? or file reader ? )

### Data set or other source materials
Creating a file to save state ?
Pulling sprites from .png image files ? (either from online or ones that you made)

### Deliverable and Demonstration
At the end we should have a fully functional side-scrolling game that will be interactive via keyboard controls. It will have a level system where a user can save their progress by level.

(I am not sure how we are going to run the program; we are going to re run just with DrRacket ) ?

### Evaluation of Results
We are successful if we have an end product that…

* allows user interactivity so they can play the game start to finish
* the game successfully handles collisions, keystrokes, and drawing new maps
* the game’s save features works successfully

## Work Plan and Schedule
The general plan is to first construct the framework for the game so that we can have key-strokes handled effectively (no lag), the side-scrolling feature implemented, handling the state of sprites so we know when they are colliding with something else (wall or enemy), and the effective drawing of the map, player, and enemy.

### First Milestone (04-13)
>I think for the first milestone we should at least have all the basic things accomplished

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
