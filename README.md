# HTML Cheatsheet

HTML Cheatsheet

### Headings
```html
<h1> HEADING1 </h1>
<h2> HEADING2 </h2>
<h3> HEADING3 </h3>
<h4> HEADING4 </h4>
<h5> HEADING5 </h5>
<h6> HEADING6 </h6>
```
output :
<h1> HEADING1 </h1>
<h2> HEADING2 </h2>
<h3> HEADING3 </h3>
<h4> HEADING4 </h4>
<h5> HEADING5 </h5>
<h6> HEADING6 </h6>

### Fonts
```html
<em> emphaize </em>
<i> italics </i>
<b> bold </b>
<strong>strong</strong>
<small>small</small>
```
output: 
<em> emphaize </em>
<i> italics </i>
<b> bold </b>
<strong>strong</strong>
<small>small</small>

### inputs
```html 
<input type = "text">
<input type = "password">
<input type = "date">
<input type = "range">
```
### Forms
```html
<form action="mail.cgi" method="post">
	<input type="text" name="firstName" size  = "15"/>
	<input type="submit" name="sbutton" value="Send">
</form>
```
### break tag 
```html
<br> 
```
### Image tag 
```html
 <img src="img_girl.jpg"  width="500" height="600"> 
```
<img src="img_girl.jpg"  width="500" height="600"> 
 

### Head Elements
```html 
<head></head> Container for metadata
<title></title> The title of your project
<link rel="stylesheet" href=""> link to external style sheets
<meta> specify the character set, page description, keywords, author of the document, and viewport settings
<style></style> used to define style information for a single document
<base href="">  specifies the base URL and/or target for all relative URLs in a page
<script></script> define client-side JavaScripts
```

### Horizontal Rules 
```html
<hr> 
```

### Links 
```html
<a href="url">link text</a> Link to url
<a href="#yourSection">link text</a> Link to your section
```

### Table 
```html
<table></table> define a table
<tr></tr> define a table row
<th></th> define a table heading
<td></td> define a table data
```

### Lists
```html
<ul></ul> Defines an unordered list
<ol></ol> Defines an ordered list
<li></li> Defines a list item
<dl></dl> Defines a description list
<dt></dt> Defines a term in a description list
<dd></dd> Describes the term in a description list
```

### Form
```html
<form action=""></form> create an HTML form
<label for=""></label> defines a label for many form elements
<input type=""> Defines an input control
<textarea name="" id="" cols="30" rows="10"></textarea> Defines a multiline input control (text area)
<select name="" id=""></select> Defines a drop-down list
<option value=""></option> Defines an option in a drop-down list
<fieldset></fieldset> Groups related elements in a form
<legend></legend> Defines a caption for a <fieldset> element
```

### Button
```html
<button></button> Defines a clickable button
```

### SVG
```html
<svg></svg> container for SVG graphics

### Video tag
```html
 <video controls src="movie.mp4" type="video/mp4">
	Video type not supported by this browser!
 </video>
```

### Unordered List tag
```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

### HTML Semantics
```html
<header></header> Specifies a header for a document or section
<main></main> Specifies the main content of a document
<footer></footer> Defines a footer for a document or section
<article></article> Defines independent, self-contained content
<aside></aside> Defines content aside from the page content
<figure></figure> Specifies self-contained content
<nav></nav> Defines navigation links
<section></section> Defines a section in a document
```
