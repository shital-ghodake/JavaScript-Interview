### **JavaScript Basics - MCQ Set 2**

Below is the next set of 25 questions for your `basic-set 2`. 
This set contains a mix of multiple-choice, multiple answers, code error identification, and code completion questions.  

---

### **Questions**

#### **Question 1**  
Which of the following are valid JavaScript loops?  
1. `for`  
2. `while`  
3. `do-while`  
4. `foreach`

---

#### **Question 2**  
What will be the output of the following code?  
```javascript
console.log(1 + "2" + "3");
```  
1. `123`  
2. `6`  
3. `"123"`  
4. `NaN`  

---

#### **Question 3**  
What does the following code return?  
```javascript
Boolean([]);
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `TypeError`  

---

#### **Question 4**  
What is the difference between `==` and `===` in JavaScript?  
1. `==` checks for both value and type equality.  
2. `===` checks for both value and type equality.  
3. `==` performs type coercion, `===` does not.  
4. `==` and `===` are interchangeable.  

---

#### **Question 5**  
What is the purpose of the `break` statement in JavaScript?  
1. Stops a loop.  
2. Exits a function.  
3. Skips an iteration of a loop.  
4. Stops executing a `switch` case.  

---

#### **Question 6** (Code Completion)  
Complete the function to find the maximum number in an array:  
```javascript
function findMax(arr) {
    let max = arr[0];
    for (let i = 1; i < arr.length; i++) {
        // Complete the code
    }
    return max;
}
```  
---

#### **Question 7** (Code Error Identification)  
What is wrong with this code?  
```javascript
const x;
x = 10;
console.log(x);
```  
1. `const` variables cannot be declared without initialization.  
2. Reassignment of a `const` variable is not allowed.  
3. Syntax error in `console.log`.  
4. Nothing is wrong; it will log `10`.  

---

#### **Question 8**  
Which of the following are JavaScript built-in objects?  
1. `Math`  
2. `Date`  
3. `RegExp`  
4. `Set`  

---

#### **Question 9**  
What is the result of the following expression?  
```javascript
"hello".toUpperCase();
```  
1. `"HELLO"`  
2. `"hello"`  
3. `HELLO`  
4. `Error`  

---

#### **Question 10**  
How can you check if a value is an array in JavaScript?  
1. `value instanceof Array`  
2. `Array.isArray(value)`  
3. `typeof value === 'array'`  
4. `value.isArray()`  

---

#### **Question 11**  
Which of the following are valid ways to declare a function in JavaScript?  
1. `function myFunc() { }`  
2. `const myFunc = () => { }`  
3. `let myFunc = function() { }`  
4. `var myFunc = new Function() { }`  

---

#### **Question 12**  
What is the value of `x`?  
```javascript
let x = "5";
x = +x;
```  
1. `"5"`  
2. `5`  
3. `NaN`  
4. `undefined`  

---

#### **Question 13**  
What will this code output?  
```javascript
console.log(typeof NaN);
```  
1. `number`  
2. `NaN`  
3. `undefined`  
4. `string`  

---

#### **Question 14**  
What will the following code print?  
```javascript
let arr = [1, 2, 3];
arr.length = 0;
console.log(arr);
```  
1. `[]`  
2. `[1, 2, 3]`  
3. `undefined`  
4. `Error`  

---

#### **Question 15** (Code Completion)  
Complete the code to reverse an array:  
```javascript
function reverseArray(arr) {
    let reversed = [];
    for (let i = arr.length - 1; i >= 0; i--) {
        // Add code here
    }
    return reversed;
}
```

---

#### **Question 16**  
Which of the following methods modifies the original array?  
1. `slice()`  
2. `splice()`  
3. `map()`  
4. `push()`  

---

#### **Question 17**  
What is the output of this code?  
```javascript
console.log(null + 5);
```  
1. `5`  
2. `null`  
3. `NaN`  
4. `undefined`  

---

#### **Question 18**  
Which of the following are valid JavaScript string methods?  
1. `charAt()`  
2. `split()`  
3. `includes()`  
4. `filter()`  

---

#### **Question 19**  
What will the following code output?  
```javascript
let obj = { a: 1, b: 2 };
console.log("a" in obj);
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `Error`  

---

#### **Question 20**  
What is the result of the following code?  
```javascript
let a = [1, 2];
let b = a;
b.push(3);
console.log(a);
```  
1. `[1, 2, 3]`  
2. `[1, 2]`  
3. `undefined`  
4. `Error`  

---

#### **Question 21**  
Which keyword is used to handle exceptions in JavaScript?  
1. `catch`  
2. `throw`  
3. `try`  
4. `error`  

---

#### **Question 22** (Code Error Identification)  
What is wrong with this code?  
```javascript
function add(a, b) {
    return a + b
}
add(2);
```  
1. Syntax error due to missing semicolon.  
2. Function is missing a return statement.  
3. Function is called with insufficient arguments.  
4. Nothing is wrong.  

---

#### **Question 23**  
What is the purpose of the `return` statement in a function?  
1. Terminates the function.  
2. Returns a value to the caller.  
3. Ends the execution of all code.  
4. Declares a new variable.  

---

#### **Question 24**  
Which of the following methods creates a shallow copy of an array?  
1. `Array.from()`  
2. `concat()`  
3. `slice()`  
4. `splice()`  

---

#### **Question 25**  
What will be the result of the following code?  
```javascript
console.log(0.1 + 0.2 === 0.3);
```  
1. `true`  
2. `false`  
3. `NaN`  
4. `undefined`  

---
