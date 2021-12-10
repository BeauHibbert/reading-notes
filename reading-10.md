# Reading 10
Notes from:
https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c
https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/

## What is a ‘call’?

“At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).”

## How many ‘calls’ can happen at once?

Only one can happen at a time.

## What does LIFO mean?

Last in first out.

## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

[Call Stack](callstack.png)

## What causes a Stack Overflow?

“A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accommodate before throwing a stack error.”

## What is a ‘refrence error’?

“This is as simple as when you try to use a variable that is not yet declared you get this type os errors.” “Whatever you are using (var, let or const) the fix is as simple has declaring the variable before any declaration is made.”

## What is a ‘syntax error’?

“I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.”

## What is a ‘range error’?

“Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.”

## What is a ‘type error’?

“Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.”

## What is a breakpoint?

It is a point in the code where the code will stop executing.

## What does the word ‘debugger’ do in your code?

It is a way to search for bugs in your code.
