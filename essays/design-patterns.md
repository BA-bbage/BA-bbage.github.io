---
layout: essay
type: essay
title: Design Patterns
# All dates must be YYYY-MM-DD format!
date: 2020-12-03
labels:
  - Software Development
  - OOP
  - JavaScript
  - C
---
## Introduction
Often, many programmers notice some recurring solutions in their code when solving many development problems. Rather than repeating those solutions multiple times, they can apply abstract blueprints that separates code to what is changeable and what is repeatable. These abstract blueprints are termed design patterns and are considered the best practices for programmers for speeding development in their software.

## What is a Design Pattern
Every object we see in life is built upon a certain design pattern that is used multiple times in other objects with similar functionality. Take a chair for an example. There are many different kinds of chairs available, such as a sofa, a beanie chair, a stool, and a wheelchair. Though all are made with different parts and materials, every chair must follow a design that provides someone a comfortable place to sit. As the seat provides a place to sit on, the design demands every type of chair to implement at least one seat.

Design patterns in programming are abstract templates that provide reusable solutions for common development problems. They define recurring relationships between software objects to make code more flexible. They also provide maintainability as it reduces the scope for debugging whenever an issue occurs, which is highly appreciated for large-scoped projects handled by a large group of programmers. By these factors, design patterns can speed up the overall development process of a software.

Programmers do not necessarily need to implement multiple design patterns throughout their code. Some may argue that overusing design patterns can lead to bad coding habits as it hinders critical thinking for highly complex solutions. However, design patterns should be taken into consideration when common problems arise in a program. The best way to utilize design patterns is to figure out where in the code they are most applicable and which pattern is best suited in that area.

### Types of Design Patterns in Programming
As a game developer, I had utilized a few design patterns to help define interactions and behavior of many different game objects. One popular design pattern I used was the singleton pattern. This pattern is used to ensure only one instance of a class is created and managed throughout an entire program. The single instance is useful for classes that cannot perform correctly with more than one instance existing. It also acts as a global point of access to its class, allowing multiple external classes to access members and functions of the class without needlessly making more instances to do so. I had utilized this pattern on counters, such as object collisions and high scores, where only instance of a particular counter is needed throughout a whole game.

Another design pattern I used in game development is object pooling. In this design pattern, a object known as a pool is made to act as a container for reusable instances of another object. The pool follows a cycle where it first defines a limit for the amount of instances it needs to create, then sends the instances to parts of the program that needs them, and finally collects instances currently not in use back to it. By doing so, it minimizes the amount of times the class constructor is used in a program, thereby increasing performance with less processing power and memory consumption. I had utilized this pattern with SHMUP (Shoot Em Up) games where multiple instances of a projectile and enemy are present in a game. By reusing projectile and enemy objects, I am able to skip multiple creation and destruction processes and maintain preferabble framerate throughout the runtime of the game.

## Conclusion
Design patterns are helpful when tackling multiple occurences of a general problem. When used correctly, they can increase a software's flexibility and maintainabilty, allowing room for faster development. There are many different design patterns in existence, and it is up to the programmer to determine where is it best to apply them.
