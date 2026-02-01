# Random Calculator (Buggy Version)

## Description
This project is a simple Python calculator that takes two numbers as input.
The program currently attempts to perform addition but produces incorrect results.

## How It Works
- The user enters two numbers
- The add() function is called
- Instead of adding the two numbers, the function returns a random integer

## Current Issue
The add() function ignores the input parameters `a` and `b` and returns a random number using Python's random module.

## Example
Input:
10
20

Expected Output:
30

Actual Output:
-98732638238940187463183 (random value)

## Reason for Bug
The logic inside the add() function does not use the provided arguments.
This results in unpredictable outputs for every calculation.

## Future Improvements
- Replace random number generation with actual arithmetic logic
- Implement proper addition using input values
- Extend calculator to support other operations
