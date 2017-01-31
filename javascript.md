# Javascript

Javascript is programming language commonly used along side HTML to enable certain types of functionality for web pages. There have been various versions of Javascript since it's initial release in 1996. Around 2005 some Javascript frameworks started to emerge including JQuery and Prototype Javascript can run in a web browser \(client-side\) or on a server \(server-side\). Javascript implements object-oriented and event-driven methodologies. Here are some definitions that will help when learning Javascript.

**Object** - An element of a programme that represents a particular entity.  
**Property** - An attribute of an object that can be assigned a value.  
**Function** - An encapsulated part of a programme that receives, processes and may return data.  
**Method** - A function that is associated with an object.  
**Variable** - A temporary store for data that can be used at other points in the programme.  
**Event** - An encapsulation of the data that is captured during an action. e.g. mouse click

**Example**

An object could represent a person. A property of that person could be their name. A method of that person could be "Wave" and and event could be that the person "started walking".

Javascript will response to an event that could be executed when the web page loads or when the user performs an action in the browser. Javascript can be applied in three main ways:

**Inline** - an event attribute can be added to any HTML element. The content of the event attribute is Javascript that will be executed if the action occurs.

**Example**

`<div onclick="alert('Hello');"> Hello </div>`

This will open an alert box with the content "Hello" if the element is clicked.

**Embedded** - script tags can be added to an HTML document. The content in these tags is Javascript that can be executed when the page loads or added to a Javascript function.

**Example**

`<script> function hello(){ alert('Hello'); } </script>`

This will open an alert box with the content "Hello" if the 'hello' function is executed.

**External** - Javascript can be put into a separate file that can be associate with one or more HTML documents. The association is made using the script tag.

**Example**

`<script src="main.js"></script>`

This will associate the current document with a file called main.js that should contain Javascript.

Javascript is commonly used to update the elements of the DOM.

**Example**

`document.getElementById("test").style.width = "300px";`

This will set the width of the element with the id "test" to 300px.

### Common Properties

| Property | Description of Value |
| :--- | :--- |
| style | This is the style of an element using sub-properties that correspond to CSS styles except the names are camel case instead of hyphenated. e.g. backgroundColor instead of background-color and fontSize instead of font-size. |
| innerHTML | This is the HTML that is extracted from inside the element's tags. |
| children | This is a collection of the HTML elements extracted from inside the element's tags. |
| attributes | This is a collection of the attributes extracted from inside the opening tag of the element. An individual attribute can be extracted by passing an identifier to the attributes collection e.g. document.getElementById\('test'\).attributes\('id'\) |
| length | This is the number of items in a collection that can be used on any property that returns a collection e.g. document.getElementById\('test'\).children.length |



