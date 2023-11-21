1. ```<i>:``` This is an HTML tag traditionally used to render text in italic style. However, in modern web development, particularly with the use of icon libraries like FontAwesome, the <i> tag is often repurposed to display icons. This is not its semantic meaning, but it's a common practice due to its simplicity and convenience.

class="fas fa-qrcode": The class attribute is used here to apply CSS classes. In this context, fas and fa-qrcode are classes provided by the FontAwesome icon library. FontAwesome is a popular library used to add scalable vector icons to web projects.

fas stands for "FontAwesome Solid", indicating that the icon should be solid (as opposed to regular or light, which are other styles FontAwesome offers).
fa-qrcode specifies the particular icon to be used, in this case, a QR code icon.

## Background 

<a href="https://www.w3schools.com/cssref/css3_pr_background.php"> Background </a>

The background property is a shorthand property for:

1. background-color: Specifies the background color to be used
2. background-image: 	Specifies ONE or MORE background images to be used	
3. background-position: Specifies the position of the background images
4. background-size: Specifies the size of the background images
background-repeat: Specifies how to repeat the background images (Vertically,Horizontally)
background-origin: Specifies the positioning area of the background images
background-clip: Specifies the painting area of the background images
background-attachment: Specifies whether the background images are fixed or scrolls with the rest of the page

1. background-color: red;
2. background-image: url('paper.gif'); | background-image: url('img_tree.gif'), url('paper.gif');
3. background-position: left top; | background-position: left center; | background-position: left bottom; | background-position: right top; | background-position: right center; | background-position: right bottom;
4. background-size: auto; | background-size: contain; | background-size: cover;
5. background-repeat: repeat; | background-repeat: repeat-x; | background-repeat: repeat-y; | background-repeat: no-repeat;

```html
body {
  background: lightblue url("img_tree.gif") fixed center no-repeat;
}
/* For shorthand use only color image position and repeat properites only */
```

## Box-shadow Property

<a href="https://www.w3schools.com/cssref/css3_pr_box-shadow.php"> Box-shadow </a>
The box-shadow property attaches one or more shadows to an element.

```css
#example1 {
  box-shadow: 5px 10px;
}

#example2 {
  box-shadow: 5px 10px 160px #888888; 
  /* horizontal-offset vertical-offset blur clolor
}
```

1. h-offset: The horizontal offset of the shadow. A positive value puts the shadow on the right side of the box, a negative value puts the shadow on the left side of the box'
2. v-offset: Required. The vertical offset of the shadow. A positive value puts the shadow below the box, a negative value puts the shadow above the box
3. blur: The blur radius. The higher the number, the more blurred the shadow will be
4. spread: Optional. The spread radius. A positive value increases the size of the shadow, a negative value decreases the size of the shadow
5. color: Optional. The color of the shadow. The default value is the text color. Look at CSS Color Values for a complete list of possible color values.

**Note: <label> and <input> used together to link the label id to the specific form element.

## Transection 

## Child Elements 