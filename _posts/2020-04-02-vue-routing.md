---
layout: post
title: Day 59 Vue Routing
summary: Today we covered route handling in Vue. 
---
I'm feel like it's the last week of class my senior year. It's getting harder and harder to focus as we approach the final projects. It's a strange state of mind that scoffs at over-consumption of new information and desperately craves the opportunity to put it all into practice! 

Today was the second to last day of class. The mental and emotional fatigue that comes with the final weeks of any education program are unfortunately intertwined with the forms of fatigue a global pandemic brings. 

Programmers are experts at finding information they need and understanding how to use it. That's the skill of programming, not memorizing exact syntax. With this in mind, it's easy to feel eager to jump ahead to the final capstone. I can read the Vue documentation to find out how to handle routing! 

Slow down. Breathe. Today **Brian** taught me about Vue Routing.

In a typical web application, you can use navigation buttons in the browser to go backwards, forwards and to bookmark internal urls. In Vue, you have to handle navigation manually. 

The terminal command `vue add router` adds a router.js file to your Vue application where you will set up routes. In this file, you add the routes in the form: 
```
{
    path: '/products',
    name: 'products',
    component: Products
}
```

Then, when you want to create a link to the page you use `<router-link>`:
```
<router-link :to="{name: 'products'}">Products</router-link>
```
The `<router-link>` tag is rendered as a `<a>` tag by default but you can add the `tag="element"` attribute to change the element rendered on the page. 

Tomorrow we'll learn about RESTful APIs in Vue and then its off to building our own applications!  
