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