# HTML Lists, Control Flow with JS, and the CSS Box Model

## Lists

### Numbered Lists
- lists that start w/ a #
```<ol>``` Ordered List
```<li>``` List Item

### Unordered (Bullet) Lists
```<ul>``` Unordered List
```<li>``` List Item

### Definition Lists
```<dl>``` Definition List
```<dt>``` Defintion Term
```<dd>``` Defintion

## CSS Boxes
- called out by width and height
- can limit dimensions with ```min-width``` & ```max-wid5h```
- same goes for height

### Overflow
- tells the browser what to do when content is larger than what's in box w/ 2 ways:
    1. hidden
    1. scroll

### Box Model Layers
```border```
```margin```
```padding```

### Border Width
```border-width```

### Border Style
```border-style```

### Border Color
```border-color```

### Shorthand Border
```p {
    width: 250px;
    border: 3px dotted #000000;
}
```

### Padding
```padding:```

### Margin
```margin```

### Box Shadows
```box-shadow```

### Rounded Corners
```border-radius```

### Elliptical Shapes
```border-radius```

## Basic Javascript Instructions

### Arrays
- special type of variable that stores a list of values

Example:
```
var colors;
colors = ['white', 'black', 'custom'];

var el = document.getElementById('colors');
el.textContent = colors[0];
```
## Decisions and Loops

### If...Else Statments
- if stantement evaluates a condition

### Switch Statements
- each statement indicates a possible value for the variable

### Type Coercion & Weak Typing
- JS tries to make sense of unexpected data types rather than reporting errors

### Truth & Falsey Values
- Falsy values can be treated as if they're "0"
- Truthy values can be treated as if they're true and as if they're "1"

### Short Circuit Values
- the same incorrect value is returned when  it is short-circuited(stopped)

### Loops
- 3 Keywords:
    1. For
    1. While
    Do While

### Loop Counters
- Made up of 3 statements:
    1. Initialization
    1. Condition
    1. Update


