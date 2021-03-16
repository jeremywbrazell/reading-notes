# States & Props

## States & Lifecycles
- state is similiar to props, but, it is private & fully controlled by the component

- by convertting a function to a class, one can use additional features such as local state and lifecycle methods

- class components should always call the base constructor w/ props

- setting up a timer whenever a Clock is rendered to the DOM for the first time is called "mounting" in React

- clearing the timer whenever the DOM that's produced by the Clock is removed is called "unmounting"

- "lifecycle methods" are special methods on the component class that run code when a component mounts and unmounts
    - ex: ```componentDidMount()```



