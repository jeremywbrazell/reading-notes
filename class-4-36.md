# Application State with Redux

1. **What are the advantages of storing tokens in “Cookies” vs “Local Storage”**
- If you're using httpOnly and secure cookies, that means your cookies cannot be accessed using JavaScript. This means, even if an attacker can run JS on your site, they can't read your access token from the cookie.
- It's automatically sent in every HTTP request to your server.
[Ref](https://dev.to/cotter/localstorage-vs-cookies-all-you-need-to-know-about-storing-jwt-tokens-securely-in-the-front-end-15id)

1. **Explain 3rd party cookies.**
Third-party cookies are created by domains that are not the website (or domain) that you are visiting. These are usually used for online-advertising purposes and placed on a website through adding scripts or tags. A third-party cookie is accessible on any website that loads the third-party server’s code.
[Ref](https://www.cookiepro.com/knowledge/what-is-a-third-party-cookie/#:~:text=Third%2Dparty%20cookies%20are%20created,the%20third%2Dparty%20server's%20code.)

1. **How do pixel tags work?**
also known as a "tracking pixel," A tag (or often called pixel) is a short snippet of javascript (code) that does something on your website. In the context of marketing/advertising tags and pixels, they are often collecting some information about the visitor to a website and their behavior on the site. This is then sent back to the respective marketing/advertising platform to be processed and reported. [Ref](https://taginspector.com/articles/marketing-tags-and-pixels-form-and-function/)

## Vocab
- **cookies:**
HTTP cookies (also called web cookies, Internet cookies, browser cookies, or simply cookies) are small blocks of data created by a web server while a user is browsing a website and placed on the user's computer or other device by the user’s web browser. [Ref](https://en.wikipedia.org/wiki/HTTP_cookie)
- **authorization:**
Determination of who has access

- **access control:**
Controlling who has what roles or permissions

- **conditional rendering:**
conditional rendering refers to the process of delivering elements and components based on certain conditions. [Ref](https://blog.logrocket.com/conditional-rendering-in-react-c6b0e5af381e/)

## Additional Resources
- [Dan Abranov's Redux Tutorials](https://egghead.io/courses/fundamentals-of-redux-course-from-dan-abramov-bd5cc867)
- [World's Easiest Guide To Redux](https://www.freecodecamp.org/news/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)
- [Testing Reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)
- [Redux Docs](https://redux.js.org/)
