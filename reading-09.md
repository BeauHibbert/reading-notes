# Reading 09
Notes from:
https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa
https://www.youtube.com/watch?v=xHLd36QoS4k
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules
https://www.freecodecamp.org/news/require-module-in-node-js-everything-about-module-require-ccccd3ad383/

## What is functional programming?

“Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — Wikipedia"

## What is a pure function and how do we know if something is a pure function?

It returns the same result if given the same arguments (it is also referred as deterministic)
It does not cause any observable side effects

## What are the benefits of a pure function?

The code is easier to test.
Immutable

## What is immutability?

“When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.”

## What is Referential transparency?

Basically, if a function consistently yields the same result for the same input, it is referentially transparent.
pure functions + immutable data = referential transparency

## What is a module?

A module is a file of JavaScript code. Separate modules of code usually make up and help distinguish different parts of a JavaScript Project.

## What does the word ‘require’ do?

Require is used to import the constructs using the module.exports

## How do we bring another module into the file the we are working in?

Require or import.

## What do we have to do to make a module available?

You have to use require or import to connect the modules to either each other or to the parent file.