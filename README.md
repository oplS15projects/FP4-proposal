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

# Project Title: Da Dank Decoder
### Problem Statement
Data security is a large topic in computer science. Therefore crpytography is useful in concealing fragile information such as passwords. For example a database of unencrypted passwords. If a hacker were to gain access to this database, they would be able to use the passwords with ease. However, if the passwords were encrypted, the hacker would then have to find a way to decrype the passwords before they could be used. This acts as an extra line of defense against cyber-attacks. Often times encrypting things can prevent any harm from being done, or delaying the 'hacker' from doing any damage before the host realizes that there was a breach.

### Problem Analysis
We will use a lot of higher-order procedures. The basic stratgy of our encryption will be to take the message, convert it to a sequence of characters and then use `map` to manipulate that list.

### Data set or other source materials
We will use documentation on ciphers, namely the Caear cipher and the Vigenere cipher.

### Deliverable and Demonstration
We will make a proof of concept for ciphers. We will use the bank account example from class. We will make a bank client, you can create an account. You will be able to withdraw and deposit money in the account... if you have the password. The usernames, passwords, and amount will be saved. The passwords will be encrypted.

### Evaluation of Results
If we can encrypt and decrypt messages/passwords.

## Work Plan and Schedule
Explain how you will go from proposal to finished product. Write your general plan here. 
There are three deliverable milestones to explicitly define, below. The nature of deliverables depend on your project, but may include things like processed data ready for import, core algorithms implemented, interface design prototyped, etc. 

You will be expected to turn in code, documentation, and data (as appropriate) at each of these stages, so take care in writing concrete steps for your schedule. 

In this general plan, and in the deliverables below.

### First Milestone (04-13)
A test GUI that will decipher caeser and vigenere ciphers.

### Second Milestone (04-21)
GUI which will take password and type of encryption and will allow you to manipulate a bank account.

## Group Responsibilities
Tyler: Incharge of GUI for test GUI and bank.

Michael: Incharge of Caesar cipher and part of bank code.

Matt: Incharge of Vigenere cipher and part of bank code.

## Proposal Presentation Link
[Google Presentation](https://docs.google.com/presentation/d/1CqUN65wKD8UlQcG6Gpj7xlaJtX4hBMUDCit0NEeUyRY/edit?usp=sharing)

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/
