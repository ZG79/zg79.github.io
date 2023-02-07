HTML, CSS, and JavaScript form the core technologies for building web pages and web applications. 

# HTML

## Why is it important to use sematic elenets in our HTML?

Using semantic elements in HTML such us 'header, nav, main, article, and footer' are important because it gives structure to the page and provide meaning and  helps to provide meaning and context to the content on a web page. The semantic elements also make the web page more accessible and improves the user experience. 

## How many levels of headings are there in HTML?

There are 6 levels of headings in HTML, defined using h1 - h6. h1 is the largest and boldest, it is encouraged to use only one h1 in a web page. 

## What are some uses for the sup and sub elements?

sup and sub elements are used in HTML to display text as superscript or subscript. <strong> Sup </strong> element is used for footnotes, exponents in math expressions, and trademarks or copyright symbols. <strong> Sub </strong> element is used for chemical formulas, subscripts in math expressions, displaying footnote references. 

## When using the abbr element, what attribute must be added to provide the full expansion of the term?
  
  The <strong> title </strong> attribute must be added to provide the full expansion of the term. This info can be used by assistive technologies, such as screen readers. 

# CSS

## What are ways we can apply CSS to our HTML?

1. Inline styles: CSS is added to an HTML element using the "style" attribute in the HTML tag. Highest priority

Internal stylesheet: A block of CSS is added to the head of an HTML document using the "style" tag. 

External stylesheet: CSS is stored in a separate file with a .css file extension and linked to the HTML document using the "link" tag in the head of the HTML document. This method is best used for large websites. Lowest priority. 

## Why should we avoid using inline styles?

Lack of Reusability: Inline styles are applied directly to individual HTML elements, so it's not possible to reuse them elsewhere on the page or across multiple pages.

Increased File Size: Using inline styles increases the size of the HTML file, making it harder to maintain and slowing down the page load time.

Harder to Maintain: With inline styles, it can be difficult to keep track of which styles are applied to which elements, making it harder to maintain and update the look and feel of the site.

Decreased Performance: When there are many inline styles, it can slow down the performance of the page, especially in older browsers.

Inconsistent Style: Inline styles can result in an inconsistent look and feel across the website, as styles may be applied differently on different pages or elements.

## Review this code: 
![Screen Shot 2023-02-06 at 8 56 55 PM](https://user-images.githubusercontent.com/101478282/217152037-2d53d8d7-1890-4800-a18b-b7e7cae69634.png)

## What is representing the selector?
The selector "h2" specifies that the styles will be applied to all "h2" elements.
## Which components are the CSS declarations?
The CSS declarations are "color: black" and "padding: 5px".
## Which components are considered properties?
The properties are "color" and "padding". They determine the styles that will be applied to the elements selected by the selector. The values "black" and "5px" define how the properties will be applied.

# JavaScript

## What data type is a sequence of text enclosed in single quote marks?

A string data type. 

## List 4 types of JavaScript operators.

1. Arithmetic Operators: These operators perform arithmetic operations, such as addition (+), subtraction (-), multiplication (*), division (/), and modulus (%).

2. Assignment Operators: These operators are used to assign values to variables, such as the equal (=) operator, the addition-assignment (+=) operator, the subtraction-assignment (-=) operator, etc.

3. Comparison Operators: These operators compare values and return a Boolean value indicating whether the comparison is true or false. Examples include the equal to (==) operator, not equal to (!=) operator, greater than (>) operator, etc.

4. Logical Operators: These operators perform logical operations and return a Boolean value. Examples include the logical AND (&&) operator, logical OR (||) operator, and logical NOT (!) operator.

## Describe a real world Problem you could solve with a Function.

Converting measurement or temperature units between each other.

## Conditionals

 An if statement checks a <strong>condition</strong> and if it evaluates to <strong>true</strong>, then the code block inside the if statement will execute.

## What is the use of an else if?

An else if statement is used in conjunction with an if statement in programming to specify additional conditions to test. 

## List 3 different types of comparison operators.

- Equality operators : '==' - loose equality and "===" strict eq quality
- Relational operators: < (less than), > (greater than), <= (less than or equal to), and >= (greater than or equal to).
- Inequality operators:  != (loose inequality) and !== (strict inequality).

## What is the difference between the logical operator && and ||?

- The && operator, also known as the logical AND operator, returns true only if both the conditions on either side of the operator are true. If either of the conditions is false, the overall expression evaluates to false.
- The || operator, also known as the logical OR operator, returns true if either of the conditions on either side of the operator is true. If both conditions are false, the overall expression evaluates to false.

#### Reference: 

https://www.w3schools.com
https://chat.openai.com/chat
