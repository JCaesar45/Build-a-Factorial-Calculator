````markdown
# Factorial Calculator 🧮

This is a simple JavaScript project that calculates the factorial of a number between **1 and 20**. It demonstrates the use of functions, loops, variables, and string interpolation in JavaScript.

## 🚀 Features

- Accepts a number between 1 and 20
- Calculates the factorial of the number using a loop
- Returns and displays the result in a readable message format

## 📜 User Stories Fulfilled

- ✅ Declare a variable `num` and assign it a number between 1 and 20
- ✅ Create a function `factorialCalculator` that takes a number as an argument and returns its factorial
- ✅ Use a loop inside the function to compute the factorial
- ✅ Call the function with `num` as the argument
- ✅ Store the result in a variable `factorial`
- ✅ Create a message string in the format `Factorial of [num] is [factorial]`
- ✅ Output the message to the console

## 🧩 Code Example

```javascript
// Declare the input number (must be between 1 and 20)
let num = 5;

// Function to calculate factorial
function factorialCalculator(n) {
  let result = 1;
  for (let i = 1; i <= n; i++) {
    result *= i;
  }
  return result;
}

// Call the function and store result
let factorial = factorialCalculator(num);

// Create and output the result message
let resultMsg = `Factorial of ${num} is ${factorial}`;
console.log(resultMsg);
```

## ✅ Example Output

```
Factorial of 5 is 120
```

## 📁 Project Setup

No setup is required. Simply copy and paste the code into your browser console, an online JavaScript editor like [JSFiddle](https://jsfiddle.net/) or [CodePen](https://codepen.io/), or a local `.js` file and run it using Node.js or your browser's DevTools.

## 📚 Topics Covered

* Variables
* Functions
* Loops (`for`)
* Template literals
* Console output

## 📌 Notes

* The input `num` must be between 1 and 20 to prevent stack or performance issues.
* You can change the value of `num` to test different results.

---

Created as part of a JavaScript fundamentals lab.

```
