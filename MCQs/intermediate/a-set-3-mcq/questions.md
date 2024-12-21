Here is **Intermediate JavaScript - Set 3**:

---

### **JavaScript Intermediate - Set 3**

---

#### **Question 1**  
What will the following code output?  
```javascript
const a = [1, 2, 3];
const b = a;
b[0] = 10;
console.log(a);
```  
1. `[1, 2, 3]`  
2. `[10, 2, 3]`  
3. `undefined`  
4. `Error`

---

#### **Question 2**  
What will be the result of the following code?  
```javascript
const obj = { a: 1 };
const obj2 = Object.freeze(obj);
obj2.a = 2;
console.log(obj.a);
```  
1. `1`  
2. `2`  
3. `undefined`  
4. `Error`

---

#### **Question 3**  
What will the following code output?  
```javascript
let x = 1;
function test() {
    let x = 2;
    setTimeout(function() {
        console.log(x);
    }, 1000);
}
test();
```  
1. `1`  
2. `2`  
3. `undefined`  
4. `Error`

---

#### **Question 4**  
Which of the following statements is true about JavaScript promises?  
1. Promises can only be created using the `Promise` constructor.  
2. Promises are always resolved asynchronously, regardless of how they are executed.  
3. Promises can never be rejected once they are resolved.  
4. Promises can only handle asynchronous code.

---

#### **Question 5**  
What will be the output of the following code?  
```javascript
let a = 5;
function test() {
    let a = 10;
    return function inner() {
        console.log(a);
    }
}
let func = test();
func();
```  
1. `5`  
2. `10`  
3. `undefined`  
4. `Error`

---

#### **Question 6**  
What will be the result of the following code?  
```javascript
let a = [1, 2, 3];
let b = a;
b = [...a, 4];
console.log(a);
```  
1. `[1, 2, 3]`  
2. `[1, 2, 3, 4]`  
3. `undefined`  
4. `Error`

---

#### **Question 7**  
Which of the following methods is used to attach an event handler to an element in JavaScript?  
1. `addEventListener()`  
2. `attachEvent()`  
3. `onEvent()`  
4. `bind()`

---

#### **Question 8**  
What will the following code output?  
```javascript
const nums = [1, 2, 3];
const result = nums.map(num => num * 2);
console.log(result);
```  
1. `[1, 2, 3]`  
2. `[2, 4, 6]`  
3. `[1, 4, 6]`  
4. `[2, 3, 5]`

---

#### **Question 9**  
What will the following code output?  
```javascript
function test() {
    let a = 5;
    if (true) {
        let a = 10;
        console.log(a);
    }
}
test();
```  
1. `5`  
2. `10`  
3. `undefined`  
4. `Error`

---

#### **Question 10**  
What does the following code do?  
```javascript
const obj = { a: 1, b: 2 };
Object.defineProperty(obj, 'c', {
    value: 3,
    writable: false
});
obj.c = 4;
console.log(obj.c);
```  
1. `3`  
2. `4`  
3. `undefined`  
4. `Error`

---

#### **Question 11**  
What will the following code output?  
```javascript
let x = 5;
function test() {
    let x = 10;
    function inner() {
        console.log(x);
    }
    return inner;
}
const func = test();
func();
```  
1. `5`  
2. `10`  
3. `undefined`  
4. `Error`

---

#### **Question 12**  
What is the output of the following code?  
```javascript
console.log(1 + '1');
```  
1. `2`  
2. `'11'`  
3. `11`  
4. `Error`

---

#### **Question 13**  
What does the following code output?  
```javascript
const obj = { a: 1, b: 2 };
const obj2 = { ...obj };
obj2.a = 10;
console.log(obj.a);
```  
1. `1`  
2. `2`  
3. `10`  
4. `undefined`

---

#### **Question 14**  
Which of the following is NOT a valid way to declare a function in JavaScript?  
1. `function foo() {}`  
2. `let foo = function() {};`  
3. `const foo = () => {};`  
4. `var function foo() {};`

---

#### **Question 15**  
What will be the result of the following code?  
```javascript
let x = 10;
let y = 20;
console.log(x === y);
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `NaN`

---

#### **Question 16**  
What does the following code do?  
```javascript
const a = { x: 1 };
const b = a;
b.x = 2;
console.log(a.x);
```  
1. `1`  
2. `2`  
3. `undefined`  
4. `Error`

---

#### **Question 17**  
What is the output of the following code?  
```javascript
const nums = [1, 2, 3, 4];
const [a, , b] = nums;
console.log(a, b);
```  
1. `1 3`  
2. `1 2`  
3. `undefined undefined`  
4. `3 4`

---

#### **Question 18**  
What does the following code do?  
```javascript
function foo() {
    this.a = 10;
}
let obj = {};
foo.call(obj);
console.log(obj.a);
```  
1. `undefined`  
2. `10`  
3. `foo`  
4. `Error`

---

#### **Question 19**  
Which of the following is used to import modules in JavaScript?  
1. `import { x, y } from 'module';`  
2. `import 'module'`  
3. `require('module')`  
4. All of the above

---

#### **Question 20**  
What will be the output of the following code?  
```javascript
console.log([1, 2] == '1,2');
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `Error`

---

#### **Question 21** (Code Completion)  
Complete the function `sum` so that it returns the sum of all the arguments passed to it.  
```javascript
function sum() {
    // Add code here
}
console.log(sum(1, 2, 3, 4)); // Output should be 10
```

---

#### **Question 22**  
What will be the result of the following code?  
```javascript
const obj = { x: 10 };
const newObj = Object.create(obj);
newObj.y = 20;
console.log(newObj.x);
```  
1. `10`  
2. `20`  
3. `undefined`  
4. `Error`

---

#### **Question 23**  
What will be the output of the following code?  
```javascript
function test(a, b = 2) {
    return a + b;
}
console.log(test(3, 4));
```  
1. `7`  
2. `6`  
3. `undefined`  
4. `NaN`

---

#### **Question 24**  
What is the result of the following code?  
```javascript
const arr = [1, 2, 3];
const result = arr.find(num => num > 2);
console.log(result);
```  
1. `2`  
2. `3`  
3. `1`  
4. `undefined`

---

#### **Question 25**  
What will the following code output?  
```javascript
let obj = { a: 1, b: 2 };
let { a, b } = obj;
console.log(a + b);
```  
1. `3`  
2. `1`  
3. `undefined`  
4. `NaN`

---

