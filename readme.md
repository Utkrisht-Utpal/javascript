# This is the files where i will be learning javascript till intermediate level.

console.log prints the message.
<br>
variable declaration means nothing.
<br>
I am exploring with git as well so that i can learn new things.
<br>

document.title = 'Hii' it basically changes the properties of the html document

let cost = Number(document.getElementById('input').value);   we can typecast like this

event listeners: onclick, onKeydown, onscroll, onmouseenter, onmouseleave

this stores and logs every input that we get in a text box
input.addEventListener('input', () => {
    output.textContent = input.value;
});

Asynchronous (async) is a programming approach that allows certain operations, such as network requests (fetching data from an API), file operations, or time delays, to run in the background without blocking the main program from continuing to execute other code, example: setTimeout();

data attribute is used to give id to a product/button which can be used to store data in the backend. just an HTML attribute, name should always be start with data, like data-product-rate.

#modules:
to avoid name conflicts. used with: type = "module" (in the script tag in html file), import (in using file), export (to transfer) 
-> most importantly, variables are read only when exported, we have to use getter and setter to change values.
syntax: import { cart as myCart (optional) } from "./Database/cart.js";
    <script type="module" src="script.js" defer></script>


