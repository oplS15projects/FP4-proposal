# Project Title: RacketSynth
### Problem Statement
The RSound sound engine is a powerful tool. It allows for the representation, reading, writing, playing and manipulation of
sounds. Unfortunately, it is rather complicated and difficult to use. Our plan is to simplifiy it's use by wrapping it with
a graphical user interface. This will be done using the Racket GUI Toolkit. 

We would also like to create a playable instrument using the Racket GUI Toolkit and RSound. Users can use their keyboard and the
interface mentioned above to control sounds. 

### Problem Analysis
We will need to take the difficult process of creating particular types of sound waves at particular frequencies and abstract it
in to simple procedures. These procedures will then be called by our user interface which will present a clear, obvious way to
create sounds. 

This will allow users to more expressively control the RSound library. 

### Data set or other source materials
The only things we plan to use that isn't code we've written ourselves is the GUI Toolkit and RSound. 

### Deliverable and Demonstration
The final version of our project will, ideally, have an interface for creating various types of sound waves at selected
frequencies. These could be sine, sawtooth, square, or pulse waves. The frequencies will have reasonable upper and lower limits
in order to protect the user's audio hardware and their ears. If we have time, we would like to add the layering of multiple
sounds and differnet values. Theoretically, these layers could be used to synthesize any sound. 

We will also create a way for the frequencies to be set by mapping keyboard inputs to particular values. This will allow a user
to use their computer's keyboard as a playable instrument. 

We will show all of the working freatures in our final demonstration. 

### Evaluation of Results
As the main purpose of this assignment is to make RSound easier to use, (though will a reduced functionality), we will conduct
brief usability tests. This will consist of asking friends, both with substantial experience with computers and without, to use
our program and describe the experience. We may also give them a short list of simple tasks to complete. Also, we will have the
program tested by a keyboard or piano player to see if they can actually get some music out of the program. 

## Work Plan and Schedule
The first step in our plan will be to create a simple mock-up of the user interface. This may go through different version as it must have a design that we all agree on. After this has been decied, we will use it as a model to create the actual user interface. After the interface has the correct look and feel, we will all procedures to detect user input. These can be a simple as generating messages to the interpreter such as 'User has pressed key x.', or 'User has selected radio-button y.' These procedures will later be used to connect to the RSound library. 

After the interface is completed, we will begin simplifying the RSound wave generation procedures. We will do this by limiting their options and generalizing the procedure calls. The new procedures will generate sine, sawtooth, square, and pulse waves within a specified frequency range. Again, this limits the level of freedom a user has to use the RSound library, but simplifies the proccess considerably. 

After these simplifed proceures have been written we will modify the user-input-detection procedures to create sounds. If all goes to plan, this will essentially complete the project. 

### First Milestone (04-13)
We would like to have the user interface completed, though with very little actual functionality. However, any user actions in
the interface shoud trigger special test events so that we know the user actions are being detected. This could be a test as
simple as displaying a string in the interpreter when the user presses a particular button. 

This will not yet include any of the keyboard instrument functionality. 

### Second Milestone (04-21)
The user interface should now be able to call procedures that create sounds according to the user's specifications. The sound
creation should be achieved through simple, expressive procedure calls. 

We will also have the interface for the keyboard instrument working. As we will need to take keyboard input, a good test would 
be echoing whatever key is pressed in the interpreter, again, to make sure that user input is being properly detected. 


## Group Responsibilities
Here each group member gets a section where they, as an individual, detail what they are responsible for in this project. Each group member writes their own Responsibility section. Include the milestones and final deliverable.

### David Lordan
Along with the rest of the team, I will focus on getting the user interface completely implemented for the first milestone, which is quickly approaching. I will create a simple mock-up which the rest of the team and I will try to recreate.

After the first milestone I will working on creating procedures that can simplify the RSound wave generation procedures. After these are working properly I will use the procedure calls generated by the interface to connect the two libraries together. 

### Leonard Lambda
will work on...

## Proposal Presentation Link
insert your google presentation public link here, so with one click it will open up in the browser and you can present.

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/
