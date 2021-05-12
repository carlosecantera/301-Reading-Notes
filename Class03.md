# React Docs
- What does `.map()` return? `.map() renders a list of data.
- If I want to lopp through an array and display each value in JSX, how do I do that in React?  You would use the `map()`while creating an array of objects. 
- Each list item needs a unique **_Key_** .
- What is the purpose of a key? A key is a string attribite you need in order to create a list of elements.  It helps React identify what items have changed, added , or removed. 

# Spread Operator

- What is the spread operator? The spread operator is a syntax usedfor adding objects to arrays, combing arrays or objects, and spreadin an array out into a function's arguement.
- List 4 things that the spread operator can do. It can copy an array, concatenate or combine arrays, add items to lists, and using math functions.
- Give an example of using the spread operator to combine two arrays.

``[...["1, 2, 3"]]
[...4, 5, 6]``
``const firstNum = { "1, 2, 3"}
const secNum = {"4, 5, 6"}
const twoSets = {...firstNum,...secNum}``

- Give an example of using the spread operator to add a new item to an array.

`` const oneArray = {'1', '2', '3'}
  const twoArray = { '4', '5', '6'}``
  ```const totalArray = ````[...oneArray,...twoArray]````

- Give an example of using the spread operator to combine two objects into one.

` const objOne = {"thing1"}
 const objTwo = { "thing2"}
 const objThree = { ...objOne, ...objTwo, laugh: "laugh"}
 const objFour ={...objOne, ...objTwo, laugh: `()` => ...}'

# How to pass functions between components

- In the video, what is the first step that the developer does to pass fucntions between components?
He uses the arraymap method  by creating a function where the state he is going to change he then passes an object through it.  
- In your own words, what does the `increment` function do?
Increment function refreshes the page with a number going up in value or updating the count.
- How can you pass a method from a parent component into a child component? You pass the parent as a prop to the child componenet
- How does the child component invoke a method that was passed to it from a parent component?
this.props..