# FP4-proposal
Project Proposal is due 2015-04-08 at 8am

# Project Title: Create a Racket Mathematics and Graphing REST API
### Problem Statement
To set up a racket Webserver with API landing points that interpret JSON input, which would then be processed by Racket to evaluate solutions. These solutions would then be returned by the webserver and in JSON form.

### Problem Analysis
We will use objects to generate the API handler, and mathematic objects for calculations.

### Data set or other source materials
We will be generating our own test data for input, and will be using [json][jsonlint.com] to validate structure.

This data will be sent to our server and caught, it will then be interpreted by our json object class and turned into a form that our API can manage. The API object will then determine the operation and use a handler procedure like in the bank account examples to determine what to do with the data. Once the operations are processed our json object will construct a response and return it to the user through the Webserver.

### Deliverable and Demonstration
We will be able to do basic mathematical operation such as:

| method  | params     | Description             |
|---------|------------|-------------------------|
|add      | + a b      | addition of a pair      |
|subtract | - a b      | subtraction of a pair   |
|multiply | * a b      | multiplication of a pair|
|divide   | / a b      | division of a pair      |
|modulus  | % a b      | modulus of a pair       |
|exponent | a ^ b      | exponent of a pair      |
|equal    | = a b      | equality of a pair      |
|eval     | f( x ) , x | evaluate a function at  |
| ...     | ...        | ...                     | 

We will also try to implement graphing of equations such as with 
| method  | params             | Description             |
|---------|--------------------|-------------------------|
|sin      | a sin( b )^p       | sin curve graph         |
|cos      | a cos( b )^p       | cos curve graph         |
|tan      | a tan( b )^p       | tan curve graph         |
|graph    | f( x ) , x , a , b | graph a generic function|
| ...     | ...                | ...                     | 

This project will be run on a webserver that will return live results, any user will be able to access the API and view dynamic results.

### Evaluation of Results
Since our project will involve mathematics it will be easy to prove that the results are what was expected, sample data will be run with identites such as 1 * x = x , 0 * x = 0 . Results will be compared to actual results for validity. 

## Work Plan and Schedule

Steps to complete

| # | task | state |
|---|------|-------|
| 1 | Create Web Server object | in progress |
|1.1| Web Server Documentation | not started |
| 2 | Allow for multiple landing pages associated to the API methods | investigation|
|2.1| Web API Documentation | not started |
| 3 | Create a JSON processor object | in progress |
|3.1| JSON object Documentation | not started |
| 4 | Create a Server API Handler object | not started |
|4.1| Server API handler Documentation | not started |
| 5 | Create a Mathematics object | not started |
|5.1| Mathematics object Documentation | not started |
| 6 | Create a Graphing object | not started |
|6.1| Graphing object Documentation | not started |

You will be expected to turn in code, documentation, and data (as appropriate) at each of these stages, so take care in writing concrete steps for your schedule. 

In this general plan, and in the deliverables below.

### First Milestone (04-13)
During the First Milestone we will have turned in Client related items (Items 1 - 2.1) as well as the Mathematics portion (Items 5 - 5.1)  

### Second Milestone (04-21)
During the Second Milestone we will have turned in Server related items (Items 3 - 4.1) as well as the Graphing portion (Items 6 - 6.1)  

## Group Responsibilities
### Jose Flores
Will be responsible for the transmission and interpretation of data, so will be primarily working with (Items 1 - 4.1)

### Munkhjargal Narmandakh
Will be responsible for the production of results, so will be focusing on (Items 5 - 6.1)

## Proposal Presentation Link
[link][proposal]

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/
[json]:http://jsonlint.com/
[link]:http://proposal-link/
