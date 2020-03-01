# Charts 
  is  a way to display data visually on websites and it has a lot of benifit for the layout but the charts not always easy to create ,So the best way to start using charts with using **_Chart.js_** whish is a java plugin that uses HTML5’s canvas element to draw the graph onto the page

# Canvas API
  - ``` <canvas> ``` its an HTML element its look like ```<img>``` tag but without _src_ and _alt_ attributes and the only attributes that it has :
    1. width
    2. hight
  also this tag required a closing tag ``` </canva> ```
  and we can genirated using DOM 

 - we can drow shapes with canvas using new tags but its only support two primitive shapes :
   1. rectangles 
   2. lists of points connected by lines (path)

 - and for sure we can style any thing we create with canvis using some tags like :
  * ``` fillStyle = color ``` this will fill the shap 
  * ``` strokeStyle = color ``` this will style the outline 

 - also there is some tags to style the text like :
  * ``` fillText(text, x, y [, maxWidth]) ```
  * ``` strokeText(text, x, y [, maxWidth]) ```