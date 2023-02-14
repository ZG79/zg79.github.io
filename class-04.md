## HTML 
### The href attribute contains what information?

Hyperlinks allow us to link documents to other documents or resources, link to specific parts of documents, or make apps available at a web address. Almost any web content can be converted to a link so that when clicked or otherwise activated the web browser goes to another web address (URL).

  a href="https://www.mozilla.org/en-US/">the Mozilla homepage</a
  
 ### To create a basic link, we wrap text or other content inside what element?
 
 To create a basic link, we wrap text or other content inside the <a> (anchor) element.
  
  ### What are some ways we can ensure links on our pages are accessible to all readers?
  
  Adding suitable semantic links. For example Screen readers will identify all headers and use them to make programmatic associations between those headers and the cells they relate to. The combination of column and row headers will identify and interpret the data in each cell so that screen reader users can interpret the table similarly to how a sighted user does.
  
  ## CSS
  
  ### What is meant by “normal flow”?
  
  In CSS (Cascading Style Sheets), "normal flow" refers to the default behavior of elements in a document before any layout or positioning properties are applied.

In normal flow, elements are laid out in their natural order within the document flow, and their positions are determined by the order in which they appear in the HTML code, as well as the size and position of their parent container.

Elements are positioned vertically one after the other, with each element taking up the full width of its parent container by default. Elements are also stacked in the order in which they appear in the HTML, with later elements appearing on top of earlier ones.

Normal flow can be modified by using CSS positioning properties such as position, top, bottom, left, and right, as well as properties such as float, clear, and display.

  ### What are a few differences between block-level and inline elements?
  
 Key differences:

- Layout and positioning: Block-level elements take up the full width available in their parent container, and they typically begin on a new line. They can have margins, padding, and borders, and they can be used to create the main structure of a web page (e.g., sections, headings, paragraphs, lists, etc.). Inline elements, on the other hand, only take up as much width as necessary to display their content, and they flow along with the text of a document. They do not have margins, padding, or borders, and they are often used to style and format content within block-level elements (e.g., links, bold or italic text, images, etc.).

- Nesting behavior: Block-level elements can contain other block-level elements and inline elements, while inline elements cannot contain block-level elements. However, inline elements can contain other inline elements, which can be useful for creating small snippets of formatted text.

- Default styles: Block-level and inline elements have different default styles that affect their appearance. For example, block-level elements are typically displayed with a line break before and after the element, while inline elements do not create line breaks by default. Block-level elements are also often styled with a default width of 100%, while inline elements do not have a default width.

- Accessibility: Block-level and inline elements can have different accessibility implications. For example, block-level elements can be easier to navigate with a screen reader because they are clearly defined and can be given headings and labels, while inline elements can be more difficult to navigate because they are part of the flow of text.
  
  ### <em> Static </em> positioning is the default for every html element.
  
  ## Name a few advantages to using absolute positioning on an element.
  
 - Precise control over placement: Absolute positioning allows you to precisely control the placement of an element on a page, regardless of its surrounding content. You can position an element relative to any parent element with a position other than static, or relative to the viewport itself.

- Layering and overlapping: Absolute positioning allows you to layer elements on top of one another, creating visual effects like pop-up menus, modal windows, and tooltips. You can use the z-index property to control the order in which elements are layered on top of one another.

- Flexible layouts: Absolute positioning can be used in combination with other layout techniques, like flexbox and grid, to create complex, flexible layouts. By positioning elements absolutely within a parent container, you can create complex, dynamic layouts that adjust to different screen sizes and device types.

- Animation and interactivity: Absolute positioning can be used to create dynamic, interactive web experiences. By positioning elements absolutely and manipulating their position, size, and other properties with CSS and JavaScript, you can create animations, drag-and-drop interfaces, and other interactive features.
  
  ## What is a key difference between fixed positioning and absolute positioning?
  
  The key difference between fixed and absolute positioning is how they are positioned relative to the viewport.

When an element is positioned absolutely, it is positioned relative to the nearest positioned ancestor, or the initial containing block if there is no positioned ancestor. This means that an absolutely positioned element will move with its ancestor element, even if the ancestor is scrolled or resized.

In contrast, a fixed positioned element is positioned relative to the viewport, meaning that it remains in the same position even as the page is scrolled or resized. This makes fixed positioning useful for creating elements like navigation bars, sidebars, or other UI elements that need to stay in a fixed position on the screen as the user scrolls.

Another key difference between fixed and absolute positioning is that a fixed element is removed from the normal document flow, meaning that other elements will flow around it as if it doesn't exist. In contrast, an absolute element still takes up space in the document flow, meaning that other elements will not flow around it.
