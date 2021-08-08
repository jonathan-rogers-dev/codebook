---
layout: default
title: JavaScript - Variables
parent: JavaScript
has_children: false
nav_order: 5
---

# JavaScript Variables
- Redeclaring a variable inside a block will also redeclare the variable outside the block:

## Var
- Variables defined with `var` can be Redeclared.
- Variables defined with `var` are hoisted to the top and can be used before they are declared.

## Let
- Variables defined with `let` cannot be Redeclared.
- Variables defined with `let` have Block Scope.

## Const
- A `const` variable cannot be reassigned.
- `const` variables must be assigned a value when they are declared.
- Always declare a variables with `const` unless you know that the value will change.
- Variables defined with `const` have Block Scope.

- Because of this you can NOT:
 - Reassign a constant value.
 - Reassign a constant array.
 - Reassign a constant object.

- But you CAN:
 - Change a constant array.
 - Change a constant object.
