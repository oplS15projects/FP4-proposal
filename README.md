# FP4-proposal
Project Proposal is due 2015-04-08 at 8am

# Project Title: Goat Lambda
### Problem Statement
Our regular computer calculators aren't expressive enough and Racket is an expressive language. We can use Racket and its expressive sytax to create a calculator that takes in an equation and analyzes it, simplifies it, and graphs it, all in its own contained GUI.

### Problem Analysis
* We plan to make different lays of abstraction so that the code can be very easily build on.
* We also plan to build objects that allow us to link are key words to there perspective procedure.
* The high order procedures that we have covered in class such as filter and map will be used to handle searching and limiting are data structures.

### Data set or other source materials
* The only data that is needed for this program is the data that is given by the user.
* The data that the user has supplied to the program is then sent through a parser that breaks it apart and passes down to the handle to be processed.

### Deliverable and Demonstration
* The goal is the have an program that is simple and powerful and a ease to build upone. Simple in terms that it allows the user to enter there expression without the need of worring about what bottons to press or what order it is needed to be entered. The power of the program will come from the ease at which the program can be expanded on to add new math function.   
* During the demonstration the gaol is to let the programs ease of use be the focal point. To do this people will be able to come to the system and take it for a spin by trying out there favorite math expression.  
* Also at the demonstration a example of how to add functionality to the program will be shown  so that users can get a sense of how simple it is for them to build on are platform.

### Evaluation of Results
* We are able to input controlled math expressions that have known results that we have calculated by hand.
This gives us the ability to check the validity of are computing code.
* The plot functionality can be test by giving expressions to both are code and a graphing calculator to check
and make sure both sources match.
* The parsing of user input will be able to be tested by seeing if the proper key words are applied to expression
in the proper order.


## Work Plan and Schedule
The work for the project will be split equaly between all three members. The schedule will be made up of are own mini milestones. This will allow us to make sure each component is progressing so that it will meet the larger milestones that have been put in place. 

In this general plan, and in the deliverables below.

### First Milestone (04-13)
* The complete GUI layout will be complete and ready to be hooked to the back end processing code.
* The parsing of use input will be complete and functional.
* The look up table needed to link the user input to the processing procedures will be complete.

### Second Milestone (04-21)
* Create procedure needed for the plot/graph keyword.
* Create procedure needed for the derivative keyword.
* Create procedure needed for the simplify keyword.
* Add more keywords/procedures as long as time permits.

## Group Responsibilities
Here each group member gets a section where they, as an individual, detail what they are responsible for in this project. Each group member writes their own Responsibility section. Include the milestones and final deliverable.

### Joshua Caravetta
##### First Milestone:
* Will complete the table needed to link the user input to the back end processing procedures.
* Also will help Brian on completing the parser for the user input.

##### Second Milestone:
* Creating procedures for keywords

### Brian Carlson
##### First Milestone:
* Parser for user input (extracting procedure keywords and mathematical expression)

##### Second Milestone:
* Creating procedures for keywords

### Norman Mutunga
##### First Milestone:
* Design a user friendly  GUI for Goat Lambda ( λ ) providing an input window 
* Provide 2D and 3D Buttons for the output of the processed procedure
* Provide a Canvas where the output will be displayed

##### Second Milestone:
* Creating procedures for keywords

## Proposal Presentation Link
[**Goat Lambda**][Goat-Lambda]

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/

[Goat-Lambda]:https://docs.google.com/presentation/d/16Rdq3k_QRaX8tFefR1sQdzLVkyQ6EENQuHVDwc9Axak/edit#slide=id.gad3b04a0b_0_7
