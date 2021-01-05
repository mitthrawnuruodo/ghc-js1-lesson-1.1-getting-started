# Programming Foundations Lesson 1.1: Getting Started

## Excersises for Lesson 1.1

Open the index.html file in a local browser and show the JavaScript console. 

## Excersise 1
In js/script.js add another log message, with any text message inside, save and refresh browser.

## Excersise 2
In js/script.js add the following code snippet: 
```js
const p = document.getElementById("blankParagraph");
p.textContent = "Hello from ...?";
```
Save and refresh browser. 
Add a comment over the code snippet describing what it does.

## Excersise 3
In js/script.js add the following: 
```js
const ul = document.getElementById("emptyList");
ul.innerHTML = "<li>HTML</li>";
ul.innerHTML += "<li>CSS</li>";
```
Save and refresh browser.
Add a comment over the code snippet describing what it does. 

### 3b
Add another list element to the above: JavaScript

Tip: Note the `+=` in `ul.innerHTML += "<li>CSS</li>";`