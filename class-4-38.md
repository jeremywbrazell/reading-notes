# Redux - Asyncronous Actions

1. **How granular should your reducers be?**
Depends on the size of the application and what it is used for.
1. **Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched**
Pro since this makes actions more scalable.
1. **Name a strategy for preventing the above**
Use different names for actions.

## Vocab
- **store:** 
an immutable object tree in Redux. A store is a state container which holds the application’s state. Redux can have only a single store in your application. Whenever a store is created in Redux, you need to specify the reducer.
[Ref](https://www.tutorialspoint.com/redux/redux_store.htm#:~:text=A%20store%20is%20an%20immutable,the%20createStore%20method%20from%20Redux.)

- **combined reducers:**
helper function that turns an object whose values are different reducing functions into a single reducing function you can pass to createStore [Ref](https://redux.js.org/api/combinereducers#:~:text=The%20combineReducers%20helper%20function%20turns,into%20a%20single%20state%20object.
)
## Additional Resources
- [Async Actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)
- [Thunk Middleware GH](https://github.com/reduxjs/redux-thunk)
- [Redux Thunk](https://www.digitalocean.com/community/tutorials/redux-redux-thunk)