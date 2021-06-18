# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

_You have **three hours** to complete this challenge. Plan your time accordingly._


## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead as the evaluate your solution.

## Interview Questions
### (please edit this file and write your answer below each question. In addition, you may also review these questions with your mentor)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Briefly compare and contrast `.forEach` & `.map` (2-3 sentences max)

    .forEach will iterate through the entire array without stopping, it also won't automatically create a new array. Return is optional
    .map returns a new array automatically without manipulating the original array. it needs the return keyword.


2. Explain the difference between a callback and a higher order function.

    Callback functions are passed into higher order functions as arguments. Higher order functions receive callback functions.

3. Can you explain what a closure is and how you used it in the counter function? 

    A closure is used when a function reaches into the outer scope to grab a value. You can pass values down in scope but never back up.
    I used closure in the counter function to define the variable 'total' outside of the for loop, and then the for loop is using the variable total to run its loop, which will add every number from 0 to the total.


4. Describe the four principles of the 'this' keyword.

    Window Binding -- If no other rules apply, this defaults to the entire window. Basically an error and should not be used. If in node it will return the global object, or if in strict mode it will return undefined.

    Implicit Binding -- When you invoke the function, this refers to what is left of the dot. This is the most common use of the 'this' keyword. It applies to objects with methods (object functions)

    Explicit Binding -- You are explicity defining what this will reference... (.call, .bind, .apply) example -- data.call(newdata) -- in this example, this is being bound to newdata

    New Binding -- using 'new' keyword will make a new object out of a constructor function, when a function is invoked as a constructor function, this points to the new object

5. Why do we need super() in an extended class?
    super() does what .call and object.create do, they inherit  methods and attributes from the parent class. 
    extends tells super() what to super to. in the following example -- class Parent extends Child -- super will grab whats in Parent.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set Up

Follow these steps to set up your project:

1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
NOTE: Tests will run for the JavaScript portion of this challenge only
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test:watch` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Task 2: Project Requirements

Your finished project must include all of the following requirements

#### Task A: Closure

This challenge takes a look at closures as well as scope. 
* [x] Find this challenge in the index.js file. Read the instructions carefully!

#### Task B: Objects and Arrays

Test your knowledge of advanced array methods and callbacks.
* [x] Find this challenge in the index.js file. Read the instructions carefully!

#### Task C: Prototypes

Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [x] Find this challenge in the index.js file. Read the instructions carefully!

#### Task D: Classes

Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* Find this challenge in the index.js file. Read the instructions carefully!!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

### Task 3: Stretch Goals 

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements! Please remember to comment out your stretch goals before you submit 

## Submission format

See Canvas for submission instructions 

