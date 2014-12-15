README.md

## [Re]Introduction to JavaScript

- Small, lightweight language designed for embedding into other software environments -- like browsers
- Provides programmatic control over the browser environment, the DOM
- Object Oriented
  - No distinction between types of objects
  - Properties and methods can be added to objects dynamically
  - Prototypal inheritance
  - Functions are first-order objects
- Dynamically typed
  - You don't have to specify a type when you declare a variable
  - You can assign different types of values to the same variable
- Case sensitive
- Single line comments start with `\\`
- Multiline comments delimited with `\* *\`
- Lines end with semicolons

### Primitive types

- `number`
  - `parseInt()` and `parseFloat()`
- `string`
  - `+` for String concatenation
  - `length` property
  - `chatAt`, `indexOf`, `lastIndexOf`, `concat`, `split`, `slice`, `substr`, `toUpperCase`, `toLowerCase`
  - `match`, `replace`, `search` to work with regular expressions
- `boolean`
- `null`
- `undefined`
- Equality
  - `==`
  - `===` strict equal

### Variables

- `var` keyword for declaring variables
- Declaring a variable without var creates a global variable.  Don't do it!
- Scope
  - local: available within the function where it's declared
  - global: available everywhere
  - no block-level local scope in JavaScript
- Global variables
  - global scope is the `window` in the case of browsers.  `window.variable_name`_
- Constants
  - `const` keyword

### Expressions
- Assignment operators
- Arithmetic
- Logical
  - JavaScript uses short circuit evaluation
- String
- Conditional (ternary) operator

### Loops

- `for` loop
- `while`
- `do .. while`

### Arrays

- predefined in JS
- Creating Arrays
  - Array literals
- Indexing to individual elements
- The first index is 0
- `.length`
- Array methods
  - `push`, `pop`, `concat`, `join`, `shift`, `unshift`, `slice`, `splice`, `reverse`, `sort`
  - `indexOf`, `lastIndexOf`, `forEach`, `map`, `filter`, `every`, `some`

### Object Literals (Hashes)

- A list of pairs of property names and values
- Object literals can be nested
- Accessing values
  - Array syntax `[]`
  - Dot syntax `.`
- `(for .. in ..) { .. }` to iterate over enumerable properties

### Functions

- Declaration
- Invocation
- Parameters
- Can be called recursively
- Function scope
- Anonymous functions


### Interacting with the DOM without jQuery

- What is the DOM?
- With JavaScript you have full CRUD control over the DOM nodes
- You can hook into any events on the page
- Finding nodes in the DOM
    - `document.getElementById()`
    - `document.getElementsByTagName()`
    - `document.getElementsByClassName()`
    - `document.queryselector()`
    - `document.queryselectorall()`
- Changing nodes
    - `element.innerHTML`
    - `element.attribute`
    - `element.setAttribute()`
    - `element.style.attribute`
- Adding/Removing nodes
    - `document.createElement()`
    - `document.removeChild()`
    - `document.appendChild()`
    - `document.replaceChild()`
    - `document.write(text)`
- Adding event handlers
    - `element.addEventListener(event_name, function)`
    - EXCEPT IE 6-8 has `element.attachEvent` instead

### The Console

USE IT ALWAYS.

- `console.log`

## Extend your learning
- Common JS mistakes: http://www.w3schools.com/js/js_mistakes.asp
- JS best practices: http://www.w3schools.com/js/js_best_practices.asp
- HTML DOM events: http://www.w3schools.com/jsref/dom_obj_event.asp
- Strict equality: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Equality_comparisons_and_when_to_use_them
- Regular expressions in JavaScript: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions
- Web API: https://developer.mozilla.org/en-US/docs/Web/API/document

## Resources

Mozilla Developer Network JavaScript Resource: https://developer.mozilla.org/en-US/docs/Web/JavaScript
