# Combined Reducers

1. **Why choose Redux instead of the Context API for global state?**
Redux is better at managing large scope global state
1. **What is the purpose of a reducer?**
to handle state and action as arguments and return them as a new state
1. **What does an action contain?**
a type and a payload
1. **Why do we need to copy the state in a reducer?**
because the initial state is immutable

## Vocab
- **immutable state:**
state that is unchangeable
- **time travel in redux:**
the ability to move back and forth among the application’s previous states and view the results in real time. [Ref](https://developer.ibm.com/tutorials/wa-manage-state-with-redux-p4-david-geary/)
- **action creator:**
dispatches an action to the store
- **reducer:**
is a pure function that takes an action and the previous state of the application and returns the new state [Ref](https://www.pluralsight.com/guides/how-to-write-redux-reducer)
- **dispatch:**
a function of the Redux store. You call store.dispatch to dispatch an action. This is the only way to trigger a state change. [Ref](https://react-redux.js.org/using-react-redux/connect-mapdispatch#:~:text=dispatch%20is%20a%20function%20of,connect%20does%20it%20for%20you.)

## Additional Resources
- [Multiple Reducers](https://www.youtube.com/watch?v=gBER4Or86hE)
- [Redux Docs: Using Combined Reducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)
- [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)
