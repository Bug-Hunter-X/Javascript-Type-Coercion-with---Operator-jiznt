# Javascript Type Coercion with + Operator
This repository demonstrates a common error in Javascript related to type coercion when using the + operator.  The + operator will perform string concatenation if either operand is a string, rather than numeric addition. This can lead to unexpected results.

## Bug
The `bug.js` file contains a function `foo` that adds two numbers. However, due to type coercion, unexpected results occur when strings are passed as arguments.

## Solution
The `bugSolution.js` file shows how to use the Number() function to convert strings to numbers before adding them. This ensures that numeric addition occurs as expected.

## How to run
1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in your preferred Javascript environment.
3. Run the code to see the differences between the original and corrected functions.