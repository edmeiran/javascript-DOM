# DOM Atomic 01: Show One Element

## Questions

---

> If you click the link to reveal more text and then refresh the page, does the text remain revealed, or is it hidden again? Why?

It is hiden again, because the comand refresh, everytime, page is loaded/ refreshed again. :)

---

> Remove `window.addEventListener("load", function(){` (and the closing `})`) from **global.js**. Does the link still reveal the text? What is the purpose of this code that you've removed?

No, it doeasn't, it makes sure you can actaully use the function, so that specific line of code would work.

---

> Describe the the `addEventListener` method. (Remember that there is a specific, technical, methodical way to describe methods. Your reply should match that format.)

The addEventListener() method attaches an event handler to an element without overwriting existing event handlers. You can add many event handlers to one element. 
