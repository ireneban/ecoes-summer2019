# Full JavaScript Course - freeCodeCamp

## Introducing compiler

## Print out

```js
console.log("Hello world!");
```

## Comment your javascript code

lines of code that javascript will intensionally ignore. These are usually used for notes about what the code does.

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

## Data types

- undefined: something that hasn't been defined
- null: null is nothing
- boolean: true or false
- string: series of characters
- number: number
- object: can store a lot of different key-value pairs

## Variables

- Set data into a variable. Variables allow computers to store and manipulate data in dynamic fashion. It's basically a label to point to the data variable.

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

- If you want to check data type of a variable, you can use `typeof()`

```js
var a = 1;
console.log(typeof a); // number
var b = 0.001;
console.log(typeof b); // number
var c = "Alex";
console.log(typeof c); // string
```

- Variable names are case-sensitive.

```javascript
// all of them are different
var number = 0;
var nuMber = 1;
var numBer = 2;
```

## Operations

1. Addition

```javascript
var sum = 10 + 10;
console.log(sum);

var number1 = 10;
var number2 = 10;
var sum = number1 + number2;
console.log(sum);
```

2. Subtraction

```js
var differennce = 45 - 33;
```

3. Multiplication

```js
var number1 = 10;
var number2 = 10;
var product = number1 * number2;
console.log(product);
```

4. Division

```js
var number1 = 66;
var number2 = 33;
var quotient = number1 / number2;
console.log(quotient);
```

5. Remainder

```js
var remainder;
remainder = 11 % 3;
console.log(remainder); // 2

// It is often used when you need to check if a number is odd or even
var a = 10 % 2; // 0 --> even number
var b = 11 % 2; // 1 --> odd number
```

5. Incrementing/decrementing a number

```js
var myNumber = 1;
myNumber++; // same as myNumber = myNumber + 1;
console.log(myNumber);

myNum--; // same as myNumber = myNumber - 1;
console.log(myNumber);
```

5. Assignment operators

```js
// Addition
var a = 1;
a += 5; // same as a = a + 5
console.log(a); // 6

// Subtract
.
.
.
```

## Strings

```js
var name = "Mijeong";
var str = "My name is " + name + ", how are you?";
console.log(str);
```

## Data Structures

A data structure is a particular way of organizing data in a computer so that it can be used effectively

- Array
- Linked List
- Stack
- Queue
- Binary Tree
- Binary Search Tree
- Heap
- Hashing
- Graph
- Matrix...etc

We will look at one of them, Array

## Array

Arrays allow you to store several pieces of data in one place.

```js
var arr1 = [1, 2, 3];
var arr2 = ["John", 23]; // elements can be any data type
```

1. Access/ Modify array data with Indexes

- **Index starts with 0**

```js
var myArray = ["a", "b", "c", "d"];

/* Access to the first data in array */
var myData = myArray[0];
console.log(myData);

/* Modify the first element of the array */
myArray[0] = "f";
console.log(myArray);
```

2. Array Operations - `pop()`

- The `pop()` method removes the last element from an array

```js
var students = ["John", "David", "Irene", "Alex"];
/* pop the last element out of an array */
var removed = students.pop();
console.log(students);
console.log(removed); // Alex: pop() method returns the value that was popped out
```

3. Array Operations - `push()`

- The `push()` method adds a new element to an array at the end

```js
var students = ["John", "David", "Irene", "Alex"];
/* push a new element into an array */
var added = students.push("Steve");
console.log(students);
console.log(added); // 5: push() method returns the new array length
```

4. Array Operations - `shift()`

- The `shift()` method removes the first array element and shfts all other elements to a lower index.

```js
var students = ["John", "David", "Irene", "Alex"];
/* Removes the first element */
var removed = students.shift();
console.log(students);
console.log(removed); // John: shift() method returns the element that was shifted out
```

5. Array Operations - `unshift()`

- The `unshift()` method adds a new elemennt to an array at the beginning, and unshifts older elements

```js
var students = ["John", "David", "Irene", "Alex"];
/* Adds a new element "Steven" */
var added = students.unshift("Steve");
console.log(students);
console.log(added); // 5: unshift() method returns the new array length
```

## Function: Write Reusable Code

Functions allow us to create reusable code. Instead of writing the same code repeatably, we can write a function to perform a particular task and use it whenever we want.

- Syntax

```js
function name(parameter1, parameter2, ...) {
    // code to be executed
}
```

- Example

```js
/* Declare a function */
function sayHi() {
  console.log("Hi there!");
}

/* Call a function */
sayHi();
sayHi();
sayHi();
```

- Passing values to functions with arguments

```js
function addition(num1, num2) {
  return num1 + num2;
}

var sum = addition(4, 3);
console.log(sum); // 7
```

- Add exercises for function here!!
