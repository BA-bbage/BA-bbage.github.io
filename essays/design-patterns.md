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
Often, many programmers notice some recurring solutions in their code when solving many development problems. Rather than repeating those solutions multiple times, they can transform them into abstract blueprints that separates reoccuring parts of code to code that can change.

## What is a Design Pattern
Every object we see in life is built upon a certain design pattern that is used multiple times in similar, yet different-looking objects. Take a chair for an example. There are many different kinds of chairs available such as a sofa, a beanie chair, a stool, and a wheelchair. Though all are made with different parts and materials, every chair must follow a design that provides someone a comfortable place to sit. As the seat provides a place to sit on, the design demands every type of chair to implement at least one seat.

Design patterns are, in short, abstract templates utilized in solving common development problems. They can be made 

### Working with Semantic UI
Prior to writing this essay, I developed experience in a UI framework called Semantic UI. This framework utilized HTML syntax that references concepts based on a class' name. The class name takes at least one word listed in the framework's documentation and produces an outcome based on the following: the noun/modifier relationship, the word order, and the plurality. For example, if I want to implement an image that is small and fluid, I would write:
> img class="ui small fluid image" src="NAME-OF-IMAGE.png"

Furthermore, the framework simplifies Javascript code in which functionality is triggered through simple phrases called "behaviors". This is helpful for certain webpage features such as dropdowns and sidebar menus.

Despite how apparent the amount of code was reduced in my HTML files, I struggled in developing complex web features utilizing the framework. During an assignment that involves recreating a webpage, I utilized concepts of Semantic UI to implement most of the features, such as menus, header/footer, and image/text formatting. There were some features that required hard coding, such as background images, floating text, and text with links. The difficult part of the assignment was creating a grid of images and links and integrating them into the page. The grid involved initializing three rows and their column size/count while implementing the desired content inside the columns. Since the background made the images hard to see, a background color was implemented to the grid with reduced opacity.

## Conclusion
UI Frameworks revolves around the idea of simplifying code while maintaining functionality by creating pre-built HTML classes for web makers to utilize instead of writing raw HTML/CSS code from scratch. However, it has a set of object-oriented programming concepts to follow and may require code from scratch if it lacks tools needed for a certain feature. If used correctly and efficiently, a web maker can create designs in a short amount of time.
