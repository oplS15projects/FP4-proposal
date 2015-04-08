# Project Title: Graph-ical Emulation Program (a.k.a. GrEP)
### Problem Statement
There is a need for a simpler way for people with a non-technical backgrounds to utilize the capabilities of plotting mathematical functions. Creating a solution for this problem allows us to not only help people, but permits us to be innovative and learn more about utilizing both graphical user interfaces and graph plotting together.

### Problem Analysis
We will develop multiple processes to complete little tasks, such as receiving data, parsing it, and updating the procedure. Our approach, after breaking down the project into its core components (which will include the user input, the transfer of input data, and the use of that information for plotting), will be to break each core component down to programmable sections. While programming, it is ideal to create a layer of abstraction to separate (1) the specific manipulation of data and (2) the use of the procedures that manipulate data. Overall, our approach will be to clearly define each part of the program and optimize the design to make it more efficient.

### Data set or other source materials
We will be using the introduction code provided in the Racket library for plot and gui to better understand how to use those libraries. Also, we’ll be using any tutorials for the libraries that Racket provides. Any required data that we don’t have will be supplied by the user as input.

### Deliverable and Demonstration
At the end of this project, we will have a program that creates a gui window. On that window, we will have two components: (1) a choice from a menu for what sort of mathematical function is to be plotted (e.g., linear, planar, etc.) and (2) a textbox that reads in an input for that kind of mathematical function. The program will then parse and store that input as data to plot, either on the same window, a separate one, or on console. Our project will demonstrate the aforementioned, along with any possible developments that time permits. Some additional features we would like to implement is the ability to take in and plot multiple functions at once. In addition to this, we could also give them the ability to stylize the plots to differentiate them (e.g., by color). 

The analytical results that will arise from processing will be given by an interactive plot diagram of input functions. This program is heavily focused on what the user wants to graph. Therefore, it will definitely be interactive and will allow the user to customize and update the plot accordingly.

### Evaluation of Results
We will be successful if a user can input a function(s), click a button, and then see the function(s) plotted.

## Work Plan and Schedule
The general plan for the project is to divide it into three parts. The first part focuses on ascertaining input from GUI, parsing that data, and storing it correctly. The second part primarily focuses on taking that data and displaying it back to the window. And the final part focuses on integrating more functions to plot and adding the options of graphical styling and customization.

### First Milestone (04-13)
The part handed in is the initial layout of the GUI. Code that shows receiving input from the GUI and storing it as a function. Also, capabilities of plotting are shown.

### Second Milestone (04-21)
A program that will receive user input and output a related graph based off of it.Code that shows a GUI with the stored data plotted. 

### Final Milestone
Finished project to present. It will be able to handle different function inputs and plot them.

## Group Responsibilities
Here each group member gets a section where they, as an individual, detail what they are responsible for in this project. Each group member writes their own Responsibility section. Include the milestones and final deliverable.

### Michael Forsyth (mike01720)
I will be working on the plotting of the function and how it is displayed. For the first milestone, I will be focusing on working with the plot and gui libraries to display functions onto the gui window and helping to make it look nice. With the second milestone, I will be incorporating the input from the GUI, and will be using that to display the functions on the window. As part of the final milestone, I will be working on plotting multiple functions at once and incorporating color and styles to the plots.

### Nicholas Forsyth (nick01720)
I will be creating the GUI layout and setting up the inputs for the different plots. For the first milestone, I will have a gui window that has the necessary widgets (textboxes, scroll menus, and other gui features) that the user can interact with. For the second milestone, I will add or change any widgets as necessary to improve and possibly increase the transferring of inputted data from the gui to plot. As part of the final milestone, I will finalize the layout of the gui and the types of data that the user can provide as input.

### Emily Seto (svnaptic)
I will be working on the intermediate step of abstracting data from the gui input, and sending that information to the plot procedures. In addition to this, I will be working with Nick to parse the input data for relevant values to save and to send off for plotting. For the first milestone, I’ll be working on receiving basic user input from gui and storing it. For the second milestone, I’ll be working on coordinating new user inputs with plot. I’ll also be working on rewriting the initial input with a secondary input; in other words, creating state and reformatting objects so that we can allow for updated inputs. For the final milestone, I’ll be working with the finalized set of data input to make sure that everything is being transferred correctly and that the program can also be updated with secondary input. 

## Proposal Presentation Link
https://docs.google.com/presentation/d/1-gDy_dI0RKrSQPWZTt7XP3W-vjw0YBXTj1qiQGvo1AM/edit?usp=sharing
