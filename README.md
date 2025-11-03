# swe-sr-1-1

Welcome to your first short response assignment! If the code that you write is what gets your foot in the door for a job interview, how you communicate is what will get you the job. So, treat these assignments seriously! Write your responses as if you were planning on publishing them in a blog for the world to see (and, if you're confident, actually publish them!).

## Setup

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

Here are some useful commands to remember.

```sh
npm i                   # install dependencies
git checkout -b draft   # switch to the draft branch before starting

git add -A              # add a changed file to the staging area
git commit -m 'message' # create a commit with the changes
git push                # push the new commit to the remote repo
```

## Prompt

Imagine you are teaching a brand new programmer a brief lesson about functions and function calls. Your lesson should have the following components:

* A technical definition ("According to MDN, a function is...").
* An explanation of the concept with an analogy ("You can think of a function a ...")
* An example of the syntax for an arrow function using a JavaScript code block (triple backticks)
* An explanation of the syntax using the terms **arrow function**, **parameter**, **code block**, **return statement**, and **call/invoke**.

Below, we've provided an outline for your response but feel free to modify it as you see fit.

### Response

According to MDN (Mozilla Developer Network), a function is “a reusable block of code that performs a specific task, often taking input and returning an output.”

You can think of a function like a vending machine.
When you press the buttons (give it input), it performs an action inside (runs the code), and then gives you what you asked for (output).

Check out this example:

// This is an arrow function
const calculateArea = (width, height) => {
  // width and height are parameters
  return width * height; // return statement sends back the result
};

// calling (or invoking) the function
console.log(calculateArea(5, 3));  // 15
console.log(calculateArea(10, 7)); // 70


Explanation of the example and syntax:

const calculateArea = (width, height) => { ... }
This is an arrow function.

Inside the parentheses (width, height) are the parameters — these act like placeholders for the values you pass in.

The { ... } part is called the code block. It’s where the instructions for the function live.

The return statement tells the function what value to give back when it finishes running. In this case, it returns the result of width * height.

calculateArea(5, 3) is a function call (also called invoking the function). Here we pass the numbers 5 and 3 as the actual input values, and the function returns 15.

In short, functions let us reuse code, organize logic, and make programs easier to read and maintain.