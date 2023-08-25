# Day09Class
2.Class Assignment
In this assignment, you are tasked with employing DOM manipulation. Let's go through the steps you've outlined:

First, I created a div with the ID "target_div" and inserted a sentence. This will allow the CSS properties specified in the task to be applied to it.

Following that, I generated another div with the ID "main." Inside this div, I selected elements for each property outlined in the task, such as Color, 
Background color, Padding, Font Size, and Font Weight. I assigned specific values to each property using option elements to be applied to the sentence.
To connect the JavaScript file to the HTML file, I added a script element.
In the JavaScript file, I began by fetching elements using the getElementById method. Subsequently, I established an event using the addEventListener method for each property, 
namely Color, Background color, Padding, Font size, and Font weight. These events are triggered on the "change" event type to dynamically alter property values as needed.
The implementation involves using the syntax "target.style.color = element.value," which is present within each event listener.
This enables the modification of the specified CSS property based on the selected value.
