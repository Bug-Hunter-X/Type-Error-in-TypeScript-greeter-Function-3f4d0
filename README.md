# TypeScript Type Error in greeter Function

This repository demonstrates a common type error in TypeScript and its solution.

## The Bug

The `greeter` function is designed to accept a string and return a greeting. However, the code passes an array to the function, resulting in a type error.

## The Solution

The solution involves adding a type guard to check if the input is a string before using it in the function.