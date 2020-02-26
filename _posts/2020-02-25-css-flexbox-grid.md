---
layout: post
title: Day 32 Handling Reactivity in CSS with Flexbox and Grid
summary: Flexbox and Grid make managing reactivity in css easy. We learned all about it today while designing a fall festival website. Employer showcase at lunch. 
---

Today in class we learned about the *flexbox* and *grid* display options in CSS. Yesterday we had *block* and *inline-block* at our disposal but it was still difficult to get things to line up correctly while resizing the browser.

Grid allows us to define a grid in which items line up. Labels we give to the grid can be linked to html elements as a way to tell CSS what to put where in the grid. `fr` refers to the unit of the grid and periods are used for spaces.

The container:
```
.container {
    display: grid;
    grid-template-columns: 2fr 4fr 2fr;
    grid-template-areas: "header nav-bar ."
                         "sidebar main main"
                         "footer  .     .";
}
```

The children:
```
.header {
    grid-area: header;
}
```

An example of flexbox is a bit simpler because all css goes in the container. 
```
.container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}
```

Of course, these are many ways to implement and combine these two and many options no detailed here.

#### Employer Showcase:
After class we had an employer showcase. I'm starting to get use to these showcases. The companies that come in and present pay the bill for catered lunch so they can teach us about their companies. The gesture itself makes me feel valued as a Tech Elevator student. 

Today was Huntington. Though I've never been excited about working at a bank, I liked Huntington's presentation a lot. They came right out and said they were a corporate environment but then focused on the value they can provide junior developers in terms of growth, learning potential, and support. The software architects they brought in were excited about the power of developing using Salesforce in a way that was contagious. 

One of the architects spent a good amount of time echoing something we've heard a few times: ask questions during interviews! He gave us examples of questions to ask so that we can get a feel for what it's like to work on a team, what their development cycle is like, and how people work together.
