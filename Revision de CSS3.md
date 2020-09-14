# Revision de CCS3

Descripcion

En este documento se prorciona un subconjunto de las preguntas y respuestas que aparecen en w3schools.
Esta vez me he creado un usuario para que se guarden los puntos obtenidos...

- - - 
## Selectors
- - - 
Exercise 1

Change the color of all \<p> elements to "red".

~~~
<!DOCTYPE html>
<html>
<head>
<style>
p {
	color: red;
}
</style>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

</body>
</html>
~~~

Exercise 2

Change the color of the element with id="para1", to "red".

~~~
<!DOCTYPE html>
<html>
<head>
<style>
 #para1 {
        color: red;
    }
</style>
</head>
<body>

<h1>This is a Heading</h1>
<p id="para1">This is a paragraph.</p>
<p>This is another paragraph.</p>

</body>
</html>
~~~

Exercise 3

Change the color of all elements with the class "colortext", to "red".

~~~
<!DOCTYPE html>
<html>
<head>
<style>
    .colortext {
        color: red;
    }
</style>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>
<p class="colortext">This is another paragraph.</p>
<p class="colortext">This is also a paragraph.</p>

</body>
</html>
~~~

Exercise 4

Change the color of all &lt;p&gt; and &lt;h1&gt; elements, to "red". Group the selectors to minimize code.

~~~
<!DOCTYPE html>
<html>
<head>
<style>
p, h1 {
    color: red;
}
</style>
</head>
<body>

<h1>This is a Heading</h1>
<h2>This is a smaller heading</h1>
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

</body>
</html>
~~~

- - - 
## Background
- - - 

Exercise 5

Use the shorthand background property to set background image to "img_tree.png", show it once, in the top right corner.

~~~
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background: url("img_tree.png") no-repeat top right;
}
</style>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

</body>
</html>
~~~


- - - 
## Border
- - - 
Exercise 3

Change the 3 border properties, so that they only show the border on the top side.

~~~
<!DOCTYPE html>
<html>
<head>
<style>
p {
  border-top-style: dotted;
  border-top-width: 4px;
  border-top-color: red;
}
</style>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
~~~

- - - 
## Margin
- - - 
Exercise 4

Use the margin property to center align the \<h1> element.

~~~
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  background-color: lightblue;
  width: 300px;
  margin: auto;
}
</style>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
~~~


- - - 
## Box Model
- - - 
Exercise 1 to 4

1. Set the width of the div to "200px".  
2. Set the padding of the div to "25px".  
3. Set the border of the div to "25px solid navy".  
4. Set the margin of the div to "25px".  

~~~
<!DOCTYPE html>
<html>
<head>
<style>
div {
  background-color: lightblue;
  width: 200px;
  padding: 25px;
  border: 25px solid navy;
  margin: 25px;
}
</style>
</head>
<body>

<div>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</div>

</body>
</html>
~~~


- - - 
## Tables
- - - 

- - - 
## Display/visibility
- - - 

- - - 
## Positioning
- - - 

- - - 
## Overflow
- - - 

- - - 
## Align
- - - 

- - - 
## Combinators
- - - 

- - - 
## Pseudo-classes
- - - 

- - - 
## Pseudo-elements
- - - 

- - - 
## Opacity
- - - 

- - - 
## Attribute Selectors
- - - 

- - - 
## Rounded Corners
- - - 

- - - 
## Border Images
- - - 

- - - 
## Backgrounds
- - - 

- - - 
## Colors
- - - 

- - - 
## Gradients
- - - 

- - - 
## Shadow Effects
- - - 

- - - 
## Text Effects
- - - 

- - - 
## Web Fonts
- - - 

- - - 
## 2D Transforms
- - - 

- - - 
## 3D Transforms
- - - 

- - - 
## Transitions
- - - 

- - - 
## Animations
- - - 

- - - 
