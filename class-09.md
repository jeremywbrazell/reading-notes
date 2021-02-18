# Forms and JS Events

## Forms

### How Forms Work:
- a user fills in a form and then presses a button to submit the info to the server

### Form Syntax
```<form>```
```<form action>```
```<input type>```
```<type="text" name="username size="15>```
```<input type="password>```
```<textarea name="comments">```
```<input type="radio">```
```<input type="checkbox">```
```<select>``` - dropdown boxes
```<input type="file>```
```<input type="submit">```
```<input type="image">```

## Lists, Tables, & Forms
- CSS shorthand for list ```list style: inside circle;```

### Gaps Between Cells
```table.one {
    border-spacing: 5px 15px;}
```

```
table.two {
    border-collapse: collapse;}
```
## Events
- Per MDN: Events are actions or occurrences that happen in the system you are programming, which the system tells you about so you can respond to them in some way if desired.

1. different types:
    - load
    - unload
    - error
    - resize
    - scroll
    - keydown
    - keyup
    - keypress
    - click
    - dbclick
    - mousedown
    - mouseup
    - mousemove
    - mouseover
    - mouseout

### How Events Trigger JS Code
1. Select the element node(s) you want the script to respond to
1. Indicate which event on the selected node(s) will trigger the response
1. State the code you want to run when the event occurs

