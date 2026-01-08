# Functional Programming

## Overview
Functional programming is a paradigm that treats computation as the evaluation of **mathematical functions**. It avoids changing state and mutable data.

The focus is on **what to compute**, not how to compute it.

## Key Concepts
- Pure functions
- Immutability
- First-class and higher-order functions
- Function composition
- Recursion

## Key Characteristics
- No shared state
- No side effects
- Functions are treated as data
- Declarative style

## Advantages
- Easier to reason about code
- Fewer bugs due to immutability
- Better support for parallelism
- Cleaner and more predictable logic

## Disadvantages
- Steeper learning curve
- Can be less intuitive
- Performance overhead in some cases

## Popular Functional Languages
- Haskell
- Lisp
- Erlang
- Scala
- Elixir

(Many modern languages like Python and JavaScript support functional features.)

## Example (JavaScript)
```javascript
const numbers = [1, 2, 3, 4];

const squared = numbers.map(n => n * n);

console.log(squared);
```

## When to Use
- Data processing
- Concurrent and parallel systems
- Mathematical and logical computations
