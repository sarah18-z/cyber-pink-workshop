# Introduction:
Welcome to today’s workshop!
Today you will learn everything about websites and how they are built.
At the end of the workshop, you will be able to create a personal or professional portfolio. 

### What is a Portfolio ?

A portfolio is a personal record in which an individual's previous learning and experience is identified and demonstrated for recognition by an educational institution or employer. It differs from a resume in the sense that the information it contains is constructed with a purpose, such as a job application, and it must also present support for the individual's learning.


# Requirements
- Code editor.

[![code editor](https://i.postimg.cc/T2jQDQ5M/Capture.png "code editor")](http:https://i.postimg.cc/T2jQDQ5M/Capture.png// "code editor")

- web navigator.

[![web navigator](https://i.postimg.cc/fbLTxHRH/Capture1.png "web navigator")](httphttps://i.postimg.cc/fbLTxHRH/Capture1.png:// "web navigator")

### Setup the local server
#### For windows users
- Download Visual studio: https://code.visualstudio.com/#alt-downloads
- Download sublime text: https://www.sublimetext.com/3
 
#### For mac os users:   
- Download Visual studio: https://code.visualstudio.com/#alt-downloads
- Download sublime text: https://www.sublimetext.com/3

# Definition
### What is a web site ?
A website is a set of web pages viewable in a browser, these pages are connected by links that allow you to move from one to another. In general, we recognize a website to the comparability of the design of its pages.


[![web site](https://i.postimg.cc/Zq9VvSpV/Sans-titre.png "web site")](http://https://i.postimg.cc/Zq9VvSpV/Sans-titre.png "web site")

### How does a website work?
The operation of the WEB is based on an exchange system called **client-server.**

[![site web](https://i.postimg.cc/t4746STB/Chrome.png "site web")](http:/https://i.postimg.cc/t4746STB/Chrome.png/ "site web")

#### What is a Client-Server model?
- The client is us, it's our web browser, Chrome, Firefox, Safari, Internet Explorer, etc.
- And the server is in fact a powerful computer that stores and hosts websites.

------------
### HTML  :tw-2712:
------------

### What is html?
Hyper Text Markup Language (HTML) is a language of tags that defines the structure of a web page and its content.

[![html ](https://i.postimg.cc/d0JG0s5b/Capture8.png "html ")](http://https://i.postimg.cc/d0JG0s5b/Capture8.png "html ")

It is based on a system of tags to add titles, paragraphs, images, links ... etc.

[![tag](https://i.postimg.cc/Yqh5fJ6L/Capture4.png "tag")](http://https://i.postimg.cc/Yqh5fJ6L/Capture4.png "tag")


### Create your first web page:
il suffit de suivez les étapes suivants:

**step 1:** open the text editor and click on   **File+ New File** 

[![new file](https://i.postimg.cc/x1fKfjxW/Capture9.png "new file")](http://https://i.postimg.cc/x1fKfjxW/Capture9.png "new file")

**Step 2:** click on **Save AS**


[![save as](https://i.postimg.cc/cC6bhnnG/Capture6.png "save as")](http://https://i.postimg.cc/cC6bhnnG/Capture6.png "save as")

# Structure of an HTML page:

[![html](https://i.postimg.cc/PqFNkT9z/Capture7.png "html")](htthttps://i.postimg.cc/PqFNkT9z/Capture7.pngp:// "html")

##### Exemple: 
    
```html
<!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <title>My page name </title>
        </head>
    </html>
```

# START CODING
------------
### Learn HTML TAGs   By Examples
------------
>  ALL HTML FILES MUST HAVE .html EXTENSION

**Example 01** :  HTML div Tag.
> The tag is used as a container for HTML elements - which is then styled with CSS or manipulated with JavaScript.

```html
<div> contents</div>
```

**Example 02** : HTML Headings.
> **headings** are titles or subtitles that you want to display on a webpage.

```html
<h1> Titre niveau 1</h1>
<h2> Titre niveau 1</h2>
<h3> Titre niveau 1</h3>
<h4> Titre niveau 1</h4>
<h5> Titre niveau 1</h5>
<h6> Titre niveau 1</h6>
```

**Example 03** :  HTML Paragraphs.
> The HTML **p** element defines a paragraph.

```html
<p>
hello world
</p>
```

**Example 03** :  HTML **br** Tag.
> Insert single line breaks in a text:

```html
<p>To force<br> line breaks<br> in a text,<br> use the br<br> element.</p>

```


**Example 04** :  HTML Links.
>The HTML **a** tag defines a hyperlink for example [ celec-club.com](http://celec-club.com " celec-club.com")

```html
<a href="celec-club.com"> celec website</a>
```

**Example 05** : HTML Lists (An unordered  list).

```html
<ul>
	<li>List1</li>
	<li>List2</li>
	<li>List3</li>
</ul>
```
**Example 06** : HTML Lists (An ordered  list).
```html
<ol>
	<li>List1</li>
	<li>List2</li>
	<li>List3</li>
</ol>
```
**Example 07** :  ADD images
> - The src attribute represents the image location
> -  The **alt** attribute provides alternative information for an image if a user for some reason cannot view it (due to a slow connection).

```html
<img src="image.jpg"  alt="titre d'image" width="500px" height="600px">
```

**Example 08** :  HTML Comment Tag.
> You can add comments to your HTML source by using the following syntax:

```html
<!--Comment-->
```
**Example 09** : HTML input type Attribute
> You can add comments to your HTML source by using the following syntax:

```html
<input type="text"  name="text"  placeholder="message">
```
**Example 10** : HTML input type Attribute
> - The **button** tag defines a clickable button.
> - Always specify the type attribute for a **button** element, to tell browsers what type of **button** it is.

```html
<button type="button">send </button>
```

------------
### CSS  :tw-2712:
------------

# what is  CSS :

- CSS stands for Cascading Style Sheets
- CSS describes how HTML elements are to be displayed on screen, paper, or in other media
- CSS saves a lot of work. It can control the layout of multiple web pages all at once
- External stylesheets are stored in CSS files

# Why Use CSS :

CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.


# How To Add CSS
Three Ways to Insert CSS:
```css
- External CSS
- Internal CSS
- Inline CSS
```

### External CSS :
> Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

**Example :**
```css
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>
	<h1>This is a heading</h1>
	<p>This is a paragraph.</p>
</body>
</html>
```
- An external style sheet can be written in any text editor, and must be saved with a .css extension.
- The external .css file should not contain any HTML tags.

   Here is how the "mystyle.css" file looks:

```css
   body {
         background-color: blue;
       }

	h1 {
		  color: dark;
		  margin-left: 20px;
  	 }
```
### Internal CSS:
> The internal style is defined inside the **style** element, inside the head section.

**Example :**
```css
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
</head>
<body>
	<h1>This is a heading</h1>
	<p>This is a paragraph.</p>
</body>
</html>

```
### Inline CSS :
> - An inline style may be used to apply a unique style for a single element.
- To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

**Example :**
```css
<!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
</html>
```
# The CSS id Selector :

------------

> - The id selector uses the id attribute of an HTML element to select a specific element.
- The id of an element is unique within a page, so the id selector is used to select one unique element!
- To select an element with a specific id, write a hash (#) character, followed by the id of the element.

**Exemple :**
> The CSS rule below will be applied to the HTML element with **id="paragraphe"**

```css
#paragraphe {
  text-align: center;
  color: red;
}
```
# The CSS class Selector :

------------

> - The .class selector selects elements with a specific class attribute.
- To select elements with a specific class, write a period (.) character, followed by the name of the class.

**Exemple :**
>  The CSS rule below will be applied to the HTML element with **class="hello"**

```css
.hello {
  text-align: center;
  color: red;
}
```



# CSS Text 
> **Text color:**
The color property is used to set the color of the text.

**Example**
```css
h1 {
  color: green ;
}
```
> **Text size:**
he text-size property is used to change the size of the text.

**Example**
```css
h1 {
  color: red ;
}
```
> **CSS font-family**:
In CSS, we use the font-family property to specify the font of a text this is the diffrent faont-family:
- Serif
- Sans-serif
- Monospace
- Cursive
- Fantasy
- Times New Roman

**Example :**
```css
p{
  font-family: "Times New Roman";
}
```
# CSS Margins :
> The CSS margin properties are used to create space around elements, outside of any defined borders.

1. **Margin - Individual Sides :**
- margin-top
- margin-right
- margin-bottom
- margin-left

**Example :**
```css
p {
  margin-top: 100px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 80px;
}
```
 2.**Margin - Shorthand Property  :**
>  margin: top right bottom left ;

**Example :**

```css
p {
  margin: 10x 12px 13px 14px ;
}
```
# CSS padding :
> Padding is used to create space around an element's content, inside of any defined borders.

**1. Padding - Individual Sides :**
- padding-top
- padding-right
- padding-bottom

- padding-left

**Example :**
```css
div{
  padding-top: 50px;
  padding-right: 30px;
  padding-bottom: 50px;
  padding-left: 80px;
}
```

**2.Padding - Shorthand Property :**
> padding: top right bottom left ;

```css
div {
  padding: 25px 50px 75px 100px;
}
```
# CSS Background :
> The CSS background properties are used to add background effects for elements.

**CSS background-color :**
The background-color property specifies the background color of an element.

**Example :**:
```css
body {
  background-color: #1D1E20 
}
```
# CSS Outline :
> An outline is a line that is drawn around elements, OUTSIDE the borders, to make the element "stand out".

![](https://i.postimg.cc/T1zCx17s/Capture-web-19-3-2021-85322-www-w3schools-com.jpg)


**Example :**:
> none - Defines no outline

```css
p{
outline: none;
}
```
# The display Property: 
> - The display property specifies if/how an element is displayed.
- Every HTML element has a default display value depending on what type of element it is. The default display value for most elements is **block** or** inline.**.

**Example :**
```css
/*display inline*/
li {
  display: inline;
}
/*display block*/
span {
  display: block;
}
```

# ADD Coments : 
> CSS comments are not displayed in the browser, but they can help document your source code.

**Example :**:
```css
/* This is a  comment */
p {
  color: red;
}
```

