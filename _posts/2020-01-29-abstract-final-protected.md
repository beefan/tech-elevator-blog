---
layout: post
title: Day 13 Abstract Methods & Intro to Test Driven Development
description: Today we covered abstract methods & protected keyword and final keywords.
summary:  We covered abstract methods, final & protected keywords, as well as an intro to Testing. 
tags: [OOP, abstract, pair programming, test driven development]
---

Today was a much relaxed day compared to yesterday. We covered the *final* keyword, the *protected* keywords, and abstract classes. Final on method signatures means the methods cannot be overridden in subclasses. Final on class signatures means the class cannot be extended in a subclass. Protected is a qualifier that makes a data member available to all sub classes. 

This keywords were relatively straightforward. The *abstract* modifier is not so. To over-simplify it, we learned that abstract classes are combined functionality of interfaces and superclasses. The abstract classes cannot be instiated and are mostly models for building subclasses. 

Brian said that abstract classes are not often used. Though we will likely encounter them in others' codebase, we will not likely have to write them. 

Today Brian also introduced test driven development. We talked about waterfall development (sequential) and agile development (synchronous, iterative) and learned the key pros and cons of each. The concept of test driven development (TDD) was also introduced. Soon, we will work on a project where we first create tests based on requirements and then write code to get those tests to pass. 



