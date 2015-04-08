# FP4-proposal
Project Proposal is due 2015-04-08 at 8am

# Project Title: Lambda (λ)
### Problem Statement
Regular computer calculators are clunky and aren't expressive enough. Let us break free from that and create a mathematical engine that is simple while being expressive. 

* The current problem we see with most computer calculators is that the user needs to put everything into the calculator one    digit at a time, but why not type it in just as if you were writing it on paper.
* This problem is interesting because looking at it there is the possibility to create a powerful tool that can be easily       expanded due to the ability to create high level functions and layers of abstraction in the racket environment.

### Problem Analysis
* We plan to make different layers of abstraction so that the code can be very easily built on.
* We also plan to build objects that allow us to link the key words to their respective procedures.
* The high order procedures that we have covered in class such as filter and map will be used to handle searching and limiting   the data structures.

### Data set or other source materials
* The only data that is needed for this program is the data that is given by the user.
* The data that the user has supplied to the program is then sent through a parser that breaks it apart and passes down to the handler to be processed.

### Deliverable and Demonstration
* The goal is to have a program that is simple , powerful and easy to build upon. Simple in terms that it allows the user to enter their expression without the need of worrying about what buttons to press or what order it is needed to be entered. The power of the program will come from the ease at which the program can be expanded on to add new math functions.   
* During the demonstration the goal is to let the programs ease of use be the focal point. To do this people will be able to come to the system and take it for a spin by trying out their favorite math expression.  
* Also at the demonstration, an example of how to add functionality to the program will be shown  so that users can get a sense of how simple it is for them to build on the platform.

### Evaluation of Results
* We are able to input controlled math expressions that have known results that we have calculated by hand.
This gives us the ability to check the validity of the computing code.
* The plot functionality can be a test by giving expressions to both the code and a graphing calculator to check
and make sure both sources match.
* The parsing of user input will be able to be tested by seeing if the proper key words are applied to expression
in the proper order.


## Work Plan and Schedule
The work for the project will be split equally between all three members. The schedule will be made up of our own mini milestones. This will allow us to make sure each component is progressing so that it will meet the larger milestones that have been put in place. 

|   | task | state |
|---|------|-------|
| 1 | GUI | in progress |
| 1.1 | Create GUI Skeleton | in progress |
| 1.2 | Link GUI to  | not started |
| 1.3 | Finalize GUI| not started |
|2| User Input Parser | in progress |
| 2.1 | Basic Parser Skeleton  | in progress |
| 2.2 | Plot/Graph Keyword Support Added  | not started |
| 2.3 | Derivative Keyword Support Added  | not started |
| 2.4 | Simplify Keyword Support Added  | not started |
| 3 | Keyword Linking Table | in progress|
|4| Keyword Procedures | not started |
|4.1| Plot/Graph Keyword Procedure | not started |
|4.2| Derivative Keyword Procedures | not started |
|4.3| Simplify Keyword Procedures | not started |


### First Milestone (04-13)
* The complete GUI layout will be complete and ready to be hooked to the back end processing code.
* The parsing of user input will be complete and functional.
* The lookup table needed to link the user input to the processing procedures will be complete.

### Second Milestone (04-21)
* Create procedure needed for the plot/graph keyword.
* Create procedure needed for the derivative keyword.
* Create procedure needed for the simplify keyword.
* Add more keywords/procedures as long as time permits.

## Group Responsibilities
Below is a breakdown of what each person is in charge of during the project. This will be added to as we add more features to Lambda ( λ )

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
* Design a user friendly  GUI for Lambda ( λ ) providing an input window 
* Provide Compute Button for the output of the processed procedure
* Provide a Canvas where the output will be displayed
* Will also give a hand with the parser for the user input.

##### Second Milestone:
* Creating procedures for keywords

## Proposal Presentation Link
[**Lambda**][Goat-Lambda]

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/
[Goat-Lambda]:https://docs.google.com/presentation/d/16Rdq3k_QRaX8tFefR1sQdzLVkyQ6EENQuHVDwc9Axak/edit#slide=id.gad3b04a0b_0_7


