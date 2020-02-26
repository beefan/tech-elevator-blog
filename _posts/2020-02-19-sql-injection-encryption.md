---
layout: post
title: Day 28 SQL Injection & Encryption
summary: Brian showed us how to do simple SQL injections and explained how to santize inputs to avoid them. We also learned about encryption and how it can used to increase security on the internet. 
---

We started the day off learning about SQL injections. Brian showed us an example of how to execute one on a sample web application (while at the same time making sure we understood it might be illegal to attempt an attack of our own). Bascially, a SQL injection is an attack where someone enters a SQL command into a form on a website which is run upon submission. This command can get access to numerous records in a database if proper security has not been enabled.

Luckily with SpringJDBC and parameterized queries, there is a simple way to sanitize our inputs and prevent such an attack. Brian told us that there is really no reason why web applications should be subject to such attacks in present day, but that doesn't mean there aren't plenty of vulnerable websites out there.

We also learned about encryption. Brian taught about how passwords are often hashed and then hashes are stored in the database. Then at login, the password is hashed and the hash is compared to the one stored in the database. This design prevents passwords being stored in plain text. Even if the database is comprised, attackers then still have to decrypt the passwords which takes some significant computing power. 

There are a few different hashing algorithms, but all of them take some text and provide a completely unique hash of a constant length. Change the text by even one character and the hash is completely different. Everything from encrypted email to the https protocol uses this technology. 

#### Pathway: 
After class we had a pathway meeting about employement types and recruiters. The types of employement Katie compared were: Full time employment, contract to hire, and free lancing. The only benefit I see to contract work is the potential to learn many different technologies and work with many different people. Full time employment offers the most security by far. 

#### Interactive Workshop:
Later on in the evening, Andrew put on an interactive Git workshop. In our day-to-day at Tech Elevator, we use basic Git commands. Andrew helped us to learn about merging and branching while also introducing us to a way to safely practice other git commands with [git katas](https://github.com/praqma-training/git-katas.git).


