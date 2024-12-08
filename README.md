# Uncommon TypeScript Type Error: String to Number Assignment

This repository demonstrates an uncommon variation of the common TypeScript type error: 'Type 'string' is not assignable to type 'number'. This specific example highlights a scenario where the type error might not be immediately obvious due to implicit type coercion or complex data structures.

## The Bug

The `bug.ts` file contains a function `add` that is designed to add two numbers. However, due to implicit type coercion, a string '2' is passed as an argument and it causes the error.

## The Solution

The `bugSolution.ts` file demonstrates a solution by explicitly checking the types of inputs using type guards or by using a more robust type definition for the input parameters that handles various types including strings that can be converted to numbers.

## How to Reproduce

1. Clone this repository.
2. Open `bug.ts` to see the code that causes the error.
3. Run `tsc bug.ts` to compile the code and observe the error. 
4. Open `bugSolution.ts` to view and run a more robust solution. 