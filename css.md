# Cascading Style Sheets \(CSS\)

CSS is a language that is used to define the styles of elements in markup languages like HTML. CSS can be applied in three main ways:

Inline - a style attribute can be added to any HTML element. The content of the style attribute is CSS that will be applied to that element.

**Example**

`<div style="background-color:red;"> Hello </div>`

This will add a div with the content "Hello" and will set the bacground background colour of the div to red.

Embedded - style tags can be added to an HTML document. The content in these tags is CSS that can be assigned to an HTML elements in the document.

**Example**

`<style> p{ margin-top: 10px; } </style>`

This will put a top margin of 10 pixels on all paragraph \(&lt;p&gt;\) tags.

External - CSS can be put into a separate file that can be associate with one or more HTML documents. The association is made using the link tag.

**Example**

&lt;link rel="stylesheet" type="text/css" href="main.css"&gt;

