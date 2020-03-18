---
layout: post
title: Day 48 Functions, Documenting Functions, Anonymous Functions, Array Functions
summary: Functions, functions, functions! Today we covered all sorts of Javascript functions and presented our capstones from module 3. 
---
Today was better in the remote world. I went out and bought a mini-display to HDMI adapter last night so that I could use my TV as a second monitor. I took the interviewer's advice from yesterday and moved my desk to face a window. I cleaned my room and prepared my work space with intention. I'm adjusting. My mindset is shifting and I'm starting to settle in to how things are just going to be.

We covered javascript functions in class. We talked about anonymous functions which are simply functions without names. 
```
function blastoise(foeName) {
    return `${foeName} is hit with hydropump`;
}
```
becomes 
```
(foeName) => return `${foeName} is hit with hydropump`;
```
Then we learned a use case for anonymous functions: array functions. There are many functions on an array such as `reduce()`, `map()`, `forEach()`, `filter()` that take a callback function as an argument. As easy to understand example of this is: 
```
let arr = [1, 2, 3, 4, 5];
arr = arr.filter( x => x % 2 == 0);
console.log(arr);
    --> [2, 4]
```
In that example, the callback function is a simple function that checks if a number is even. Here are a few ways to write the same thing:
```
1. 
let filterEvens = (x) => {
    return x % 2 == 0;
}
arr = arr.filter(x => filterEvens(x));

2.
function filterEvens(x) {
    return x % 2 == 0;
}
arr = arr.filter(x => filterEvens(x));

3.
arr = arr.filter( 
    x => {
        return x % 2 == 0;
    }
);
```

Just from the work I've done trying to understand node.js, I have a feeling that anonymous functions are going to play a huge role in working with javascript. 

The last thing we covered was javascript documentation. This is very similar to javadoc we used in Java.

#### Code Reviews
After class, we presented our capstone projects from module 3. The virtual presentation was not so intimidating and we were able to share our screens very easily. Austin and I both shared a little of what we were most proud of, he walked through the application itself, and I went through the tests we wrote. 

It was cool to see what some of the groups accomplished under the creative license of "make it your own". 


