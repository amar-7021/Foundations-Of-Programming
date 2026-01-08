# Procedural Programming

## Overview
Procedural programming is a programming paradigm based on the concept of **procedures** (also called functions or routines). A program is structured as a sequence of steps that operate on data.

It focuses on **how** a task is performed by breaking problems into smaller, reusable procedures.

## Key Characteristics
- Programs are organized into functions or procedures
- Follows a top-down approach
- Emphasizes step-by-step execution
- Uses shared data (global or local variables)
- Simple and efficient for small to medium programs

## Common Concepts
- Variables
- Control structures (if, loops, switch)
- Functions/procedures
- Parameters and return values

## Advantages
- Easy to understand and implement
- Efficient execution
- Good for simple and performance-critical applications

## Disadvantages
- Hard to manage large codebases
- Poor data security due to shared data
- Difficult to maintain and scale

## Popular Procedural Languages
- C
- Pascal
- Fortran
- BASIC

## Example (C)
```c
#include <stdio.h>

void greet() {
    printf("Hello, World!");
}

int main() {
    greet();
    return 0;
}
```

## When to Use
- System-level programming
- Embedded systems
- Applications with clear, linear workflows