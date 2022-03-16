# Notes from Read: 03 Passing Functions as Props
[Home](README.md)

## lists and keys

Keys
- React needs keys to help keep track of the element <br>
- Like to have specific keys, but can just use index <br>
- extract: used to pull based on key <br>
- key must be unique <br>

1. What does .map() return?
Looks through an array and effect each element if needed
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
you can use map to search through them
3. Each list item needs a unique ____.
key
4. What is the purpose of a key?
an id for a specific element

## Spread Operator
- the same as the ... spread <br>
- things it can do <br>
  - Copying an array <br>
  - Concatenating or combining arrays <br>
  - Using Math functions <br>
  - Using an array as arguments <br>
  - Adding an item to a list <br>
  - Adding to state in React <br>
  - Combining objects <br>
  - Converting NodeList to an array  <br>
- https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab Ref for examples of the above <br>

1. What is the spread operator?
It is used to modify arrays
2. List 4 things that the spread operator can do.
see above
3. Give an example of using the spread operator to combine two arrays. ref above.
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
4. Give an example of using the spread operator to add a new item to an array. ref above.
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
5. Give an example of using the spread operator to combine two objects into one. ref above.
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}

## linked video

1. In the video, what is the first step that the developer does to pass functions between components?
make in increment function
2. In your own words, what does the increment function do?
a function that effects an value outside of itself
3. How can you pass a method from a parent component into a child component?
refrence the method inside the child component
4. How does the child component invoke a method that was passed to it from a parent component?
by having a callback function

## Things I want to know more about
- I would like to see how we are going to use ... in more detail.