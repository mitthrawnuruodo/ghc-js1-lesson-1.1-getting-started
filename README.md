# JavaScript 1 Lesson 1.1: Getting Started

## Excersises for Lesson 1.1

Open the index.html file in a local browser and show the JavaScript console.

## Exercise 1
In js/script.js add another log message, with any text message inside, save and refresh browser.

Did you see the log entry in the console?

## Exercise 2
In js/script.js add the following code snippet : 
```js
const p = document.getElementById("blankParagraph");
p.textContent = "Hello from ...?";
```
Save and refresh browser. 
Add a comment over the code snippet describing what it does, and change the text to add your own (nick-) name.

## Exercise 3
In js/script.js add the following snippet: 
```js
const ul = document.getElementById("emptyList");
ul.innerHTML = "<li>HTML</li>";
ul.innerHTML += "<li>CSS</li>";
```
Save and refresh browser.
Add a comment over the code snippet describing what it does. 

### Exercise 3b
Add another list element to the above: JavaScript

Tip: Note the `+=` in `ul.innerHTML += "<li>CSS</li>";`

## Exercise 4

In js/script.js add the following snippet: 
```js
p.style.color = "red";
p.style.fontWeight = "bold";
```
Save and refresh browser.
Add a comment over the code snippet describing what it does. 

> Tip: Note that the CSS property `font-weight` is written in camelCase here: `fontWeight`.

### Exercise 4b

Make the all the list items from Exercize 3 blue and italic.

### Exercise 4c

Make the background colour of the whole page beige.

> Tip: use `document.body` and not the `p` or `ul` elements.

## Exercise 5

In js/script.js add the following snippet: 
```js
document.write(7 * 6);
```
Save and refresh browser.
Add a comment over the code snippet describing what it does.

### Exercise 5b

In index.html add the following snippet (eg. between the `<ul id="emptyList>` and `<script src="js/script.js"></script>`): 
```html
<button type="button" onclick="document.write(7 * 6)">Try it</button>
```
Save and refresh browser.
What happens when you push that button?

## Exercise 6

In js/script.js add the following snippet: 
```js
window.alert(23 + 19);
```
Save and refresh browser.
Add a comment over the code snippet describing what it does.

### Exercise 6b

Change the snippet from above to:
```js
window.alert("The answer is: " + 23 + 19);
```
What happens? Add to comment.

### Exercise 6c

Add parenthesis, like so:
```js
window.alert("The answer is: " + (23 + 19));
```
Now, what happens? Add to comment.

Comment out the alert (keep it in the code, but add `// ` at the beginning of its line).

## Exercise 7

In js/script.js add the following snippet: 

```js
document.body.innerHTML = "";
```
Save and refresh browser.
Add a comment over the code snippet describing what it does.

Comment out that last line, again (keep it in the code, but add `// ` at the beginning of its line).
