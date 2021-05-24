[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Advanced-JavaScript: Assignment

## Problems

### 1: Scope

Write a JavaScript code snippet that has a global variable defined on the first line in 
the global scope. Then have a local variable defined inside the a function.

1. Under the `src` directory, create a file named `scope.js`
1. Declare a global variable
1. Define a function named `demo`
1. Declare a local variables

**Example:**

```js
// global
demo(){
  // local
};
```
### 2: Scope Practice

Execute the code in Function 1 and 2, explain the difference in output.

```javascript
// Function #1
function foo() {
  function bar() {
    i = 100;
  }

  bar();

  console.log(i);
}

foo();

// Function #2
function foo() {
  function bar() {
    let i = 100;
  }

  bar();

  console.log(i);
}

foo();

// YOUR ANSWER
```


### 3: Hoisting

Try to guess the output of the following code

**Example:**

```javascript
let x = 10;

function test() {
  let x = 20;
}

test();

console.log(x);

// YOUR ANSWER
```

### 4: Closure

Write a JavaScript closure that will execute the inner function

1. Under the `src` directory, create a file named `hoisting.js`
1. Define a function named `outer`
1. Inside outer function declare a function `inner` with a variable
1. Make a call to `inner` function and display the value

**Example:**

```javascript
// closure

function outer() {
  // variable to be created

  function inner(){
    // variable to be returned
  }

  return inner;

}

// store inner function in variable

// make call to inner function to display variable

```
## Submission Guidelines

- Cite any relevant sources consulted during your research
- Solve the problems using your own code
- Do not copy and paste solutions from the source material
