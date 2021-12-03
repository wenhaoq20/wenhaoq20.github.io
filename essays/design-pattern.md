---
layout: essay
type: essay
title: Baking and Coding
# All dates must be YYYY-MM-DD format!
date: 2021-12-02
labels:
  - Coding
  - Software Engineering
  - Design Pattern
  - Learning
  - Reflection
---
<img class="ui image" src="/images/codeS1.jpg">

Ever since the pandemic started, I have been introduced to a new hobby, baking. For the past two years, I have been baking an assortment of goods ranging from cookies, cakes, pies, and other desserts. When you start baking something new like macaroons, you always start by finding a recipe you fancy making; you never would want to start making something from scratch without a general plan or the next thing is your creation will be in the dump. When I learned about what design patterns are in programming this week, it reminded me of the process of baking. A baking recipe can be treated as a form of design pattern, it’s a set of instructions that is trying to help you solve a common problem (in this case, baking a macaroon). Similar to how there are various design patterns to solve different problems in coding, there are different baking techniques when making pastry. At the end of the day, it just depends on what you are trying to bake (the coding problem) and what recipe (design pattern) you choose to follow to create that macaroon. 

Since I’ve only learned about design patterns recently, I will primarily talk about the recent design patterns I have used in my code.

## Implementations of Design Patterns
Throughout this semester, I have been writing code that I didn’t know followed a design pattern. Notably, design patterns like singleton, observer, and MVC (model view controller).

The singleton design pattern is one of the most common design patterns seen in Java. Singleton is like a “global variable” that can be accessed globally. It works by creating exactly one instance of a class that is used by other classes. It’s like a Netflix account that the whole family uses. It’s useful when you need an object that is referenced frequently, saving you both memory and code. The downside is that it’s not normally thread-safe. I implemented this design in my final project where the collection of a set of data is a singleton. The collection of data is able to be accessed by multiple pages on the website to display things like graphs and lists of data for the website.

The observer design pattern is an automatic notification system that notifies an object’s dependents (observers) when there is a change to the object. This design pattern provides an easy, automatic way to update any of the object’s dependents instead of manually updating them. However, if a problem were to have occurred during development, it would be difficult to debug it. Something similar to this design in real life is the subscription to a mailing list of a website. It will automatically send you an email when there are updates from the website. I implemented this design in my website where I used Meteor’s subscribe and publish method.

Finally, the MVC design pattern is the primary design I used for the whole website project. It’s a design that separates the user’s interface into data (model), how the data is presented (view), and any governing intermediary processes between the two (controller). This design pattern is similar to baking. The ingredients you work with are the model and the resulting pastry is the view. The recipe, the controller, tells you how to use those ingredients to make the macaroon to share with your family and friends. 
