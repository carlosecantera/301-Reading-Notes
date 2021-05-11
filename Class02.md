# React Life Cycle Events

## What are componenet life cycle events?

- Lifecycles are the methods that you use on the classes and functions in react.

- In the diagram the render happened before the componentDidMount.  The order is Constructor>getDerivedStateFromProps>render>React updates DOM and refs>componentDidMount.  This is all done in the Render, Pre-commit,and Commit Phases.

-The first thing that happens in the lifecycle of react is Mounting.  Mounting is when an instance of a compoenent is made and put into the DOM.

-Next in the lifecyle of react is Updating. Updating is where a component is updated and is then rerendered.  It happens in this order.

**static getDerivedStateFromProps, should componentUpdate,getSnapshotBeforeUpdate,componentDidUpdate,UNSAFE_componentWillUpdate,UNSAFE_componentWillReceiveProps**

-Last step is Unmounting, this is where the component is removed from the DOM.

### In order:

1. `Constructor`
2. `Render`
3. `React Updates`
4. `componentDidMount`
5. `componentWillUnmount`

#### componentDidMount:

This is a method that runs after a component is mounted.


#### What types of things can you pass in the props?

You can arguments to a function.

#### What's the big difference between props and state?

Props you pass into a component and state you is handled inside a component.

#### When do we re-render our application?

When the state is changed inside the application it will re-render the application.

#### What are some examples of things that we could store in state?

A counter count can be stored in state, inside a form where things are updated by a user.