# FP4-proposal
Project Proposal is due 2015-04-08 at 8am

Produce a plan for your final project, and prepare an in-class presentation.

Ask questions, as always, [on piazza!][piazza]

## Written Proposal Instructions

Teams will submit ONE written proposal, with sections that each member has done individually detailing their proposed contributions. The submission will be on github, as a pull request of this very file. Below is a template proposal report.

You should be proposing something that you have high confidence that you can achieve, and the proposal should project that confidence.
The proposal should be no longer than necessary, but long enough to include critical detail. Three pages is appropriate. Diagrams are welcome. 

Remember, you can do some neat [formatting things with Markdown.][markdown]

## In-Class Presentation Instructions
Teams will each deliver an in-class presentation. **Presentations will be Wednesday, April 8** (and Friday, April 10 as necessary). The presentation material is due on April 8 by 9 am for everybody. [See piazza for full schedule.][piazza]

Your team will have two minutes to present. Create presentation with two or three slides. Make the slides in google drive, and share the public-viewable link at the bottom of this report. The day of presentations, I'll have the list of links on the display computer, so each team can simply click their link and begin. 

(Template follows. You may delete this line and all above it. Please edit the following template to create your report.)

# Project Title: [Esc]
### Problem Statement
Racket has a large variety of libraries that focus on the graphical aspect of programming. With that in mind our project will simulate an interactive graphics based game. The player will be dealt with the task of cleverly navigating his way through the playing field as he must avoid being caught by moving enemies and encounter randomly placed obstacles. The most intriguing features to our game is that it will give the user direct interaction and create computer implemented interaction. For example, the user will be given the ability to control his movements (speed?) and the computer will be able to display some interaction as we will be able to implement some basic artificial intelligence to give other objects movement. With the wide range of graphics libraries that Racket provides will make this task possible. 

### Problem Analysis
Our primary focus will be to get all of the game objects to run simultaneously on the playing field. The universe.rkt library, which is a sub-library to the 2HtDP, provides us with a function called ``big-bang`` that will aid us in our objective of placing all the objects in the same universe (playing field). The ``big-bang`` function requires a list of objects as one of it's parameters, which will make us display our knowledge in list manipulation.  We believe the bulk of our project will have to deal with higher order procedures. In order to be able to manipulate all objects on the same universe we will need a vast number of smaller procedures (like movement, collision detection, time tracking, etc.) being linked to one procedure which will be the caller procedure. This will be the main concept we will follow in our implementation. Besides the graphical aspect of our game we will also like to add some gui features. For instance, we would like to keep track of the players time and then be able to display that time to the user. We believe these tasks will present the biggest problems.

### Data set or other source materials
Besides the libraries that we have listed in our Team Declaration assignment, we will not be using any already existing data.

### Deliverable and Demonstration
We expect to have a working and running game to display to the audience. The game will be completely user interactive. We will demonstrate how our game changes (increases in difficulty) as the game progresses. We will also demonstrate the different situations of our game. For example: 

1) How the user can move its playable character with the arrow keys. 

2) How failure occurs when a collison is detected. 

3) A display message with your time. 

### Evaluation of Results
We will consider ourselves successful if we are able to fulfill our goals and task. When we run our game we'll be expecting to have our game objects show movements simultaneously as the game runs, be able to deal with collision detection, and display the total time of the running game.

## Work Plan and Schedule
To achieve the finished product we will need to break down our objective into smaller tasks and goals. First we will focus on having our objects that are displayed on the same universe to move in a fluid motion while avoiding collisions. Then once we accomplish this goal we can implement a way to keep track of the amount of time the game is running, while adding more objects to the universe at certain time intervals. 

### First Milestone (04-13)
* Give the user player control of his movements based on using the arrow keys.
* Give the other game objects movement based on artficial intelligence implementations.
* Be able to detect collisions of objects and stop the simulation when this occurs.
* Finally have all this occur while the objects are placed on the same playing field.
 
### Second Milestone (04-21)
* Be able to keep track of the elapsed time of running the game.
* Once time can be accessed, at certain time intervals place more game objects onto the playing field and give it movement.
* Add small GUI interface which displays a message of success or failure allotted with your elapsed time. 
 
## Group Responsibilities

### Christopher Ly
1) Detect collisions and stop simulation. 

2) Keep track of elapsed time of running the game. 

3) At certain time intervals place more game objects and manipulate its movement. 

### Jerra Khorn
1) Player control using arrow keys. 

2) Giving game objects artificial intelligence 

3) GUI interface     

## Proposal Presentation Link
[presentation]

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/
[presentation]: https://docs.google.com/presentation/d/182K3rDangoqWCpvJP7llnjgyzdIb2QHeRyhOxvDW3L8/edit?usp=sharing
