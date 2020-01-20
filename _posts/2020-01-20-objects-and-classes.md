---
layout: post
title: Day 6 Objects & Classes
description: Today we covered objects and started talking about classes. 
summary: Objects dominated today's conversation. We also talked about classes, string methods, immutability, and elevator pitches! 
tags: [object, classes, stack, heap, strings, pathway]
---

First day of the second week! We spent most of the lesson talking about classes and using classes to create instances of objects. Brian was sure to explain how objects are created in the heap, with references to the object stored in the stack. This is different than other data types we have worked with so far. One key difference is that we can create a variable say, int x = 0 then create a seperate int y = x. If we change x it doesn't change y. However if we made a new object, xObject x = new xObject() and then create a seperate xObject y = x, we have not created two seperate objects. Instead, we have created two references to the same object in the heap. 

Brian spent a significant amount of time focusing on strings because strings in java are special objects which are created and passed around quite differently. Plus, the String class in java contains a plethora of methods that we can use to operate on strings. Strings are immutable which means that we cannot change its value once created. If we want to change the value, we are effectively created a new string object with the altered value. This is for security and performance reasons. 

Today's lesson was a great example of how incomplete my programming knowledge is. Though I know how to manipulate strings and create objects, Brian taught me a lot about what goes on behind the scenes that will be crucial to debugging my code. I never could have explained heap or stack before today. 

After class, we had a pathway event where Ben gave a presentation on how to craft an elevator pitch. He emphasized that we will have a lot of opportunities throughout our career (and our time at tech elevator) to introduce ourselves to people who may be beneficial to our network. When we are faced with the dreaded question of "So, what do you do?" we need to be ready to concisely describe ourselves, our motivations, and our goals. We got to see some examples of elevator pitches and even got time to work on our own. Ben and Vinny both explained how these pitches will never be recited verbatim in a real life scenario, but that having a rehearsed pitch on deck will allow us to improvise an relevant narrative when the opportunity arrises to talk about ourselves. 

Tonight I will be attending my first programming meetup. The Columbus Ruby Brigade is holding a talk downtown. Maybe tomorrow I will include a little summary of my experience. 


