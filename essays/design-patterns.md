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
Every object we see in life is built upon a certain design pattern that is used multiple times into similar, yet different-looking objects. Take a chair for an example. There are many different kinds of chairs available such as a sofa, a beanie chair, a stool, and a wheelchair. Though all are designed with different parts, every chair must have a seat for someone to sit on. Even the seat itself can be called a chair as it still provides a place to sit. The seat defines an abstract template for all chair designs that can be utilized to create all sorts of chairs.

## UI Frameworks
When a framework is utilized, web makers can reference a pre-built class from its collection that functions similarly to what HTML/CSS code they would have written. These classes cover fundamental webpage tools, such as image/text formatting, themeing, and content grouping, allowing for different customization on a web page. By themselves, classes can implement basic web page features. However, for more complex features multiple classes must be used according to the framework's object-oriented programming concepts. It should also be noted that frameworks may not have the classes necessary to implement certain features, which would then involve writing code from scratch. Developers would usually provide documentation of all the classes in the framework to provide background information on its syntax and its outcomes. It is then up to the web maker to figure out implement them correctly to produce their features.

### Working with Semantic UI
Prior to writing this essay, I developed experience in a UI framework called Semantic UI. This framework utilized HTML syntax that references concepts based on a class' name. The class name takes at least one word listed in the framework's documentation and produces an outcome based on the following: the noun/modifier relationship, the word order, and the plurality. For example, if I want to implement an image that is small and fluid, I would write:
> img class="ui small fluid image" src="NAME-OF-IMAGE.png"

Furthermore, the framework simplifies Javascript code in which functionality is triggered through simple phrases called "behaviors". This is helpful for certain webpage features such as dropdowns and sidebar menus.

Despite how apparent the amount of code was reduced in my HTML files, I struggled in developing complex web features utilizing the framework. During an assignment that involves recreating a webpage, I utilized concepts of Semantic UI to implement most of the features, such as menus, header/footer, and image/text formatting. There were some features that required hard coding, such as background images, floating text, and text with links. The difficult part of the assignment was creating a grid of images and links and integrating them into the page. The grid involved initializing three rows and their column size/count while implementing the desired content inside the columns. Since the background made the images hard to see, a background color was implemented to the grid with reduced opacity.

## Conclusion
UI Frameworks revolves around the idea of simplifying code while maintaining functionality by creating pre-built HTML classes for web makers to utilize instead of writing raw HTML/CSS code from scratch. However, it has a set of object-oriented programming concepts to follow and may require code from scratch if it lacks tools needed for a certain feature. If used correctly and efficiently, a web maker can create designs in a short amount of time.
