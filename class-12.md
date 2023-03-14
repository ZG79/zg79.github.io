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

  
