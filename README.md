# FP4-proposal
Project Proposal is due 2015-04-08 at 8am

# Project Title: Data Editing GUI
### Problem Statement
The problem that I am trying to solve is the difficulty in visualizing data structures in Scheme. This is particularly important for programmers who are new to Scheme. In order to really understand what is happening behind the scenes, programmers need a picture of the structures they are working with. Drawing these structures is tedious and error prone. I propose that creating a tool to display and edit data structures graphically would provide a faster and more accurate way of introducing data structures in scheme.

### Problem Analysis
I will use several approaches from class to solve this problem. The first is abstraction. My goal for this project is to provide a simple method for entry-level users to load, view, edit, and save a data structure. This means using abstraction to shield the inner complexities of the solution. The second approach is building a solution up from smaller components. Each diagram is built up of smaller drawings including a node diagram, terminal node diagram, data block, and various arrows. Based on the the tools Scheme provides to manipulate data structures, my third approach will be using high order procedures such as map and filter to edit indiviual elements.

### Data set or other source materials
I am not using any starting materials other than the Racket GUI and Racket Drawing frameworks. The Racket GUI library will be used to create the frame for the application and handle user interaction. The application frame will make calls through call-backs to the Racket Drawing library. Button clicks will trigger different drawing functions to display the data structure.

### Deliverable and Demonstration
At the end of the project period, I will have a simple application to load a single data structure, draw it, provide a way to edit the data in each element, and save it. In a live demo, it will able to do these four things. It will be interactive, the user will be manipulating the data and then saving it.

### Evaluation of Results
I will know if I am successful if displaying the data structure in Racket reflects the changes made in the GUI. For example:
(define a (list 1 2 3))
(data-editor a) -> Display app
;; User changes '3' to '4'
;; User saves and exits
a -> Prints '(1 2 4)

## Work Plan and Schedule
I plan on breaking the project up into three parts. The first part is figuring out how to dynamically draw data structures. This is the core of the project. I have used the Racket Drawing toolkit to draw static shapes, but have not yet found a way to combine them. Once these are established, the The second part of the project is adding GUI support for the basic editing commands. This will be mainly creating buttons and assigning call-backs. 
Explain how you will go from proposal to finished product. Write your general plan here. 
There are three deliverable milestones to explicitly define, below. The nature of deliverables depend on your project, but may include things like processed data ready for import, core algorithms implemented, interface design prototyped, etc. 

You will be expected to turn in code, documentation, and data (as appropriate) at each of these stages, so take care in writing concrete steps for your schedule. 

In this general plan, and in the deliverables below.

### First Milestone (04-13)
What exactly will be turned in on this day? 

### Second Milestone (04-21)
What exactly will be turned in on this day? 

## Group Responsibilities
Here each group member gets a section where they, as an individual, detail what they are responsible for in this project. Each group member writes their own Responsibility section. Include the milestones and final deliverable.

### Susan Scheme
will write the....

### Leonard Lambda
will work on...

## Proposal Presentation Link
insert your google presentation public link here, so with one click it will open up in the browser and you can present.

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/
