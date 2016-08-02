## Website Performance Optimization portfolio project

### To load the site

Download the zip from my github at https://github.com/fierytengoku/WEBOP
Unzip to desired location. Inside WEBOP right-click on index.html and open-with desired browser of choice.
Enjoy exploring the portfolio!

####Part 1: Optimize PageSpeed Insights score for index.html

To optimize the PageSpeed Insights score I: 

Resized and compressed pizza.png, pizzeria.png, and profilepic.jpg.
Inlined CSS for print, style, and webfont in index.html.
Async analytic.js.


####Part 2: Optimize Frames per Second in main.html and pizza.html

To optimize the FPS of the sliding pizzas I:

Moved the phase calculation outside the for-loop, populated it into an array to use.
Moved pizzasDiv line outside of for-loop.

To optimize the pizza-resize FPS I:

Removed determineDx and calculated the needed width for all three size, used a switch to assign the changed width to each pizza container .
Took out querySelectorall to reduce overhead by assigning the pizzaContainer to a variable outside the for-loop.



