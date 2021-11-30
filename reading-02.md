# Reading Assignment 02
-Notes from https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093
https://blog.logrocket.com/react-lifecycle-methods-tutorial-examples/
react.js.org
Quote specifically from first link.
https://www.youtube.com/watch?v=IYvD9oBCuJI

## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Render happens first.

## What is the very first thing to happen in the lifecycle of React?

The mounting phase is the first thing to happen in the life cycle of react. It goes mounting(adding nodes to the DOM), updating(altering existing nodes in the DOM), unmounting(removing nodes from the DOM), error handling(verifying that your code works and is error free).

## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

Constructor, React updates, render, componentDidMount, componentWillUnmount

## What does componentDidMount do?

This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here.




## What types of things can you pass in the props?

Props allow values of any data type to be passed down from a parent to a child component.

## What is the big difference between props and state?

Props are passed into a component and state is handled inside of a component. State is used for when the application needs to be updated or changed due to user input and props are useful for displaying information inside of a component without hardcoding it

## When do we re-render our application?

The application automatically rerenders whenever there is a change in the state or props.

## What are some examples of things that we could store in state?

Booleans, objects, arrays are just a couple examples.