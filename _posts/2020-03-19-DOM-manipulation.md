---
layout: post
title: Day 49 DOM Manipulation
summary: Today we learned about manipulation the document object model and populating webpages with javascript.
---
The Document Object Model (DOM) is a programming interface for graphical representation of documents loaded in the browser. HTML source code is not the same as the DOM, but they are often similar. The DOM is made up of nodes in a tree structure. A Node is a representation of an HTML element but does not also match an element in the actual HTML page. 

If we want to manipulate the DOM, we first select a node, then select an element which is a child of the node. An element is a representation of an HTML tag. 

Some ways to manipulate the DOM in js: 
```
document.getElementById('header').firstChild().innerText = 'Title Page';

const arrList = document.querySelector('cssSelector').querySelectAll('li');

document.getElementById('main').lastChild().setAttribute('class', 'purple');
```
We covered a few other examples but most of this DOM manipulation stuff will require online documentation for specific ways to select and manipulate certain elements on the page. 

I'll note one last thing we covered in class today: HTML templates. In order to avoid typing a lot of the same code in our javascript files, we can create HTML templates in our HTML files. So long as these templates are empty, they won't load anything on the page, but will give us a pre-built for to copy and then populate and insert into the DOM using javascript.

We clone the node like this:
`let node = content.cloneNode(true);` We can use this if we want to say, create a specific div for each element in a list we return from a database. 
