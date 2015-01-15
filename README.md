###Website Optimization Project for Udacity Front End Nanodegree

This is my submission for Project 4.  In this project I optimized a mock portfolio
for the web.  The portfolio includes a landing page and three sample project pages, 
the third of which is a website for a pizza restaurant.  The pizza site originally 
used several methods which caused the page to render and scroll slowly.

In order to optimize the website, I resized all of the images to be closer to the 
size actually needed for the website.  Then I wrote all of the CSS inline and set 
the javascript files to load asynchronously. Specifically, in the pizza website, I 
eliminated a lot of unnecessary DOM calls and a lot of the CSS that was originally 
in the Bootstrap file.

Lastly, I minified the JavaScript file.  The original is left in tact in the main.js 
file for easier review.

The site is published at http://mimibambino.github.io/Optimizer.

http://stackoverflow.com/questions/5898656/test-if-an-element-contains-a-class

https://developer.mozilla.org/en-US/docs/Web/CSS/Descendant_selectors

http://www.smashingmagazine.com/2009/07/15/clever-png-optimization-techniques/

Bootstrap Documentation

Mozilla Developer Network - JavaScript

Pro JavaScript Development published by Apress
