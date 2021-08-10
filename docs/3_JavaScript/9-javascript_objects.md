---
layout: default
title: JavaScript - Objects
parent: JavaScript
has_children: false
nav_order: 9
---

# JavaScript Objects
```js
const car = {type:"Fiat", model:"500", color:"white"};
```

## Accessing Object Properties
`objectName.propertyName` or `objectName["propertyName"]`

## JavaScript Methods
- A method is a function that is associated with a particular object.

```js
const person = {
  firstName: "John",
  lastName : "Doe",
  id       : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};
```

### `this` Keyword
- `this` is a reference to the current object.
 ` The "owner" of the function.

## `new` Keyword
- `new` is used to create a new object.

```js
x = new String();        // Declares x as a String object
y = new Number();        // Declares y as a Number object
z = new Boolean();       // Declares z as a Boolean object
```