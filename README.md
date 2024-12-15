# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error occurs because the loop condition incorrectly includes the index equal to the array's length, leading to an `ArrayIndexOutOfBoundsException`. The solution shows how to correctly iterate within the bounds of the array.

## Bug

The `Bug.java` file contains the code with the off-by-one error. When run, this code throws an `ArrayIndexOutOfBoundsException`.

## Solution

The `BugSolution.java` file provides a corrected version of the code. The loop condition is changed to `i < arr.length` to prevent the error.
