---
layout: default
title: JavaScript - Data Types
parent: JavaScript
has_children: false
nav_order: 7
---

# JavaScript Data Types
- JavaScript Variables can change the type of data they contain.

## Strings
- Text in a string is enclosed in double/single quotes.

### String Length
- `.length` property of a string returns the number of characters in the string.
```js
let text = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
text.length;    // Will return 26 
```
### Escape Sequences
- `\`': ' // Single quote
- `\`": " // Double quote
- `\\`: \ // Backslash
- `\n`: \n // New line
- `\r`: \r // Carriage return
- `\t`: \t // Tab
- `\v`: \v // Vertical tab
- `\h`: \h // Horizontal tab
- `\b`: \b // Backspace
- `\f`: \f // Form feed
- `\x`: \x // Hexadecimal
- `\u`: \u // Unicode

### Strings as Objects
`let firstName = new String("John");`

```js
 let x = "John";
let y = new String("John");

// typeof x will return string
// typeof y will return object 
```
- Objects can not be compared using `==` or `!=`.

## Numbers
- Numbers are whole numbers, decimals, and floating point numbers.
- JavaScript has only one type of numbers.

## Booleans
- Booleans are true or false.

## Arrays
- JavaScript arrays are written with square brackets.
- Array items are separated by commas.

## Objects
- Objects are written with curly braces `{}`.

## typeof Operator
- The typeof operator returns the type of a variable.