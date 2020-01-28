---
layout: post
title: Day 11 More on Inheritence
description: Today's lesson focused on inheritence. 
summary: We started week three talking about inheritence and designed Ticket classes to demonstrate.
tags: [OOP, inheritence, lightning talks]
---

Today we spent a lot of time talking about inheritence. This is a topic I explored in Java when I worked at IBM as an intern, so it wasn't the most exciting day of learning. A superclass is essentially a parent class. The children classes are called subclasses. Any subclass inherits behaviors and attributes of its superclass. 

This functionality allows for specificity to be built on top of a basic set of attributes and behaviors. The example we used in class was a Ticket superclass and subclasses WillCallTicket and UnderageTicket. Both subclasses have attributes not contained in the super, but also inherit attributes from the Ticket class.

One thing I learned today that wasn't made clear to me in the past is that subclasses only inherit public attributes and methods. In order to call methods not inherited, you can use super.methodExample();

After class, we spent time working on pair exercises demonstrating these concepts. I also met with Andrew to go over my slides for a lightning talk I'm giving tomorrow. More on that then. 
