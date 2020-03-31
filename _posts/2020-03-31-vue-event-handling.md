---
layout: post
title: Day 57 Vue Event Handling
summary: We covered Vue.js event handling in class today. 
---
Today we learned how to manage events in Vue.js. In vanilla javascript, we used DOM manipulation to get access to specific HTML elements and then added event listeners to the elements. With Vue, adding event listeners is much easier:
```
<button v-on:click="showForm()">Show Form</button>
```
This code registers `showForm` function to the click of the button. 

Brian was sure to remind us that Vue processes everything we type in our code into javascript that runs in the browser. What this means in the case of event handling is that we can create event listeners for the same events we learned last week. If you can do it in vanilla javascript, there is probably a way to implement it in Vue using `v-on:<event>="function()"`. 

In class, we practiced Vue event handling by building a review page which loaded reviews from data, show/hid a form, allowed users to submit a review, and implemented filtering by rating. 

#### Pathway
After class we had a brief pathway presentation to talk about next steps in our job search now that Matchmaking is over. Ben and Vinny re-iterated what we've been told before about applying to **at least** 3 jobs per week (preferably 10 or more). They also talked about finding recruiters by email to emphasize interest in the position. They also spent some time re-assuring us that businesses are adjusting in real time to work under coronavirus and opportunities will multiply once adjustments have been made. 

After the pathway event, I had a second round interview with BigLots. This is the first connection made during Matchmaking to bear fruit so far. I tensed up during a basic question about servlets (Servlets are objects that receive a request and generate a response based on that request!) but other than that the interview went pretty smoothly. 