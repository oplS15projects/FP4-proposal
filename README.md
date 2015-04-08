# FP4-proposal
Project Proposal is due 2015-04-08 at 8am

# Project Title: Data Structure GUI
### Problem Statement
The problem that I am trying to solve is the difficulty in visualizing data structures in Scheme. This is particularly important for programmers who are new to Scheme. In order to really understand what is happening behind the scenes, programmers need a picture of the structures they are working with. Drawing these structures is tedious and error prone. I propose that creating a tool to display and edit data structures graphically would provide a faster and more accurate way of introducing data structures in Scheme.

### Problem Analysis
I will use several approaches from class to solve this problem. The first is abstraction. My goal for this project is to provide a simple method for entry-level users to load, view, edit, and save a data structure. This means using abstraction to shield the inner complexities of the solution. The second approach is building a solution up from smaller components. Each diagram is built up of smaller drawings including a node diagram, terminal node diagram, data block, and various arrows. Based on the the tools Scheme provides to manipulate data structures, my third approach will be using high order procedures such as map and filter to edit indiviual elements.

### Data set or other source materials
I am not using any starting materials other than the Racket GUI and Racket Drawing toolkits. The Racket GUI toolkit will be used to create the frame for the application and handle user interaction. The application frame will make calls through call-backs to the Racket Drawing tool-kit. Button clicks will trigger different drawing functions to display the data structure.

### Deliverable and Demonstration
At the end of the project period, I will have a simple application to load a single data structure, draw it, provide a way to edit the data in each element, and save it. This will occur through the use of a grid of interchangable diagram pieces based on a supporting data table. Exact implimentation details will be available as different challenges are encountered and overcome. For example, the grid approach is subject to collisions, meaning a structure trying to store two different elements in the same grid cell. Solutions to this and similar problems will ultimately determine the look, feel, and extended capabilities of the finished product. Regardless of the implimentation, in a live demo it will allow users to load, view, edit, and save a data structure. The soultion will be very interactive as the user will be manipulating the data and then saving it.

### Evaluation of Results
I will know if I am successful if displaying the data structure in Racket reflects the changes made in the GUI. For example:
```
(define a (list 1 2 3))
(data-editor a) //Display app
//User changes '3' to '4'
//User saves and exits
a  //Prints '(1 2 4)
```

## Work Plan and Schedule
I plan on breaking the project up into three parts. The first part is creating the supporting procedures and algorithms to facilitate drawing and storing data. This is the core of the project. Once these are established, the second part of the project is creating the high order procedure to draw the structure and re-save the structure. Once these components are in place, the third part of the project will be adding GUI support. In this stage I will create buttons and assign call-backs. 

### First Milestone (04-13)
* Completed diagram components
* Drawing procedures for components
* List of defined steps for drawing
* List of defined steps for saving
* Collision algorithm code

### Second Milestone (04-21)
* Completed drawing algorithm code
* Completed saving algorithm code
* At this point, a data structure should be completely drawable in the Racket
 
### Final Deadline
* Completed GUI prototype using the procedures and algorithms above
* User documentation

## Group Responsibilities
I will be working alone on this project and completing all the necessary code.

## Sample diagrams
https://drive.google.com/folderview?id=0B7j4TU2jQ5KxcWF5Z1ZTbVQ2Q1k&usp=sharing

## Proposal Presentation Link
https://docs.google.com/presentation/d/13hk-3AIIiUzXvLPeod1FAFwjMrDfpLaQEIQkS0LslM4/edit?usp=sharing

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/
