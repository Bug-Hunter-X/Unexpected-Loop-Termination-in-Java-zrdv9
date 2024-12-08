# Unexpected Loop Termination Bug in Java

This repository demonstrates a common logic error in Java programming involving unexpected loop termination. The `Bug.java` file contains code with a `break` statement inside a `while` loop, which might not terminate as intended depending on the condition. The `BugSolution.java` file shows the corrected version of the code with proper loop control and handling. 

## Bug Description
The bug lies in how the break statement interacts with loop variables and the loop's termination condition. If the `break` statement's condition is not properly set or interacts with other parts of the loop in an unintended way, the loop's behavior can be unexpected and lead to difficult-to-diagnose issues.   

## How to reproduce the bug
1. Compile and run the code in `Bug.java`. Observe the output and compare it to the expected output where the loop should continue until x == 10.
2. Examine the corrected code in `BugSolution.java` which shows how to solve the problem and correctly handle the conditions.

## How to fix the bug
Ensure that the conditions for the loop termination and the conditions for breaking out of the loop are correct. Check for logical errors and unintended side effects related to variable updates in the loop. 