# Debugging in Javascript

## The Stack
- JS interpreter processes one line of code at a time, from top to bottom

## 2 Phases of Activity for Scripts Entering New Execution Context
1. Prepare:
    1. new scope is created; variables
    1. functions, and arguments are created
1. Execute:
    1. now it can assign values to variables
    1. references functions and runs code
    1. executes statement

## Hoisting
- per W3Schools - Hoisting is JavaScript's default behavior of moving declarations to the top.
    - Note: JavaScript only hoists declarations, not initializations.

## Error Objects

### Properties of Error Objects
```name = type of error```
```message = description```
```fileNumber = name of the JS file```
```lineNumber = line number of error```

### 7 Built-In Error Objects
1. ``` Error = generic error```
1. ```SyntaxError = syntax has not been followed```
1. ```ReferenceError = tried to references a variable that is not declared/within scope```
1. ```TypeError = unexpected data type that cannot be coerced```
1. ```RangeError = #'s not in acceptable range```
1. ```URIError = encodeURI(), decodeURI, & similar methods used incorrectly```
1. ```EvalError = eval() function used incorrectly```

## Debugging Workflow
1. Where is the Problem?
1. What Precisely is the Problem?

## Handling Exceptions
- code used to debug that's given its own code block
1. Try
1. Catch
1. Finally

## Throwing Errors
- if you know something might cause an issue for your script, you can generate your own errors before the interpreter creates them


