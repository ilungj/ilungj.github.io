---
layout: essay
type: essay
title: Should I Use an UI Framework?
date: 2017-10-05
labels:
---

<del>UI framework is not a bed of roses for beginners. Beginners should avoid using them like the plague.</del>

For the sake of discretion- in this article, I discourage beginners who are just getting started in front-end web development from using UI frameworks. UI frameworks can be a big investment, hinder long term learning, and may ultimately slow down the performance of your product.

But before I downplay the use of UI frameworks, I first establish that I fully understand the importance of using UI frameworks. If the subject at hand is anything but a beginner, using an UI framework is an absolute necessecity in all developer's workflow for two reasons: responsiveness and complex components. For example, the grid system that most frameworks provide plays an important role in making any website responsive. It detaches you from worrying about breakpoints and have you write a lot less media queries than you normally should. And if you were to implement such system yourself... you would have to write somewhere along 1561 lines of code (https://github.com/twbs/bootstrap/blob/v4-dev/dist/css/bootstrap-grid.css). Also, slightly more complex components that involve the use of JavaScript like the carousel is very easy to implement with an UI framework like the Twitter Bootstrap. 

But for people who are just getting started things are a litttle different:

1) Learning is a barrier of entry. There are different open source UI frameworks on the net, and they all have slightly different syntax, terms for classes, use of mixins, etc. To try each and every one of them to find what works best for you will be almost like learning a whole another programming language (I mean the time invested in it). Certainly there are documentations and example codes written that will ease your pain... But because UI frameworks are very comprehensive, the extra documentation may turn out to be extra stress. 

2) UI frameworks make front end coding so easy for you, that you may neglect writing your own CSS code. Remember that you will need to write CSS code sooner or later. Otherwise, you will be using the same components with the same design that everybody else is using. Based on personal experience, a complete reliance on using uncustomized, raw pre-defined classes will make your product look like the documentation page of your choice of UI framework. In addition, not learning the CSS code can evolve into hard time for you later on when you have to use more complicated selectors, 3D transformations, etc. 

3) For small projects, there will be a lot of things that you don't use from the UI framework that becomes dead weight. While you can reduce this bloat through the use of preprocessors like LESS and SASS to get rid of some modules. But it becomes counter intuitive to expect this from a beginner. Even if you knew how to do this, there's another hurdle of working with the CDN (content delivery network) which can significantly impact your project's performance. If you forgo the default CDN that's provided to you by the UI framework, you may have to pay the cost of running your own server, find another way to host it, or not use it at all (possibly not a good idea for the reason described above).

When you're first learning about front-end programming, the best thing to do is to go to your favorite website, press F12, and start copying and pasting the styles of elements that you think look good. That should teach you more things than what UI frameworks do in the beginning.
