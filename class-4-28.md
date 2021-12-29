# Component Lifecycle/useEffect()

**1. Why do we not need more .html pages in a multi-page React app?**
Because React JS handles the interactive states that happen in the React DOM.

**2. If we wanted a component to show up on every page, where would we put it and why?**

- Inside the ``<BrowserRouter />``, outside a ``<Route />``
BrowserRouter handles all instances of dynamic routes.

**3. What does routing do with the components that were rendered when a new route is requested?**
It will create a new component on every render.

**4. What does props.children contain?** whatever is included between the opening and closing tags when invoking a component [Ref](https://codeburst.io/a-quick-intro-to-reacts-props-children-cb3d2fce4891)

**5. How do useState() and this.setState() differ?**
setState() merges the previous state w/ the new one & useState() rewrites a previous state with a new one but does not perform any merging.

## Vocab
- **State Hook:** also known as ``useState()``, used to control dynamic states on a page and doesn't require the use of a class [Ref](https://reactjs.org/docs/hooks-state.html)

- **Mounting & Un-Mounting:**
Mounting: initial lifecycle compoment that contains the launching of the app in the browser via the DOM (uses render,  componentWillMount, & componentDidMount)

Un-Mounting: final lifecycle compoment whereby nodes are removed from the DOM

[Ref](https://www.code-sample.com/2019/11/react-lifecycle-components-mounting.html)

## Additional Resources
[Effects Hook Documentation](https://reactjs.org/docs/hooks-effect.html)