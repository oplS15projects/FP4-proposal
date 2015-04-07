# FP4-proposal
Project Proposal is due 2015-04-08 at 8am

## Written Proposal Instructions

Teams will submit ONE written proposal, with sections that each member has done individually detailing their proposed contributions. The submission will be on github, as a pull request of this very file. Below is a template proposal report.

You should be proposing something that you have high confidence that you can achieve, and the proposal should project that confidence.
The proposal should be no longer than necessary, but long enough to include critical detail. Three pages is appropriate. Diagrams are welcome. 

## In-Class Presentation Instructions
Teams will each deliver an in-class presentation. **Presentations will be Wednesday, April 8** (and Friday, April 10 as necessary). The presentation material is due on April 8 by 9 am for everybody. [See piazza for full schedule.][piazza]

Your team will have two minutes to present. Create presentation with two or three slides. Make the slides in google drive, and share the public-viewable link at the bottom of this report. The day of presentations, I'll have the list of links on the display computer, so each team can simply click their link and begin. 

(Template follows. You may delete this line and all above it. Please edit the following template to create your report.)

# Project Title: Goat Lambda
### Problem Statement
Our regular computer calculators aren't expressive enough and Racket is an expressive language. We can use Racket and its expressive sytax to create a calculator that takes in an equation and analyzes it, simplifies it, and graphs it, all in its own contained GUI.

### Problem Analysis
* We plan to make different lays of abstraction so that the code can be very easily build on.
* We also plan to build objects that allow us to link are key words to there perspective procedure.

### Data set or other source materials
* There is no other data needed other then the data that the user gives in the form of math expressions at 
run time.

### Deliverable and Demonstration
* At the end of the project we will have a fully functional easy to use gui that allows the used to enter math 
expressions to be solved.   
* At the live demo users will be able to come up to the GUI and take it for a spin putting in math function
and intern get the answer such as when the put in "derivative of x^2" they will get back "2x". This is a 
very simple example but we expect the system to be able to do much more complicated expression at the time
of the demo.

### Evaluation of Results
* We are able to input controlled math expressions that have known results that we have calculated by hand.
This gives us the ability to check the validity of are computing code.
* The plot functionality can be test by giving expressions to both are code and a graphing calculator to check
and make sure both sources match.
* The parsing of user input will be able to be tested by seeing if the proper key words are applied to expression
in the proper order.


## Work Plan and Schedule
Explain how you will go from proposal to finished product. Write your general plan here. 
There are three deliverable milestones to explicitly define, below. The nature of deliverables depend on your project, but may include things like processed data ready for import, core algorithms implemented, interface design prototyped, etc. 

You will be expected to turn in code, documentation, and data (as appropriate) at each of these stages, so take care in writing concrete steps for your schedule. 

In this general plan, and in the deliverables below.

### First Milestone (04-13)
* The complete GUI layout will be complete and ready to be hooked to the back end processing code.
* The parsing of use input will be complete and functional.
* The look up table needed to link the user input to the processing procedures will be complete.

### Second Milestone (04-21)
* Procedures for basic mathematical keywords. Examples: Derivative, Graph, Simplify.

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
