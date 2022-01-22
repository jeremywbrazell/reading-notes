# API Integration

1. **How do bearer tokens work?**
The Bearer Token is created for you by the Authentication server. When a user authenticates your application (client) the authentication server then goes and generates for you a Token. [Ref](https://stackoverflow.com/questions/25838183/what-is-the-oauth-2-0-bearer-token-exactly/25843058#:~:text=The%20Bearer%20Token%20is%20created,token%20used%20with%20OAuth%202.0.&text=You%20use%20the%20bearer%20token%20to%20get%20a%20new%20Access%20token.)

1. **Describe express middleware**
Express middleware are functions that execute during the lifecycle of a request to the Express server. Each middleware has access to the HTTP request and response for each route (or path) it’s attached to. In fact, Express itself is compromised wholly of middleware functions. Additionally, middleware can either terminate the HTTP request or pass it on to another middleware function using next (more on that soon). This “chaining” of middleware allows you to compartmentalize your code and create reusable middleware. [Ref](https://developer.okta.com/blog/2018/09/13/build-and-understand-express-middleware-through-examples)
1. **What is a JWT?**
JSON Web Token - a proposed Internet standard for creating data with optional signature and/or optional encryption whose payload holds JSON that asserts some number of claims. The tokens are signed either using a private secret or a public/private key. [Ref](https://en.wikipedia.org/wiki/JSON_Web_Token)

## Vocab
- **role based access control:**an approach to restricting system access to authorized users. It is an approach to implement mandatory access control (MAC) or discretionary access control (DAC). [Ref](https://en.wikipedia.org/wiki/Role-based_access_control)
- **http cookies:**
small blocks of data created by a web server while a user is browsing a website and placed on the user's computer or other device by the user’s web browser. Cookies are placed on the device used to access a website, and more than one cookie may be placed on a user’s device during a session.
[Ref](https://en.wikipedia.org/wiki/HTTP_cookie)

