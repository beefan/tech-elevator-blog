---
layout: post
title: Day 60 RESTful APIs in Vue
summary: Today we covered REST APIs in Vue (or how we will connect Vue frontend to our Java code). In the afternoon we had a presentation on Agile/Scrum methodolgies. 
---
In our last day of class we learned about REST APIs in Vue. We learned about MockAPI.io which is a service that provides free dummy APIs. We used this throughout class to show we were handling our request correctly in Vue. If it works with the mock apis, it should work when we get our API endpoints completed in Java.

A while back, we learned about using `fetch` blocks to get data from APIs in javascript. Well, it works very similar in Vue. The only main difference is where we put the fetch in the code.

Vue has built in lifecycle hooks. These are methods that Vue calls at certain points in the loading of Vue components. A commonly used one is `created ()`, called when the document is first created and similar to the vanilla javascript event `DOMContentLoaded`. 

We learned that the `created` lifecycle hook is a good place to use `fetch` to receive the intial data necessary to populate the web application. We also covered writing fetch for POST, PUT, and DELETE API calls.

#### Agile/SCRUM
In the afternoon, we had an outside Agile/Scrum trainer, Jim Sammons, come in and show a presentation about Agile and Scrum. He taught us that Agile is more than a set of methodologies--it's really a mindset about building software. Scrum is the set of practices that make promote and manage the Agile mindset. 

The main Agile techniques are:
1. Daily Standup - meet daily with the team to talk about progress/blockages
2. Sprint/Iteration Planning - planned phases of development
3. Retrospectives - meeting for each sprint to discuss how groups can work together better
4. Sprint/Iteration Review
5. Short Iterations

The main Scrum Values are:
1. Courage
2. Focus
3. Commitment
4. Respect
5. Openness

In our final capstone, we are going to be tasked with putting these methodologies into practice!