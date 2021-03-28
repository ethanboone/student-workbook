# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let or const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a defined set of code to execute or return a value when invoked
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
SOLID is an acronym that sets rules for the way a program should be written. 
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
On the fruit array, the index of pineapple would be two because arrays are considered a zero based index meaning the first index starts at zero.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you[friends].push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
Switch statements, if/if else statements, and ternary's are all examples of conditionals
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
the incrementer, example: i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM refers to the document object model. The HTML document is the first to be loaded in the DOM.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
There are 6 data types: undefined, boolean, number, string, BigInt, symbol. The structural types are objects and functions. The structural root is a primitive value called null.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
The parameter is the placeholder with no value used within a function. The parameter doesn't have a value until the function is invoked and provided an argument, then that argument replaces where the specified parameter is used within the function.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive value is a simple key value pair thats stored in the stack. A reference data type is stored in the heap, and is a keyword that references collection of values.
```