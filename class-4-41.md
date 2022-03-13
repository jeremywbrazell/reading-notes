# React Native

1. **Compare and Contrast Redux Toolkit with Redux “Ducks”**
Redux Toolkit architecture is usually spread throughout several files where Ducks consolidates reducers, action types, and actions all into the same file. [Ref](https://medium.com/swlh/the-good-the-bad-of-react-redux-and-why-ducks-might-be-the-solution-1567d5bdc698)

1. **What is the principle advantage of Redux Toolkit?**
Redux Toolkit makes it easier to write good Redux applications and speeds up development, by baking in our recommended best practices, providing good default behaviors, catching mistakes, and allowing you to write simpler code. Redux Toolkit is beneficial to all Redux users regardless of skill level or experience. [Ref](https://redux.js.org/redux-toolkit/overview#:~:text=Redux%20Toolkit%20makes%20it%20easier,of%20skill%20level%20or%20experience.)

## Vocab
- **Redux Toolkit Slices:**
createSlice is a higher order function that accepts an initial state, an object full of reducer functions and a slice name. It automatically generates action creators and action types that correspond to the reducers and state.
In Redux-Toolkit, the createSlice method helps us create a slice of the redux-store. This function aims to reduce the boilerplate required to add data to redux in the canonical way. Internally, it uses createAction and createReducer. [Ref](https://medium.com/geekculture/understanding-createslice-in-redux-toolkit-reactjs-eca8d20f45d7)
- **Namespace:**
In computing, a namespace is a set of signs (names) that are used to identify and refer to objects of various kinds. A namespace ensures that all of a given set of objects have unique names so that they can be easily identified. [Ref](https://en.wikipedia.org/wiki/Namespace)

## Additional Resources:

- [Getting Started With React Native](https://reactnative.dev/docs/getting-started)
- [React Native Basics -- Tutorial](https://reactnative.dev/docs/tutorial)
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [Expo Snack](https://snack.expo.dev/)
- [Ejecting](https://docs.expo.dev/expokit/eject/?redirected)