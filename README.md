# Project Title: Photobench
### Problem Statement
These days, everything is documented by photos. People take them every day, both of themselves and their lives. Sometimes, these photographers (both amateur and professional) need to make changes to their photos, but they don't want to spend money on expensive photo-editing suites to do so. That's where Photobench comes in. Photobench is a Racket-based photo-editing program which has an emphasis on maintaining the abstraction barrier between the user and the components that actually make up the image. 

### Problem Analysis
The main idea from class which we will be using in this project is the idea of building an abstraction barrier between the user and the program. This barrier will be the tools provided for the user, which will each dispatch, in different ways, the underlying procedures.

### Data set or other source materials
Since this is a photo editor, the data used will be inputted by the user.  This data will be images in bitmap, and the work will be done directly on the image itself.

The image that the user inputs should be ready to use, as Racket will convert images into a bitmap format.

### Deliverable and Demonstration
The end product of this project will be a fully functional Photobench program. As a live demonstration of this program, we will run the suite of tools on a sample image, showing things such as painting, desaturation, and red-eye removal.

### Evaluation of Results
Our level of success will be based on the effectiveness of each tool in our toolset. This will be judged on a case-by-case basis for each tool independently.

## Work Plan and Schedule
Explain how you will go from proposal to finished product. Write your general plan here. 
There are three deliverable milestones to explicitly define, below. The nature of deliverables depend on your project, but may include things like processed data ready for import, core algorithms implemented, interface design prototyped, etc. 

You will be expected to turn in code, documentation, and data (as appropriate) at each of these stages, so take care in writing concrete steps for your schedule. 

In this general plan, and in the deliverables below.

### First Milestone (04-13)
For this milestone, the deliverable will be a basic GUI which has toolbars and a canvas, which can load and display the user's desired image. It will not have much functionality beyond that at this point.

### Second Milestone (04-21)
For this milestone, the deliverable will be a more advanced GUI, with icons for each tool, functionality for saving, closing, resizing, and level-correction procedures (RGB, white balance, gamma, saturation).

## Group Responsibilities
Here each group member gets a section where they, as an individual, detail what they are responsible for in this project. Each group member writes their own Responsibility section. Include the milestones and final deliverable.

### Nathan Goss
Will be creating the backend of the project, namely the procedures for each tool that will be in the GUI. These procedures will include white balance adjustment, red-eye correction, simple drawing tools, gamma level adjustment, (de)saturation, and more.

*Milestone One*

-Procedures for loading and displaying the desired image

*Milestone Two*

-RGB balance

-White balance

-Gamma adjustment

-Saturation

*Milestone Three*

-Paintbrush

-Eraser

-Other drawing tools

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
