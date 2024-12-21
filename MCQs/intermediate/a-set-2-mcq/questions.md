Here’s **Set-2** for **Intermediate JavaScript** questions. 
These will continue with the concepts of functions, variable scopes, and related topics but with more complexity.

---

### **JavaScript Intermediate - Set 2**

---

#### **Question 1**  
What will the following code output?  
```javascript
let x = 10;
function test() {
    let x = 20;
    return function inner() {
        console.log(x);
    }
}
let myFunc = test();
myFunc();
```  
1. `10`  
2. `20`  
3. `undefined`  
4. `Error`

---

#### **Question 2**  
Which of the following statements is true about JavaScript's event loop?  
1. The event loop executes all asynchronous code immediately after the main thread.  
2. The event loop handles asynchronous code only after the stack is empty.  
3. The event loop executes synchronous code after the asynchronous code.  
4. The event loop does not handle callbacks from asynchronous code.

---

#### **Question 3**  
What will be the output of the following code?  
```javascript
let a = 5;
let b = a++;
let c = ++a;
console.log(b + c);
```  
1. `11`  
2. `12`  
3. `10`  
4. `15`

---

#### **Question 4**  
Which of the following is true about `const` in JavaScript?  
1. A `const` declaration creates a block-scoped variable that cannot be reassigned.  
2. `const` can be reassigned, but its value cannot be changed.  
3. `const` creates a function-scoped variable.  
4. `const` can be used with functions only.

---

#### **Question 5**  
What is the result of the following code?  
```javascript
const arr = [1, 2, 3];
arr[0] = 10;
arr.push(4);
console.log(arr);
```  
1. `[1, 2, 3, 4]`  
2. `[10, 2, 3, 4]`  
3. `[1, 2, 3, 10]`  
4. `Error`

---

#### **Question 6**  
What is the output of the following code?  
```javascript
function foo() {
    console.log(this);
}
foo();
```  
1. `undefined`  
2. `window` (in browsers)  
3. `foo`  
4. `this`

---

#### **Question 7**  
What will be the output of the following code?  
```javascript
let x = 10;
(function() {
    let x = 20;
    (function() {
        let x = 30;
        console.log(x);
    })();
})();
```  
1. `10`  
2. `20`  
3. `30`  
4. `undefined`

---

#### **Question 8**  
What does the following code do?  
```javascript
function myFunc(a, b = 5) {
    return a + b;
}
console.log(myFunc(2));
```  
1. Returns `2`  
2. Returns `7`  
3. Returns `undefined`  
4. Returns `NaN`

---

#### **Question 9**  
Which of the following is true about `setTimeout()` in JavaScript?  
1. `setTimeout()` executes code synchronously after the specified delay.  
2. `setTimeout()` executes code asynchronously after the specified delay.  
3. `setTimeout()` executes code immediately.  
4. `setTimeout()` does not accept any arguments.

---

#### **Question 10**  
What is the output of the following code?  
```javascript
let a = 2;
let b = 5;
console.log(a + b * 2);
```  
1. `14`  
2. `12`  
3. `10`  
4. `16`

---

#### **Question 11** (Code Completion)  
Complete the code to return the factorial of a number using recursion.  
```javascript
function factorial(n) {
    if (n <= 1) return 1;
    // Add code here
}
```  

---

#### **Question 12**  
What will be the output of the following code?  
```javascript
let x = 5;
function test() {
    let x = 10;
    function inner() {
        let x = 15;
        console.log(x);
    }
    inner();
}
test();
```  
1. `5`  
2. `10`  
3. `15`  
4. `undefined`

---

#### **Question 13**  
Which of the following is NOT a valid way to create an object in JavaScript?  
1. `let obj = {};`  
2. `let obj = new Object();`  
3. `let obj = Object.create();`  
4. `let obj = object();`

---

#### **Question 14**  
What is the output of the following code?  
```javascript
function multiply(a, b = 2) {
    return a * b;
}
console.log(multiply(5));
```  
1. `10`  
2. `7`  
3. `5`  
4. `undefined`

---

#### **Question 15**  
Which of the following statements is true about closures in JavaScript?  
1. A closure is created every time a function is executed.  
2. A closure has access to variables in its outer scope.  
3. A closure can only access global variables.  
4. A closure is not related to lexical scoping.

---

#### **Question 16**  
What is the result of the following code?  
```javascript
let obj = { a: 1, b: 2 };
let newObj = { ...obj, c: 3 };
console.log(newObj);
```  
1. `{ a: 1, b: 2, c: 3 }`  
2. `{ a: 1, b: 2, c: 3, d: undefined }`  
3. `{ a: 1, b: 2 }`  
4. `Error`

---

#### **Question 17**  
What will be the output of the following code?  
```javascript
let arr = [1, 2, 3, 4];
let sum = arr.reduce((acc, val) => acc + val, 0);
console.log(sum);
```  
1. `10`  
2. `24`  
3. `4`  
4. `undefined`

---

#### **Question 18**  
What is the output of the following code?  
```javascript
function add() {
    return arguments[0] + arguments[1];
}
console.log(add(2, 3, 4));
```  
1. `5`  
2. `7`  
3. `undefined`  
4. `NaN`

---

#### **Question 19**  
What will be the result of the following code?  
```javascript
const person = { name: 'John', age: 30 };
const newPerson = person;
newPerson.age = 35;
console.log(person.age);
```  
1. `30`  
2. `35`  
3. `undefined`  
4. `Error`

---

#### **Question 20**  
Which of the following methods is used to find the index of an element in an array?  
1. `find()`  
2. `indexOf()`  
3. `index()`  
4. `getIndex()`

---

#### **Question 21**  
What is the output of the following code?  
```javascript
let x = 10;
let y = '10';
console.log(x === y);
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `NaN`

---

#### **Question 22**  
What is the result of the following code?  
```javascript
const obj = { a: 1, b: 2 };
delete obj.a;
console.log(obj);
```  
1. `{ a: 1, b: 2 }`  
2. `{ b: 2 }`  
3. `undefined`  
4. `Error`

---

#### **Question 23**  
What will the following code output?  
```javascript
let foo = (x) => x * x;
console.log(foo(3));
```  
1. `3`  
2. `6`  
3. `9`  
4. `undefined`

---

#### **Question 24**  
What does the following code do?  
```javascript
let arr = [1, 2, 3];
arr.length = 2;
console.log(arr);
```  
1. `[1, 2, 3]`  
2. `[1, 2]`  
3. `[2, 3]`  
4. `Error`

---

#### **Question 25**  
What will be the result of the following code?  
```javascript
let x = 5;
let y = ++x * 2;
console.log(y);
```  
1. `5`  
2. `10`  
3. `12`  
4. `20`

---

