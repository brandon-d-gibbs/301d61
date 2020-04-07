#Jquery

###Jquery is a JavaScript library that allows you to do the things you would do in vanilla JS in a MUCH simpler and MUCH faster way, with what is often A LOT less code.

For instance:

```js
//Vanilla 
let a = getElementByID('element');

//jQuery
let a = $(#element); 
Now in this example, there isn't the biggest difference in the amount of code, but you can see how much more simple jQuery makes the code.

//A pretty simple way of adding content in vanilla JS
let a = getElementById('element');
a.innerHTML = 'Hello world!';

// jQuery
$(#element).text('Hello World'); 

```

See, one line! There is so much more that can be done with jQuery including animations and AJAX just to name a few.