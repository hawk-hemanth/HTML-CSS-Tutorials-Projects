# HTML Introduction

HTML describe webpage structure with tags marking the documents appropriately to tell the browser what each tagged element is.

Here, <!DOCTYPE html> defines that document is html5, <html> is root element of an html page, <head> contains meta information about the html page, <title> specifies the title for the page.

``` html 
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>
<h1>My First Heading</h1>
<p>My first paragraph.</p>
</body>
</html>
```
All the HTML filenames should have a extensions .html

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## HTML BASICS

```<!DOCTYPE>``` declaration represents the document type, and helps browsers display web pages correctly. <!DOCTYPE html> this is how it should be displayed for HTML5.

* Attributes provide additional information about html elements 
```<a> </a>``` defines html links.

```href``` attribute defines link destination

```<img>``` defines html images. The attributes has following parameters [src(source file), alternative text(alt), width & Height].

```html
<!DOCTYPE html>
<html>
<body>

<h2>HTML Images</h2>
<p>HTML images are defined with the img tag:</p>

<img src="example.jpg" alt="example.com" width="104" height="142">

<a href="http://www.example.com">This is a link</a>

</body>
</html>
```
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## HTML ATTRIBUTES  

 **Attributes in HTML tags allow you to specify additional information for an element. They always come after the opening tag and before the closing tag.

 * HTML links: ```<a href="http://www.example.com"> URL for Exmaple.com </a>``` 
  
<b>The SRC Attribute: </b>

```html
<h2> The src Attribute </h2>
<p> HTML images are defined with the img tag, and the filename of the image source is specified in the src attribute: </p>
<img src="img_girl.jpg" width="500" height="600">
```
**specifying the URL in the ```src``` attribute 

1. Absolute url: Links to the images in other site: ```<img src="https://www.example.com/images/new.png">```
2. Relative url: Links to the images hosted within the websites. ```<img src="example.png"``` or  ```<img src="/images/example.png"```  
    **The slash is related to the site url

** <b> Width and Height attribute(pixels) with ```<img>``` </b>

```html
 <img src="img_girl.jpg" width="500" height="600"> 
```

** <b> Alt attribute </b> includes alternative text for the image incase a user can not read the image: ```<img src="img_girl.jpg" alt="Girl with a jacket">```


** <b> Style Attribute</b> adds style elements like color, font, size, etc to an image/text.

```html
<p style="color:red;"> This is a red color paragraph </p>
```

** <b>Lang attribute:</b> Should always be included inside an <html> tag the declare website language to assist search engines locate you

```html
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
```

** <b> Title attribute:</b> Gives extra information about an element and the attributes will be displayed as a tooltip when mouse pointer runs over it. It needs to be in the Quotes.

```html
 <p title="I'm a tooltip">This is a paragraph.</p> 
```
***Attributes Summary

* All HTML elements can have attributes
* The href attribute of ```<a>``` specifies the URL of the page the link goes to
* The src attribute of ```<img>``` specifies the path to the image to be displayed
* The width and height attributes of ```<img>``` provide size information for images
* The alt attribute of ```<img>```provides an alternate text for an image
* The style attribute is used to add styles to an element, such as color, font, size, and more
* The lang attribute of the ```<html>``` tag declares the language of the Web page
* The title attribute defines some extra information about an element

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## HTML HEADING

Headings go from ```<h1> </h1> to <h6> </h6>```. Search Engines use them to understand the structure of the webpage.

Use ```<h1>``` for main heading followed by ```<h2>``` and so on.

Each heading has its default size. You can change that by specifying inside a style element.

** chnage your style like this.
```html
<h1> style="font-size:60px;">Heading 1</h1>
```
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

## HTML PARAGRAPHS

In html, you cannot be sure of how html will be displayed on each screen size. Adding extra lines or spaces to the document does not add new lines to the page. 
Browser removes extra spaces once page displays.

```html
<p>This is a paragraph</p>
```

* Line breaks: ```<br>``` element
Use this when you want a line break without starting a new paragraph.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

## HTML STYLES

The HTML Style attribute syntax:

```html
<tagname style="property:value;">
```
* Where the property is a CSS property and value is a CSS Value.

*  <b>Background color:</b> Defines the background color for an HTML element
```html
<body style="background-color:powderblue;">
```

* Set background color for two different elements:
```html
<h1 style="background-color:powderblue;">This is a heading</h1>
<p style="background-color:tomato;">This is a paragraph.</p>
```

** Text color
```html
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p> 
```
** Fonts
```html
<h1 style="font-family:verdana;">This is a heading</h1>
<p style="font-family:courier;">This is a paragraph.</p> 
```
** Text Size
```html
<h1 style="font-size:300%;">This is a heading</h1>
<p style="font-size:160%;">This is a paragraph.</p> 
```

** Text alignment
```html
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:center;">Centered paragraph.</p> 
```

<strong>Styles summary</strong> 

* Use the style attribute for styling HTML elements
* Use background-color for background color
* Use color for text colors
* Use font-family for text fonts
* Use font-size for text sizes
* Use text-align for text alignment

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

## HTML FORMATTING

```html
<b>      - Bold text
<strong> - Important text
<i>      - Italic text...often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.
<em>     - Emphasized text. A screen reader will emphasize the text using verbal stress
<mark>   - Marked text. Element that should be highlighted. You can use style to change the color.
<small>  - Smaller text
<del>    - Deleted text. Browsers usually strike a line through
<ins>    - Inserted text... (into a document) Browsers usually underline this. Can be used after del. 
<sub>    - Subscript text...appears half a character below the normal line
<sup>    - Superscript text...can be used for footnotes citation
<address>- To Write the Address
```
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## HTML COMMENTS

There is only exclamation at the start not at the end.

```html
<!-- This is a comment -->

<p>This is a paragraph.</p>

<!-- Remember to add more information here -->
```
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## HTML CSS

HTML STYLES-CSS

CSS can control layout of multiple pages at same time.

CSS: Cascading Style Sheet: To control color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes etc

Tip: The word cascading means that a style applied to a parent element will also apply to all children elements within the parent. So, if you set the color of the body text to "blue", all headings, paragraphs, and other text elements within the body will also get the same color (unless you specify something else)!

CSS can be added to HTML documents in 3 ways:

   a. <b>Inline</b> - by using the style attribute inside HTML elements
   b. <b>Internal</b> - by using a ```<style>``` element in the ```<head>``` section
   c. <b>External</b> - by using a ```<link>``` element to link to an external CSS file.

  1. CSS INLINE:- To apply a unique style to a single HTML element, and it uses the style attribute of such element.
   Eg:- Set h1 color to blue and p color to red.

   ```html
   <h1 style="color:blue;"> A Blue Heading </h1>
   <p style="color:red;"> A red Paragraph </p>
   ```

   2. CSS INTERNAL:- To define style for a single HTML Page and it defined in ```<head>``` section of an html page within ```<style>``` element.
    Eg:- Defining the ```<style>``` in the ```<head>``` section.

    ```html
    
     <!DOCTYPE html>
  <html>
    <head>
     <style>
        body {background-color: powderblue;}
        h1   {color: blue;}
        p    {color: red;}
     </style>
    </head>
    <body>

      <h1>This is a heading</h1>
      <p>This is a paragraph.</p>

    </body>
   </html> 
    ```

   3. CSS EXTERNAL:- Define style for many HTML pages. To use the external style, you add a link to it in the head section of the html. File must not contain any HTML Code and can be written in any text editor. Save with a .css extension. 

    ```html
    <!DOCTYPE html>
    <html>
        <head>
        <link rel="Stylesheet" href="styles.css">
        </head>

        <body>
            <h1>This is a heading</h1>
            <p>This is a paragraph.</p>
        </body>
    </html>
    ```
    This is the style sheet with extension of (.css)

    ```css
    body {
        background-color: powderblue;
    }
    h1 {
        color: green;
    }
    p {
        color: red;
    }
    ```

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## CSS FONTS COLORS AND SIZES

Here, we will demonstrate some commonly used CSS properties. You will learn more about them later.

The CSS color property defines the text color to be used.

The CSS font-family property defines the font to be used.

The CSS font-size property defines the text size to be used.

``` html
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  color: blue;
  font-family: verdana;
  font-size: 300%;
}
p {
  color: red;
  font-family: courier;
  font-size: 160%;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html> 
```
--------------------------------------------------------------------------------------------------------------------------------------------

## CSS BOX MODEL

![Alt text](image.png)

![Alt text](image-1.png)

The CSS box model is a container that contains multiple properties including borders, margins, padding, and the content itself. It is used to create the design and layout of web pages. It can be used as a toolkit for customizing the layout of different elements. The web browser renders every element as a rectangular box according to the CSS box model. 

   1. <b>Content:- </b> The actual data in the form of text, images, or other media forms and it can be sized using the width & height property.
       <b>Content Area:- </b> This area consists of content like text, images, or other media content. It is bounded by the content edge and its dimensions are given by content-box width and height.
   2. <b> Padding:- </b> This property is used to create space around the element, inside any defined border.
       <b> Padding Area:- </b> It includes the element’s padding. This area is actually the space around the content area and within the border-box. Its dimensions are given by the width of the padding-box and the height of the padding-box.
   3. <b> Border:- </b> This property is used to cover the content & any padding, & also allows setting the style, color, and width of the border.
      <b> Border-Area:- </b> It is the area between the box’s padding and margin. Its dimensions are given by the width and height of the border.
   4. <b> Margin:- </b>  This property is used to create space around the element ie., around the border area.
      <b> Margin Area:- </b>  This area consists of space between the border and the margin. The dimensions of the Margin area are the margin-box width and the margin-box height. It is useful to separate the element from its neighbors.

    ```css
      p {
    width: 80px;
    height: 70px;
    margin: 50px;
    border: 2px solid black;
    padding: 5px;
    }
    ```
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

## CSS Link to External

External style sheets can be referenced with a full URL or with a path relative to the current web page.

```html
<link rel="stylesheet" href="https://www.w3schools.com/html/styles.css"> 
```
Links to a style sheet located in the html folder on the current web site:

```html
<link rel="stylesheet" href="/templates/styles.css"> 
```
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

# HTML LINKS 1

They are hyperlinks that can be clicked to be redirected to another page.

```html
<a href="url">link text</a>

href attribute is the link destination.

Link Text:- It is something like a place holder for the URL.

 <a href="http://example.com/">Visit Example.com!</a> 
```

** By default, links will appear as follows in all browsers:
An unvisited link is underlined and blue
A visited link is underlined and purple
An active link is underlined and red

You can also style a link with CSS 

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

# HTML LINKS 2 

The linked page will be displayed in the current browser window. To change this, you must specify another target for the link. using the ```target``` Attribute.

The target attribute specifies where to open the linked document.

Possible Values for the target attribute: 
```html
_self - Default. Opens the document in the same window/tab as it was clicked
_blank - Opens the document in a new window or tab
_parent - Opens the document in the parent frame
_top - Opens the document in the full body of the window
```

```html
<a href="https://www.w3schools.com" target="_blank|_self|_parent|_top">Visit W3Schools.com!</a>
<!-- Choose anyone for the target attribute -->
```

Examples of relative and absolute URL:-
```html
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p> 
```

** HTML Links - Use an Image as a Link: To do this, just use in image <img> tae
```html
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a> 
```

** Link to an Email Address:<b>use mailto:</b> inside href attribute to create a link that oopens in the user's email program (to let them send a new email):

```html
<a href="mailto:someone@gmail.com">Send email</a>
```
** Here is the JS code
```<button onclick="document.location='default.asp'">HTML Tutorial</button>``` 

** LInk titles: Shown as tooltip when mouse pointer is moved on element.
```<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>``

  a. Use the ```<a>``` element to define a link
  b. Use the ```href``` attribute to define the link address
  c. Use the target attribute to define where to open the linked document
  d. Use the ```<img>``` element (inside ```<a>```) to use an image as a link
  e. Use the mailto: scheme inside the href attribute to create a link that opens the user's email program

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
  
## HTML IMAGES

Image tag is used to insert images in a webpage. Images are linked to a webpage not embeded.

SRC attributes 
1. src - Specifies the path to the image 
2. alt - Specifies an alternate text for the image

Syntax
```<img src="url" alt="alternatetext">``` 

Browsers get image from a web server and inserts into the page each time you load. Image stays in same spot in relation to a webpage...else the alt text shows up to indicate that the link is brocken.

**Value of alt attribute shows in cases where: because of slow connection, an error in the src attribute, or if the user uses a screen reader which reads html code and reads out for the user...usually used by the visually impaired people.

**You can also specify width and height in the style attribute of the image
 ```<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">``` 

**With and height attribute as width and height attribute...which is always in pixels
 ```<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">``` 

**It is better to use style attribute so the stylesheet does not end up changing image size.
```html
<!DOCTYPE html>
<html>
<head>
<style>
img {
  width: 100%;
}
</style>
</head>
<body>

<img src="html5.gif" alt="HTML5 Icon" width="128" height="128"> <!-- This image uses the <style> in header by default -->

<img src="html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;"> <!-- This Image tag uses the inline style attribute so it is not affected by the <style> attribute inside the <head> -->

</body>
</html> 
```
**Animated Images:: HTML allows GIFs

```<img src="programming.gif" alt="Computer Man" style="width:48px;height:48px;">``` 

**Image as a tag:: Put <img> tag inside the <a> tag

```html
<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a> 
```
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

# HTML TABLES

```
<table> tag defined the HTML table. 
<tr> defines table row
<th> defines table header. By default bold and centered.
<td> defines table data/cell.. (Columns) By default regular and left-aligned. They are data containers for text, images, lists, other tables, etc.
```

* A Simple HTML Table

```html
 <table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
 </table> 
```
* Add a border to HTML table:::
```css
table, th, td {
  border: 1px solid black;
}
```

** Collapsed Table Border:: Add Border collapse property to enable all borders to collapse into  one border. 
```css
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
```

** Add Cell Padding::: Specifies the space between the cell and its borders. If not specified, table cells are displayed without padding. Use css padding property to set padding:

```css
th, td {
  padding: 15px;
}
```
** Left-align Headings::Table headings are by default bold and centred. 

To left-align table headings, use CSS text-align property. 
```css
th {
  text-align: left;
}
```

** Add border spacing:: Specifies space between cells. Use CSS border-spacing property. Border spacing has no effect for table with collapsed borders
```css
table {
  border-spacing: 5px;
}
```
** Cells that Spans Many Columns:: use colspan attribute
```html
 <table style="width:100%">
  <tr>
    <th>Name</th>
    <th colspan="2">Telephone</th>
  </tr>
  <tr>
    <td>Bill Gates</td>
    <td>55577854</td>
    <td>55577855</td>
  </tr>
</table> 
```

** Make cell that spans many rows::use rowspan. rowspan=2 means that you will specify two row <tr> elements to contain the content spanning two rows
	
```html
 <table style="width:100%">
  <tr>
    <th>Name:</th>
    <td>Bill Gates</td>
  </tr>
  <tr>
    <th rowspan="2">Telephone:</th>
    <td>55577854</td>
  </tr>
  <tr>
    <td>55577855</td>
  </tr>
</table> 
```
** Add a caption to the table:: use <caption>  tag...inserted immediately after the table tag
	
```html
 <table style="width:100%">
  <caption>Monthly savings</caption>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$50</td>
  </tr>
</table> 
```

** Define a special style for one table. Add an id to the table and then define the special style next

``` html
<table id="t01">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table> 
```
```css
#t01 {
  width: 100%;
  background-color: #f1f1c1;
}
```

* <b> CHAPTER SUMMARY _HTML CHAPTER SUMMARY </b>

1. Use the HTML ```<table>``` element to define a table
2. Use the HTML ``<tr>``element to define a table row
3. Use the HTML ``<td>`` element to define a table data
4. Use the HTML ```<th>``` element to define a table heading
5. Use the HTML ```<caption>``` element to define a table caption
6. Use the CSS border property to define a border
7. Use the CSS border-collapse property to collapse cell borders
8. Use the CSS padding property to add padding to cells
9. Use the CSS text-align property to align cell text
10. Use the CSS border-spacing property to set the spacing between cells
11. Use the colspan attribute to make a cell span many columns
12. Use the rowspan attribute to make a cell span many rows
13. Use the id attribute to uniquely define one table 