# Advanced State with Reducers

1. **How can we ensure that an effect hook runs only once?**
By giving the function an empty array.

1. **Can useState() update more than one state variable at the same time?**
Yes. To store multiple values in useState, they would all go in a single object. [Ref](https://pretagteam.com/question/how-to-update-multiple-state-at-once-using-react-hook-reactjs)
1. **Is useState() synchronous?**
Both useState & setState are asyncronous.  [Ref](https://www.linkedin.com/pulse/provide-callback-usestate-hook-like-setstate-saransh-kataria/)
## Vocab

- **State Hook:**
Hook that allows the updating of state in a functional component.
- **Component Lifecycle:**
Three main states in React composed of mounting, updating, and unmounting.

## Additional Resources

- [useReducer Hook](https://reactjs.org/docs/hooks-reference.html#usereducer)
- [Ultimate Guide To useReducer](https://blog.logrocket.com/guide-to-react-usereducer-hook/)