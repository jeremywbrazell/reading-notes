**Name 3 real world use cases where you’d want to change the request with custom middleware:**
1. Logon or authentication
1. Parsing data
1. determing if a user is logged in or not

**True or false: The route handler is middleware?**
True. It is the vehicle that handles requests.

**In what ways can a middleware function end the process and send data to the browser?**
- can refrain from calling ```next()``` but one should make sure that the middleware ends the request-response by calling ```res.end```, ```res.send```, ```res.render``` or any method that implicitely calls ```res.end```

**At what point in the request lifecycle can you “inject” middleware?**
After a request from client to server

**What can cause express to error with “Request headers sent twice, cannot start a second response”**
calling next after response has been returned.

## Definitions

[Middleware:](https://en.wikipedia.org/wiki/Middleware) software that makes it easier for devs to implement communication and input/output
[Request Object:](https://docs.microsoft.com/en-us/previous-versions/iis/6.0-sdk/ms524948(v=vs.90)) retrieves the values that the client browser passed to the server during an HTTP request
[Response Object:](https://docs.microsoft.com/en-us/previous-versions/iis/6.0-sdk/ms525405(v=vs.90))used to send output to the client
[Application Middleware:](https://expressjs.com/en/guide/using-middleware.html#middleware.application) middleware bound to the app object by using ```app.use()``` & ```app.METHOD()``` functions
[Routing Middleware:](https://expressjs.com/en/guide/using-middleware.html#middleware.router)works in the same way as application-level middleware, except it is bound to an instance of ```express.Router()```.
[Test Driven Development:](https://en.wikipedia.org/wiki/Test-driven_development)sw dev process that relies on sw requirements being converted to test cases before sw is fully developed, and tracking all sw development by repeatedly testing the sw
[Behavioral Testing:](https://www.tutorialspoint.com/software_testing_dictionary/behaviour_testing.htm#:~:text=Behavioural%20Testing%20is%20a%20testing,is%20usually%20a%20functional%20testing.) testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing.

## Preview

1. Which 3 things had you heard about previously and now have better clarity on?
    - Constructor functions and how they can be used without React's render/return
    - dynamic Express routes
    - Route handlers

1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- additional response methods
- route middleware
- login routes and how they are used for authentication

1. What are you most excited about trying to implement or see how it works?
- generator methods
- how to redirect a request with ```res.redirect()```
- how middleware is used for logging in