# Revision de HTML 5

DESCRIPCION

## HTML

- - -

 #### Attributes
- - -
Exercise 1

Add a "**tooltip**" to the paragraph below with the text "About W3Schools":

~~~
<p title="About W3Schools">W3Schools is a web developer's site.</p><br/><br/>
~~~

Exercise 2

Set the size of the image to 250 pixels wide and 400 pixels tall:

~~~
<p><img src="img/w3schools.jpg" width="250" height="400"> </p>
~~~

- - -
#### Headings
- - - 
Exercise 1

Use the correct HTML tag to add a heading with the text "London":

~~~
<h1>London</h1>
~~~

Exercise 3

Mark up the text with appropriate tags:  
"Universal Studios Presents" is the most important heading.  
"Jurassic Park" is the next most important heading.  
"About" is the third most important heading.  
The last sentence is just a paragraph.  
Start with the most important heading (the largest) and end with the least important heading (the smallest):  

~~~
<h1>Universal Studios Presents</h1>
<h2>Jurassic Park</h2>
<h3>About</h3>
<p>On the Island of Isla Nublar, a new park has been built: Jurassic Park is a theme park of cloned dinosaurs!!</p>
~~~

- - -
#### Paragraphs
- - - 
Exercise 5

Wrap this poem around HTML tags that will preserve all spaces and linebreaks when the element is displayed:  
My Bonnie lies over the ocean.  
My Bonnie lies over the sea.  
My Bonnie lies over the ocean.  
Oh, bring back my Bonnie to me.  

~~~
<pre>
    My Bonnie lies over the ocean.  
    My Bonnie lies over the sea.  
    My Bonnie lies over the ocean.  
    Oh, bring back my Bonnie to me.  
</pre>
~~~

- - -
#### Styles
- - -
Exercise 1, 2, 3 and 4

1. Use the correct HTML attribute, and CSS, to set the color of the paragraph to "blue".
2. Use CSS to set the font of the paragraph to "courier".
3. Use CSS to center align the paragraph.
4. Use CSS to set the text size to 50 pixels.

~~~
1. <p style="color:blue;">This is a paragraph.</p> 
2. <p style="font-family:courier;">This is a paragraph.</p>
3. <p style="text-align:center;">This is a paragraph.</p> 
4. <p style="font-size:50px;">This is a paragraph.</p>
~~~

- - -
#### Formatting
- - - 
Exercise 1, 2, 3, 4 and 5

1. Add extra importance to the word "degradation" in the paragraph below.
2. Emphasize the word "metropolitan" in the text below.
3. Highlight the word "FUN" in the text below.
4. Apply subscript formatting to the number "2" in the text below.
5. Add a line through (strikeout) the letters "blue" in the text below.

~~~
1. <p>WWF's mission is to stop the <strong>degradation</strong> of our planet's natural environment.</p> 
2. <p>Tokyo is the capital of Japan, the most populous <em>metropolitan</em> area in the world.</p> 
3. <p>HTML is <mark>FUN</mark> to learn!</p> 
4. <p>H<sub>2</sub>O is the scientific term for water.</p> 
5. <p>My favorite color is <del>blue</del> red.</p> 
~~~

- - -
#### Quotations
- - -
Exercise 2

The text below should be a quoted section. Add the proper HTML element to it, and specify that it is quoted from the following URL: http://www.worldwildlife.org/who/index.html  

For 50 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by 1.2 million members in the United States and close to 5 million globally. 

~~~
<blockquote cite="http://www.worldwildlife.org/who/index.html">For 50 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by 1.2 million members in the United States and close to 5 million globally. </blockquote>
~~~
- - -
#### CSS
- - -
Exercise 4

Use CSS to make a yellow, 3 pixel thick, border around all paragraphs in a class:

~~~
<!DOCTYPE html>
<html>
<head>
<style>
p.one {border: 3px solid yellow;}
</style>
</head>
<body>

<p class="one">This is a paragraph.</p>
<p class="one">This is a paragraph.</p>
<p class="one">This is a paragraph.</p>

p {border: unset;}

<p>This is a paragraph.</p>

</body>
</html> 
~~~

- - -
#### Links
- - -
Exercise 2

Add a "tooltip" to the link. The "tooltip" should say "Home".

~~~
<a href="volver.html" title="Home">Pulsar aquí para ir a volver.html</a> 
~~~

- - -
#### Images
- - -
Exercise 4

Make the image below float to the right of the paragraph.

~~~
<p>
<img src="img/smiley.gif" style="float:right;">
This is a paragraph.
This paragraph contains an image
</p> 
~~~

- - -
#### Tables
- - -
Exercise 6

Use the correct HTML attribute to make the second TH element span two rows.

~~~
<table>
  <tr>
    <th>Name</th>
    <td>Jill Smith</td>
  </tr>
  <tr>
    <th rowspan="2">Phone</th>
    <td>555-77854</td>
  </tr>
  <tr>
    <td>555-77854</td>
  </tr>
</table>
~~~


- - -
#### Lists
- - -
Exercise 5

Use the correct HTML attribute to display uppercase roman numbers.

~~~
<ol type="I">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol> 
~~~

- - -
#### Classes
- - -
Exercise 3

Add two classes to the H1 element, to make the background pink and the color red.

~~~
<!DOCTYPE html>
<html>
<head>
<style>
.intro {background:pink;}
.special {color:red;}
</style>
</head>
<body>
<h1 class="intro special">My Home Page</h1>
</body>
</html> 
~~~


- - -
#### Id
- - -
Exercise 2

Create an id selector named "special".  
Add a color property with the value "blue" inside the "special" declaration block.

~~~
<!DOCTYPE html>
<html>
<head>
<style>
#special  {
    color:blue;
}
</style>
</head>
<body>

<p id="special">My paragraph</p>

</body>
</html>
~~~

- - -
#### Iframes
- - -
Exercise 3

Use CSS to display an iframe with no borders.

~~~
<iframe src="incrustable.html" style="border:none"></iframe> 
~~~

- - -
#### Script
- - -
Exercise 4

Use JavaScript to change the image source from "scream.png" to "smiley.gif":

~~~
<body>
<img id="demo" src="scream.png">
<script>
document.getElementById("demo").src = "smiley.gif";
</script>
</body> 
~~~

- - -
#### Computercode
- - -
Exercise 2

Define the text inside the <code> element as preformatted text (to preserve spaces and line breaks).

~~~
<pre><p>Code example:</p>
<code>var person = {
  firstName:"John",
  lastName:"Doe"
}</code></pre>
~~~

- - -
#### Forms
- - -
Exercise 2

In the form below, add two radio buttons, both with the name "gender".

~~~
<form>
<input type="radio" name="gender" value="male"> Male
<input type="radio" name="gender" value="female"> Female
</form> 
~~~

- - -
#### Form Attributes
- - -
Exercise 2

Specify that the form is submitted using the "POST" method.

~~~
<form action="/action_page.php" method="post">
Name: <input type="text" name="name">
<input type="submit">
</form> 
~~~
- - -
#### Form Elements
- - -
Exercise 2

In the form below, add two option elements to the drop down list.  
The first option must have the value "Volvo".  
The second option must have the value "Ford".  

~~~
<form action="/action_page.php">
<select name="cars">
<option value="Volvo">Volvo</>
<option value="Ford">Ford</>
</select>
</form> 
~~~

- - -
#### Input Types
- - -
Exercise 5

In the form below, add a input field that can only contain numbers.  
Use the correct input attributes to only allow numbers between 1 and 5.  

~~~
<form action="/action_page.php">
<input type="number" min="1" max="5">
</form> 
~~~

- - -
#### Input Attributes
- - -
Exercise 4

Set the input field to be read only (meaning that the value cannot be changed).  
~~~
<form action="/action_page.php">
<input type="text" readonly>
</form> 
~~~

- - -
Revision de CCS3.md

