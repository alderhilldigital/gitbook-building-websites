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

Properties are the identifiers for what style is going to be set. A colon and then the value to which the property is going to be set follow the identifier. The definition for a property finishes with a semi-colon.

**Example**

`div { color: blue; font-size: 10px; }`

### Common Properties

| Property | Description of Value |
| :--- | :--- |
| color | This will set the foreground color that normally equates the the colour of the text. Can be a colour name or hexadecimal colour value. |
| background-color | This will set the background colour. Can be a colour name or hexadecimal colour value. |
| background-image | This will set the image used for the background of an element. Other properties can be used to define it's size, position and tiling. |
| border-width | This will set the width of an element's border. Normally set in pixels. |
| border-color | This will set the colour of an element's border. Can be a colour name or hexadecimal colour value. |
| float | This will specify if an element will float. Can be left, right or none. |
| margin | This will specify the margin for an element. Usually set in pixels or percentages. |
| height | This will set the height for an element. |
| width | This will set the width for an element. |
| left | This will set the distance from the left hand edge of the parent element. |
| right | This will set the distance from the right hand edge of the parent element. |
| top | This will set the distance from the top edge of the parent element. |
| bottom | This will set the distance from the bottom edge of the parent element. |
| padding | This will set the spacing between the edge of an element and it's content. |
| position | This sets the positioning method of an element. Can be static, relative, absolute or fixed. |
| text-align | This sets the text alignment for the content of an element. Can be left, center or right. |
| font-size | This sets the font size for the content of an element. Usually set in pixels or ems \(width of a standard character. |
| font-weight | This sets the font weight for the content of an element. Can be normal, bold, bolder, lighter or a numerical value between 100 and 900 at 100 intervals. |
| font-family | This sets the font for the content of an element. |

There are some properties that are only available in more recent versions of CSS.

**Example**

`#rounded_element { border-radius: 5px; }`

This will round the corners of an element and is available in CSS version 3 an higher.

### Box Model

CSS uses the box model with regards to layout of elements in an HTML document. Each elements consists of a box that contains a series of boxes inside it. The outer box contains the whole element. The next box in is spaced by a margin from the outer box. The next box in is spaced by padding from the margin box and contains the main content of the element.

### Advanced CSS

As well as common styles for HTML elements, CSS can do style transitions and transformations.

**Transitions** allow the control of how an element changes from one style to another. They can be used to make the element be animated over a specified period of time.

**Example**

`#animate_me { width: 100px; transition: width 1s; }`  
`#animate_me:hover { width: 300px; }`

This will set the with set the width of the element named 'animate\_me' to 100 pixels. When the cursor hovers over the element it will animate to 300 pixels wide over a period of 1 second.

**Transformations** allow the 2D and 3D rendering of an element to be changed. This includes moving, turning and scaling elements in both 2 and 3 dimensions.

**Example**

`#turn_me { transform: rotate(90deg); }`

This will rotate the element named 'turn\_me' 90 degrees clockwise.

`#turn_me { transform: rotateY(180deg); }`

This will rotate the element named 'turn\_me' 180 degrees clockwise around the Y axis.

**Transparencies** allow HTML elements to be made more or less transparent by using the 'opacity' property.

**Example**

`#see_through_me { opacity: 0.5; }`

This will set the transparency of the element named 'see\_through\_me' to 0.5, which is 50% see-through. 1 is not transparent and 0 is completely transparent.

