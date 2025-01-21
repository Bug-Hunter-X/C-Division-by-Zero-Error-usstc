# C Division by Zero Error

This repository demonstrates a common runtime error in C: division by zero. The `bug.c` file contains code that attempts to divide an integer by zero, resulting in undefined behavior. The `bugSolution.c` file shows how to prevent this error using proper error handling.

## Bug

The `bug.c` file contains a simple program that divides an integer by zero. This results in undefined behavior, which typically causes the program to crash.

## Solution

The `bugSolution.c` file demonstrates how to prevent division by zero errors. Before performing the division, it checks if the denominator is zero. If it is, the program displays an error message and exits gracefully.  This prevents the program from crashing and provides informative feedback to the user.