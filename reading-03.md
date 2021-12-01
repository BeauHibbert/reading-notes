# Reading 03
Notes from:
https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab
https://reactjs.org/docs/lists-and-keys.html


## What does .map() return?
An array of modified items.

## If I want to loop through an array and display each value in JSX, how do I do that in React?
You would use the JS map() function which returns a <li> element for each item and then assign the resulting array of elements to listItems 

## Each list item needs a unique ____.
key

## What is the purpose of a key?
“Keys help React identify which items have changed, are added, or are removed.”


## What is the spread operator?
The spread operator is a useful syntax for quickly manipulating arrays

## List 4 things that the spread operator can do
Copying an array
Concatenating arrays
Using math functions
Using an array as arguments

## Give an example of using the spread operator to combine two arrays
const myArray = [‘dog’, ‘cat’, ‘snake’,]
const yourArray = [‘tiger’, ‘bear’, ‘monkey’]
const ourArray = […myArray…yourArray]
console.log(…ourArray) //dog cat snake tiger bear monkey

## Give an example of using the spread operator to add a new item to an array.
const nfcWestTeams = [‘seahawks’, ‘rams’, ‘cardinals’]
const anotherTeam = [‘niners’…nfcWestTeams]
console.log(anotherTeam) // seahawks rams cardinals niners


## Give an example of using the spread operator to combine two objects into one. Example from https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂