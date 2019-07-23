# Full JavaScript Course - freeCodeCamp

1. Introducing compiler
2. Print out: `console.log("Hello world!");`
3. Comment your javascript code: lines of code that javascript will intensionally ignore. These are usually used for notes about what the code does

   - in-line comment:

```javascript
var number = 5; // in-line comment
```

    - multi-line comment:

```javascript
/*
This
is
multi-line comment
*/
```

4. Data types

- undefined: something that hasn't been defined
- null: null is nothing
- boolean: true or false
- string: series of characters
- number: number
- object: can store a lot of different key-value pairs

5. Variables
   Set data into a variable. Variables allow computers to store and manipulate data in dynamic fashion. It's basically a label to point to the data variable.

```javascript
var myName = "Mijeong"; // you don't need to specify data type in javascript
console.log(myName);
myName = "David"; // manipulate data
console.log(myName);

// There are two more ways to declare a variable in javascript
// let: this will only be used within the scope of where you declare that
// const: this is for a variable that should never change.
// var: It can be used throughout your whole program
let number = 5;
const pi = 3.14;
```
