# Project Title: Scalable virtual audio launchpad
### Problem Statement
We always think it'd be great if everyone with a computer can create music.
We come up with the idea of making a music launchpad controlled with keyboard.

### Problem Analysis
We will apply the concept of managing objects to buttons that contains audio loops.

### Data set or other source materials

Most audio samples will be gathered online and modified in alternate programs like Audacity and file converters.

Each audio samples will be associated to a button. When the button is clicked, the entire audio sample will be played once.

Rsound is a sound engine library for racket.  We will be utilizing the file streaming portion of RSound to import audio files.

Audio samples are the basic components of a song. Our objective is to provide an environment for users to put them together.

### Deliverable and Demonstration

At the end of the project, there will be a window that we can toss in audio loop files, and they will turn into button objects that we can trigger by keyboard events. Then we can use it as an instrument.

The software makes the computer become an instrument. Users can try out their own combinations. If possible, we will make a recorder to capture and replay user input.

The software will be very interactive. The keyboard is like a programmable digital keyboard. The entire software is designed for the benefit of user control. To show that the software works, we will play a song with our software as a demo, live in class.

### Evaluation of Results
How will you know if you are successful?
When these two objectives are achieved:
  1.  Playback of 5 to 10 audio samples can be played in a short time interval without crashing the program
  2.  Keyboard events actually triggers audio samples playback

## Work Plan and Schedule=

The General plan is to do divide and conquer. We have three core aspects of our project: GUI, Audio, and Framework.  To start off, we want to create something basic where an audio sample can be played at the press of a button.  At the same time we will develop a simple GUI with buttons and a launchpad.  We will combine these components together to get a working launchpad that will play samples at either a click or key press.

To make this truly a launchpad, we need to implement a way to loop these samples while maintaining a stable tempo.  We will have to implement time and loops.

There are three deliverable milestones to explicitly define, below. The nature of deliverables depend on your project, but may include things like processed data ready for import, core algorithms implemented, interface design prototyped, etc. 

In this general plan, and in the deliverables below.

### First Milestone (04-13)
Audio samples can be played at a press of a key on the keyboard.

### Second Milestone (04-21)
Full implementation of GUI and audio portion being played.  We will have a working launchpad.

## Group Responsibilities
Here each group member gets a section where they, as an individual, detail what they are responsible for in this project. Each group member writes their own Responsibility section. Include the milestones and final deliverable.

### Luis Perez
I'll be in charge of even handling. Implementations within the given gui. Making things light up when they need to.  Making sure that the buttons when pressed port over to your music library.

### YuetLong Leung
I'll design the internal structure of the button object, and draw it on GUI. Most likely I'll use Racket Drawing Toolkit.

### Yesehaq Fauconier
Ive just been experimenting with the racket gui library creating frames  and canvases. So I'm going to cover that.

### Zachary Wong
Edit audio files and making it compatable in Racket.  Making sure sound can be played by a command.

## Proposal Presentation Link
https://prezi.com/mpcphsxs2zz_/launchpad-simulator/?utm_campaign=share&utm_medium=copy

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/
