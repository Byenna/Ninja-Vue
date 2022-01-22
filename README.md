# Ninja-Vue

# VUE-NINJA
CodeAlong with the Net Ninja

To learn VUE a bit better I will ask myself the same questions after each assignment.

1 Watch (piece) film
2 Do the same (by heart)
3 Write down what you will

#3 What will I do
- I rendered data on a html file. To do that I had to install Vue.js (npm init) make a vue instance, link my javascript to html and added the vue also on the html with node modules.

- I created a method, let it return a string and rendered it on the html

- I passed in a parameter through this method to render different arguments on the page

- After that I added data with the 'this' keyword to the function and rendered it on the page 

#4 What will I do
- I binded an attribute to render data from the vue instance

- I used a v-html directive to reder a html link from the vue instance


#5 What will I do
- I made two buttons, added a v-on:click directive to add or substract a value out of the data with a function from the vue instance

- I will add again two buttons. Now with a v-on:dblclick that in of decrement with 10

- I will create a canvas and track the movement of my mouse inside the box by using the offset property from the DOM. I want to put the coordinates of my mouse on screen relative to the box
(The offset property returns the position (in pixels) relative to the offsetParent)

#6 What will I do
- I will add a modifier to a clickevent so I can only execute the function once.

- I will add a modifier to a clickevent so it prevents de default behahaviour of that event.

#7 What will I do
- Every time a key will come up I log something in my console. To realize this I will make an inputfield with a keyboardevent and a function in the vue instance

- This time I log something in my console after the use of (a modifier)the enter key.

- I will use another modifier to log somthing in my console after a used the enter and alt key

#8 What will I do
- I will add v-model to an inputfield so everything a user is typing will show on the screen

#9 What will I do
- There are two buttons. Button A will increase the value of A and button B will increase the value of B. I will create a (method) function that will add one to a certain age when clicked on it.

- To prevent that both functions will run when pressing one button I will copy and paste this functions in a computed property

- 
#10 What will I do
- I will bind a html-property class and give a classname as key and a boolean as value

- Then I add another key:value pair to this class seperated by comma

- Now I will make the class more dynamically by storing the value in the data and give it a boolean value
I also make a span(inside the div) with a clickevent. This clickevent toggles the value of the class(property of data) on and off =!

- I want more (value of) classes but don't want to put it in the html so I will wrap it into a computed property 
I also will make two buttons. One to toggle one (value of a) class and on to toggle the other.

#11 What will I do

#12 What will I do
- I will make two buttons with clickevents. One toggles between the value error and the other between the value success (negation operator).
Then I will make two span elements. Each with a v-if statement.
When I toggle a button the text of the span will show/dissapear.

#13 What will I do
I will watch what I have learned so far. Maybe in the future I will make my own vue-game

#14 What will I do
- I will create two vue instances, add a title variable in the data property and render it on the page

- I will also create for each instance a computed function outputting a string

- I will change the title in instance one with a button in instance two

- I will change the title in instance two from outside both instances (make sure it is in the javascriptfile;))

#15 What will I do
- I will create 'one' component with a template and render this in 'both' instances. 

- In the component I will create a button that changes data. When showed on screen I can change data of one instance and the other stays the same.



#16
- When a user types in a inputfield I will reder the input on the screen by using the $ref attribute.

- I will render the innerText of a div when pushing a button

==========================================================================
The Net Ninja now is going to use Vue Cli, but I cannot manage to install it. Seems like I don't have the rights...?

The upcomming tutorial I try to do without the CLI

#21
I will set up an root component with three subcomponents containing the heather, footer and a list. 