To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:

<br>
<br>
<br>

Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element
<br>
<br>
<br>
 canvas doesn't have the src and alt attributes but width and height
<br>
<br>
<br>
 When you set the strokeStyle and/or fillStyle property, the new value becomes the default for all shapes being drawn from then on. For every shape you want in a different color, you will need to reassign the fillStyle or strokeStyle property.