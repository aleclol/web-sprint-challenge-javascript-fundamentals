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
    
    .map: Takes a function as an argument and then applies that function to each element (or index, or the whole array) in an array. It then returns the resulting modified array as a new array. Good for entire dataset manipulation.
    
    .reduce: Also takes a function as an argument and then applies that function to each element/currentValue (or index, or the whole array) in an array. After each running of the function the result is stored in the accumulator parameter. It returns a value, which is the result of running the function on the final element in the array. Good for averages, totals, and other simple statistics.
    
    .filter: Also takes a function as an argument and then applies that function to each element (or index, or the whole array) in an array. It then returns an array, not of modified values, but of elements that when input to your filter function return "true". Good for creating specific data subsets based off a given criteria.

2. Explain the difference between a callback and a higher order function.

    callback: A function that is defined previously in the code, then passed to another function as an argument.

    higher order function: A function that takes one or more functions as arguments.

3. Explain what a closure is.

    closure: A function plus its lexical environment. I.e. Every function comes with a specific reference library that is defined when the function is defined, but can be modified subsequently. It's sort of like the function is in an object where the first key is the actual function/method, but there is a second hidden key: an array of variables the function has access to. I.e. a closure is a single-method object.

4. Describe the four principles of the 'this' keyword.

    1. Global/Window: When no context is defined, the Window object is the default.
    2. Implicit: Context is to the left of the dot. E.g. "myObj" in myObj.method();
    3. Explicit: Using .call, .bind, or .apply to define "this":
        .call: Pass in arguments one-by-one, immediately invokes the function.
        .bind: Pass in arguments one-by-one, returns a brand-new function to be invoked later.
        .apply: Pass in the arguments as an array, immediately invokes the function.

    4. New keyword: sets "this" to point to a new object which is created by a constructor function.

5. Why do we need super() in an extended class?

    We need super() to pass arguments from a child class to a parent class and obtain properties and methods from that parent.


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
