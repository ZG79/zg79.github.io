## How the Web Works

HTTP, the ruler of the internet,

Transmits data with ease, its purpose to represent.

It moves from one computer to another with fluidity,

Creating a harmonious flow of information for all to see.

Computers connected to the internet are called clients and servers. <img src = "https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works/simple-client-server.png" alt = "Alternate text" height = 100 > 

- Clients are the typical web user's internet-connected devices.
- Servers are computers that store webpages, sites, or apps. 

- Your internet connection: Allows to send and receive data on the web.
- TCP/IP: Transmission Control Protocol and Internet Protocol are communication protocols that define how data should travel across the internet. This is like the transport mechanisms. 
- DNS: Domain Name System is like an address book for websites. When you type a web address in your browser, the browser looks at the DNS to find the website's IP address before it can retrieve the website. The browser needs to find out which server the website lives on, so it can send HTTP messages to the right place. They are special numbers that look like this: 63.245.215.20. This is called an IP address, and it represents a unique location on the web. 
- HTTP: Hypertext Transfer Protocol is an application protocol that defines a language for clients and servers to speak to each other. 
- Component files: A website is made up of many different files, which are like the different parts of the goods you buy from the shop. These files come in two main types:
- Code files: Websites are built primarily from HTML, CSS, and JavaScript. 
- Assets: This is a collective name for all the other stuff that makes up a website, such as images, music, video, Word documents, and PDFs.

### What happens? 

- The browser goet to DNS server, and finds the real address of the server that the website lives on. 
- The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client. This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.
- If the server approves the client's request, the server sends the client a "200 OK" message. 
- The browser assembles the small chunks into a complete web page and displays. 

### Parsed files

- The browser parses the HTML file first, and that leads to the browser recognizing any <link>-element references to external CSS stylesheets and any <script>-element references to scripts.
As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.
The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.
  
 ### Packets
  
 When data is sent across the web, it is sent in thousands of small chunks. There are multiple reasons why data is sent in small packets. They are sometimes dropped or corrupted, and it's easier to replace small chunks when this happens. Additionally, the packets can be routed along different paths, making the exchange faster and allowing many different users to download the same website at the same time. 
  
### How can you find images to add to a Website? 
  
 - To choose an image, go to Google Images and search for something suitable.

When you find the image you want, click on the image to get an enlarged view of it.
Right-click the image (Ctrl + click on a Mac), choose Save Image As…, and choose a safe place to save your image. Alternatively, copy the image's web address from your browser's address bar for later use. Remember images are copyrighted. you can use Google's license filter. Click on the Tools button, then on the resulting Usage rights option that appears below. You should choose the option Creative Commons licenses.
  
  ## JavaScript basics
  
  JavaScript is a programming language invented by Brendan Eich, that adds interactivity to your website. This happens in games, in the behavior of responses when buttons are pressed or with data entry on forms; with dynamic styling; with animation, etc. 
  
  ### How do you create a String vs a Number in JavaScript?
  
  In JavaScript, you can create a string by using either single quotes (') or double quotes (") around a sequence of characters:
  
  let string1 = 'Hello, world!';
  
  let string2 = "Hello, world!";
  
  
  To create a number, you can simply assign a numeric value to a variable:
  
  let number1 = 42;
  
  let number2 = 3.14;
  
  ### Variable 
  
  A variable in JavaScript is a named storage location for values.  Variables are important in JavaScript because they allow you to dynamically manipulate data within your code.

   #### Variable types
  
  In JavaScript, there are two main types of variables: primitive types and reference types.

Primitive Types: Primitive types are the basic building blocks of data in JavaScript. They include:

Number: for numeric values, including integers and floating-point numbers.
String: for sequences of characters, such as words and sentences.
Boolean: for representing true/false values.
Undefined: for variables that have been declared but have not been assigned a value.
Null: for representing a deliberate non-value.
Reference Types: Reference types are more complex data structures that are built from primitive types. They include:

Object: for representing a collection of key-value pairs.
Array: for representing an ordered list of values.
Function: for representing a block of code that can be executed.
  
  
  ### Describe 2 things that require JavaScript in the Browser?
  
 -  Dynamic User Interface Interactions: JavaScript can be used to create dynamic user interfaces that can update and change in response to user input or events. For example, drop-down menus, accordions, modal dialogs, and other interactive elements can be created and manipulated with JavaScript.

- Dynamic Content: JavaScript can be used to dynamically update the content of a web page without the need for a page refresh. This allows for a more seamless user experience and can make it easier to create applications that rely on real-time data or user input. For example, dynamic forms, real-time charts, and dynamic search results can all be created and managed with JavaScript in the browser.
  
  ### How can you add JavaScript to an HTML document?
  JavaScript can be added to an HTML document in two ways:

- Embedding the JavaScript code directly within the HTML document using the <script> tag. This is typically placed within the <head> or <body> section of the HTML document, and the code is executed when the HTML document is loaded.
  
  
  <script>
  function myFunction() {
    alert("Hello World!");
  }
</script>

  - Including an external JavaScript file in the HTML document using the <script> tag and the src attribute. This method is useful when the same JavaScript code needs to be used across multiple HTML pages.
  
 <script src="script.js"></script>
 
  ## HTML 
  HTML (HyperText Markup Language) is the standard markup language for creating web pages and web applications. It provides the structure and content of a web page, using a set of tags and attributes to define the elements on the page, such as headings, paragraphs, images, and links.
  
  ### What is an HTML attribute?
  
  HTML attributes are special keywords used within an HTML element to define the characteristics or properties of that element. An attribute typically     has a name and a value, and is written in the form name="value".

 Different elements can have different attributes, and some attributes are specific to certain elements.

Some common HTML attributes include:

- class: defines the class name for an element, used for CSS styling.
- id: defines a unique identifier for an element, used for CSS styling and JavaScript scripting.
- src: defines the source URL of an image, a script, or an iframe.
- alt: defines alternative text for an image, used for accessibility and SEO purposes.
- href: defines the destination URL of a hyperlink.
- width and height: define the width and height of an element, such as an image or a table cell.
- style: defines inline CSS styles for an element.
  
 ### Anatomy of the HTML element
  
 The anatomy of an HTML element consists of three parts: the opening tag, the content, and the closing tag.

- Opening tag: The opening tag consists of the element name surrounded by angle brackets, such as <p>. It also may include one or more attributes in the form of name="value", which provide additional information about the element.

- Content: The content is the information or data that the element contains. For example, the content of a paragraph element could be text or other HTML elements.

- Closing tag: The closing tag consists of a forward slash followed by the element name surrounded by angle brackets, such as </p>. The closing tag marks the end of the element's content.
  
  ### The difference between <article> and <section> element tags
  
  the main difference between the <article> and <section> elements is that <article> represents a standalone, self-contained piece of content, while <section> represents a generic section of content that can contain other sections and does not have to be self-contained.
  
  ### What elements does a 'typical' website include? 
  
  A typical website typically includes the following elements:

- Header: The header of a website usually contains the site logo, navigation links, and other important information.

- Main Content: This is the core content of the website and usually includes text, images, videos, and other types of multimedia.

- Footer: The footer of a website typically contains information such as the site's copyright notice, privacy policy, and links to additional resources.

- Navigation: Navigation is an important element of a website, allowing users to quickly and easily access different pages and sections of the site.

- Sidebar: A sidebar is a column of content that is typically located on the right or left side of the main content area. It can contain links to other pages, advertisements, or other types of content.

- Forms: Forms allow visitors to interact with the website, such as by submitting contact information, making a purchase, or signing up for a newsletter.

- Images and Graphics: Images and graphics can add visual interest to a website and help communicate important information.

- Audio and Video: Audio and video can enhance the user experience and add another dimension to the content.

- Background: The background of a website can be used to add visual interest and create a distinct look and feel for the site.
  
  ### How does metadata influence Search Engine Optimization?
  Metadata plays an important role in Search Engine Optimization (SEO) by providing information about the content of a website to search engines. Search engines use this information to understand the context and relevancy of the content and to determine how to rank the website in search results.

There are several types of metadata that can impact SEO, including:

- Title tags: Title tags are the text that appears in the browser's tab and in search engine results. They help search engines understand the main topic of a page and what the page is about.

- Meta descriptions: Meta descriptions are short summaries of the content of a page that appear in search engine results. They give users a preview of what they can expect to find on the page and can impact the click-through rate of a website.

- Header tags: Header tags (H1, H2, H3, etc.) are used to structure the content of a page and help search engines understand the hierarchy of the content.

- Alt tags: Alt tags are used to describe images on a page and can impact the accessibility and SEO of a website.
  
  ### How is the <meta> HTML tag used when specifying metadata?
  
  The <meta> HTML tag is used to specify metadata about the document, such as keywords, description, and character encoding. The information provided in the <meta> tag is not displayed on the web page, but is instead used by search engines, browsers, and other applications to understand the context and content of the page.
  
  ## Semantics
  
 Semantics in coding refers to the meaning or interpretation of the code and how it relates to the underlying structure and purpose of the content it represents. 
  
  ### Why should you use an h1 element over a <span> element to display a top level heading?
  
  You should use an h1 element instead of a <span> element to display a top-level heading because the purpose of the h1 element is to represent a top-level heading in HTML, whereas the <span> element is used to group inline elements together and apply styles to them. 
  
  ## What are the benefits of using semantic tags in our HTML?
  The use of proper HTML semantic elements is important for accessibility, SEO and maintainability of a website.
  
  ## How to start to design a Website. 
  
  ### What is the first step to designing a Website?
  
  - Set your goal, and the most important question to answer is "what you want to accomplish, and how a website can help with that". Make a lists of small steps that can help you to achieve your goal. Once the list is done, start prioritize what steps you need to take to reach those goals. It's called <strong> project ideation </strong> . Technique and idea are both crucial for designing a Website. 
  
  ##### References: 
  
  https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works
  https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics
  
