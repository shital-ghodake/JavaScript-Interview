
Here’s **Set-1** for **Intermediate JavaScript** based on those topics:

This set covers **let**, **const**, **var**, **functions**, **arrow functions**, and variable scoping in **intermediate** scenarios.

---

### **JavaScript Intermediate - Set 1**

---

#### **Question 1**  
Which of the following statements is true about the `let`, `const`, and `var` keywords in JavaScript?  
1. `let` and `const` are block-scoped, whereas `var` is function-scoped.  
2. `let` and `const` are function-scoped, whereas `var` is block-scoped.  
3. `var` is block-scoped, but `let` and `const` are globally scoped.  
4. `let` and `const` are not allowed to be used within functions.

---

#### **Question 2**  
What will be the output of the following code?  
```javascript
function test() {
    if (true) {
        var x = 10;
    }
    console.log(x);
}
test();
```  
1. `10`  
2. `undefined`  
3. `Error`  
4. `null`

---

#### **Question 3**  
What is the value of `y` after the following code is executed?  
```javascript
let x = 5;
const y = x++;
console.log(y);
```  
1. `5`  
2. `6`  
3. `undefined`  
4. `null`

---

#### **Question 4**  
What will be the output of the following code?  
```javascript
function greet() {
    console.log(name);
    var name = 'Alice';
}
greet();
```  
1. `Alice`  
2. `undefined`  
3. `Error`  
4. `null`

---

#### **Question 5**  
Which of the following statements is true about arrow functions in JavaScript?  
1. Arrow functions do not have their own `this` value and inherit `this` from the surrounding context.  
2. Arrow functions always bind `this` to the function itself.  
3. Arrow functions can be used as constructors.  
4. Arrow functions cannot have a return statement.

---

#### **Question 6**  
What is the output of the following code?  
```javascript
let x = 1;
function foo() {
    let x = 2;
    return function bar() {
        console.log(x);
    }
}
let myFunc = foo();
myFunc();
```  
1. `1`  
2. `2`  
3. `undefined`  
4. `Error`

---

#### **Question 7**  
What is the correct way to define a function that accepts a variable number of arguments in JavaScript?  
1. `function myFunc(...args) {}`  
2. `function myFunc(args...) {}`  
3. `function myFunc(args) {}`  
4. `function myFunc(variadic) {}`

---

#### **Question 8**  
Which of the following is true about `const` variables in JavaScript?  
1. `const` variables must be initialized at the time of declaration.  
2. `const` variables can be reassigned.  
3. `const` variables are not block-scoped.  
4. `const` variables can be changed, but not re-declared.

---

#### **Question 9**  
What is the output of the following code?  
```javascript
function sum(a, b = 2) {
    return a + b;
}
console.log(sum(5));
```  
1. `5`  
2. `7`  
3. `undefined`  
4. `NaN`

---

#### **Question 10**  
What will be the result of the following code?  
```javascript
let x = 10;
let y = x++;
console.log(y);
```  
1. `10`  
2. `11`  
3. `undefined`  
4. `Error`

---

#### **Question 11** (Code Completion)  
Complete the function to return the sum of all arguments passed to it, using the rest parameter syntax.  
```javascript
function calculateSum(...args) {
    let total = 0;
    // Add code here to sum all arguments
    return total;
}
```  

---

#### **Question 12**  
What is the output of the following code?  
```javascript
let a = 5;
let b = '5';
console.log(a === b);
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `Error`

---

#### **Question 13**  
What is the output of the following code?  
```javascript
let x = 5;
let y = '5';
console.log(x == y);
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `Error`

---

#### **Question 14**  
Which of the following are valid ways to declare a function in JavaScript?  
1. `function myFunc() {}`  
2. `const myFunc = function() {}`  
3. `const myFunc = () => {}`  
4. All of the above

---

#### **Question 15**  
What is the scope of a variable declared with `let`?  
1. Global scope  
2. Function scope  
3. Block scope  
4. None of the above

---

#### **Question 16**  
What is the output of the following code?  
```javascript
let a = 10;
if (true) {
    let a = 20;
    console.log(a);
}
console.log(a);
```  
1. `20 10`  
2. `10 20`  
3. `10 10`  
4. `Error`

---

#### **Question 17**  
Which of the following options can be used to ensure that a function is invoked only once in JavaScript?  
1. `setTimeout()`  
2. `setInterval()`  
3. `bind()`  
4. `once()`

---

#### **Question 18**  
What will be the output of the following code?  
```javascript
let myVar;
console.log(typeof myVar);
```  
1. `undefined`  
2. `object`  
3. `string`  
4. `Error`

---

#### **Question 19**  
What will be the output of the following code?  
```javascript
let x = 10;
function test() {
    x = 20;
    console.log(x);
}
test();
console.log(x);
```  
1. `10 10`  
2. `20 10`  
3. `20 20`  
4. `20 undefined`

---

#### **Question 20**  
What will the following code output?  
```javascript
const multiply = (a, b) => a * b;
console.log(multiply(2, 3));
```  
1. `2`  
2. `6`  
3. `3`  
4. `undefined`

---

#### **Question 21**  
Which of the following statements is true about JavaScript functions?  
1. Functions in JavaScript are first-class objects.  
2. Functions in JavaScript cannot be assigned to variables.  
3. Functions in JavaScript cannot be passed as arguments to other functions.  
4. Functions in JavaScript are not objects.

---

#### **Question 22**  
What will be the output of the following code?  
```javascript
function add(a, b) {
    return a + b;
}
const addNum = add.bind(null, 5);
console.log(addNum(10));
```  
1. `15`  
2. `5`  
3. `NaN`  
4. `Error`

---

#### **Question 23**  
What is the result of the following code?  
```javascript
const numbers = [1, 2, 3, 4];
numbers[2] = 100;
console.log(numbers);
```  
1. `[1, 2, 100, 4]`  
2. `[1, 2, 3, 4]`  
3. `[1, 2, 3, 100]`  
4. `[100, 2, 3, 4]`

---

#### **Question 24**  
What will be the output of the following code?  
```javascript
let x = 5;
function myFunc() {
    x = 10;
    console.log(x);
}
myFunc();
console.log(x);
```  
1. `5 5`  
2. `10 5`  
3. `10 10`  
4. `Error`

---

#### **Question 25**  
What will be the output of the following code?  
```javascript
function test() {
    if (true) {
        let x = 5;
    }
    console.log(x);
}
test();
```  
1. `5`  
2. `undefined`  
3. `Error`  
4. `null`

---


