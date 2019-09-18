# Dynamic web pages with JavaScript

## The 3 layers of web pages are

- HTML(.html): the content layer
- CSS(.css): the presentation layer
- javascript(.js): the behavior layer

The 3 layers form the approach called *pregressive enhancement*.

#### A basic javascript is written in plain text.
```
    var today = new Date();
    var hourNow = today.getHours();
    var greeting;

    if (hourNow > 18) {
      greeting = 'Good evening!';
    } else if (hourNow > 12) {
     greeting = 'Good afternoon!';
    } else if (hourNow > 0) {
        greeting = 'Good morning!';
    } else {
     greeting = 'Welcome!';
    }
    document.write('<h3>' + greeting + '</h3>');

To link to a javascript file from a HTML page, you use the <script> element to tell the brouser that it is coming across as a script. 

    <script scr="js/add-content.js"></script>
 
 
 
