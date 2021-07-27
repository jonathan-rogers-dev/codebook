---
layout: default
title: JavaScript - Output
parent: JavaScript
has_children: false
nav_order: 2
---

# JavaScript Output
## Display Possibilities
- Writing into an HTML element, using `innerHTML`.
- Writing into the HTML output using `document.write()`.
- Writing into an alert box, using `window.alert()`.
- Writing into the browser console, using `console.log()`.

## `document.getElementById()`
- `document.getElementById(id)` can be used to access an HTML element.
  - `id` is the id of the HTML element.

## `.innerHTML`
- `innerHTML` can be used to write into an HTML element.
- Changing the `innerHTML` property of an HTML element is a common way to display data in HTML.

```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My First Paragraph</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = 5 + 6;
</script>

</body>
</html>
```

## `document.write()`
- `document.write()` can be used to write into the HTML output.
- Using document.write() after an HTML document is loaded, will delete all existing HTML.
- Should only be used for testing.

```html
 <!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My first paragraph.</p>

<script>
document.write(5 + 6);
</script>

</body>
</html>
```

## `window.alert()`
- `window.alert()` can be used to write into an alert box.
- `window` is the global object of the browser.

```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My first paragraph.</p>

<script>
window.alert(5 + 6);
</script>

</body>
</html>
```
```html
 <!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My first paragraph.</p>

<script>
alert(5 + 6);
</script>

</body>
</html>
```

## `console.log()`
- `console.log()` can be used to write into the browser console.

```html
<!DOCTYPE html>
<html>
<body>

<script>
console.log(5 + 6);
</script>

</body>
</html>
```

## Print
- `window.print()` with a button can be used to print the HTML output to a printer.

```html
<!DOCTYPE html>
<html>
<body>

<button onclick="window.print()">Print this page</button>

</body>
</html>
```