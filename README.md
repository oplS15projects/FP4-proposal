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

# Project Title: League of Legends API
### Problem Statement
If you take a look around your classroom, whether you be the teacher or a student, it is overwhelmingly likely that there is a solid chunk of people in that very classroom that play the game League of Legends. Easily the most popular game in the world, with a world tournament with more watches than the World Series or NBA finals, those statistics really aren't that surprising. Speaking of statistics, wouldn't you like to know how well you've been doing in your games? Luckily Riot Games provides an API of which can be manipulated to crunch those numbers and display exactly that information.

Apart from that, Nick planned on building something like this in PHP for his own site anyways. Might as well build it in Racket and get class credit, as well as get to present it to the class and work with a team.

### Problem Analysis
Well the obvious approach is the utilization of the Scheme programming language, specifically Racket. We will be utilizing two libraries to achieve our end result. Something that will be heavily used is abstraction. We're hoping to abstract all HTML and front-end interface out from the logic, thus achieving a separation of concerns.

### Data set or other source materials
We will be utilizing the Riot API to pull player data and game data to display statistics on a web page. The primary trick is grabbing the data and manipulating it to get what we want. An example is to get a players rank, it's not simply a single query, you have to search for them within the League that they are in, and then return their rank from there. It's actually kind of unnecessarily difficult, but will be achieved nonetheless.

All data pulled from the API is simply returned as strings and is easy to display once we actually retrieve it. The API is well documented, and RESTful.

### Deliverable and Demonstration
The statistics application will have a front end web page interface. Thus to display our project, we simply need to boot up the program on the main screen, and we'll have our web page running on our racket web server. From there, it's highly likely we'll run a few test examples on some summoner names from the crowd, that is if anyone is brave enough to display their player statistics on the main screen for everyone to see.

### Evaluation of Results
We will know if we are successful if the application retreives the data quickly, and displays it even quicker. No output from the API should break the structure of the web page and if the API is down at the time of query, then an error message should be displayed. It is however unlikely that the API will be down at all. A lot of web services rely on it being up.

## Work Plan and Schedule
Explain how you will go from proposal to finished product. Write your general plan here. 
There are three deliverable milestones to explicitly define, below. The nature of deliverables depend on your project, but may include things like processed data ready for import, core algorithms implemented, interface design prototyped, etc. 

You will be expected to turn in code, documentation, and data (as appropriate) at each of these stages, so take care in writing concrete steps for your schedule. 

In this general plan, and in the deliverables below.

### First Milestone (04-13)
Front end interface design draft (not coded)
API JSON Parser
Web Server Program

### Second Milestone (04-21)
Front end interface coded
API JSON Data Wrapper Built (Maybe)
Web Server & Front end interface integrated, data passed between two cleanly

## Group Responsibilities
Here each group member gets a section where they, as an individual, detail what they are responsible for in this project. Each group member writes their own Responsibility section. Include the milestones and final deliverable.

### Nick Lombardi
For the first milestone, I'll be starting with a deisgn mockup of how the interface will be layed out. That'll be done mostly on paper. After that's been finalized, I'll start putting some thought into colors and opacities. Once that's been decided on by running it by the team, I'll begin coding for the second milestone, getting the front-end of the interface in HTML & CSS. Maybe I'll even throw some JavaScript in there, who knows. A little bit of animation might go a long way for the end user. Once I have the interface completed, I'll be working directly with Ron & Josh to bring this project together.

During this whole process I'll be Project Manager to make sure everything comes together nicely and ends meet. My part will not be solely design, I'll be heavily involved in both other parts.

### Joshua Semedo
For our project, I'm going to be the one responsible for getting and manipulating the data we're displaying.  I'm going to be pulling it from Riot Games' API. This will include stats like KDA, wins, losses, games played, etc. but also more indepth stats, like how well you play a certain champions or particular achievements you've met with them.  I will be taking the input from the website, then santizing it and putting it in a url, then parsing the JSON from that url into relevant chunks, where it will eventually be displayed on the webpage.
I hope to have the parsing completed, pulling the relevant information from the JSON and putting it into variables, for the first milestone, and for the second I aim to analyze the variables, and return text based on the stats(ex. if they have a good KDA, "KDA: 3.5, Above average!" or "Your high kills and high deaths suggest an aggressive playstyle; try playing safer")

### Ron
I am going to be using the web-server library that the Racket language has to setup a web server and figure out how to pass data from racket variables to templates that have been built by Nick. That is how I'll be contributing to the project. For the first milestone, I will have the web-server running and displaying a dummy page with the basic layout.  For the second milestone, I will have the web-server running and displaying the proper information in the right style, correctly passing information back and forth between the json parsing and the name lookup.

## Proposal Presentation Link
insert your google presentation public link here, so with one click it will open up in the browser and you can present.

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/
