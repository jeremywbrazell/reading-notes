# Javascript Call Stack 
[Reference Article](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/)
- primarily used for function invocation(call), which is synchronous since the call stack is single, function exectuion from top to bottom

- a call stack is a data structlure tha uses LIFO (last in first out)

# Stack Overflow Causes
- when there is a recursive function (a function that calls itself) without an exit point.  The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error

Example:

```
function callMyself(){
  callMyself();
}

callMyself();
```

## Key Takeaways of the Call Stack
1. It is single-threaded, maning it can only do one thing at a time.
1. A function invocation creates a stack frame that occupies a temporary memory.
1. It works as a LIFO — Last In, First Out data structure.

# Javascript Error Messages && Debugging
[Reference Article](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

## Types of Error Messages
1. Reference Errors
1. Syntax Errors
1. Range Errors
1. Type Errors


