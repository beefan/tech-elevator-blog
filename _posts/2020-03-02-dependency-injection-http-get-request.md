---
layout: post
title: Day 36 Dependency Injection & HTTP Get Request
summary: Monday week 8 was about new object oriented principles and correctly using the HTTP Get request in JSP.
---

Today started off with a lesson on **Inversion of Control**. Brian said this Objected Oriented Principle is often refered to as the Hollywood Principle (We'll call you; Don't call us). He tied this concept to **Dependency Injection** saying that though dependency injection is the design pattern which implements inversion of control, the two terms are often used interchangably. 

Dependency Injection is a design which instantiates classes and injects them into classes which run them. The idea is that this contributes to modularity and allows for pieces to be easily swapped. 

We also learned about HTTP Get requests. These are requests made by the client browser which change nothing on the server side. There are parameters in the query string which are passed to server-side methods. A `Request Header` defines the request while a `Response Header` defines the response. Brian took some tens of minutes to draw a complicated version of the MVC diagram on the whiteboard with lines going every which way. This diagram was way too complicated to digest in a few hours of class, but the point is that a lot is happening when the client makes a GET request. Understanding what is happening is not critical, but it knowing we can consult the diagram if we run into issues is.

For now, it is important that we understand a form contains an action with the URL to receive the GET request. We then create a controller class which responds the the request and builds a reponse. 