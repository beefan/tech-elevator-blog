---
layout: post
title: Day 38 Sessions and Cookies 
summary: HTTP is Stateless meaning it always forgets what it just did. This is great for security, but what does it mean for storing data? Today we look at using cookies to store session information.
---

Benefits of HTTP being stateless:
* simple design
* limits server storage
* scalable

Drawbacks:
* no easy way to remember user information

A **Session** is established when a user first starts an application and expires when a user logs out or after a certain amount of time has passed. The session is maintained accross a series of requests and responses. 

A **cookie** is a small piece of data a browser stores on a client's computer. One piece of information the cookie contains is a user's session ID. Now when a user changes pages and HTTP forgets what's happening, the browser can say, "Hey, this is the session ID we have in our cookies." 

And then the server can say, "Oh cool, here is the information we have pertaining to that session." 

#### Meetup

After class today I attended a meetup at Accenture with the Columbus Machine Learners group. We have had so much work assigned this week (at Tech Elevator til 6pm every night) that I wasn't sure attending meetups was the best way to prioritize my time. I'm glad I stuck to my RSVP though because this was one of the most interesting meetups I've been too yet! 

The speaker, David Weirich, shared his approach to training a recurrent neural network to generate its own Sabrina the Teeange Witch scripts. He went through the high level process with us on the whiteboard and then browsed through the code in sections. Finally, he ran the model on a low training time just to show us an example. 

Most of the text was nonsense with such a short training time, but it was still really cool to see and learn more about. Prospects of working in natural language processing keeps me engaged and dreaming. 

