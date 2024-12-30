# JavaScript Loose Typing Bug

This repository demonstrates a common JavaScript bug caused by loose typing.  The `foo` function intends to add two numbers, but due to JavaScript's dynamic typing, it performs string concatenation when one of the arguments is a string.

## Bug Description
The `foo` function should add two numbers. However, if one of the arguments is a string, it concatenates the arguments as strings instead of performing numeric addition.  This can lead to unexpected results and errors in larger programs.

## Solution
The solution involves explicit type checking or conversion to ensure that both arguments are numbers before performing the addition.

## How to reproduce
1. Clone this repository.
2. Open `bug.js` and run it in a JavaScript environment (e.g., Node.js or a browser's console).
3. Observe the unexpected output.