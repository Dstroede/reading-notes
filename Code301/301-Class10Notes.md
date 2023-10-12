# Class 10 Notes

## What is a ‘call’?

a call in an ivoking or executing of a function or method

## How many ‘calls’ can happen at once?

One at a time

## What does LIFO mean?

Last In, First Out

## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
 
 push    pop
   v     ^
 ____________
|    top     |
|____________|
|            |
|____________|
|            |
|____________|

function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();

## What causes a Stack Overflow?

Basically its when you don't have an exit point for a function and it continues to run until the maximum call size is exceeded.

## What is a ‘reference error’?

You need to define the declaration using var, const, or let

## What is a ‘syntax error’?

when you are not following the rules (syntax) of the language

## What is a ‘range error’?

if you are using .length on something that does not have length

## What is a ‘type error’?

when the type you are trying to access in incompatible

## What is a breakpoint?

It is a set point where you can ask the code to stop so you can attempt to correct any errors.

## What does the word ‘debugger’ do in your code?

It is in the devolper tools and you can run your code line by line to see where it stops running or creates and unexpected result.

## Things I want to know more about

This was very useful. I would like to dive deeper in the stack and see in real life what stack overflow is. Seems like it is very easy to avoid but I have heard it often so maybe I am incorrect.
