

---

# JavaScript Basics - MCQ Set 1

This file contains a set of 25 multiple-choice questions designed to test and enhance your knowledge of JavaScript basics.
These questions are suitable for interview preparation and cover foundational concepts, syntax, and common coding scenarios.

#### **Question 1**  
What is the correct syntax to print a message in the console?  
1. `print("Hello World");`  
2. `console.log("Hello World");`  
3. `document.write("Hello World");`  
4. `alert("Hello World");`  

---

#### **Question 2**  
Which of the following are primitive data types in JavaScript?  
1. String  
2. Object  
3. Number  
4. Undefined  

---

#### **Question 3**  
What is the output of the following code?  
```javascript
let x = "5";
let y = 5;
console.log(x == y);
```  
1. `true`  
2. `false`  
3. `NaN`  
4. `undefined`  

---

#### **Question 4**  
What does the `typeof` operator return for `null`?  
1. `object`  
2. `null`  
3. `undefined`  
4. `string`  

---

#### **Question 5**  
Which of the following methods can be used to convert a string to an integer?  
1. `parseInt()`  
2. `parseFloat()`  
3. `Number()`  
4. `String()`  

---

#### **Question 6**  
Which of the following will throw a syntax error?  
1. `let a = 5; let b = 6; let c = a + b;`  
2. `const num = 10; num = 15;`  
3. `var x; console.log(x);`  
4. `if (true) { console.log("Hello"); }`  

---

#### **Question 7**  
What is the output of the following code?  
```javascript
let arr = [1, 2, 3];
arr[5] = 10;
console.log(arr.length);
```  
1. `3`  
2. `6`  
3. `5`  
4. `undefined`  

---

#### **Question 8**  
How do you declare a function in JavaScript?  
1. `function myFunc() { }`  
2. `def myFunc() { }`  
3. `function: myFunc() { }`  
4. `func myFunc() { }`  

---

#### **Question 9**  
Find the error in the code below:  
```javascript
const x;
x = 10;
console.log(x);
```  
1. `const variables must be initialized during declaration.`  
2. `x is not defined.`  
3. `Missing semicolon.`  
4. `console.log is not a function.`  

---

#### **Question 10**  
Which of the following are valid ways to declare variables in JavaScript?  
1. `var`  
2. `let`  
3. `const`  
4. `define`  

---

#### **Question 11**  
What will be logged by the following code?  
```javascript
function test() {
    var a = 10;
    if (true) {
        var a = 20;
    }
    console.log(a);
}
test();
```  
1. `10`  
2. `20`  
3. `undefined`  
4. `Error`  

---

#### **Question 12**  
Complete the missing code:  
```javascript
function addNumbers(a, b) {
    return ______;
}
console.log(addNumbers(2, 3));
```  
1. `a + b`  
2. `a - b`  
3. `b - a`  
4. `a * b`  

---

#### **Question 13**  
What does the `map()` method do in JavaScript?  
1. Filters elements based on a condition.  
2. Transforms each element in an array and returns a new array.  
3. Joins two arrays together.  
4. Finds the index of an element in an array.  

---

#### **Question 14**  
What will be logged by the following code?  
```javascript
let x = 0;
while (x < 3) {
    console.log(x);
    x++;
}
```  
1. `0 1 2`  
2. `1 2 3`  
3. `0 1 2 3`  
4. `Infinite loop`  

---

#### **Question 15**  
What will be the output of the following code?  
```javascript
let obj = { a: 1, b: 2 };
console.log("c" in obj);
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `Error`  

---

#### **Question 16**  
Which of the following are false values in JavaScript?  
1. `null`  
2. `0`  
3. `""`  
4. `NaN`  

---

#### **Question 17**  
What does the `bind()` method do?  
1. Executes a function immediately.  
2. Creates a new function with a specified `this` value.  
3. Binds two objects together.  
4. Stops event propagation.  

---

#### **Question 18**  
Find the missing line to make the function return an array of even numbers:  
```javascript
function filterEven(arr) {
    return arr.filter(______);
}
console.log(filterEven([1, 2, 3, 4]));
```  
1. `x => x % 2 === 0`  
2. `x => x % 2 !== 0`  
3. `x => x > 0`  
4. `x => x < 0`  

---

#### **Question 19**  
What will be logged?  
```javascript
console.log(typeof NaN);
```  
1. `number`  
2. `NaN`  
3. `undefined`  
4. `object`  

---

#### **Question 20**  
What is the purpose of `JSON.stringify()`?  
1. Parse a JSON string into an object.  
2. Convert a JavaScript object into a JSON string.  
3. Copy a JSON object.  
4. Validate a JSON string.  

---

#### **Question 21**  
What will the following code return?  
```javascript
console.log("Hello".charAt(0));
```  
1. `H`  
2. `e`  
3. `o`  
4. `Error`  

---

#### **Question 22**  
What does the `setTimeout` function do in JavaScript?  
1. Pauses script execution for a set amount of time.  
2. Executes a function after a specified delay.  
3. Sets a timeout for event propagation.  
4. Stops the execution of a function.  

---

#### **Question 23**  
What will the following code log?  
```javascript
let arr = [1, 2, 3];
arr.push(4);
console.log(arr);
```  
1. `[1, 2, 3]`  
2. `[4, 1, 2, 3]`  
3. `[1, 2, 3, 4]`  
4. `Error`  

---

#### **Question 24**  
Which of the following methods removes the last element from an array?  
1. `shift()`  
2. `unshift()`  
3. `pop()`  
4. `slice()`  

---

#### **Question 25**  
What will the following code log?  
```javascript
console.log(Boolean("false"));
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `Error`  

---
