---
layout: post
title: Day 34 Spring MVC Framework, Scope, Expression Language
summary: Learned about scope in Spring MVC, Java Bean standards, dot operator in Expression Language. First round of mock interviews. 
---

Today in class we learned about the `RequestObject` in Spring MVC. In the Model View Controller handled by Spring, there is a request object which keeps track of different variables we might need throughout the application. All of these scopes are maps which store a key and a value. 
1. RequestScope - available in the duration of a single request. Default scope in Java.
2. SessionScope - available for the duration of one user visit to our site.
3. PageScope - available to a singular JSP file. Default scope in JSP. 
4. Application scope - another scope we won't use much. 

Variables in these scopes are accessed through explicit invocation of the scope map or through **Search Order**. Search order is the order in which Spring searches for variables if the scope is not declared. First it checks the page scope, then the request scope, and then the session scope. 

We also learned about the standards we must follow when creating simple java objects (java beans). If we follow naming conventions and make proper getters and setters, we can use the **dot operator** to call those getters and setters in JSP. Using the dot operator inside Expression Language allows us to called limited java functions without passing in arguments. For example, calling getters like `${ variable.name }` where .name calls the `getName()` method on the variable bean. We can also use some string functions like `${ str.substring(0, 4) }`. 

#### Pathway 
We had our first mock behavioral interview today. Tech Elevator brough in real recruiters to interview us over the course of the afternoon for about 25 minutes each. I thought the interview went well and the woman who interviewed me gave me some extremely helpful feedback. I'm itching to get started with real interviews!  