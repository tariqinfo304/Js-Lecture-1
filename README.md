# Basic JavaScript Course - Lecture One

Welcome to the Basic JavaScript Course! In this first lecture, we will cover fundamental concepts that form the foundation of JavaScript programming. By the end of this lecture, you'll have a solid grasp of the following topics:

## Table of Contents

1. [Variables](#variables)
2. [Functions](#functions)
3. [Conditional Statements](#conditional-statements)
4. [Loops](#loops)
5. [Modules: Import and Export](#modules-import-and-export)

Variables are used to store data values in JavaScript. They are like containers that hold different types of information, such as numbers, strings, and more complex data structures. In JavaScript, you can declare variables using the `var`, `let`, or `const` keywords. Here's an example of variable declaration:

Functions are blocks of code that can be defined and reused to perform specific tasks. They allow you to organize your code and make it more readable. A function can accept input (parameters) and return a value.

Conditional statements allow you to execute different blocks of code based on specific conditions. The if-else statement is one of the most basic forms of conditional statements.

Loops are used to repeat a block of code multiple times. One common type of loop is the for loop. It allows you to iterate over a sequence of values and execute a block of code for each iteration

JavaScript supports modular programming through the use of modules. Modules help you organize your code into separate files, making it easier to manage and maintain. You can use the import and export keywords to work with modules.

```javascript
let name = "hello";
var name1 = "hello test";
const name_cont = "name";

num = 51;

//Diff between let/var/const

console.log(name, name1, num);

// condition
if (num === 10) {
  console.log("==10");
} else {
  console.log("!= 10");
}

switch (num) {
  case 10:
    console.log("==10");
    break;
  case 5:
    console.log("!= 10");
    break;
  default:
    console.log("default run");
}

//loop

for (let i = 0; i < 10; i++) {
  console.log(i);
}

let i = 0;
while (i < 10) {
  console.log(i);
  i++;
}

//array
arr = [1, 2, 3, 4, 5];
i = 0;
while (i < arr.length) {
  console.log(arr[i]);
  i++;
}

arr = [1, 31, 23, 4, 5];
for (let row of arr) {
  console.log("Value:", row);
}

for (let row in arr) {
  console.log("key:", row);
}

//hoistig concept ?
//test();

function hello() {
  console.log("Hello function");
}

function test(n1, n2) {
  return "Hello Test: " + (n1 + n2);
}

//hello();
let result = test(10, 20);
console.log(result);
```
