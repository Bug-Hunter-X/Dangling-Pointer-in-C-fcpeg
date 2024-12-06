# Dangling Pointer in C

This repository demonstrates a classic example of a dangling pointer bug in C programming and its solution.  A dangling pointer occurs when a pointer points to a memory location that has been freed or is no longer valid.  This can lead to unpredictable behavior, crashes, and security vulnerabilities.

## The Bug

The `bug.c` file showcases the problem of dangling pointers.  The integer variable `x` is created, and a pointer, `ptr`, is assigned its address.  The pointer is then used to modify the value of `x`, which is standard practice.

## The Solution

The `bugSolution.c` file provides a corrected version of the code. While the original code is functionally correct in this simple case, in more complex scenarios with dynamically allocated memory, using dangling pointers could cause severe errors.