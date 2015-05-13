# Branch2 Frontend Developer Test

## Intro
Welcome! This is the Branch2 Frontend Developer Test, where you will complete small tasks, each successively harder, to prove your skills. Remember, programming isn't about knowing everything, it's about being able to figure out how use the tools that are available. 

## Task 1: Twitter Bootstrap + Responsive Design
Your first task is to setup Twitter Bootstrap and use its prewritten HTML grid classes ("col-xs-6" for example) to make the sample page (index.html) look better. 

Here's what you need to do:
- [ ] Set up a Github account if you don't already have one. 
- [ ] Fork this repository and clone your fork on your computer
- [ ] Go to [getbootstrap.com](http://getbootstrap.com) and download the necessary files
- [ ] Use the Bootstrap getting started guide to add Bootstrap to index.html
- [ ] Add a container div around all the content
- [ ] Add the row class inside container (see comments in code)
- [ ] Add as many CSS classes from Bootstrap as you see fit and any custom CSS you want

### *Bonus points:*
Setup Grunt and LESS to compile Bootstrap and any custom LESS that you write


Commit and push your changes with a commit message of how long this task took you, then move on to the next task!

## Task 2: AngularJS
Your next task involves AngularJS, the JavaScript library we use for every application at Branch2. The learning curve for this task is much steeper than in Task 1 if you have never used AngularJS before. It will also involve calling the [colr.org](http://colr.org/api.html). The page has a number input and a button. When a user inputs a number and clicks the button, your code will call the Colr API and get that many random colors returned, displaying these colors on the screen. 

Here's what you need to do:
- [x] Complete Task 1 
- [x] Include AngularJS in the index.html file. This is already done for you.
- [ ] Optional: Complete [AngularJS CodeSchool Course](http://campus.codeschool.com/courses/shaping-up-with-angular-js/intro)
- [ ] Putting all JavaScript code in task2.js, set up a service that uses $http to call the Colr API with a GET request for a random number of colors: http://www.colr.org/json/colors/random/4. You'll want to replace the 4 with a URL parameter.
- [ ] In index.html, make the form element bind to the $scope by using ng-model
- [ ] Use the MainController to call the service when the user clicks the button, sending the number entered on the form as the parameter for number of random colors to receive
- [ ] In the box on the right, display just the "hex" property of each color returned using ng-repeat

### *Bonus points:*
- [ ] Instead of displaying the hex codes, make a grid of small squares that have the background-color of the colors returned.
- [ ] Create a service for calling the API to replace the use of $http (commit before doing this so we can view your code with $http version too)
- [ ] Implement a Firebase database connection. Be creative.

Commit and push your changes with a commit message of how long this task took you, then move on to the next task!

## Task 3: D3.js (Not set up yet)
Task 3 involves creating a simple timeline of events from a theoretical cross-country journey. Use the files in /task3 to create this visualization. There is events.json and a mockup of what the timeline could look like. Feel free to be creative with this task with design, interactions, even adding data!

Fork this repo (or create your own), implement the timeline, commit your files, and send us a link to the repo!

## Task 4: Ionic Goal Tracking
This task is based on a simplified version of a typical project at Branch2. You will need to develop an app using Ionic Framework that meets the following requirements:
- [ ] Users have accounts and can log in
- [ ] Users set goals for themselves with two parts - the name of the activity, and how many times per day they would like to complete this. (See mockup in goal-tracking.png)
- [ ] Users can track how many times they have completed that activity that day. (See mockup in goal-tracking.png).

Use of a backend API such as FireBase is required. FireBase is recommended but not required, and if you choose to use another backend technology please communicate that in the README.md file for the project. Include any other needed info in the README as well.

This is purposely an open-ended task, and you should feel free to implement it however you choose. The mockups are only to communicate functionality and are not how the final product needs to look, feel free to change the UI as you wish. 

Please build this app and commit your code when finished. 

### *Bonus points:*
Pick and choose any additional bonus tasks you would like to add, these are in no particular order. 
- [ ] Add any additional styles you wish, in order to improve the UI
- [ ] Implement other ways of defining and tracking goals. Be creative.
- [ ] Implement a graph of the user's progress over time. Feel free to load your backend with historical data. Use of D3.js is recommended but not required.
- [ ] If a user has multiple goals, try to find correlations between their performance on one goal and their performance on another to create an insight such as "When you drink 5 glasses of water per day you are less likely to eat cake." Display these insights in the app somewhere. 
