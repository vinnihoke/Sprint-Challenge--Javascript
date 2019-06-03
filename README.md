# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. Describe the biggest difference between `.forEach` & `.map`.

- [ ] Both items will call every item in an array and execute a block of code. However, only the .map() method will return a new array. If you aren't careful, your .forEach() method can modify your original array and give you unexpected results, therefore a .map() method that automatically creates a new array may be favorable.

2. What is the difference between a function and a method?

- [ ] Although both perform similar operations, a method only works on an object, whereas a function can be on its own. Methods are found in object oriented programming. 

3. What is closure?

- [ ]  Closure could also be referred to as scope in programming. For instance there are local and global functions and variables. A local variable can pull global variables, but a function living in the global scope cannot accept a local variable living in a function; unless it has been returned in some cases. You must be mindful when creating variables, and when you'll need to access those variables in the future.

4. Describe the four rules of the 'this' keyword.

- [ ] Window/Global Object Binding: When in global scope, this will refer to the window/console object.

- [ ] Implicit Binding: The object will be whatever is to the left of the dot. This will "reset" `this` to the object you're referring to. You can then use dot notation to access it's values with this.value.

- [ ] New Binding: This will create a new object based on a constructor function. This is a "template" of an object that with the `new` keyword will generate a new variable with all of the constructor's values. Essentially we're creating a function that creates an object for us.

- [ ] Explicit Binding: Whenever JavaScript’s call or apply method is used, this is explicitly defined. We can explicitly pull values into the new objects and create new context for them.
 
5. Why do we need super() in an extended class?

- [ ] Super() pulls in the values of the previous constructor. This is especially useful because we can pull in all of the object values from the previous, then add new ones that pertain specifically to the new object. For instance we might create a base class of Person, but then we might have an extended class of Occupation. Each person would have an occupation, therefore we can extend the Person class with the Occupation class to talk about their line of work. We can pass in values to Occupation without disturbing the Person class.

## Project Set up

Follow these steps to set up and work on your project:

- [ ] Create a forked copy of this project.
- [ ] Add PM as collaborator on Github.
- [ ] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [ ] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [ ] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
- [ ] You are now ready to build this project with your preferred IDE
- [ ] Implement the project on your Branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo).
- [ ] Add your Project Manager as a Reviewer on the Pull-request
- [ ] PM then will count the HW as done by  merging the branch back into master.


## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays
Test your knowledge of objects and arrays. 
* [ ] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

## Task 2: Functions
This challenge takes a look at callbacks and closures as well as scope. 
* [ ] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [ ] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [ ] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
