---
layout: post
title: Day 53 Fetch and Asynchronous Code
summary: Today we covered using the fetch API to get data from web services. We also talked about what it meant for code to be asynchronous vs. synchronous. 
---
The fetch API is a universal interface present in all browsers that we can call from javascript to easily connect with our web services. 

Previously, we covered how to set up API endpoints in our Java code. We would use fetch to connect with those endpoints and pull server data into our web application. In class and for exercises, we simply pulled data from a local JSON file, but the idea is the same.

Here's the syntax for a proper fetch, pulled from my solution to tonight's exercises:
```
/**
 * Fetches Grocery List from a JSON file
 */
function loadGroceries() {
    fetch('assets/data/shopping-list.json')
        .then( response => {
            return response.json();
        })
        .then ( groceries => {
            displayGroceryList(groceries);
        })
        .catch( error => console.error(error) );
}
```

This code is **asynchronous** because it does not wait for a response. Code after the fetch continues to run until the response is returned. In this instance, if `displayGroceries()` populates some HTMLElements and after the fetch we tried to insert those elements into the page, we would get an error! This is because javascript will move along and try to insert them before the response is actually returned. 

The opposite is **synchronous** code. This is what we are used to. One function runs, we wait for it's response, and then the next code runs. 

#### Pathway
After class we had a pathway event to debrief from Matchmaking yesterday. Ben and Vinny gave us a pep talk about job searching in the middle of a pandemic. Short version: things are changing, opportunities are too; stay bright and focused. 

Feedback from the employers who attended Matchmaking was good but the emphasis on this particular event was really about providing us with the guidance necessary to continue our momemtum and invest our energy even more into the job search. 
