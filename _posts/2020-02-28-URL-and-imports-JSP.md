---
layout: post
title: Day 35 Imports and Links in JSP
summary: Today we learned how to appropriately use URLs in JSP. We also learned how to make reusable layouts in JSP. 
---

Brian taught us today that links can easily break in maven projects if we try to use absolute paths in our code. He told us that depending on the server administrator, it is possible that our absolute paths will change. In order to account for this, we must build URLs with:
```
<c:url value="/relative/path/to/file" />
```

And to add query strings to our link we can do this:

```
<c:url value="/path/to/new/page" >
    <c:param name="imageId" value="4" />
</c:url>
```
The above will build the link `www.yoursite.com/path/to/new/page?imageId=4`

Besides links, we also learned about building reusable layouts. With JSP if you have a header and footer that will remain constant on your site, you can build a seperate JSP file for each and simply import them in your content pages. 

This allows you to build reusable components in JSP to write less duplicate code. Here's how you do it:
```
<c:import url="/WEB-INF/jsp/header.jsp" />
```
And if there's a value in the header page you want to change depending on where you import it you can pass in parameters to pages you import using similar syntax to building a query string:

```
<c:import url="/WEB-INF/jsp/header.jsp >
    <c:param name="pageTitle" value="About Us" />
</c:import>
```

These components are relatively simple but it's exciting because they represent the move to building more functional web applications. Our exercises have us building the front end of an ecommerce product page. It's easy and exciting to see now how we can build real things! 
