---
layout: post
title: Day 38 Server Side Validation & Flash Attributes
summary: Today we learned about server side validation using the Hiberate Validation library. We also learned about using flash attributes to pass information temporarily through a redirect. Accenture came in for lunch to showcase the Columbus Innovation Hub.  
---
Previously this week we learned about the POST-REDIRECT-GET design pattern. Because Http is stateless the GET has no access to the information in the POST. Using **flash attributes**, we can put any object of any type into a temporary scope. Flash attributes are stored for just one more request and allow us to do things like display confirmation numbers to the users. 

**Server side validation** was the big topic for the day. Validating input data is important because if users input types of data we don't expect, it can break our applications. There are client side validation libraries and server side. Server side is slower and less responsive, but we need both to make a secure application. Today we learned a server side validation library called Hiberate Validation. There are a lot of steps to the process, but it isn't too difficult of a concept. Steps:

Model
1. Add validation annotations on the model

Controller

2. Add empty model in the GET request to bind to
3. In POST add `@Valid @ModelAttributes("modelname") Modelname modelname` as a parameter
4. In POST add `BindingResult result` as a parameter
5. Check `result.hasErrors()` to see if validation successful

View

6. Add Spring form tag library to JSP files
7. Use Spring form instead of HTML forms with `modelAttribute="modelname"`.

#### Employer Showcase 
Accenture came in for lunch to talk about their company. They were the first company that sent four tech people and no HR representatives. This was kind of cool. Accenture is a gigantic global consulting company with nearly half a million employees in 120 countries. 

But at the Columbus Innovation Hub, there are only 150 employees working on small teams. The Hub focuses on [xtreme programming principles](https://www.agilealliance.org/glossary/xp/#q=~(infinite~false~filters~(postType~(~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'xp))~searchTerm~'~sort~false~sortDirection~'asc~page~1)), pair programming, and constant learning. At the hub, the focus is on writing good code with no pressure on finding clients.  

#### Meetup
[Front End Happy Hour](https://frontendhappyhour.com/) came to Root Insurance downtown tonight for a live recording of their podcast. The topic was Design Systems. Representatives from Root, Kiva, Netflix, and Atlassian were on the panel. It was amazing to hear the thought processes about design coming from these incredibly smart professional designers. 

Met a few people from Root's product design department and chatted with some Tech Elevator students that also attended. One key takeaway I left with was that the importance of communication between design and engineering cannot be overstated. 
