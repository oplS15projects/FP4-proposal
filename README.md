# FP4-proposal
Project Proposal is due 2015-04-08 at 8am

# Project Title: iLambda (iλ)

### Problem Statement

iSENSE (isenseproject.org)--an online system that promotes collaborative scientific analysis by providing accessible ways to upload, share, and visualize data--is a website developed for teachers. Teachers can setup projects for their classroom experiments. Both students and teachers can input data into projects, and iSENSE will display the data on different visualizations.

The problem is when creating projects, teachers have to create data fields. These fields are like the variables in an experiment, also known as the project, and they hold data which is later graphed on iSENSE. Teachers can find that creating a project is a bit confusing. iLambda will make it easier to setup projects on iSENSE, and it is interesting because it will contribute to an ongoing research project at the university.

### Problem Analysis

We will build a web application in Scheme using GUI and Network libraries that will help teachers easily setup projects. It will first display a login page, then a page with a list of predefined common projects. By simply clicking on the project, it will automatically create that project on iSENSE. Lastly, it will give them the options to change or alter the project.

We will apply several programming practices from class including object-oriented concepts to create and maintain projects as well as higher order procedures to manipulate the project objects.

### Data set or other source materials

When we create our login page, we will need to verify that the email and password information is correct in the iSENSE user database.  We won’t need to download or pull any information from the user database, we will just check it through a call in iSENSE’s API. We also need data variables, so we can create data fields, instructions, and a default picture for each of the pre-defined projects, but we won’t need to download or pull this data from any external database. We will populate our own database with project information. Project information will most likely come from all the projects we’ve done at iSENSE workshops over the past few years.


### Deliverable and Demonstration

We will create interactive software that communicates with iSENSE to assist teachers in creating projects. The software will contain multiple parts including the following:

(1) *Login Page*: First, teachers will login using their iSENSE credentials. We will verify the given email and password exist in the iSENSE user database by making a GET request to the iSENSE API. When teachers successfully login, they will be redirected to the projects page.<br>
![wireframe 1](http://weblab.cs.uml.edu/~kcarcia/OPLProject/1.png) <br>

(2) *Projects Page*: Teachers will then select one of the 10 pre-existing projects listed. (Only four projects are shown in the wireframe to save space.) We will store all project information in a database. Project information will include a default title (which can be changed), fields, and two media objects--a default image and project instructions in a PDF. Once a teacher selects a project, they will be directed to the title page.<br>
![wireframe 2](http://weblab.cs.uml.edu/~kcarcia/OPLProject/2.png) <br>

(3) *Project Title Page*: Projects will be automatically assigned a name, but users will have the option to modify it on this page. After this point, the project will actually be created via the iSENSE API by grabbing the given project title and information associated with the selected project in the database.<br>
![wireframe 3](http://weblab.cs.uml.edu/~kcarcia/OPLProject/3.png) <br>

(4) *Media Object Page*: Teachers will then have the opportunity to upload additional media objects, such as files or images, to their project. Media objects will be added to the project via a POST request to the iSENSE API.<br>
![wireframe 4](http://weblab.cs.uml.edu/~kcarcia/OPLProject/4.png) <br>

(5) *Contributor Key Page*: Users also will have the option to create a contributor key for their project to make contributing data easier for their students. Contributor keys will be added to the project via a POST request to the iSENSE API.<br>
![wireframe 5](http://weblab.cs.uml.edu/~kcarcia/OPLProject/5.png) <br>

(6) *Goodbye Page*: Finally, teachers will be provided the link to their brand new project on iSENSE.<br>
![wireframe 6](http://weblab.cs.uml.edu/~kcarcia/OPLProject/6.png) <br>

### Evaluation of Results

We will reach success if we implement all aspects of the software described above--creating a project, modifying the title, adding media objects, and setting up a contributor key. In addition to developing functional software, we also think building an intuitive user interface and including 10 different project options will be a part of reaching success.

## Work Plan and Schedule
![schedule](http://weblab.cs.uml.edu/~kcarcia/OPLProject/schedule.png) <br>

### First Milestone (04-13)

For the first milestone, we will turn in code, documentation, and data.

Code and documentation for:
- Inputting projects into database
- Login page UI

An image for:
- Our logo

Data for:
- Projects to be selected by users

### Second Milestone (04-21)

For the second milestone, we will turn in additional code and documentation for:

- Login functionality
- Project selection page UI
- Project title page UI
- Project creation functionality

## Group Responsibilities

Kaitlyn and Ravy will both collect project data and work on assignments together. Their individual assignments are listed below.

### Kaitlyn Carcia
Kaitlyn will input projects into the database; build the UI of the login, project title page, as well as the “you’re finished!” page; and implement project creation as well as contributor key creation.

### Ravy Thok
Ravy will create the logo; build the UI of the project selection page, media objects page, as well as contributor key page; and implement iSENSE login as well as uploading media objects.

## Proposal Presentation Link
[Presentation](https://docs.google.com/presentation/d/1dsIfek5W0uXWie95RNLjmPFDuw9SvUgawQ5HGWtAzwM/edit?usp=sharing)
