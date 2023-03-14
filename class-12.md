# JavaScript Canvas
JavaScript canvas is a web technology that allows developers to create and manipulate graphics and animations in a web browser. It is a part of the HTML5 specification and provides a way for developers to draw and render graphics, text, and images using JavaScript code.
HTML5 features the `<canvas>` element that allows you to draw 2D graphics using JavaScript.
The `<canvas>` element requires at least two attributes: width and height that specify the size of the canvas:

`<canvas width="500" height="300" id="canvas"></canvas>`

![Screenshot 2023-03-12 at 9 31 58 PM](https://user-images.githubusercontent.com/101478282/224608768-5dcf8b2a-7d34-4ddc-bb28-e8902d2beb94.png) ![Screenshot 2023-03-12 at 9 32 36 PM](https://user-images.githubusercontent.com/101478282/224608845-18f71c6f-7f93-4a1a-8b11-9745e6a6f66e.png)

### What does the <canvas> allow a developer to acheive?

  Drawing graphics and animations: With the canvas element, a developer can draw and animate graphics, such as lines, circles, rectangles, and curves. They can also create animations by changing the position, color, or shape of these graphics over time.

Creating interactive applications: The canvas element allows developers to create interactive applications that respond to user input. For example, they can create games where users can move objects on the canvas with the mouse or touch screen.

Creating data visualizations: With the canvas element, developers can create data visualizations such as charts, graphs, and diagrams. They can draw data points, labels, and other graphical elements to represent data in a meaningful way.

Manipulating images: The canvas element allows developers to manipulate images, such as cropping, resizing, and applying filters. They can also create image animations and composite multiple images together.
  
   ### What is the importance of the closing `</canvas>` tag?
   
   The closing </canvas> tag is important because it tells the web browser where the canvas element ends. It is used to close the opening <canvas> tag and to indicate the end of the canvas element.

If the closing </canvas> tag is missing, the web browser will assume that the canvas element continues until the end of the HTML document, which can cause unexpected behavior and errors in the web page.

### Explain what the `getContext()` method does.

The getContext() method is a built-in method of the HTML5 canvas element that returns an object that provides methods and properties for drawing and manipulating graphics on the canvas.

The getContext() method is called on the canvas element and takes one parameter, which is a string that specifies the context type. There are two context types available: "2d" for 2D graphics and "webgl" for 3D graphics using WebGL. Once you have the context object, you can use its methods and properties to draw and manipulate graphics on the canvas element. Some common methods of the 2D context object include:

- fillRect(x, y, width, height): Draws a filled rectangle on the canvas.
- strokeRect(x, y, width, height): Draws a rectangular outline on the canvas.
- beginPath(): Starts a new path on the canvas.
- moveTo(x, y): Moves the current drawing position to the specified point.
- lineTo(x, y): Draws a line from the current position to the specified point.

## Chart.js documentation
### What is Chart.js and how it can be brought into your project?
  Chart.js is an open-source JavaScript library that allows you to create interactive and responsive charts and graphs for your web applications. It supports various chart types, such as line charts, bar charts, pie charts, scatter charts, and more.  It’s open-source, licensed under the very permissive MIT license , and maintained by an active community. Chart.js is very well suited for large datasets. Such datasets can be efficiently ingested using the internal format so you can skip data parsing and normalization. 
  
  I will use it in my Odd Duck project to display the graphics using outside library. 
  
  ### List 3 different Chart types you can create using Chart.js.
  
 - Line Chart - A line chart displays data points connected by lines, which can be used to show trends over time.

- Bar Chart - A bar chart displays data using horizontal or vertical bars, which can be used to compare different categories of data.

- Pie Chart - A pie chart displays data as slices of a circle, where the size of each slice represents the proportion of the data it represents. Pie charts are useful for showing how different categories contribute to a whole.

### What are some advantages to displaying data via a chart over a table?

Charts can make data easier to understand by presenting it in a visual format. They allow users to quickly identify trends, compare data sets, and communicate insights effectively. Also, charts can be aesthetically pleasing and engaging, which can increase their impact and effectiveness.

### How could Chart.js aid your previously created applications visually?

I can use Chart.js for Salmon Stand project to display it as a chart instead of table, so it's easier for users to see the data. Also, Odd Duck project can really use aesthetic aspect of the chart.js, because it has many different options to display. The bar chart will be much easier to see how many times the pictures have shown than the text. 

  
  
