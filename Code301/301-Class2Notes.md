# Class 2 Notes

## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

render happens before as it is apart of the render phase and then moves to the pre -commit phase, lastly ut moves to the commit phase where it runs componentDidMount.

## What is the very first thing to happen in the lifecycle of React?

calling of the constructor.

## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

Constructor, render, React Updates, componentDidMount, componentWillUnMount

## What does componentDidMount do?

It loads requests and intitializes the DOM

## What types of things can you pass in the props?

When you are passing things from a parent to a child component.

## What is the big difference between props and state?

When you are  handling info inside the component only you use state. When you are andling info outside the component like a partent component then you use props.

## When do we re-render our application?

When we are using state

## What are some examples of things that we could store in state?

Things like counters where its going to be continue to be updating it based off the user has done.
