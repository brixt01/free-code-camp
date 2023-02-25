# free-code-camp
This repository contains a collection of solutions to the challenges on [freeCodeCamp](https://www.freecodecamp.org/learn/) which I am in the process of completing, to help me learn web development through HTML, CSS and JavaScript.

---
## Table of Contents
---
* [Responsive Web Design](#responsive-web-design)

    (Basic HTML and HTML5, Basic CSS, Applied Visual Design, Applied Accessibility)

* [JavaScript Algorithms and Data Structures](#javascript-algorithms-and-data-structures)

    (Basic JavaScript, ES6, Regular Expressions, Debugging, Basic Data Structures, Basic Algorithm Scripting, Object Oriented Programming, Functional Programming, Intermediate Algorithm Scripting)

* [Front End Development Libraries](#front-end-development-libraries)

    (Bootstrap, jQuery, Sass, React, Redux, React and Redux)

* [Data Visualization](#data-visualization)

    (Data Visualization with D3, JSON APIs and Ajax, Data Visualization with React)

* [Relational Database](#relational-database)

    (Data Visualization with D3, JSON APIs and Ajax, Data Visualization with React)

* [Back End Development and APIs](#back-end-development-and-apis)

    (Managing Packages with NPM, Basic Node and Express, MongoDB and Mongoose)

* [Quality assurance](#Quaity-assurance)

    (Information Security with HelmetJS, Quality Assurance and Testing with Chai)

* [Scientific Computing with Python](#scientific-computing-with-python)

    (Python for Everybody, Scientific Computing with Python Projects)

* [Data Analysis with Python](#data-analysis-with-python)

    (Data Analysis with Python Projects)

* [Information Security](#information-security)

    (Information Security with HelmetJS, Quality Assurance and Testing with Chai)

* [Machine Learning with Python](#machine-learning-with-python)

    (Machine Learning with Python Projects)

---
## Responsive Web Design
---

## Boilerplate
```
<!DOCTYPE html>
<html>
  <head>
    <meta lang="en">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
  </head>
  <body>

  </body>
</html>
```

## Comments
`<!-- -->`

## Images
Include an `alt`

## Anchor
Include `target=""` - `_self`=Same window/tab (default), `_blank`=New window/tab

## Sections 
`<section></section>` - Used to group related content

## Lists
```
<ul>
  <li></li>
</ul>
```
```
<ol>
  <li></li>
</ol>
```
`ol` = Ordered list (numbers),
`ul` = Unordered list (bullets)

## Figures
```
<figure>
  <img src="" alt="">
  <figcaption></figcaption>
</figure>
```

## em and strong
```
<em></em>
<strong></strong>
```
`em` = Emphasized text,
`strong` = Important text

## Forms
```
<form action="" method="">
</form>
```
`action` = URL for form submission,
`method` = HTTP method for form submission (GET/POST)

## Fieldset
```
<fieldset>
  <legend></legend>
</fieldset>
```
Section of a form

## Labels
```
<label for=""></label>
```
`for` = ID of the input element

## Input
```
<input type="" placeholder="" name="" id="">
```
`type` = Type of input (button, text, email, password, number, date, checkbox, radio, etc.),
`placeholder` = Placeholder text,
`name` = Name used to reference input,
`id` = ID used to reference input

(For radio, same name=group)

(`value` = Value of input, e.g. for radio and checkbox)

## Textarea
```
<textarea name="" id="" cols="" rows=""></textarea>
```

## Submit button
```
<button type="submit"></button>
```

## Footer / Nav
```
<footer></footer>
<nav></nav>
```

## Containers
```
<div></div>
<span></span>
```
Generic and inline containers

## Horizontal rule
```
<hr>
```

---

## Boilerplate
`<link rel="stylesheet" href="">` = Link to CSS stylesheet

## Selectors
```
*{
}
```
All selector
```
element{
}
```
Element selector
```
.class{
}
```
Class selector
```
#id{
}
```
ID selector

## Comments
```
/* */
```

## font-weight
`font-weight: ;`, value = `normal`, `bold`, `100`, `200`, `300`, `400`, `500`, `600`, `700`, `800`, `900`

## Units
```
px
em
rem
```
`px` = Pixels, `em` = Relative to parent element, `rem` = Relative to root element

## Text decoration
```
text-decoration: ;
```
`none`, `underline`, `overline`, `line-through`, `blink`

## Display style
```
display: ;
```
`inline` = Inline element, `block` = Block element, `inline-block` = Inline-block element, `none` = Hidden element

## Positioning
```
position: ;
```
`static` = Default, `relative` = Relative to its normal position, `absolute` = Relative to the nearest positioned ancestor, `fixed` = Relative to the viewport

## Overflow
```
overflow: ;
```
`visible` = Default, `hidden` = Content is clipped, `scroll` = Content is clipped and a scrollbar is added

## Psuedo-classes
```
a:link{
}
```
Unvisited link
```
a:visited{
}
```
Visited link
```
a:hover{
}
```
Hovered link
```
a:active{
}
```
Active link

## Psuedo-elements
```
::first-letter{
}
```
First letter of a paragraph
```
::first-line{
}
```
First line of a paragraph
```
::before{
}
```
Insert content before an element
```
::after{
}
```
Insert content after an element

## Content
```
content: ;
```
Text to be inserted