# Understanding CSS

CSS allows you to create rules that control the way that each individual HTML element is presented.
CSS rules usual appear in a seperate document that you link to you HTML page.

## Each HTML element is in an invisible box, CSS lets you
- control the width and height
- add borders
- change the background color
- place images with in that "box"

###CSS also allows you to control text
- typeface
- size
- color
- *italicize*
- **bold**

You can also add lists, tables and forms

To do this you have to make a declaration to the element you want to change, for example:

    p {font-family: Arial}

"p" is called the selector, and "{font-family: Arial}" is called the declaration.
CSS declarations are always inside curly brackets { }.  And inside the curly brackets, you have the 
    p {property: value;}
The property is always followed by a colon :, and the value is always followed by a semi-colon ;

One of the fun elements of CSS is adding color to your website. 
There are 3 ways to specify colors:
- RGB values
- hex codes
- color names 
There are 147 predefined color names that are recognized by browsers.  To choose a different color you may have to you a color picker tool to get the hex code or RGB value for that particular color.

CSS3 had indroduced an opacity property that you can add to any element.  
    p {background-color: rgb(50, 164, 168);
       opacity: 0.5;}
Or you can do this by using RGBA 
    p {background-color: rgba(50, 164, 168.5);}

CSS3 has also added HSL, which lets you control the hue, saturation and lightness of values.
    body {
        background-color: #C8C8C8;
        background-color: hsl(0.0%.78%);
    }
Hue is expresses as and angle between 0-360 degrees.  Saturation and lightness are expressed as a percentage.