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
- [ ] Add as many CSS classes from Bootstrap as you see fit (columns, forms, etc.)

### *Bonus points:*
Setup Grunt and LESS to compile Bootstrap and any custom LESS that you write


Commit and push your changes with a commit message of how long this task took you, then move on to the next task!

## Task 2: AngularJS
Your next task involves AngularJS, the JavaScript library we use for every application at Branch2. The learning curve for this task is much steeper than in Task 1 if you have never used AngularJS before. It will also involve calling the [colr.org](http://colr.org/api.html). The page has a number input and a button. When a user inputs a number and clicks the button, your code will call the Colr API and get that many random colors returned, displaying these colors on the screen. 

Here's what you need to do:
- [x] Complete Task 1 
- [ ] Optional: Complete [AngularJS CodeSchool Course](http://campus.codeschool.com/courses/shaping-up-with-angular-js/intro)
- [ ] Include AngularJS in the index.html file. "The Basics" section on [AngularJS.org](http://angularjs.org) can show how.
- [ ] Create the following JavaScript files in the /js folder: app.js, controllers.js, services.js
- [ ] Include the three JavaScript files from above in the index.html page
- [ ] Set up the Angular app and instantiate a new controller. Use ng-controller and ng-app in index.html to connect these. 
- [ ] Set up a service that uses $http to call the Colr API with a GET request for a random number of colors: http://www.colr.org/json/colors/random/4. You'll want to replace the 4 with a URL parameter.
- [ ] In index.html, make the form element bind to the $scope by using ng-model
- [ ] Use the Controller to call the service when the user clicks the button, sending the number entered on the form as the parameter for number of random colors to receive
- [ ] In the box on the right, display just the "hex" property of each color returned using ng-repeat

### *Bonus points:*
- [ ] Instead of displaying the hex codes, make a grid of small squares that have the background-color of the colors returned.
- [ ] Implement a Firebase database connection. Be creative.

Commit and push your changes with a commit message of how long this task took you, then move on to the next task!

## Task 3: D3.js
Your third task involves creating a D3.js line graph and bar graph. D3 is a visualization library that is used heavily by Branch2. Since it is difficult to integrate on a page using AngularJS, switch to the task3.html file for this task. You will create both a bar chart and a line graph in this task. The data sets are already in place for you in the time-series.js and sports-data.js files. 

Here's what you need to do:
- [ ] Include D3.js on the task3.html page
- [ ] Using the time-series.js file filled with data, create a line graph. It doesn't need to be anything fancy but it should be 400 pixels wide and 400 pixels tall.
- [ ] Using the sports-data.js file filled with categorical data, create a bar graph. It doesn't need to be anything fancy but it should be 400 pixels wide and 400 pixels tall.

### *Bonus points:*
- [ ] Implement a legend for each graph
- [ ] Implement these on the index.html file, where AngularJS interrupts. You'll need to use Angular Directives to solve this. 

Commit and push your changes with a commit message of how long this task took you, then move on to the next task!
