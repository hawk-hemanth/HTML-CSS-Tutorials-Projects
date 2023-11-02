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