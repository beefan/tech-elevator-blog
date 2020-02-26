---
layout: post
title: Day 27 Integration Testing
summary: Unit testing is great for testing business logic, but today we learned how to test our connections with the database are working as expected. 
---

Integration testing is testing the integration of our java code with the other components, such as the database. Integration tests are slower to write and also slower to run. Usually, they are part of a series of tests which must run together to determine if a particular method is working as expected. 

We run our tests not on the production database however, but instead a locally hosted database, an in memory database, or a remote shared database. Other than that we use some of the same tools we used for unit testing. We can think about the structure of the test the same way: 
* Arrange - set up what is to be tested
* Act - perform the function to be tested
* Assert - check that the result is the expected result 

The most important thing about testing the database is to start a transaction in the setup, and in the teardown rollback the changes and close the database connection. 

#### Employer Showcase:
After class, we had an employer showcase. Root Insurance company came and presented information about their company and interviewing for technology companies in general. The culture at Root is highly desirable and they are hiring 60-70 engineers this year alone. !!

The tips they gave us for general interviewing are great and I'll reproduce them here: 
1. Be passionate about projects the company is working on
2. Understand the technology stacks they are using, even if you don't have experience in them
3. Get a feel for what it's like to work there
4. Ask lots of questions. Interviewing should be a two-way street. 
