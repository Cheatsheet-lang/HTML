# HTML Cheatsheet

HTML Cheatsheet

## Headings

```html
<h1>HEADING1</h1>
<h2>HEADING2</h2>
<h3>HEADING3</h3>
<h4>HEADING4</h4>
<h5>HEADING5</h5>
<h6>HEADING6</h6>
```

Output

<h1> HEADING1 </h1>
<h2> HEADING2 </h2>
<h3> HEADING3 </h3>
<h4> HEADING4 </h4>
<h5> HEADING5 </h5>
<h6> HEADING6 </h6>

## Font Style

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

## Input

```html
<input type="text" /> defines single line text input field
<input type="password" /> defines password field
<input type="checkbox" /> defines a checkbox <input type="color" /> used for
input fields that should contain a color <input type="date" /> input field
should contain date <input type="email" /> email type input field
<input type="file" /> defines file select field and browse button
<input type="image" /> upload image <input type="month" /> select month and year
<input type="number" /> defines numeric input field
<input type="radio" /> defines a radio button <input type="range" /> slider
control <input type="reset" /> defines a reset button that will reset all form
values to their default values <input type="search" /> define search field
<input type="submit" /> defines button for submitting form data
<input type="tel" /> defines telephone number field <input type="time" /> select
time(without timezone) <input type="url" /> url address type input field
<input type="week" /> select week and year
```

## Form

```html
*Note: name and id can be used for these tags, to access them uniquely
<form action="" method="" target=""></form>
container to create HTML forms <input type="" /> defines input control,
depending on the attribute 'type' <label for=""></label> defines a label for a
form element, according to 'for' attribute
<select></select>
defines dropdown list in the form
<option value=""></option>
defines an option in the dropdown list
<textarea rows="" cols=""></textarea> defines a multiple line input field
<fieldset></fieldset>
group related elements in a form
<legend></legend>
defines caption for fieldset tag
<datalist><option value="">..</option></datalist> specifies list of pre-defined
options for an input tag <output></output> used to represent result of a
calculation (for using this tag, you will have to use oninput attribute within
form tag)
<optgroup></optgroup>
used to group related options
```

## Break

```html
<br />
```

## Image

```html
You can add image if it is stored in your working space like this:
<img src="img_girl.jpg" width="400" height="400" />
Or you can add image directly from your browser like this:
<img
  src="https://cdn.mos.cms.futurecdn.net/hFm4iWXhbw4c4rdcMH8tUD.jpg"
  width="400"
  height="400"
/>
```

Output of 2nd method:

 <img src="https://cdn.mos.cms.futurecdn.net/hFm4iWXhbw4c4rdcMH8tUD.jpg"  width="400" height="400">

## Head

```html
<head></head> Container for metadata <title></title> The title of your project
<link rel="stylesheet" href="" /> link to external style sheets <meta /> specify
the character set, page description, keywords, author of the document, and
viewport settings <style></style> used to define style information for a single
document <base href="" /> specifies the base URL and/or target for all relative
URLs in a page
<script></script>
define client-side JavaScripts
```

## Horizontal Ruler

```html
<hr />
```

## Anchor

```html
<a href="url">link text</a> Link to url
<a href="#yourSection">link text</a> Link to your section
<a href="url" target="_blanl">link text</a> Opens your link in another tab in a
browser
```

## Table

```html
<table></table>
define a table
<tr></tr>
define a table row
<th></th>
define a table heading
<td></td>
define a table data
```

## List

```html
<ul></ul>
Defines an unordered list
<ol></ol>
Defines an ordered list
<li></li>
Defines a list item
<dl></dl>
Defines a description list
<dt></dt>
Defines a term in a description list
<dd></dd>
Describes the term in a description list
```

## Button

```html
<button></button> Defines a clickable button
```

## SVG

````html
<svg></svg> container for SVG graphics ### Video tag ```html
<video controls src="movie.mp4" type="video/mp4">
  Video type not supported by this browser!
</video>
````

## Unordered List

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

## HTML Semantics

```html
<header></header>
Specifies a header for a document or section
<main></main>
Specifies the main content of a document
<footer></footer>
Defines a footer for a document or section
<article></article>
Defines independent, self-contained content
<aside></aside>
Defines content aside from the page content
<figure></figure>
Specifies self-contained content
<nav></nav>
Defines navigation links
<section></section>
Defines a section in a document
```

## Semantic media Tags

````html
<figure></figure> Embeds annotated images, illustrations, photos, code, etc.
<figcaption></figcaption> For adding a caption/annotation to the <figure>.
<picture></picture> Responsive image insertion,allows developers to provide different images for different contexts.
<video poster=" " autoplay loop controls ></video>For embedding videos into a website.
   poster is the path to an image that’s displayed before the video plays.
   autoplay will start the video automatically.
   loop triggers whether the video should repeat or not.
   controls shows or hides the browser’s player buttons.
<audio></audio> For embedding audio into a website.
<source></source> Must be inside <picture>, <video> or <audio> to define the different versions of content.
```

## Audio

```html
<audio></audio> The HTML <audio> element is used to embed sound content in documents.
```

## Scripting

```html
<canvas></canvas> Used with either the canvas scripting API or the WebGL API to draw graphics and animations.
<noscript></noscript> Defines a section of HTML to be inserted if a script type on the page is unsupported or if scripting is currently turned off in the browser.
````

### Emojis

```html
<p style="font-size:48px">&#128512; &#128516; &#128525; &#128151;</p>
```

Output:

```html
<p style="font-size:48px">&#128512; &#128516; &#128525; &#128151;</p>
```

> For Emoji Unicode refer _[this](https://www.w3schools.com/charsets/ref_emoji.asp)_.
