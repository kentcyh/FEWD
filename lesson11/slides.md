![General Assembly](assets/images/ga.png)
# FEWD LESSON 11

## Variables and Data Types

### Instructors
Kit Yuen & Mart van de Ven 



## Agenda
<aside class="notes"></aside>

* Introducing JavaScript & jQuery
* jQuery Fundamentals



## Introducing JS
<aside class="notes">Mart (25 Min)</aside>

* Programming Language
* Client-side  
* Behaviour
* File extension: .js
* Ecosystem of JS SDKs, JS libraries, jQuery Plugins.

Let's visit: [Best jQuery](http://www.bestjquery.com)



## Adding the `<script>`
<aside class="notes">Kit (20 Min)</aside>

<script src="path to your js file" type="text/javascript">&#60;/script&#62;



## Adding the `<script>`
<aside class="notes">Kit (20 Min)</aside>

    <script type="text/javascript">YOUR JS CODE</script>



## Adding the `<script>`
<aside class="notes">Kit (20 Min)</aside>

* Put it in `<head>` or `<body>`?
* In general put them in `<head>`
* Putting it in `<head>`, need to wait for the .js to be completely loaded
* Putting just before the `</body>` can increase page load speed
* You can also consider making use of CDN like Google CDN



## Adding the `<script>`
<aside class="notes">Kit (20 Min)</aside>

**In Class Lab** : Adding Scripts



## The inevitable return of the Cookie Monster
<aside class="notes">Mart (40 Min)</aside>

```(.html(), .css(). .click and document ready)``` 

**In Class Lab** : Cookie Monster



## jQuery: Hitting the road
<aside class="notes">Kit (30 Min)</aside>

* `$("p").html("General Assembly");`
* `$("h1").css("color", 'blue');`
* `$(".abc").css("color", 'red');`
* `$("#def").css("color", 'green');`
* `$("#def p").css("color", 'black');`



## jQuery: Hitting the road
<aside class="notes">Kit (30 Min)</aside>

**In Class Lab** : HelloJS

* Go to codepen.io
* Copy paste HelloJS.txt to the appropriate boxes
* Complete the html and include the jquery library from Google CDN
* Write the following jQuery functions in `$(document).ready(function() { CODE });`:
  * change the back ground to black
  * change the h1 tag to read "Hello Your Name" and change the color.
  * change the h2 tag color to white.
* Review Answers



## Homework: RTFM
<aside class="notes"></aside>

**[jQuery documentation](http://api.jquery.com/)**