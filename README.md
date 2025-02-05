# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`. The code attempts to access an array element using an index that's beyond the array's bounds, leading to a runtime exception.

## Bug Description
The `Bug.java` file contains a simple program that initializes an integer array and then tries to access an element at an index that's larger than the array's size. This results in an `ArrayIndexOutOfBoundsException`.

## Solution
The `BugSolution.java` file provides a corrected version. It adds a check to ensure the index is within the valid range before accessing the array element, preventing the exception.