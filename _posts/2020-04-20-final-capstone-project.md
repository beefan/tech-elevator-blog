---
layout: post
title: Days 61-70 Final Capstone Project 
summary: This post is a summary of the final two weeks of Tech Elevator, where we worked on our final capstone projects. Our team built a Vegetable Farm Assistant which used Java for the backend and Vue.js for the frontend.  
---

Instead of make a post every day about what was going on in the final capstone, I chose to focus on the capstone project and come back for the recap. I took the weekend to relax and reflect on the entirety of my experience at Tech Elevator. In this post, I hope to show a little of that reflection as well as share the final project. 

### The bootcamp
When I first graduated high school, I wanted to be a software developer. I spent time in python, java, and C# before taking some time off to explore my interests in farming and writing. When I never lost interest in solving problems using software, I started looking for ways to get back into it. A bootcamp was attractive because it promised quick results and career coaching. I enrolled in Tech Elevator. 

So, how am I feeling now that I've finished? 
* More confident than ever that I am ready to launch a career as a full stack developer.
* Interview compentent due to all the interview/linkedin/resume coaching. 
* Excited to continue the pace of growth through personal projects.

And in the middle of a pandemic?
* Nervous about the job market and potentially going back to retail work.  
* But optimistic that things will turn around and I'll be ready.
* Eager to use the extra time spent job searching to boost my github page. 

Finishing a bootcamp in the middle of a pandemic is not ideal, but overall I was impressed with how Tech Elevator pivoted and how prepared I feel despite what seems like a temporary economic freeze. My software skills and habits have been refined. My career development skills have been expanded. Even viritual matchmaking turned out to be a great success. I didn't get the in person instruction during module 4 that I really wanted from this program, but the virtual substitute has still led me to feel prepared for the future.  


### The final capstone
**Team Name:** Bravo

**Project Name:** Vegetable Farm Assistant
 
**Team Members:** Brian, Lucas, and Noah

**Objective:** Create a web application to help small veggie farmers manage their seeding, harvesting, and logging as well as generate daily action items and weekly sales reports.
 
**Solution:**
* Tech Elevator instructor staff pre-populated a Trello board with user stories represented in cards. 
* We met every morning for SCRUM meetings to talk about what we accomplished yesterday, hope to accomplish tomorrow
* We ran short sprints lasting just two days and follow sprints with:
  * demos/card approval
  * retrospective meetings
  * planning for the next sprint
* For the most part, we wrote the entire application using **mob programming**-- a technique where one person shares their screen while the rest of us suggest code to write. We rotated the "driver" every few hours. 
* We worked in 10-12 hour days to accomplish our sprint goals. 
* Tech Stack: 
  * **Java** to write our API endpoints and data access layers
  * **Postgres SQL database** to store our persistent user data
  * **Vue.js** to make requests to java and display information to user
  * CSS/HTML in Vue to make a pretty user interface
  * SCSS css pre-processor
  * chart.js to display sales/harvest data graphically

**Screen Shots:**
![home]({{ site.baseurl }}/public/capstone-screens/home.png "Home")
![login]({{ site.baseurl }}/public/capstone-screens/login.png "Login")
![crop-planner]({{ site.baseurl }}/public/capstone-screens/crop-planner.png "Crop Planner")
![farm-log]({{ site.baseurl }}/public/capstone-screens/farm-log.png "Farm Log")
![seeding-times]({{ site.baseurl }}/public/capstone-screens/seeding-times.png "Seeding Times")
![charts]({{ site.baseurl }}/public/capstone-screens/charts.png "Charts")
![contact]({{ site.baseurl }}/public/capstone-screens/contact.png "Contact")

**Reflection:**

I was nervous going into the final capstone project primarily because I didn't know how we would accomplish virtual collaboration. From the beginning, we started developing our application using mob programming. 

I was amazed at how easily the mob style allowed us to stay on the same page, mutually understand every line, and rigoriously vet everyone's ideas on the spot in real time as they were implemented. It was only a little awkward at first, but because we were working such long days, the voices and screens of my teammates quickly became extensions of my room. It became incredibly comfortable to exist in a Zoom room, writing software with three other people. 

I enjoyed the **Agile** management of this project by the tech elevator staff. Even though sprints were incredibly short two day bursts, it was awesome to have morning SCRUM meetings and retrospectives not only to hold ourselves and our team accountable, but to also create an opportunity for communication and team development. 

As a result of these meetings, and our dedicated work we began with a simple CSV uploads of seeding times and landed with a dashboard page full of graphs and statistics to help farmer's make decisions. Largely due to Brian's design eye, our application is sleek and easy to navigate. On the backend, we wrote integration tests for every data access object to ensure our data was flowing properly to the front. We took time to polish and squash bugs in SQL queries and our vue components. We delivered a highly functional and beautiful application that I'm proud to show off as a culmination of my learning and experience at Tech Elevator. 

We finished off the program with an internal virtual demo and an external virtual expo. We rehearsed our 5-min presentation a few times so that we would be succint, yet encompassing in our description of app functionality. The internal demo went by very quickly and before we knew it, we were in a Zoom room demoing over and over again as more than 30 people came in and out to see our project. Kudos to all of the staff at Tech Elevator who organized such an awesome and successful way to showcase our final work and end the progam. 

This has been a challenging, engaging, and empowering 14 weeks. I'm excited for the future. 
