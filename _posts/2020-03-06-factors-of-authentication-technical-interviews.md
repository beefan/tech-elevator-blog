---
layout: post
title: Day 39 User Authentication & Technical Interviews 
summary: On this Friday we talked about user authentication, app security, and potential exploits. After that, we had a presentation about technical interviews to prepare us for what to expect in the near future. 
---
Authentication is verifying user account information to allow them access to our applications. This is a much more difficult issue than it initially seems. Passwords can be easy to crack and at the same time impossible to remember. There are other ways to verify user access:
1. Knowledge Factor - this is a typical password, something a user has to remember
2. Ownership Factor - RSA token, credit card, something the user has physical access to
3. Inherence Factor - Something inherent to the user like biometric data

All of these factors have flaws. 2 Factor authentication utilize two of these factors to enhance security. If we rely purely on the knowledge factor however, we learned that a longer password is more important than one with special characters. The new trend is to use pass phrases such as `MyGoodDogLivesInABlueHouseDownTheStreet`. Really long password and therefore difficult to crack, but at the same time easy to remember. 

We also talked about Authorization or Access Control. By defining roles in your application, you can prevent a typical user from doing things that an administrator might want to do in the application. Different roles will allow different levels of access to features in your application. 

After that we learned about a few different types of exploits to account for in our application design. I won't go into detail here but I will list them: 
1. Session Fixation 
2. Cross Site Request Forgery Attack
3. Open Redirect 

#### Pathway
After lunch, we met in the Elevate Space to hear a presentation on Technical Interviews. One huge takeaway which is consistent with what I've been hearing all throughout this program is **show your passion**. If we can't illustrate our enthusiasm for technology, we are significantly disadvantaged in our job search. Some other takeaways: 
* We must be able to explain everything we've learned throughout the cohort and articulate our own experiences with each technology.
* We must be willing to admit that we don't know things, but ask detailed questions to show how we approach solutions to problems for which we don't immediately know the answers. 
* We should be able to quickly walk through our capstone projects and our personal projects with examples of what we found easy and what was hard for us. 
* We have to be honest about our knowledge gaps while highlighting what we do know. 
* It's okay to pause or ask to repeat a question while we come up with a response. 
* Bring notes on questions to ask, both specific clarifying questions about the company and broad technical questions that are important to personal goals. 
