# Login & Auth 

1. **Why is the Context API useful?**
it can be used to share data with multiple compoents without having to pass data through props

1. **Can a component outside of a provider get its context?**
No.  It needs to be wrapped.

1. **What are some common use cases for using the Context API?**
theming, user language, authentication, authorization, multilingual applications, etc.

1. **Describe “Context Hell”**
Similar to the JQuery callback hell, but the condition where many Providers become dependent on one another to the point where they overload the codebase with wrappers
[Ref](https://alfredosalzillo.medium.com/the-react-context-hell-f31923013891)

## Vocab
- **global state:**
the data that is shared between all the components within a React application. When the state is changed, or let’s say a filter is added, the components re-render accordingly [Ref](https://endertech.com/blog/using-reacts-context-api-for-global-state-management#:~:text=To%20put%20it%20simply%2C%20global,the%20components%20re%2Drender%20accordingly.)
- **global context:**
context that is used to share data globally in React
- **provider:**
the container for all React Spectrum applications. It defines the theme, locale, and other application level settings, and can also be used to provide common properties to a group of components. [Ref](https://react-spectrum.adobe.com/react-spectrum/Provider.html#:~:text=Provider%20is%20the%20container%20for,to%20a%20group%20of%20components.)
- **consumer:**
a React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component. [Ref](https://reactjs.org/docs/context.html#contextconsumer)

## Additional Resources
- [What is role based access control?](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)
- [react-cookies component](https://www.npmjs.com/package/react-cookies)
- [React cookie library](https://www.npmjs.com/package/react-cookie)