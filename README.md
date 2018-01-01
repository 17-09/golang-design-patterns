# Design patterns in golang
>A beginner guide... happy coding!

## Table of Contents

- [Creational patterns](#creational-patterns)
    - [Singleton](#singleton)
    - [Builder](#builder)
- [Structural patterns](#structural-patterns)
    - [Composition](#composition)
- [Behavioral patterns](#behavioral-patterns)
- [Concurrency patterns](#concurrency-patterns)

---

## Creational patterns
Creational design patterns abstract the instantiation process. They help make a system independent of how its objects are created, composed, and represented.

### Singleton
Ensure a class only has one instance, and provide a global point of access to it.

### Builder
Separate the construction of a complex object from its representation so that the
same construction process can create different representations.

## Structural patterns
Structural patterns are concerned with how classes and objects are composed to form
larger structures. Structural class patterns use inheritance to compose interfaces or implementations.
As a simple example, consider how multiple inheritance mixes two or
more classes into one.

### Composition
Compose objects into tree structures to represent part-whole hierarchies. Composite
lets clients treat individual objects and compositions of objects uniformly.

## Behavioral patterns
Behavioral patterns are concerned with algorithms and the assignment of responsibilities
between objects. Behavio ral patterns describe not just patterns of objects or classes
but also the patterns of communication between them. These patterns characterize
complex control flow that's difficult to follow at run-time. They shift your focus away
from flow of control to let you concent ratejust on the way objects are interconnected.

## Concurrency patterns
Pattenrs for concurrent work and parallel execution in Go.