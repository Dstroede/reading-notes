# Class 3 Notes

## What does .map() return?

It creates a new array that itterates a new value for each value in the original array.

## If I want to loop through an array and display each value in JSX, how do I do that in React?

you use a map function but then use curly braces to build elements from that function.

## Each list item needs a unique *identity or key*

to learn which items are changed/updated/or deleted/

## What is the purpose of a key?

it gives elements and identity.

## What is the spread operator?

Its basically using threee dots to call all things in an array, function arguments or objects.

## List 4 things that the spread operator can do

Apply new operators, copying arrays, concatonating arrays, merging objects

## Give an example of using the spread operator to combine two arrays

const parts = ["shoulders", "knees"];
const lyrics = ["head", ...parts, "and", "toes"];
//  ["head", "shoulders", "knees", "and", "toes"]

## Give an example of using the spread operator to add a new item to an array

let arr1 = [0, 1, 2];
const arr2 = [3, 4, 5];

arr1 = [...arr1, ...arr2];

## Give an example of using the spread operator to combine two objects into one

const obj1 = { foo: "bar", x: 42 };
const obj2 = { foo: "baz", y: 13 };

const clonedObj = { ...obj1 };
// { foo: "bar", x: 42 }

const mergedObj = { ...obj1, ...obj2 };
// { foo: "baz", x: 42, y: 13 }

## In the video, what is the first step that the developer does to pass functions between components?

He creates a new function that updates the state

## In your own words, what does the increment function do?

loops through the people array that addes to the count, then that to update the state.

## How can you pass a method from a parent component into a child component?

he passes the component object into the child.

## How does the child component invoke a method that was passed to it from a parent component?

By updating state?

