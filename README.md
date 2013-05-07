Shakespeare-Insult-Generator
============================

A JS plugin that adds an insult from the great bard, William Shakespeare

Instructions
============================
Before you can use the plugin, you must have jQuery included in your page, do this by inserting the following code in the `<head>` section of your HTML document

``` html
<script src="http://code.jquery.com/jquery-1.9.1.min.js"></script>
<script src="http://code.jquery.com/jquery-migrate-1.1.1.min.js"></script>
```

To use just simply include the insultGenerator.js file in your html doc.

<script type="text/javascript" src="js/insultGenerator.js"></script>

To place an insult on a DOM element simply include the element you want the insult to appear on.

Example
===============
``` javascript
$('.insult').generateInsult();
//Generates a random insult on DOM element with class insult.

$('.subHeading').generateInsult();
//Generates a random insult on DOM element with class subHeading.

$('#myDiv').generateInsult();
//Generates a random insult on DOM element with id myDiv.
```

This is something I whipped up overnight. Have fun. Contribute if you like. Insult people. Be the Don Rickles of your friends. But, in a more Shakespearean way :)

