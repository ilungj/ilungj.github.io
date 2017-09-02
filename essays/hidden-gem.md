---
layout: essay
type: essay
title: JavaScript Started
date: 2017-08-27
labels:
---

I used to look down on JavaScript when I first started learning programming. In the case that this sounds offensive to anybody, a more qualified statement would be "JavaScript came off as an unappealing language for me to learn." I simply thought that JavaScript was too messy, and seeing how almost everybody was using JavaScript (even non-Computer Science majors to some extent), I got this impression that JavaScript was too easy, and was only good for making websites. In hindsight this was all too impetuous and I should have given some time for me to get experienced in programming before I gave it such hasty impression. So to somewhat atone for my past misperception of the language, I would like to give it some credit for what it deserves.

JavaScript is flexible.

JavaScript as a language is not necessarily messy. But due to its forgiving nature, code written in JavaScript tends to be less consistent and less concerning about syntax errors. For example, in JavaScript, if you indented however you wanted and forgot to put semi-colons all over the places, JavaScript will take it easy on you; languages like python, however, will yell at you. In a way, you can say that JavaScript is flexible.

This flexibility can come in handy when you're programming in JavaScript and you encounter some problems with classes. Different from most object oriented programming langauges that are based on class inheritance, JavaScript uses prototypal inheritance. Classes in other languages is equivalent to functions in JavaScript, and functions all boil down to objects that have a bunch of properties. And these objects have a property called "prototype" that are linked to other objects' prototypes by "[[prototype]]" (pronounced dunder proto). Finally, it is these links that make up the concept of inheritance in JavaScript.

Because properties of functions can easily be linked to other functions, you can be selective in what you inherit from other objects. This is different from languages like Java, where if you decided to extend a class from another class and call "super()", you would inherit all of methods of the parent class whether you liked it or not. Such selective prototypal inheritance lets you avoid a very annoying problem that you may commonly encounter in programming: the fragile base class problem.

The fragile base what?

The fragile base class problem is vulnerability in code where modifications to the base class can cause subclasses to malfunction. Suppose you're coding in Java again, and you have a class B that extends from class A, and classes C and D that extend from class B. Now make believe that there's a problem in C, but in order to fix this, we need to make some changes to the methods that were inherited all the way from class A. So you make these changes.. but voilà , class D is now broken because it was relying on the method that was changed in class A. If you could only inherit what you needed for each class and could easily add custom methods like in JavaScript, you would unlikely encounter this problem. 

I don't understand

If you don't quite understand concepts like what I just described, you can always search online to find tons of resources that will help you understand. This brings up my next point, which is JavaScript's widely received support from community. 
JavaScript has ubiquitous uses.

Many people know how to program in JavaScript, and this may lead people to think that JavaScript is easy to learn. But this doesn't have to imply demerits of the language. In fact, because it is so accessible and popular, JavaScript is fast growing and offers a lot of scaffolding tools to facilitate your workflow. For example, the node package manager is a repository of hundreds of thousands of libraries and modules that you can integrate into your project according to your needs. This eliminates the need for you to reinvent the wheels and spend hours creating all of those helper tools and drivers.

Speaking of node package manager, node.js is a platform that lets you program on the server side with JavaScript. With this you can slim down on the technology stack and work more cohesively between the front-end and back-end developers on your team. Also, because of JavaScript's popularity, other people have created frameworks for developing cross platform applications that you can use to make native desktop and mobile applications with JavaScript only. 
JavaScript is like a hidden gem.

I would like to rectify my initial statement about JavaScript being only good for making websites. JavaScript is good for making websites and good for doing everything else. Some people (like me) may be cautious about learning JavaScript in the beginnning because of prejudices and confusing concepts like prototypes. But if they give it a chance to really get to learn more about the language, they will find it a very useful and intriguing language.
