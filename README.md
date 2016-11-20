# Website_Optimization

######Project Overview

Project #8
"You will optimize a provided website with a number of optimization- and performance-related issues so that it achieves a target PageSpeed score and runs at 60 frames per second."

## Task 1 PageSpeed Score
Goal: index.html achieves a PageSpeed score of at least 90 for Mobile and Desktop.

-Minified css/html and js files
-Minified the images
-Added "async" to js files since the where not critical
-Added media="print" to print.css file

## Task 2 Getting Rid of Jank
#####1.Optimizations made to views/js/main.js make views/pizza.html render with a consistent frame-rate at 60fps when scrolling.
#####2.Time to resize pizzas is less than 5 ms using the pizza size slider on the views/pizza.html page. Resize time is shown in the
browser developer tools.

-I did not inline the css file since I find the loss of preformance excaptable and rather keep a clean ordered filestructure. 
-Minified css/html and js files
-Minified the images  

**1.** Clone this repo:

```
$ git clone https://github.com/esraneuhofer/Classic-Arcade-Game-Clone.git
````

**2.** Serve the application:

```
$ run index.html in your browser
```

###Resources

"http://www.willpeavy.com/minifier/"
"optimizilla.com/"
