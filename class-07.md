## Domain Modeling

  Domain Modeling is creating a model in code for a specific problem.
  
  ### Explain why we need domain modeling.
    
Creating domain model is important for software developers and the other stakeholders to gain a deeper understanding of the problem and design the software efficiently. 
  
  ## HTML Table Basics
 Information is easily interpreted by making visual associations between row and column headers are important concepts of HTML table basics. 
 <strong> The basic elements and attributes of HTML tables: </strong>
    
- Table tag: The 'table' tag is used to define the start of a table.

- Table row tag: The 'tr' tag is used to define a table row. Each row can contain one or more table cells.

- Table header cell tag: The 'th' tag is used to define a table header cell. This tag is typically used for the first row of the table to define column headers.

- Table data cell tag: The 'td'p tag is used to define a table data cell. This tag is used to define each individual cell within a table.

- Table caption tag: The 'caption' tag is used to define a table caption, which is displayed above or below the table.

- Table border attribute: The border attribute is used to define the width of the border around the table. For example, 'table border="1"' would display a table with a border width of 1 pixel.

- Table width attribute: The width attribute is used to define the width of the table. This can be specified in pixels or as a percentage of the available space.

- Table cell alignment attributes: The align and valign attributes are used to specify the horizontal and vertical alignment of table cells, respectively.

- Table rowspan and colspan attributes: The rowspan and colspan attributes are used to merge cells vertically or horizontally, respectively.

### Why should tables not be used for page layouts?

- Semantic structure: Tables are intended for displaying tabular data, not for page layouts. Using tables for layouts can lead to poor semantic structure, which can make it harder for screen readers and search engines to understand the content of the page.

- Accessibility: Tables can be difficult to navigate for users who rely on screen readers or have other disabilities. Using tables for layouts can make it harder for these users to access and navigate the content of the page.

- Responsive design: Tables are not well-suited for responsive design, which is important for creating web pages that are optimized for different devices and screen sizes. Tables can be difficult to adapt to different screen sizes, and may not display properly on mobile devices.

- Maintenance: Using tables for layouts can make it more difficult to maintain and update the design of a website. Tables require more HTML and CSS code than other layout techniques, which can make it harder to update the design and make changes to the layout.

### List and describe 3 different semantic HTML elements used in an HTML 'table'.
- Caption: : Element is used to provide a caption or title for the table. It should be placed immediately after the 'table' tag, and before any 'thead', 'tbody', or 'tfoot' tags. The text within the 'caption' tag will be displayed centered above the table.
- thead, tbody, tfoot: These elements are used to divide the table into logical sections. 
- th: element is used to define table header cells. These cells are typically used to provide column or row headings for the table. The text within the 'th' tag is usually displayed bold and centered within the cell.

## Introducing Constructors
### Object Basics
An object is an unorderd collection of related data and/or functionality. Objects basics: 
- Properties: Objects have properties, which are variables that store data values. These values can be of any data type, including strings, numbers, booleans, arrays, and other objects. Properties are defined within the object using key-value pairs, where the key is a string that identifies the property, and the value is the data stored in the property.

- Methods: Objects can also have methods, which are functions that perform actions or calculations using the object's properties. Methods are defined within the object using key-value pairs, where the key is a string that identifies the method, and the value is a function that performs the method's action.

- Instantiation: To create an object, you first need to define a class. The class specifies the properties and methods that the object will have. Once the class is defined, you can create new instances of the class, which are individual objects that have their own set of properties and methods. This process is called instantiation.

- Object-oriented programming: Objects are a key concept in object-oriented programming (OOP), which is a programming paradigm that emphasizes the use of objects and classes to organize and structure code. OOP is used in many programming languages, including Java, Python, C++, and JavaScript.

### What is a constructor and what are some advantages to using it?

 A constructor is a special function that is used to set up the properties of an object when it is created. It can be used to make sure that the object has the right values and is ready to be used. Constructors also help to control how the object is used and can make it easier to create and organize objects in a program. They provide many advantages, including initialization, encapsulation, inheritance, and consistency.
 
 ### How does the term this differ when used in an object literal versus when used in a constructor?
 
 When used in an object literal, "this" refers to the object itself. When used in a constructor, "this" refers to the object being created.
 
 ## JavaScript Prototype
 Every object has a special property called a prototype, which is essentially a template object that is used to inherit properties and methods from.In JavaScript, prototype-based inheritance is used to create new objects based on existing objects. This is done by setting the prototype of a new object to be a reference to an existing object. When we create a new object using a constructor function or the Object.create() method, the new object's prototype is set to the constructor function's prototype property or the object that is passed as an argument to Object.create(), respectively.
 
 Functional Instantiation is a method for creating objects in JavaScript using a function as a constructor. It is a way of creating multiple instances of an object that share the same properties and methods.
 
 ## Explain prototypes and inheritance via an analogy from your previous work experience.
 
 As an ultrasound technician I(Object) use ultrasound machine, and gel, electrodes (properties and methods) as set of tools and techniques to create image of the heart. Sometimes I need to use extra tools and techniques (prototypes and inheritance) to obtain images based on patients need, like object need to have access to additional properties and methods to complete the task. Sometimes I teach students or new techs and learn from experienced techs (inherit properties and methods from prototypes.)
 
