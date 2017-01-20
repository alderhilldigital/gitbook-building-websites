# HTML5

Sir Tim Berners-Lee came up with a concept called “HTML Tags” based on the Standard Generalised Markup Language \(SGML\). Other markup languages like XML where also based on SGML. HTML 2.0 was the first official specification.

The latest version of HTML is HTML5 and still uses the same syntax structure with some additional tag names added. The other main landmark HTML versions are HTML 3.2, HTML 4.01 and XHTML.

HTML5 uses a "tag" based structure that is used by a web browser to specify what and how the content of a web page should be displayed. A tag is a text-based identifier that contains a left angle bracket and a right angle bracket with the text in between. There may also be a closing tag that is the same but a forward slash is added after the left angle bracket.

Example

`<label> Hello </label>`

An HTML5 document must contain certain tags to make it an HTML5 document.

Example

`<!DOCTYPE html>`  
`<html lang="en">`  
`<head>`  
`<meta charset="utf-8">`  
`<title>title</title>`  
`<link rel="stylesheet" href="style.css">`  
`<script src="script.js"></script>`  
`</head>`  
`<body>`  
`<!-- page content -->`  
`</body>`  
`</html>`

We will go through each of the tags in the example and give some more details about how and why they are used.

The DOCTYPE tag is used to tell the web browser the document type and what version of HTML the document is using. Using html in the DOCTYPE tag tells the web browser that it should treat it as an HTML5 document.

The html tags contain all the html elements. Using the lang attribute in the opening html tag specifies the language so the web browsers knows what language the web page is written in.

The head tags contain links to related documents that contain other information about what should be displayed on the web page. These documents can be referenced using the link tag or the script tag. The head tags also contain meta data that is used by search engines and other programmes that want a summary or keywords about the web page. The meta tag is used to define most of the meta data, some programmes will also use the title tag. The title will normally display in the top bar or tab of the web browser

The body tags contain all the elements that make up the main content of the web page. The tag with an exclamation mark and two hyphens is a comment. It is used to add notes to the HTML document that won't be displayed.

To make a valid HTML web page the DOCTYPE must be declared and the html tags must contain head and body sections.

# Common Tags

| Tag | Description |
| :--- | :--- |
| `<!-- -->` | Defines a comment tag. Comment tags are used to annotate HTML code. They will not display on a web page. |
| `<!DOCTYPE>` | Defines the document type. In most cases this will be html.  There are older versions of html doctypes as well as completely different types e.g. XML |
| `<html>` | Defines the base of the HTML document. All content and definitions for a web page will appear inside this set of base tags. |
| `<head>` | Defines the information about the document. Will contain other tags that define information about the web page including style, scripts and meta data. |
| `<body>` | Defines the document body. This will contain all the elements that make up the main content of the web page. It will contain many other tags and subsets of tags. |
| `<a>` | Defines a hyperlink. A hyperlink is used to connect to a document and sometimes a particular point in a document. It uses the href attribute to define the hyperlink destination. |
| `<img>` | Defines an image. Image tags use the src attribute to define the source of the image, usually a file path or url to an image file. |
| `<p>` | Defines a paragraph. |
| `<br>` | Defines a line break. |
| `<div>` | Defines a division. A division separates the page into structural components. It is mostly used for designing and lying out of the web page. |
| `<span>` | Defines a section of a document. Similar to a division but displays inline by default. |
| `<blockquote>` | Defines a section that is quoted from another source. The blockquote is normally indented with some margins at the top and bottom of the content. |
| `<table>` | Defines a table consisting of rows and columns. The table can also be split into header, body and footer. |
| `<thead>` | Groups table elements into a header. Normally consists of a table row containing table header cells. |
| `<tr>` | Defines a table row. A table row can contain table cells or table header cells. |
| `<th>` | Defines a table header cell. |
| `<tbody>` | Groups table elements into the main table body. |
| `<td>` | Defines a table cell. |
| `<tfoot>` | Groups table elements into a footer. |
| `<ul>` | Defines an unordered list |
| `<ol>` | Defines an ordered list |
| `<li>` | Defines a list item. List items are used in both ordered and unordered lists. |
| `<form>` | Defines a form. Form tags mainly contain input fields. When a form is submitted the data from the form is sent to the location specified in the action attribute of the form tag. |
| `<input>` | Defines an input field. Input fields are used to enter information into a web page to be submitted into some other process. Inputs have many different types including text, integers and passwords. |
| `<label>` | Defines a label. Labels are commonly used to label input fields as they can be associated with other elements using the for attribute. |
| `<select>` | Defines a drop-down list. Drop-down lists contain option tags that list options that can be selected. |
| `<option>` | Defines an option for a drop-down list. |
| `<textarea>` | Defines a multiline text input element. Similar to an input of type text, it allows for multiple lines to be entered. |
| `<button>` | Defines a clickable button. Buttons can be used to perform some form actions or run scripts. |
| `<b>` | Defines bold text |
| `<strong>` | Defines important text. Visually the same as &lt;b&gt; tag. |
| `<em>` | Defines emphasised text. |
| `<i>` | Defines italic text. |
| `<u>` | Defines text that should be stylistically different from normal text. |
| `<h1>` to `<h6>` | Defines different sizes of HTML headers. These are mainly used for section titles, sub-titles etc. |
| `<hr>` | Defines a horizontal rule. This is a line that runs across it's parent element, used to show divisions between sections. |
| `<link>` | Defines a relationship between a document and another external resource. This is commonly used to create a link to a style sheet file. |
| `<script>` | Defines a client-side script. Script tags are commonly used to insert javascript. The javascript can be directly inserted inside the script tags or the script tags can be used to link to an external script file. |
| `<style>` |  |

&lt;audio&gt;    Defines sound content

&lt;link&gt;    Defines the relationship between a document and an external resource \(most used to link to style sheets\)

&lt;script&gt;    Defines a client-side script

&lt;style&gt;    Defines style information for a document

&lt;title&gt;    Defines a title for the document

