# Unhandled Exception in JavaScript Calculator

This repository demonstrates an example of an unhandled exception in JavaScript and shows how to fix it.

## Bug Description

The `operate` function calls other functions to perform arithmetic operations. However, if the `divide` function encounters a division-by-zero error, it throws an exception. This exception is not caught, causing the program to terminate unexpectedly.

## Solution

The solution involves using try...catch blocks to gracefully handle the exception and prevent the program from crashing.

## How to run

1. Clone this repository.
2. Open the `bug.js` and `bugSolution.js` files in your preferred code editor.
3. Run the files in a JavaScript environment (e.g., Node.js, browser's console).

Observe the difference in behavior between the buggy and corrected versions of the code.