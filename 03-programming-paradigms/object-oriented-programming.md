# Object-Oriented Programming (OOP)

## Overview
Object-Oriented Programming is a paradigm based on the concept of **objects**, which combine data and behavior. It models real-world entities and relationships.

The focus is on **what** the program represents rather than just how it runs.

## Key Principles
1. **Encapsulation** – Bundling data and methods together
2. **Abstraction** – Hiding implementation details
3. **Inheritance** – Reusing and extending existing code
4. **Polymorphism** – Multiple forms of the same method

## Key Characteristics
- Code organized into classes and objects
- Promotes modularity and reusability
- Improves maintainability and scalability

## Advantages
- Easier to manage large applications
- Better code organization
- Reusable and extensible
- Improved data security

## Disadvantages
- More complex than procedural programming
- Slight performance overhead
- Requires careful design

## Popular OOP Languages
- Java
- C++
- Python
- C#
- Ruby

## Example (Python)
```python
class Person:
    def __init__(self, name):
        self.name = name

    def greet(self):
        print(f"Hello, my name is {self.name}")

p = Person("Alice")
p.greet()
```

## When to Use
- Large-scale applications
- GUI applications
- Games
- Enterprise software