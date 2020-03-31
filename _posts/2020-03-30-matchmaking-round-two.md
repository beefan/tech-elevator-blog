---
layout: post
title: Day 55 Data Binding in Vue.js
summary: We covered data binding in vue today. Basically, how do we get our data to populate into our vue components?
---
Vue isn't exactly intuitive (from where I'm sitting at least). Inside the script tag, we can have something that looks like this:
```
data() {
    return { items: 
            [
                {"name": 'fish', "cost": '32'},
                {"name": 'tomatoes', "cost": '3'}
            ],
            isOpen: true
    }
}
```
This makes a simple javascript object available in our HTML through **data binding**. One way databinding looks like this: 
```
<p>{{isOpen}}</p>
```
Vue will process this statement to contain **true** in between the paragraph tags. Today we also learned how to data bind in a for loop:
```
<ul v-for="item in items" v-bind:key="item.name">
    <li>{{ item.name }}</li>
</ul>
```
This code will produce a `<li>` for every item in the javascript object `items`. We also learned about conditional data binding using `v-bind` and two way databinding using `v-model.trim`. 

There is still a lot to learn when in comes to vue, but the online documentation is extensive. I can see how the modular nature of the framework will make it really quick to build reactive front end interfaces, but for now I'm still just learning the basics.

Next week is the last week of classes where we'll talk more about vue and get some more practice in. 