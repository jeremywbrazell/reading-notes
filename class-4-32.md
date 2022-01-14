# Context API - Behaviors

1. **When you have multiple contexts, what component type should you use (class/function) and why?**
Class Component.
1. **What are some good use cases for using the Context API for global state?**
Setting up a list that can be accessed by children globally.
1. **How can you best test context?**
The best way to test Context is to make our tests unaware of its existence and avoiding mocks. We want to test our components in the same way that developers would use them (behavioral testing) and mimic the way they would run in our applications (integration testing). [Ref](https://www.samdawson.dev/article/react-context-testing)

## Vocab
- **context:**React Context is a method to pass props from parent to child component(s), by storing the props in a store(similar in Redux) and using these props from the store by child component(s) without actually passing them manually at each level of the component tree.[Ref](https://www.geeksforgeeks.org/context-in-react/)
- **useContext():**hook is used to create common data that can be accessed throughout the component hierarchy without passing the props down manually to each level.[Ref](https://medium.com/technofunnel/usecontext-in-react-hooks-aa9a60b8a461) 
- **static context:**

## Additional Resources
- [**context API:**](https://reactjs.org/docs/context.html)
- [**hooks & context example:**](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)
- [**React context links:**](https://github.com/diegohaz/awesome-react-context)