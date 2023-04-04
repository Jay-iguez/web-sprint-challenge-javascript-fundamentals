# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks. 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results. 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

The advanced array method '.map' is used to manipulate or reshape the data of a given array without altering said array. It is useful if you only want certain parts of an array and also want to ignore others, by doing so you can refine the data to that what you specificly need.

The advanced array method '.reduce' is used to shape data into a single value at your leisure, it won't return an array but rather a single value from what you set as what you need from it's own parameters at each element. It is useful for manipulating data of an existing array without altering said array.

The advanced array method '.filter' is used to return a new array with items that fit a given description to what you need. It will test each element and if it returns true based off your given requirements, it will return that element otherwise it will ignore it. It's great as is with other advanced array methods to manipulate the data of a given array without altering said array.

2. Explain the difference between a callback and a higher order function.

A higher order function is a function that is passed another function as a parameter. A callback function is a function that is itself passed as an argument into another function, that being a higher order function.

3. Explain what a closure is.

A closure is the concept of a variable being declared outside of a given function's scope. Once that function attempts to reach out and find the data for a variable that it out of its scope, that's where and when a closure happens. Closures have the ability to store/retrieve data from a given variable even if the function it is attached to stops running, essentially saving it's value for later use.

4. Describe the four principles of the 'this' keyword.

The four principles of the 'this' keyword go as follows - 

Window binding - The default given context of 'this' if you have not given it any context. It will return to the 'window' or the global object in node or undefined strict mode.

Implicit binding - Applies to objects with methods. Whenever the method or function of an object is invoked, whatever is to the left of the dot is what the 'this' context will refer to.

Explicit binding - We can call a function and explicitly give it context to look for using .apply, .call, or .bind. Call will act on objects, by passing in the object as an array into the attached function. Apply will act on arrays in a similar manner. Bind can be used to save a specific instance explictly defining the params of a new function that can be used/accessed for later.

5. Why do we need super() in an extended class?

You need super() to allow for the constuctor of a given class to be able to take the properties of the passed in param into the constructors own body, but also that of the body your extending from. Otherwise, the 'chiid' class won't be able to reach into it's 'parent' class for it's initializers or methods.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your repo to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/master; your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/bloomtech/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://bloomtech.notion.site/bloomtech/BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) (see part 2, submitting an assignment with codegrade).
