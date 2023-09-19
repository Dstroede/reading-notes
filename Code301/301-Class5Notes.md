# Class 5 Notes

## What is the single responsibility principle and how does it apply to components?

Basically a component should only do one thing.

## What does it mean to build a ‘static’ version of your application?

Its almost like building the app strictly using html where its not interactive. You should not be using things like state.

## Once you have a static application, what do you need to add?

Start building the reusable components of the data model.

## What are the three questions you can ask to determine if something is state?

Does it remain unchanged over time?
Is it passed in front of a parent via props?
Can you compute it based on existing state or props in your component?

## How can you identify where state needs to live?

1. Frequently, you can place the state directly within their shared parent.

2. Alternatively, you can position the state within a component higher up in the hierarchy than their common parent.

3. When you can't identify a suitable component for housing the state, establish a new component exclusively for that purpose. Then, incorporate it into the hierarchy above the common parent component.

## What is a “higher-order function”?

A functions that operates on other functions.

## Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

It is basically just a function that compares if m is greater than n. In the following lines you n is given the value of 10. So when we console.log the number 11 it returns it as true because it is in fact greater than 10.

## Explain how either map or reduce operates, with regards to higher-order functions.

For map you may be writing a function that creates arrays and then then use a map functions to iterate through each elem4ent over the array and possibly to even create a new array from that.
