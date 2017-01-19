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

The body tags contain all the elements that make up the main content of the web page.

To make a valid HTML web page the DOCTYPE must be declared and the html tags must contain head and body sections.

