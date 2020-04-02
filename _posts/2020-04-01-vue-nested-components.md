---
layout: post
title: Day 58 Nested Components in Vue.js
summary: We learned more about view components, how to nest them, how to emit and capture events from them. In the afternoon, we talked about final capstone projects!
---
Vue components was the topic of today's lecture. Components are re-usable parts. Two main subsections: 
1. Components - reusable chunks of code (e.g. nav bar) are still called components
2. Views - components representing full page views

In view, we can nest components. For instance, a product list page can have a search bar component, a navigation bar component, and a product list component as children. Today we learned that in Vue, children components have to talk to the parent components in order to communicate information to sibling components. 

The way we learned to handle this communcation is by emiting an event in the child `$emit('event_name', event_value)`. In the parent, we manage the event with `v-on:event_name=handleEvent()`. In the `handleEvent` function, we can set properties based on the event being fired. This would allow us to "see" the change in other child component. 

#### Final Capstone Projects
In the afternoon, we covered final capstone projects. The instructor from the .Net class, John, went over the basic expectations and guidelines for the final project:
* Two week long project. 
* 3-4 person teams. 
* No cross-class pairings. 
* Entirely Remote. 
* Deliverables in the form of user stories on Trello boards. 

There were 12 different projects to chose from--some student submitted (one by me!), some from the past, and one from a real business. We were asked to chose our top three projects. My top: 
1. `Vegetable Farm Planner` - my submission. Software to help farmers manage inventory, plantings, harvest, and sales.
2. `Study Chat Bot` - a chatbot which helps students study. Asks you random questions, etc.
3. `Sports Team Scheduler` - a basic application that stores data about teams in a sports league and creates/manages game schedules for the league.

We won't necessarily get one of our top three choices, but instructors are aiming for that to be the case. We'll write a full-stack web application with tests that meet the requirements for whichever project we are assigned. I hope I get to build my submission! 
