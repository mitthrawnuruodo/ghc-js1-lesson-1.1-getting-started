# Programming Foundations Lesson 1.1: Getting Started

## Excersises for Lesson 1.1

Open the index.html file in a local browser and show the JavaScript console. 

## Excersise 1
In js/script.js add another log message, with any text message inside, save and refresh browser.

## Excersise 2
In js/script.js add the following code snippet : 
```js
const p = document.getElementById("blankParagraph");
p.textContent = "Hello from ...?";
```
Save and refresh browser. 
Add a comment over the code snippet describing what it does.

## Excersise 3
In js/script.js add the following snippet: 
```js
const ul = document.getElementById("emptyList");
ul.innerHTML = "<li>HTML</li>";
ul.innerHTML += "<li>CSS</li>";
```
Save and refresh browser.
Add a comment over the code snippet describing what it does. 

### Exersise 3b
Add another list element to the above: JavaScript

Tip: Note the `+=` in `ul.innerHTML += "<li>CSS</li>";`

## Exersise 4

In js/script.js add the following snippet: 
```js
p.style.color = "red";
p.style.fontWeight = "bold";
```
Save and refresh browser.
Add a comment over the code snippet describing what it does. 

> Tip: Note that the CSS property `font-weight` is written in camelCase here: `fontWeight`.

### Exersise 4b

Make the all the list items from Excersize 3 blue and italic.

## Exersise 5

In js/script.js add the following snippet: 
```js
document.write(7 * 6);
```
Save and refresh browser.
Add a comment over the code snippet describing what it does.

### Exersise 5b

In index.html add the following snippet (eg. between the `<ul id="emptyList>` and `<script src="js/script.js"></script>`): 
```html
<button type="button" onclick="document.write(7 * 6)">Try it</button>
```
Save and refresh browser.
What happens when you push that button?

## Exersise 6


## Exersise 7

In js/script.js add the following snippet: 

```js
document.body.innerHTML = "";
```
What happens? 

Comment out that line, again (keep it in the code, but add `// ` at the beginning of its line).