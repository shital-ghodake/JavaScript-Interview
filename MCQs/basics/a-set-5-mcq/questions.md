Here’s the next set of **25 basic-level JavaScript questions** for **basic-set 5**. 
This set will cover additional topics like **Event Handling**, **Closures**, and **Asynchronous JavaScript** 
while also including **Code Error Finding** and **Code Completion**.

---

### **JavaScript Basics - MCQ Set 5**

---

#### **Question 1**  
Which of the following is used to define a block of code that should be executed when an event occurs in JavaScript?  
1. `addEvent()`  
2. `addListener()`  
3. `addEventListener()`  
4. `onEvent()`

---

#### **Question 2**  
What will be the output of the following code?  
```javascript
const x = [1, 2, 3];
x.length = 2;
console.log(x);
```  
1. `[1, 2, 3]`  
2. `[1, 2]`  
3. `[2, 3]`  
4. `[1]`

---

#### **Question 3**  
Which of the following are valid types of `this` in JavaScript?  
1. `Object`  
2. `Function`  
3. `Window`  
4. `null`

---

#### **Question 4**  
What is the result of the following code?  
```javascript
let obj = { a: 1, b: 2 };
let newObj = Object.create(obj);
newObj.c = 3;
console.log(newObj.a);
```  
1. `undefined`  
2. `1`  
3. `3`  
4. `Error`

---

#### **Question 5**  
What is the output of the following code?  
```javascript
const arr = [5, 10, 15];
arr.length = 0;
console.log(arr);
```  
1. `[5, 10, 15]`  
2. `[]`  
3. `undefined`  
4. `null`

---

#### **Question 6**  
Which method is used to check if a string contains a specific substring?  
1. `indexOf()`  
2. `contains()`  
3. `substring()`  
4. `includes()`

---

#### **Question 7**  
What will the following code output?  
```javascript
let x = 5;
let y = 10;
x = y = 20;
console.log(x, y);
```  
1. `5 10`  
2. `10 10`  
3. `20 20`  
4. `undefined undefined`

---

#### **Question 8**  
Which of the following is NOT a falsy value in JavaScript?  
1. `0`  
2. `null`  
3. `false`  
4. `""`  
5. `[]`

---

#### **Question 9**  
Which of the following statements is true about `localStorage`?  
1. It stores data in memory and gets cleared when the session ends.  
2. It can only store strings.  
3. It stores data for the lifetime of the page session.  
4. It can store data that is persisted across browser sessions.

---

#### **Question 10**  
What is the output of the following code?  
```javascript
const x = 5;
const y = '5';
console.log(x == y);
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `Error`

---

#### **Question 11** (Code Completion)  
Complete the code to find the factorial of a number recursively:  
```javascript
function factorial(n) {
    if (n === 0) {
        return 1;
    }
    // Add code here
}
```  

---

#### **Question 12**  
What is the result of the following code?  
```javascript
let obj = { a: 1 };
Object.freeze(obj);
obj.a = 2;
console.log(obj.a);
```  
1. `2`  
2. `1`  
3. `undefined`  
4. `Error`

---

#### **Question 13**  
What is the output of the following code?  
```javascript
console.log(5 > 3 && 3 > 1);
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `Error`

---

#### **Question 14**  
What is the result of the following code?  
```javascript
let x = 0;
let y = "0";
console.log(x == y);
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `Error`

---

#### **Question 15**  
Which of the following is the correct syntax for an anonymous function?  
1. `function() {}`  
2. `let myFunc = function() {}`  
3. `const myFunc = () => {}`  
4. All of the above

---

#### **Question 16**  
Which method can be used to convert a JavaScript string into an array?  
1. `split()`  
2. `slice()`  
3. `arrayify()`  
4. `convert()`

---

#### **Question 17**  
What is the purpose of the `JSON.stringify()` method?  
1. Convert a JSON object to a string  
2. Parse a JSON string into an object  
3. Check if a JSON object is valid  
4. Convert a JavaScript object to a JSON object

---

#### **Question 18**  
What is the output of the following code?  
```javascript
const arr = [1, 2, 3, 4];
arr.pop();
console.log(arr);
```  
1. `[1, 2, 3]`  
2. `[1, 2, 3, 4]`  
3. `[2, 3, 4]`  
4. `[4]`

---

#### **Question 19**  
What is the result of the following code?  
```javascript
let arr = [1, 2, 3];
arr.unshift(0);
console.log(arr);
```  
1. `[0, 1, 2, 3]`  
2. `[1, 2, 3, 0]`  
3. `[0]`  
4. `[1, 0, 2, 3]`

---

#### **Question 20**  
Which of the following is the correct syntax to define a function using the arrow function syntax?  
1. `let myFunc = function() {}`  
2. `let myFunc = () => {}`  
3. `function() => {}`  
4. `let myFunc => function() {}`

---

#### **Question 21**  
What is the result of the following code?  
```javascript
const obj = { a: 1, b: 2 };
const copy = Object.assign({}, obj);
copy.a = 3;
console.log(obj.a);
```  
1. `1`  
2. `2`  
3. `3`  
4. `undefined`

---

#### **Question 22**  
What is the result of the following code?  
```javascript
let num = "123.45";
let converted = parseFloat(num);
console.log(converted);
```  
1. `123`  
2. `123.45`  
3. `"123.45"`  
4. `NaN`

---

#### **Question 23**  
What will be the output of the following code?  
```javascript
function show() {
    console.log(arguments);
}
show(1, 2, 3);
```  
1. `[1, 2, 3]`  
2. `{ 0: 1, 1: 2, 2: 3 }`  
3. `undefined`  
4. `Error`

---

#### **Question 24** (Code Error Identification)  
What is wrong with this code?  
```javascript
let x = 10;
y = 20;
console.log(x + y);
```  
1. `x` is undefined  
2. `y` is undefined  
3. `x` and `y` are both undefined  
4. No error; the code runs fine

---

#### **Question 25**  
What is the result of the following code?  
```javascript
let str = "hello";
str[0] = "H";
console.log(str);
```  
1. `"Hello"`  
2. `"hello"`  
3. `undefined`  
4. `Error`

---

