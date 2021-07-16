# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from an object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in Responsive Design, and JavaScript Basics.


## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with.

### Commits

Commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)

Please answer the following questions below, you may edit the readme file to include your answers below the question.

1. How would you describe acessibility on the web to someone new to programming?
    
    I would describe accessibility as being made with all user types in mind including users with permanent or temporary disabilities, users with limited internet connection, users who are older and not as tech advanced, or users on several different screen sizes, and any other user categories as well.

2. Talk about 3 different things you can do to ensure your website is accessible. 

    To make sure your website is accessible you can make sure your images have alt attributes descibing the image, you can make sure your elements are as semantic as possible, you can make sure that your websites colors take into account color-blind users, and you can add also ARIA attributes to your page.

3. How would you explain the concept of a variable to someone new to programming?

    I would tell them that a variable is a way to store data. Variables are like labels for values. We store/declare the value with a name and we can refer back to it later, we can use it to do stuff, or we can change it in certain instances. There are 3 types of variables known as var, let, and const. Var can be reassigned and redeclared and is the variable used in older versions. Let is a variable that can be reassigned but can not be redeclared and it was made to solve the issues that var posed. Const is a variable that can be neither reassigned nor redeclared as it remains constant. It is good to use const until you can't and then use let instead. We should stay away from var. Var is function scoped while let and const are block scoped. Let and const are not hoisted.

4. What is the purpose of using functions in code?

    Functions protect a block of code until the function is invoked. Functions make it possible to be able to perform a related action without having to write it out multiple times. With a function we can plug arguments into the function's parameters and log the result then plug in different arguments over and over with just a few lines of code. Functions are reuseable and much more efficient.
    

5. How do you access a key inside of an object inside of an array?

    You give the name of the array, followed by the index the object is positioned at inside the array. This index should be inside of square brackets. You then use the dot or bracket notation with the key name. It would look along the lines of:
    arrayName[indexOfObjectPosition].objectKeyName OR
    arrayName[indexOfObjectPosition]["objectKeyName"]

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set-Up

Follow these steps to set up your project:

1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
NOTE: Tests will run for the JavaScript portion of this challenge only
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2a:  Minimum Viable Product - Responsive Design

*Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css).*

* [ ] Ensure your website is responsive at 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.



## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

🦄 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-2-Study-Guide-16f656025c8744458addb068e6348101)


## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)


