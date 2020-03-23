---
layout: post
title: Day 50 Event Handling
summary: Today we covered event handling and the observer/listener pattern
---
We covered event handling today in class. Events are actions or occurences in an application. Events are not exclusive to web applications.

The basic pattern we learned to handle events is:
* Register a listener/observer to a DOM element
* Define the callback function 

```
document.getElementById('groceries').addEventListener('click', event => callBackFunction);
```

Some common web events are:
* click
* dblclick
* mouseenter
* mouseleave
* hover
* focus
* blur
* keypress
* keydown
* keyup
* load
* unload

The most important web event however is, `DOMContentLoaded` which is triggered once all the elements on the page are loaded. This is a good time to register call any javascript to run on the page. 

We also covered **event propogation** which means that you can register a listener on a parent element and if an event occurs on a child, it will propogate up to the parent.



