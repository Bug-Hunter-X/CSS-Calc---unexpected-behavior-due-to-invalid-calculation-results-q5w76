# CSS Calc() Unexpected Behavior

This repository demonstrates an uncommon error that can occur when using the CSS `calc()` function.  The `calc()` function allows you to perform calculations directly within your CSS, but if the calculation results in an invalid value (such as a negative width or height), the behavior can be unexpected and difficult to debug.

The `bug.css` file contains the problematic code. The `bugSolution.css` file shows how to solve the issue by adding constraints to prevent invalid calculations. 