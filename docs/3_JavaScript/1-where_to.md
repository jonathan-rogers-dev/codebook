---
layout: default
title: JavaScript - Where To
parent: JavaScript
has_children: false
nav_order: 1
---

# Where To
- The `<script>` and `</script>` tags are used to embed JavaScript into a web page.
    - Old JavaScript examples may use a type attribute: `<script type="text/javascript">`.
- A JavaScript function is a block of JavaScript code, that can be executed when "called" for.
- Scripts can be placed in the `<body>`, or in the `<head>` section of an HTML page, or in both.

## In the `<head>`
```html
<!DOCTYPE html>
<html>

<head>
<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>
</head>
<body>

<h1>A Web Page</h1>
<p id="demo">A Paragraph</p>
<button type="button" onclick="myFunction()">Try it</button>

</body>
</html>
```
## In the `<body>`
```html
<!DOCTYPE html>
<html>
<body>

<h1>A Web Page</h1>
<p id="demo">A Paragraph</p>
<button type="button" onclick="myFunction()">Try it</button>

<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>

</body>
</html>
```

## In External Files

```js
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
```
- External scripts cannot contain `<script>` tags.
- Include the file extension, `.js`.
- Use `<script src="myScript.js"></script>` to include the file in the script.
- External scripts can be referenced with a full URL or with a path relative to the current web page.