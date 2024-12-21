Here is a new set of **Intermediate JavaScript - Set 4** covering additional topics 
like **Asynchronous JavaScript**, **Error Handling**, **Closures**, **Event Loop**, etc.

---

### **JavaScript Intermediate - Set 4**

---

#### **Question 1**  
What will be the output of the following code?  
```javascript
async function foo() {
    return 1;
}
foo().then(console.log);
```  
1. `1`  
2. `undefined`  
3. `Promise { 1 }`  
4. `Error`

---

#### **Question 2**  
Which of the following is a correct way to handle errors in asynchronous code in JavaScript?  
1. `try...catch`  
2. `catch()` method of Promise  
3. `async/await`  
4. All of the above

---

#### **Question 3**  
What will be the result of the following code?  
```javascript
async function test() {
    console.log(1);
    await new Promise(resolve => setTimeout(resolve, 1000));
    console.log(2);
}
test();
console.log(3);
```  
1. `1 2 3`  
2. `1 3 2`  
3. `3 1 2`  
4. `1 2 3 4`

---

#### **Question 4**  
What is the output of the following code?  
```javascript
function outer() {
    let x = 10;
    return function inner() {
        console.log(x);
    }
}
let innerFunc = outer();
innerFunc();
```  
1. `undefined`  
2. `10`  
3. `Error`  
4. `inner`

---

#### **Question 5**  
What will be the output of the following code?  
```javascript
console.log(1 + '1');
```  
1. `'11'`  
2. `11`  
3. `1`  
4. `Error`

---

#### **Question 6**  
What will be the output of the following code?  
```javascript
setTimeout(() => {
    console.log(1);
}, 0);
console.log(2);
```  
1. `2 1`  
2. `1 2`  
3. `Error`  
4. `undefined`

---

#### **Question 7**  
Which of the following statements is correct about `setTimeout`?  
1. `setTimeout` always executes the code synchronously.  
2. `setTimeout` can only be used with numeric delay values.  
3. `setTimeout` executes code asynchronously after a specified delay.  
4. `setTimeout` is not available in Node.js.

---

#### **Question 8**  
What will be the output of the following code?  
```javascript
let a = 1;
function test() {
    a = 2;
    return function() {
        a = 3;
    }
}
test()();
console.log(a);
```  
1. `1`  
2. `2`  
3. `3`  
4. `undefined`

---

#### **Question 9**  
What will be the result of the following code?  
```javascript
let arr = [1, 2, 3];
arr.push(4);
arr.unshift(0);
console.log(arr);
```  
1. `[0, 1, 2, 3, 4]`  
2. `[1, 2, 3, 4, 0]`  
3. `[1, 2, 3]`  
4. `Error`

---

#### **Question 10**  
What is the purpose of `event.preventDefault()` in JavaScript?  
1. To stop the execution of the default action of an event.  
2. To stop propagation of the event.  
3. To allow an event to propagate.  
4. To prevent an event from being created.

---

#### **Question 11**  
What will be the output of the following code?  
```javascript
async function foo() {
    console.log(1);
    await Promise.resolve();
    console.log(2);
}
foo();
console.log(3);
```  
1. `1 3 2`  
2. `3 1 2`  
3. `1 2 3`  
4. `1 3 2 3`

---

#### **Question 12**  
What is the output of the following code?  
```javascript
const x = 10;
function test() {
    let x = 20;
    console.log(x);
}
test();
console.log(x);
```  
1. `20 10`  
2. `10 20`  
3. `undefined 10`  
4. `Error`

---

#### **Question 13**  
Which of the following is true about JavaScript closures?  
1. A closure allows a function to access variables from an outer scope even after the outer function has returned.  
2. Closures only work within the function scope.  
3. Closures are only used in the `setTimeout` function.  
4. A closure does not have access to variables in the outer function's scope.

---

#### **Question 14**  
What will the following code output?  
```javascript
let x = 1;
function test() {
    console.log(x);
}
test();
```  
1. `1`  
2. `undefined`  
3. `Error`  
4. `null`

---

#### **Question 15**  
Which of the following JavaScript operators is used to handle both `null` and `undefined` values?  
1. `==`  
2. `===`  
3. `??`  
4. `||`

---

#### **Question 16**  
What is the output of the following code?  
```javascript
let a = 1;
function test() {
    let a = 10;
    return function inner() {
        console.log(a);
    }
}
let func = test();
func();
```  
1. `10`  
2. `1`  
3. `undefined`  
4. `Error`

---

#### **Question 17**  
What will be the result of the following code?  
```javascript
const arr = [1, 2, 3, 4];
const result = arr.filter(num => num > 2);
console.log(result);
```  
1. `[1, 2]`  
2. `[3, 4]`  
3. `[1, 2, 3, 4]`  
4. `Error`

---

#### **Question 18**  
What will be the output of the following code?  
```javascript
const x = { name: 'Alice' };
const y = x;
y.name = 'Bob';
console.log(x.name);
```  
1. `Alice`  
2. `Bob`  
3. `undefined`  
4. `Error`

---

#### **Question 19**  
What will be the result of the following code?  
```javascript
let x = 10;
setTimeout(function() {
    x = 20;
    console.log(x);
}, 1000);
console.log(x);
```  
1. `10`  
2. `20`  
3. `undefined`  
4. `Error`

---

#### **Question 20**  
Which of the following methods can be used to convert a string into an array?  
1. `split()`  
2. `charAt()`  
3. `join()`  
4. `map()`

---

#### **Question 21** (Code Completion)  
Complete the function `addNumbers` so that it returns the sum of all numbers in the array.  
```javascript
function addNumbers(arr) {
    // Add code here
}
console.log(addNumbers([1, 2, 3, 4])); // Output should be 10
```

---

#### **Question 22**  
What will be the output of the following code?  
```javascript
function getData() {
    try {
        throw new Error('Something went wrong');
    } catch (e) {
        console.log(e.message);
    }
}
getData();
```  
1. `Something went wrong`  
2. `undefined`  
3. `Error`  
4. `null`

---

#### **Question 23**  
Which of the following statements is correct about `setInterval` in JavaScript?  
1. `setInterval` executes a function only once at a specified time interval.  
2. `setInterval` executes a function repeatedly at a specified time interval.  
3. `setInterval` cannot be used to repeat asynchronous functions.  
4. `setInterval` is synchronous.

---

#### **Question 24**  
What will be the output of the following code?  
```javascript
let num = 5;
function outer() {
    let num = 10;
    function inner() {
        num++;
    }
    inner();
    console.log(num);
}
outer();
```  
1. `10`  
2. `11`  
3. `5`  
4. `Error`

---

#### **Question 25**  
What will be the output of the following code?  
```javascript
let arr = [10, 20, 30];
let [x, y, z] = arr;
console.log(x + y + z);
```  
1. `60`  
2. `10 20 30`  
3. `undefined`  
4. `Error`

---

