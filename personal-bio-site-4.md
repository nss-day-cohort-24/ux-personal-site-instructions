# Personal Bio Site 4: Using JS to write to the DOM (JS - loops)

## Prerequisite

> :warning: This exercise requires you to have completed the [Personal Bio Site 3: Interactive Navigation (CSS)
](personal-bio-site-3.md) exercise

### You will be working off of your previous iteration of your Personal Bio site.

## Requirements

1. Create a main.js file and link to it in your blog.html
1. Create an html element with the id ‘blog-holder’
1. Make an array called blogs
1. Add each of your existing blogs to the blogs array by making them into objects with the following key, value pairs: title, content, date  (you should have at least 5 blog objects)
1. Loop over the blogs array and build up the HTML card elements using the values from your blog objects
1. Add the HTML you created in the last step to the blog-holder element

## Final Result
* HTML File: 
	* navbar
	* blog-holder element
* JS File
	* An array with 5 blog objects
	* variable that stores DOM container element
	* Loop that iterates over the array, builds up a string, and then puts the string on the DOM