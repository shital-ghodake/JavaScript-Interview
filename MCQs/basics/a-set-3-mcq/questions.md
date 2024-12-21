### **JavaScript Basics - MCQ Set 3**

Here’s the next set of 25 questions for your `basic-set 3`. This set includes multiple-choice questions, multiple answers, code error identification, and code completion questions.

---

### **Questions**

#### **Question 1**  
What is the output of the following code?  
```javascript
console.log(typeof undefined);
console.log(typeof null);
```  
1. `"undefined", "null"`  
2. `"undefined", "object"`  
3. `"object", "null"`  
4. `"undefined", "undefined"`  

---

#### **Question 2**  
Which of the following are falsy values in JavaScript?  
1. `false`  
2. `""`  
3. `0`  
4. `"false"`  

---

#### **Question 3**  
What will the following code output?  
```javascript
let x;
console.log(x === undefined);
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `Error`  

---

#### **Question 4**  
How can you convert a number to a string in JavaScript?  
1. `num.toString()`  
2. `String(num)`  
3. `num + ""`  
4. `Number.toString(num)`  

---

#### **Question 5**  
What does the following code log to the console?  
```javascript
console.log("10" - 5);
```  
1. `"105"`  
2. `NaN`  
3. `5`  
4. `5`  

---

#### **Question 6** (Code Completion)  
Complete the function to calculate the factorial of a number:  
```javascript
function factorial(n) {
    if (n === 0) {
        return 1;
    }
    // Add code here
}
```  

---

#### **Question 7**  
What is the output of this code?  
```javascript
const obj = { a: 1, b: 2 };
Object.freeze(obj);
obj.c = 3;
console.log(obj);
```  
1. `{ a: 1, b: 2 }`  
2. `{ a: 1, b: 2, c: 3 }`  
3. `Error`  
4. `undefined`  

---

#### **Question 8**  
Which of the following are JavaScript ES6 features?  
1. `let` and `const`  
2. Arrow functions  
3. Template literals  
4. `var`  

---

#### **Question 9**  
What will this code output?  
```javascript
let a = 10;
let b = "10";
console.log(a === b);
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `Error`  

---

#### **Question 10**  
Which of the following methods can be used to merge arrays?  
1. `concat()`  
2. `push()`  
3. `...` (spread operator)  
4. `splice()`  

---

#### **Question 11**  
What is the result of the following code?  
```javascript
let arr = [10, 20, 30];
delete arr[1];
console.log(arr);
```  
1. `[10, 30]`  
2. `[10, undefined, 30]`  
3. `[10, , 30]`  
4. `[10, null, 30]`  

---

#### **Question 12**  
What will the following code output?  
```javascript
console.log(!!"");
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `Error`  

---

#### **Question 13**  
What will this code output?  
```javascript
let a = 5;
let b = a++;
console.log(a, b);
```  
1. `6, 5`  
2. `5, 6`  
3. `5, 5`  
4. `6, 6`  

---

#### **Question 14** (Code Error Identification)  
What is wrong with this code?  
```javascript
let x = 10;
const x = 20;
console.log(x);
```  
1. Syntax error: variable redeclaration.  
2. TypeError: reassignment of a constant.  
3. No error; the code runs.  
4. `undefined` is logged.  

---

#### **Question 15** (Code Completion)  
Complete the code to count the number of vowels in a string:  
```javascript
function countVowels(str) {
    const vowels = "aeiou";
    let count = 0;
    for (let char of str.toLowerCase()) {
        // Add code here
    }
    return count;
}
```  

---

#### **Question 16**  
Which of the following are valid JSON data types?  
1. `String`  
2. `Number`  
3. `Boolean`  
4. `Function`  

---

#### **Question 17**  
What will this code output?  
```javascript
let arr = [1, 2, 3, 4];
arr.splice(2, 1);
console.log(arr);
```  
1. `[1, 2, 3, 4]`  
2. `[1, 2, 4]`  
3. `[1, 3, 4]`  
4. `[2, 3, 4]`  

---

#### **Question 18**  
What is the purpose of `Array.prototype.reduce()`?  
1. Iterate over an array and perform a transformation.  
2. Combine all elements of an array into a single value.  
3. Filter elements from an array based on a condition.  
4. Create a new array with transformed elements.  

---

#### **Question 19**  
What is the output of this code?  
```javascript
const arr = [1, 2, 3];
arr[5] = 6;
console.log(arr.length);
```  
1. `3`  
2. `6`  
3. `4`  
4. `5`  

---

#### **Question 20**  
Which of the following are valid ways to copy an object in JavaScript?  
1. `Object.assign({}, obj)`  
2. `{ ...obj }`  
3. `JSON.parse(JSON.stringify(obj))`  
4. `obj.clone()`  

---

#### **Question 21**  
What is the output of this code?  
```javascript
console.log(typeof NaN === typeof Infinity);
```  
1. `true`  
2. `false`  
3. `undefined`  
4. `Error`  

---

#### **Question 22** (Code Error Identification)  
What is wrong with this code?  
```javascript
const myFunc = () => {
    return
    {
        name: "John";
    }
};
console.log(myFunc());
```  
1. Missing semicolon after `return`.  
2. Object declaration is incorrect.  
3. Returns `undefined` due to automatic semicolon insertion.  
4. Nothing is wrong; it logs `{ name: "John" }`.  

---

#### **Question 23**  
What is the result of the following expression?  
```javascript
"5" * 2;
```  
1. `10`  
2. `5`  
3. `"52"`  
4. `NaN`  

---

#### **Question 24**  
Which of the following methods can be used to iterate over object properties?  
1. `Object.keys()`  
2. `Object.values()`  
3. `Object.entries()`  
4. `Object.forEach()`  

---

#### **Question 25**  
What will the following code output?  
```javascript
console.log(1 < 2 < 3);
console.log(3 > 2 > 1);
```  
1. `true, true`  
2. `true, false`  
3. `false, true`  
4. `false, false`  

---

