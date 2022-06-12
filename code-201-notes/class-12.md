Canvas is an HTML 5 tool that allows you to draw 2d graphics using Javascipt, You can use the getContext('2d') to get the 2D drawing context for drawing 2D graphics on canvas. Also Use the fillStyle and StrokeStyle properties to set the styles for the 2D drawing context.
Unlike the <img> element, The <canvas> element requires the closing tag </canvas>. Any content between the opening and closing tags is fallback content that will display only if the browser doesn’t support the <canvas> element. The <canvas> element features the getContext() method that returns a render context object.

The getContext() takes one argument which is the type of context. For example, you use the "2d" to get a 2D rendering context object, which is an instance of the CanvasRenderingContext2D interface.





In this chapter I read about creating Charts. You can created really cool looking charts with Chart.js a javascript pluin that uses HTLM5's canvas element to draw the graph onto the page.

The first thing to do is download chart.js, then you copy the chart.min.js out of the unzipped folder into the directory you will be working in, then you create a new HTML page and import the script

You can draw a line chart using a canvas element in HTML. You can also draw a pie chart using the canvas element, then you get the contect and instantiate the chart. We can also draw a bar chart
The <canvas> looks like the <img> element, with the only clear difference being that it doesn't have the src and alt attributes
The <canvas> element can be styled just like any normal image (margin, border, background…).

You can also draw shapes with canvas such as
-The Grid
-Rectangles
-Paths
-Triangles
-Lines
-Arcs
-Curves