# Cascading Style Sheets \(CSS\)

CSS is a language that is used to define the styles of elements in markup languages like HTML. CSS can be applied in three main ways:

Inline - a style attribute can be added to any HTML element. The content of the style attribute is CSS that will be applied to that element.

**Example**

`<div style="background-color:red;"> Hello </div>`

This will add a div with the content "Hello" and will set the background colour of the div to red.

Embedded - style tags can be added to an HTML document. The content in these tags is CSS that can be assigned to an HTML elements in the document.

**Example**

`<style> p{ margin-top: 10px; } </style>`

This will put a top margin of 10 pixels on all paragraph \(&lt;p&gt;\) tags.

External - CSS can be put into a separate file that can be associate with one or more HTML documents. The association is made using the link tag.

**Example**

`<link rel="stylesheet" type="text/css" href="main.css">`

This will associate the current document with a file called main.css that should contain CSS.

### Selectors

When using embedded or external CSS, selectors are used to assign the CSS to HTML elements. Selectors can use three types of identifiers when assigning the styles:

Tag type - selectors can use the tag type to assign a style to all tags of a particular type. This is done by typing the tag type followed by curly brackets containing the CSS properties.

**Example**

`div { background-color: red; }`

This will set the background colour of all divs in the associated document or documents.

Class name - selectors can use an identifier assigned to the class attribute of an HTML element to assign styles. The identifier is prefixed with a full stop in CSS to indicate that it is using a class name.

**Example**

`.red_back { background-color: red; }`

`<div class="red_back"> Hello </div>`

This will set the background colour of any HTML element, with the class name red\_back, to red.

id - selectors can use an identifier assigned to the id attribute of an HTML element to assign styles. The identifier is prefixed with a hash symbol \(\#\) in CSS to indicate that it is using an id.

**Example**

`#red_element { background-color: red; }`

`<div id="red_element"> Hello </div>`

This will set the background colour of the HTML element, with the id red\_element, to red. Since the id attribute should be unique in an HTML document, the style will only be applied to that element.

### Properties

Properties are the identifiers for the



