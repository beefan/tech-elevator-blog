---
layout: post
title: Day 41 Selenium and Cucumber Testing
summary: Selenium facilitates writing automation around the browser. Cucumber allows non-technical members of teams to write behavior driven development features in natural language. Today, learned how to use both for testing. 
---

`Selenium` allows us to essentially drive through the browser like we do in manual tests but at automated speeds. In our unit tests, we can instantiate a `WebDriver` and use to to load pages, find elements on the page, and interact with the elements using clicks or keystrokes. 

A design pattern that helps us write coherent tests is the `Page Object Pattern`. Under this design pattern, we create one Java class per web page. Each page enscapsulates methods which represent thigns we can do on the page. Then, we can write tests which are readable by virtually anyone. 

`Cucumber` is an acceptance testing framework which helps us test features defined by product managers or business analysts. Analysts can write features in a language called `Gherkin`. Feature files follow the pattern of: `GIVEN` a particular state of system `WHEN` an action is taken `THEN` result occurs. 

As a developer, we write `Cuke` files which provide hooks from the natural language in the feature file to our programming language. The result here is super readable tests which involve non-technical team members in the process. 

Cucumber utilizes Selenium and the Page Object Pattern and can't easily be implemented without them to test web applications. 