---
layout: post
title: Day 37 HTTP Post Requests, Method Binding, & Autowiring
summary: Today we covered HTTP post requests, binding request parameters to methods in the controller, and autowiring data access layers. We also had an employer showcase with CoverMyMeds and mock behavioral interviews. 
---

So yesterday we learned about GET requests. This is one way to pass information around in a web application, but you can't use it for sensitve data and there is a size limit on the data. GET requests also should never change the state of the server. 

POST requests on the otherhand can change server state, encrypt information, and overcome limits of size. A post request can also solve an issue pertaining to user refresh. If a user submits a form and the application uses a get request, a simple user refresh will cause the form to be submitted twice. A post request doesn't automatically fix this issue, but following the `POST-REDIRECT-GET` pattern will. Using this pattern your application posts form information, does something with it on the server side, redirects to a different page, and then gets the proper information to populate that page. This prevents a reload from resumbitting the form. 

Two ways to get form data in the controller following a post request. One is similar to how we have done it with GET:
```
@RequestMapping("/formSubmit")
public String postForm(HttpServletRequest request) {
    String formElement = request.getParameter("formElement");
    //do something with form element here
    return "formReturn";
}
```
With `method binding` we can do it simpler: 
```
@RequestMapping("/formSubmit")
public String postForm(@RequestParam String formElement) {
    //we can now access the form element here
    return "formReturn";
}
```
We bound the parameters from the form to the method.

The last thing we covered is `Autowiring`. In SpringMVC we can instantiate database access objects by configuring our database information in an xml config file and then added the autowire tag to the variable in the controller like this: 
```
@Autowire
CityDao cityDao;
```
The autowire tag looks for any class that implements the CityDao interface and has the `@Component` tag. Not only is this less code, but it lends itself to easily swappable implementations. 

#### Employer Showcase 

For lunch, CoverMyMeds came in to introduce their company and their apprenticeship program. They are a local startup company 1300 employees large and growing. Their focus is on speeding up the prior autorization process to get patients their medicine (and big pharma their money...) faster. They have a plethora of incredible benefits and it seems they genuinely care about meeting their employee needs and empoyering them to feel comfortable doing their best work. Not to mention, they invest in community libraries, meetups, and other organizations. This is the new corporate culture and I'm about it. 

CoverMyMeds does not hire junior engineers. Instead, they hire apprenctices as $25/hr. The apprenticeship is an intensive learning experience where individuals get mentorship from senior devs and test their fit with the company. After 6 months, discuss your career potential and hopefully negotiate a salary. 

#### Pathway

Today was the first on a series of mock behavioral interviews. Our pathway directors are out for the time being so we had a consultant come in and run them. These interviews are structured in small groups, each being asked two questions. We have a chance to give feedback to each other and openly reflect on our own responses. The questions we are practicing are "Tell me about a time. . ." type questions. 

The pathway directors have given us a structure to use for crafting responses: the STAR model. First we describe the **situation**, then a **task** we embarked on. Most importantly, we outline an **action** we took and describe the **results** of that action. These answers are supposed to be clear and interesting stories that help employers understand us and our developement. 

I was dreading this interview but when it came down to actually answering the questions, I enjoyed it a lot. The questions were challenging, but the practice was rewarding. I feel much better equipped to tackle these questions in an interview. 

