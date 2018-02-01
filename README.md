# To-do-list-app
A to do list app for CSIS 408 - Web and Mobile Programming. Made using HTML/CSS/JavaScript and heavy use of Jquery. Using a mobile first approached and inspired by the book JavaScript &amp; Jquery by Jon Duckett. 

- Users can add new list item
- They can also click to indicate that an item is complete 
- Once an item is marked as complete, a second click on the item will remove it from the list

Because new items can be added to the list, the events are handled using event deligation. When the user clicks anywhere on the ul element, the .on() event method handles the event. Inside the event handler, there is a conditional statement to check whether the list item is complete or incomplete. 

The use of conditional statements and custom functions (used for the counter) illustrate how Jquery techniques are used with JavaScript.

The appearance and removal of the elements is also animated, and these animations demonstrate how methods can be chained together to create complex interactions based on the same selection of elements. 
