# CSS

 

[CSS Slides](https://github.com/zevenrodriguez/CIM111/blob/master/slides/CSS.pdf)

 [CSS Reference](https://www.w3schools.com/cssref/default.asp)

CSS works by using selectors. Selectors are the ways you target elements on the page.

CSS can be written in 3 locations:

* In the head
```
<head>
 <style>
  p{
   color: green;
  }

 </style>

<head>
```
* External File
 * ```<link rel="stylesheet" type="text/css" href="mystyle.css">```
* Inline Style
 * ```<h1 style="color:blue;margin-left:30px;">This is a heading.</h1>```

### Selectors
* tags
 * Most html tags
* id
 * Used to style one element on your page
* class
 * Used to style multiple elements on the page

[CSS TAGS EXAMPLES](https://github.com/zevenrodriguez/CIM111/blob/master/week8/examples/cssIntro.html)

## LOADING AN EXTERNAL FONT

[Google Fonts](https://fonts.google.com/)

You can link your font

<link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">

Or include this at the top of your with in your style tag or external CSS Document

@import url('https://fonts.googleapis.com/css?family=Roboto');

In your css:

font-family: 'Roboto', sans-serif;

## Homework

HTML/CSS Assignment (100 Points) Due OCT 18-19th

Style your Resume using CSS styling elements
* Set the color of the links and remove the underline.
* Make the underline re-appear with the :hover effect.
* Use a custom font.
* Make sure you use an external stylesheet using the <link> tag.
* Create and use 5 id
* Create and use 2 class
 * Must use each class more the once
* Make sure the webpage validates.






