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

# Project Title: Photobench
### Problem Statement
These days, everything is documented by photos. People take them every day, both of themselves and their lives. Sometimes, these photographers (both amateur and professional) need to make changes to their photos, but they don't want to spend money on expensive photo-editing suites to do so. That's where Photobench comes in. Photobench is a Racket-based photo-editing program which has an emphasis on maintaining the abstraction barrier between the user and the components that actually make up the image. 

### Problem Analysis
Explain what approaches from class you will bring to bear on the problem. Be explicit and succinct.

### Data set or other source materials
Since this is a photo editor, the data used will be inputted by the user.  This data will be images in bitmap, and the work will be done directly on the image itself.

The image that the user inputs should be ready to use, as Racket will convert images into a bitmap format.

Do your homework here: if you are pulling data from somewhere, actually go download it and look at it. Explain in some detail what your plan is for accomplishing the necessary processing.

If you are using some other starting materails, explain what they are. Basically: anything you plan to use that isn't code.

### Deliverable and Demonstration
The end product of this project will be a fully functional Photobench program. As a live demonstration of this program, we will run the suite of tools on a sample image, showing things such as painting, desaturation, and red-eye removal.

### Evaluation of Results
How will you know if you are successful? 
If you include some kind of _quantitative analysis,_ that would be fantastic.

## Work Plan and Schedule
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

### Nathan Goss
Will be creating the backend of the project, namely the procedures for each tool that will be in the GUI. These procedures will include white balance adjustment, red-eye correction, simple drawing tools, gamma level adjustment, (de)saturation, and more. For milestone one, I will have implemented the procedures to handle the loading and displaying of the desired image. For milestone two, I will have implemented the level-correction procedures (RGB, white balance, gamma, saturation). For the final deliverable, I will have implemented the drawing tools (paintbrush, eraser, etc.).

### Eric Wang

Will work on the front end, which would be the GUI procedures itself.  This would include creation of a file input/output system, where files are able to be saved after editing, along with confirmation windows and sliders for various settings.  In addition, toolbars will be created with options and icons will be made as shortcuts to the associated functions.  

*Milestone One* 

-General framework of GUI done

-Canvas ready for the image

-Toolbars Present

*Milestone Two* 

-Icons and link to their associated action.

-Toolbars functionality, like save and close.

-Resizing and rotating the image also there, with a new popup window and slider adjustment.

*Final*

-Full functionality

-This would be cut, crop, paste, undo, redo.

## Proposal Presentation Link
[The link is here.][link]

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/
[link]: https://docs.google.com/presentation/d/1S--tAZMp4S52NcYyCdCmzADmeABylFmv2kQNlapXJd0/edit?usp=sharing
