# JavaScript object basics

An object is a collection of related data and/or functionality and a collection of key-value pairs, where each key is a string (or a symbol in some cases) that identifies a specific value within the object. Objects can be created using either the object literal syntax or the constructor syntax.

### How would you describe an object to a non-technical friend you grew up with?

An object is like a container that holds information. We use it to store pieces of information that are related to together by labeling them key and value. Object key is like title of the book, where the value is a content of it. When want to see the content we can search it by its title. 

### What are some advantages to creating object literals?

Improves readibility and makes it easy to organize and maintain the code. 

### How do objects differ from arrays?

- An array is an ordered collection of values, where each value is assigned an index starting from 0. Arrays are used to store a list of values of the same data type, such as a list of numbers or strings. You can add or remove values from an array, and you can access those values by their index.
- An object is an unordered collection of key-value pairs. Objects are used to store related data, such as properties of an entity like a person or a car. The keys in an object act as labels for the values, and you can access those values using the keys.
  
 <strong>Key differences of object vs array </strong>
 
- Ordering: Arrays are ordered, meaning that each value is assigned an index based on its position in the array. Objects are unordered, meaning that the key-value pairs can be in any order.

- Accessing values: In an array, you access values by their index, while in an object, you access values by their key.

- Data types: Arrays are used to store a list of values of the same data type, while objects are used to store related data that may have different data types.

### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

- When the property name contains special characters or spaces.
- when the property name is not known until the program runs. The name of the property is not hard-coded in the program, but is determined dynamically based on some input or calculation.

### Evaluate the code below. What does the term this refer to and what is the advantage to using this?

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

In the given code, this refers to the dog object, which is the object that the humanAge method belongs to.

The this keyword in JavaScript refers to the current object, which is the object that "owns" the code that is currently being executed. When used inside an object method, this refers to the object that the method belongs to.

In the given code, the humanAge method uses this to refer to the name and age properties of the dog object. This allows the method to access these properties dynamically, without having to hard-code the object name or property names.

The advantage of using this is that it makes the code more flexible and reusable. By using this, we can write object methods that can work with any object that has the same properties and methods, without having to rewrite the code for each object. This is especially useful when working with large or complex objects, where hard-coding the object and property names can lead to errors and make the code more difficult to maintain.

# Introduction to the DOM

### What is the DOM?

 The DOM is the browser's representation of an HTML document. When a web page is loaded into a browser, the browser creates a DOM that represents the structure of the HTML document. This DOM can be modified or manipulated using JavaScript, allowing developers to dynamically change the content and styling of a web page.
 
 ### Briefly describe the relationship between the DOM and JavaScript.
 
 When a web page is loaded into a browser, the browser creates a DOM that represents the structure of the HTML document. This DOM can then be manipulated using JavaScript to dynamically change the content and styling of the page.

JavaScript provides a way to access and manipulate the elements of the DOM, such as changing the text of a paragraph, hiding or showing an element, or adding new elements to the page. JavaScript can also be used to respond to events triggered by the user, such as clicking a button or submitting a form. When an event occurs, JavaScript can use the DOM to change the page in response to the event.

