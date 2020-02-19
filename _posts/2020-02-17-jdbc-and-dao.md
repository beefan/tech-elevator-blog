---
layout: post
title: Day 26 JDBC and Data Access Objects (DAO)
summary: Week 6 Begins with the integration of Java and SQL. Today we learned about JDBC, Spring JDBC, and Data Access Objects.
---

Today was a big day. The pieces of functional web application development are coming together. Our substitute instructor, Andrew, taught us about how we use Java to interact with our database. We learned about Java Database Connectivity (JDBC) and Spring JDBC but only in a limited context. Simply:

> ### Spring JDBC --> JDBC --> JDBC Driver --> Postgres Database 

The JDBC driver connects to the database. JDBC connects to the driver. Spring JDBC acts as a wrapper around JDBC to make it easier to interact with the database as a developer. 

Beyond this simple understanding, I couldn't explain what Spring actually is though I used it at IBM and I remember spending a lot of time troubleshooting its usage. 

After glossing over the way things glued together, we jumped into Eclipse and looked at some implementation. Essentially, a row in a specific database table translates to a class in java. We build a DAO interface which maps to a particular table and create the methods we need to access specific data. Then, we implement the DAO in another class which builds the SQL strings and uses Spring JDBC to run the queries. 

### Meetup

In the evening, I went to another Columbus Ruby Brigade meetup at CoverMyMeds. [Glenn Harmon Jr.](https://www.linkedin.com/in/glenn-harmon-jr-2b1a691a/) gave a talk on The Value Of Small PR. PR = Pull Request. The essential thesis was: push smaller changes to your code base instead of larger complete features to avoid lengthy code reviews, unmanageable bugs, and doing too much. There's no doubt I will be considering this talk as I write my first professional lines of code. After Glenn spoke, the Columbus Ruby Brigade announced they will be hosted by Root Insurance from this point on. 

I didn't stay long after that. There were many interesting companies represented in the room who all announced they were hiring (CoverMyMeds, Root Insurance, Upstart, etc. ) not to mention nearly ten other Tech Elevator students, but I didn't have the energy to socialize. I will be back! 

