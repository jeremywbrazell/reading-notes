# Context API

1. **Describe use cases useState() vs useReducer()**
useReducer() is an alternative to useState & accepts a reducer of type (state, action) => newState, and returns the current state paired with a dispatch method. (If you’re familiar with Redux, you already know how this works.)useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks. [Ref](https://reactjs.org/docs/hooks-reference.html)

1. **Why do custom hooks need the use prefix?**
To utlize the properties that come with regular hooks.

1. **What do custom hooks usually do?**
Hooks that extract component logic to be used by multiple components.
1. **Using any list of custom hooks, research and name one that you think will be useful in your applications**
useFetch: fetches data
1. **Describe how a hook that fetches API data might work**
You would pass the url into useFetch.

## Vocab
- **reducer:**
Redux functions that return new state values.

## Additional Resources
- [context api](https://reactjs.org/docs/context.html)
- [hooks & context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)
- [react context links](https://github.com/diegohaz/awesome-react-context)