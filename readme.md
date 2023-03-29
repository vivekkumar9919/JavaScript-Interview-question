primitive and non primitive
shift and unshift
slice and splice
rest and spread
let,var and constant
null and undefined
undeclared and undefined
internal and external javascript
parameter and argument
deep copy and shalow copy
== and ===
call apply and bind
local storage , session storage and cookies
What is the difference between parameter and argument in JavaScript?



#  Brush up your Javascript knowledge for your 2023 interview with this list of 50+ frequently asked questions


## Table of Contents
<div id="top"></div>

- [1. What is Javascript ?](#q1)
- [2. What is Key Features of Javascript ?](#q2)
- [3. What are the data types in JavaScript? ?](#q3)
- [4. What is the difference between null and undefined in JavaScript ?](#q4)
- [5. What is NaN in JavaScript? ?](#q5)
- [6. What is the difference between Primitive and Non-primitive data types in JavaScript ?](#q6)
- [7. What is the difference between == and === in JavaScript ?](#q7)
- [8. What is the difference between synchronous and asynchronous code in JavaScript ?](#q8)
- [9. What is the difference between let ,var and const in JavaScript? ](#q9)
- [10. What is the difference between null and undefined in JavaScript? ](#q10)
- [11. What is first class function? ](#q11)
- [12. what is higher order function? ](#q12)
- [13. What is first order function? ](#q13)
- [14. What is the difference between parameter and argument in JavaScript? ](#q14)
- [15. What is Callback? ](#q15)
- [16. Why we need a callback in javascript? ](#q16)
- [17.  ](#q17)
- [18.  ](#q18)
- [19.  ](#q19)
- [20.  ](#q20)




<div id="q1"></div>

## 1. What is Javascript ? [&uarr; Top](#top)
JavaScript is a high-level, <b>interpreted programming</b>  language that is widely used for building dynamic web pages and applications. It was created in 1995 by <b>Brendan Eich</b>, then an employee of Netscape Communications Corporation, and it has since become one of the most popular programming languages in the world.

JavaScript is often used in conjunction with HTML and CSS to create interactive web pages and web applications. It runs on the client-side of the web, meaning it executes in the user's browser, as well as on the server-side using platforms such as Node.js.

JavaScript is a versatile language that supports multiple programming paradigms, including object-oriented, functional, and procedural programming. It also has a vast ecosystem of libraries and frameworks, such as React, Vue, Angular, and jQuery, which make it easier to develop complex web applications

<div id="q2"></div>

## 2. What is Key Features of Javascript ? [&uarr; Top](#top)
- **Dynamic Typing:** JavaScript is a dynamically-typed language, which means that variable types are determined at runtime rather than being declared explicitly in the code.

- **First-class Functions:** Functions in JavaScript are treated as first-class citizens, which means they can be passed around as arguments to other functions, returned as values from functions, and stored in variables.

- **Closures:** Closures are a powerful feature of JavaScript that allow functions to access variables from an outer function that has already returned. This makes it possible to create private variables and methods within a function.

- **Prototypal Inheritance:** JavaScript uses prototypal inheritance, which allows objects to inherit properties and methods from their parent objects. This makes it possible to create complex object hierarchies and reuse code in a more efficient way.

- **Event-driven programming:** JavaScript is often used for event-driven programming, where code is executed in response to events such as user input, page loads, or timer events.

- **Asynchronous Programming:** JavaScript has built-in support for asynchronous programming, which means that code can execute in a non-blocking way. This is particularly useful for tasks such as fetching data from a server or performing complex calculations that might otherwise freeze the user interface.

- **DOM Manipulation:** JavaScript is widely used for manipulating the Document Object Model (DOM) in web pages, which allows developers to create dynamic and interactive user interfaces.

<div id="q3"></div>

## 3. What are the data types in JavaScript ? [&uarr; Top](#top)
JavaScript supports several data types, including numbers, strings, booleans, null, undefined, objects, and symbols.

<div id="q4"></div>

## 4. What is the difference between null and undefined in JavaScript ? [&uarr; Top](#top)
null represents the intentional absence of any object value, while undefined represents the absence of a defined value.

<div id="q5"></div>

## 5. What is NaN in JavaScript? [&uarr; Top](#top)
NaN stands for "Not a Number," and it is a value that is returned when a mathematical operation that cannot be performed is attempted.

<div id="q6"></div>

## 6. What is the difference between Primitive and Non-primitive data types in JavaScript? [&uarr; Top](#top)
The main difference between primitive and non-primitive data types in JavaScript is that primitive data types store a single value like let, string, boolean, undefined and null while non-primitive data types can store multiple values and methods like object, date, RegExp and function. Additionally, primitive data types are immutable, while non-primitive data types are mutable

<div id="q7"></div>

## 7. What is the difference between == and === in JavaScript? [&uarr; Top](#top)
The double equals (==) operator checks for equality after converting both values to a common type. The triple equals (===) operator checks for equality without performing any type conversions.

<div id="q8"></div>

## 8. What is the difference between synchronous and asynchronous code in JavaScript?  [&uarr; Top](#top)
Synchronous code is executed in a sequential manner, where each line of code must finish executing before the next line is executed. Asynchronous code, on the other hand, allows multiple things to happen at the same time.

<div id="q9"></div>

## 9. What is the difference between let ,var and const in JavaScript?[&uarr; Top](#top)
**var**: The 'var' keyword was the only way to declare a variable prior to the release of ES6 (ECMAScript 2015). It declares a variable globally or locally to an entire function regardless of block scope. However, 'var' does not support block-scoping, which means that a variable declared with 'var' inside a block will be visible outside that block. Also, a variable declared with 'var' can be re-declared and updated.

**let:** The 'let' keyword is used to declare block-scoped variables. A variable declared with 'let' is only accessible within the block scope it was declared in, including any nested blocks. Also, 'let' variables can be updated but not re-declared.

**const:** The 'const' keyword is used to declare variables that cannot be reassigned a new value. Variables declared with 'const' are also block-scoped.

<div id="q10"></div>

## 10. What is the difference between null and undefined in JavaScript?[&uarr; Top](#top)
**undefined** is a primitive data type that is automatically assigned to a variable that has been declared but not yet assigned a value. It is also the default return value of a function that does not return a value. For example:
```
let x;
console.log(x); // Output: undefined

function foo() {}
console.log(foo()); // Output: undefined

```
On the other hand, **null** is a value that represents the intentional absence of any object value. It is often used to indicate that a variable has no value, or that a function should return no value. For example:
```
let y = null;
console.log(y); // Output: null

function bar() {
  return null;
}
console.log(bar()); // Output: null

```

<div id="q11"></div>

## 11. What is first class function?[&uarr; Top](#top)
In JavaScript, functions are considered first-class citizens, which means that they can be treated like any other value. This includes being assigned to variables, passed as arguments to other functions, and returned as values from functions. A function that can be assigned to a variable, passed as an argument, or returned from a function is called a first-class function.

Here is an example of a first-class function in JavaScript:
```
function add(a, b) {
  return a + b;
}

const result = add(2, 3); // result is 5

const sum = add; // assigning the function to a variable

const newResult = sum(4, 5); // newResult is 9

```


<div id="q12"></div>

## 12. What is higher order function? [&uarr; Top](#top)
In JavaScript, a higher-order function is a function that takes one or more functions as arguments, and/or returns a function as its result. Higher-order functions are a powerful feature of the language, as they enable functional programming paradigms and allow for code that is more modular, reusable, and expressive.

Here is an example of a higher-order function in JavaScript:
```
function multiplyBy(factor) {
  return function(number) {
    return number * factor;
  }
}

const double = multiplyBy(2);
const triple = multiplyBy(3);

console.log(double(5)); // 10
console.log(triple(5)); // 15

```

<div id="q13"></div>

## 13. What is first order function? [&uarr; Top](#top)
In JavaScript, a first-order function is a function that doesn't take any functions as arguments and doesn't return a function as its result. In other words, a first-order function is a simple function that takes only primitive data types (like strings, numbers, and booleans) as arguments and returns a value of a primitive data type.

Here's an example of a first-order function in JavaScript:
```
function addNumbers(a, b) {
  return a + b;
}

```

<div id="q14"></div>

## 14. What is the difference between parameter and argument in JavaScript?
A **parameter** is a named variable in a function definition that receives a value when the function is called. Parameters are used to define the inputs that a function expects to receive. For example, in the following function definition, "x" and "y" are parameters:
```
function add(x, y) {
  return x + y;
}

```
An **argument** is a value that is passed to a function when it is called. Arguments are used to supply the inputs that a function expects to receive. For example, in the following function call, "2" and "3" are arguments:
```
add(2, 3);

```

<div id="q15"></div>

## 15. What is Callback?[&uarr; Top](#top)
A callback is a function that is passed as an argument to another function and is executed when that function has completed its operation.

Callbacks are commonly used in asynchronous programming, where a function does not block the execution of the program but instead returns immediately, allowing other code to be executed while it waits for a response. When the response is received, the callback function is called to handle the data

<div id="q16"></div>

## 16.Why we need a callback in javascript? [&uarr; Top](#top)
Callbacks are a fundamental concept in JavaScript, and they are used extensively in asynchronous programming. Here are a few reasons why callbacks are important in JavaScript:

**Handling Asynchronous Operations:** JavaScript is often used for programming applications that rely on asynchronous operations, such as network communication, file input/output, and user interface events. Using callbacks allows us to write code that can execute non-blocking operations and still be notified when those operations complete.

**Passing Functions as Arguments:** JavaScript allows functions to be passed as arguments to other functions, which means that we can create more flexible and reusable code by passing different functions as callbacks depending on the situation.

**Event Handling:** JavaScript can be used to handle user interface events, such as button clicks, mouse movements, and keyboard input. Callbacks are often used to handle these events, allowing the application to respond to user input in real-time.

**Control Flow:** Callbacks can be used to control the flow of execution in a program, allowing us to create complex sequences of operations that execute in a specific order.

<div id="q17"></div>
<div id="q18"></div>
<div id="q19"></div>
<div id="q1"></div>
