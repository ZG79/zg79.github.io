## HTML

## When should you use an unordered list in your HTML document?
An unordered list in HTML is used to represent a list of items that don't have a specific order or ranking. This type of list is usually displayed with bullet points.

You should use an unordered list when you want to present a collection of items that don't have a particular order or hierarchy. Some common examples of when to use an unordered list include:

A list of ingredients for a recipe
A list of items in a shopping cart
A list of tasks in a to-do list
A list of items in a navigation menu
A list of options in a form
In HTML, an unordered list is created using the 'ul' element, and each list item is represented by the 'li' element.
##  How do you change the bullet style of unordered list items?
  Unordered list's bullet style can be changed by using CSS. The default bullet style for an unordered list is a filled circle, but you can change it to any other symbol, image, or character using the list-style-type property in CSS.
  
  Here are some of the other possible values for the list-style-type property:

disc: Filled circle

circle: Outlined circle

square: Square

decimal: Decimal number

lower-roman: Lowercase Roman numeral

upper-roman: Uppercase Roman numeral

lower-alpha: Lowercase letters

upper-alpha: Uppercase letters

none: No bullet

## When should you use an ordered list vs an unorder list in your HTML document?
you should use an ordered list when the items in the list need to be displayed in a specific order, and use an unordered list when the items don't have a specific order. 

Some common examples of when to use an ordered list include:

- A list of instructions or steps to follow

- A list of items in a numbered list

- A list of ranked items

- A list of items that need to be displayed in a specific order, such as a timeline

 Some common examples of when to use an unordered list include:

- A list of ingredients for a recipe

-  A list of items in a shopping cart

- A list of tasks in a to-do list

- A list of items in a navigation menu

- A list of options in a form
  ## Describe two ways you can change the numbers on list items provided by an ordered list?
  
  There are two main ways to change the numbers on list items provided by an ordered list in HTML:

1. Using CSS: You can use the CSS list-style-type property to change the numbering type of an ordered list. 
2. Using the type attribute: You can also change the numbering type of an ordered list by using the type attribute on the <ol> element. The type attribute accepts values such as a, A, i, and I, which correspond to lowercase letters, uppercase letters, lowercase Roman numerals, and uppercase Roman numerals, respectively. 

  ## Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
  
  In the world of web design, there are two important CSS properties called margin and padding. Margin creates space outside of an HTML element, separating it from other elements. Padding, on the other hand, creates space inside the element, between the element's content and its border. Together, margin and padding make up the "Box Model", and they play a crucial role in determining the appearance of elements on a web page.
  
  ## List and describe the four parts of an HTML elements box as referred to by the box model.

The four parts of an HTML element's box, as referred to by the "box model," are:

- Content: This is the actual content of the element, such as text or images. The content is surrounded by padding.

- Padding: This is the area between the content and the border. It provides space between the content and the border, giving the content room to breathe.

- Border: The border is the line that surrounds the padding and the content. It provides a visual delimiter between the content and the background.

- Margin: The margin is the space outside of the border. It provides space between the element and other elements on the page, creating separation and clear boundaries.
  
## What data types can you store inside of an Array?
  
- Numbers (integers, floating-point numbers)
- Strings (textual data)
- Booleans (true/false values)
- Objects (collections of key-value pairs)
- Arrays (nested arrays)
- Functions (blocks of code that can be executed)
- Null and undefined values
  
  ## Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
  
// const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
  
  Yes, people is a valid array, we need to use nested array method to access the value. For example if I need to access 'Smith' I will write: 
  
  people[1][0]; 
  
  ## List five shorthand operators for assignment in javascript and describe what they do.
  - +=: The += operator adds the right operand to the left operand and assigns the result to the left operand. 
  - -=: The -= operator subtracts the right operand from the left operand and assigns the result to the left operand. 
  - *=: The *= operator multiplies the left operand by the right operand and assigns the result to the left operand.
  - /=: The /= operator divides the left operand by the right operand and assigns the result to the left operand. 
  - %=: The %= operator calculates the remainder of dividing the left operand by the right operand and assigns the result to the left operand.
  
  
  ## Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
  
 let b = 'dog';
  
 let c = false;
  

 // evaluate this
 (a + c) + b; 
  
  variable a declared by let and assigned to number of 10. variable b declared by let assigned to string dog. variable c declared by let and assigned to bvoolean value false. 
  
  The evaluation of  (a + c) + b is invalid because all of the variables are different datatypes. 
  
  ## Describe a real world example of when a conditional statement should be used in a JavaScript program.
  
  If I designed a website which need to collect the user's data then I can use the conditional statement. For example: The website will only run if type yes to a data retrieving questions.  
  
  ## Give an example of when a Loop is useful in JavaScript.
  
  If I need to find the total of the array numbers, or if I'm looking for specific word in the array I can use the loop to iterate the arrays. 
  
  
  
