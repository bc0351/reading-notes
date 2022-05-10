# React Lifecycle

1. render happens first in the react lifecycle.

2. During the mounting phase, the first of three, cosntructors are used to build and define classes and functions.

3. In order:

- constructor
- render
- React updates
- componentDidMount
- componentWillUnmount

4. componentDidMount: invoked immediately after component is mounted. Used to load anything using network request or initialize the DOM. Sets up subscriptions.

# React State Vs. Props

1. Data is passed in props.

2. Props can be changed outside a component, by the parent, and the flow is uni-directional. States are changed inside a component and are only accessed inside.

3. We re-render an application when the state changes.

4. We can store counter variables in State.
