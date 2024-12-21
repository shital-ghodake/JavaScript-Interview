### **Answers for JavaScript Basics - MCQ Set 4**

Here are the answers for the questions in **Set 4**:

---

#### **Question 1**  
**Answer**: 1. `20 10`  
*Explanation*: This code swaps the values of `a` and `b` using a temporary variable `c`. So, after the swap, `a` becomes `20` and `b` becomes `10`.

---

#### **Question 2**  
**Answer**: 1. `addEventListener()`  
*Explanation*: `addEventListener()` is the standard way to attach an event handler to an HTML element.

---

#### **Question 3**  
**Answer**: 2. `window` (in a browser environment)  
*Explanation*: When `greet()` is called without any context, `this` refers to the global object (`window` in browsers).

---

#### **Question 4**  
**Answer**: 1. Create a new function that, when called, has its `this` keyword set to the provided value.  
*Explanation*: The `bind()` method creates a new function that binds the provided value of `this` and other arguments.

---

#### **Question 5**  
**Answer**: 1, 2, 3  
*Explanation*: All three options are valid examples of closures in JavaScript. A closure is a function that has access to variables from its outer function's scope.

---

#### **Question 6**  
**Answer**: 2. `1 2`  
*Explanation*: `increment()` is a closure that remembers the value of `counter` across calls, so it increments it and logs `1` and `2` sequentially.

---

#### **Question 7**  
**Answer**: 1. `removeChild()`  
*Explanation*: `removeChild()` is the standard method to remove an element from the DOM.

---

#### **Question 8**  
**Answer**: 1. `3`  
*Explanation*: `Object.defineProperty()` makes the `c` property non-writable, so the assignment of `4` is ignored, and the value remains `3`.

---

#### **Question 9**  
**Answer**: 4. `101`  
*Explanation*: Setting `arr[100] = 5` creates a sparse array with a length of `101`.

---

#### **Question 10**  
**Answer**: 1. `10`  
*Explanation*: `Object.freeze()` prevents modifications to the object. Since `obj` is frozen, the value of `a` remains `10`.

---

#### **Question 11** (Code Completion)  
**Answer**:  
```javascript
function isPalindrome(str) {
    str = str.toLowerCase().replace(/[^a-z0-9]/g, '');
    return str === str.split('').reverse().join('');
}
```
*Explanation*: This function checks if a string is a palindrome by cleaning it and then comparing it to its reversed version.

---

#### **Question 12**  
**Answer**: 1, 2  
*Explanation*: `true` and `[]` (an empty array) are truthy values in JavaScript. `0` and `""` (empty string) are falsy values.

---

#### **Question 13**  
**Answer**: 1. `true`  
*Explanation*: The `==` operator performs type coercion, so the number `5` is converted to a string `"5"`, and they are considered equal.

---

#### **Question 14**  
**Answer**: 1, 2, 4  
*Explanation*: Every object in JavaScript has a prototype, and you can add properties to an object's prototype. Prototypes are part of the object chain.

---

#### **Question 15**  
**Answer**: 2. `2 1`  
*Explanation*: `b` is assigned the value of `a` before `a` is changed, so `b` remains `1` while `a` becomes `2`.

---

#### **Question 16**  
**Answer**: 1. `push()`  
*Explanation*: The `push()` method adds one or more elements to the end of an array.

---

#### **Question 17**  
**Answer**: 3. `[2, 3]`  
*Explanation*: `push()` adds `4` to the end of the array, and `shift()` removes the first element (`1`), leaving `[2, 3, 4]`.

---

#### **Question 18**  
**Answer**: 2. `object`  
*Explanation*: `typeof null` returns `"object"`, which is a historical quirk in JavaScript.

---

#### **Question 19**  
**Answer**: 1. Delay the execution of a function by a specific number of milliseconds.  
*Explanation*: `setTimeout()` is used to delay the execution of a function for a given time.

---

#### **Question 20**  
**Answer**: 2. `false`  
*Explanation*: The `===` operator checks for both value and type. Since `x` is a number and `y` is a string, the comparison results in `false`.

---

#### **Question 21**  
**Answer**: 1. `11`  
*Explanation*: The `+` operator in JavaScript converts the number `1` to a string `"1"`, and then concatenates the two strings, resulting in `"11"`.

---

#### **Question 22**  
**Answer**: 1. `"object"`  
*Explanation*: Arrays in JavaScript are of type `"object"`, not `"array"`, when checked with `typeof`.

---

#### **Question 23**  
**Answer**: 1, 2, 3  
*Explanation*: All the first three options are correct ways to declare a function in JavaScript. The fourth option (`function: myFunc() {}`) is incorrect.

---

#### **Question 24** (Code Error Identification)  
**Answer**: 2. No error; the code runs.  
*Explanation*: JavaScript allows reassigning variables, even if they are initially assigned different types. So, `a` can be reassigned from a number to a string without error.

---

#### **Question 25**  
**Answer**: 2. `true, false`  
*Explanation*: `==` performs type coercion, so `10 == "10"` returns `true`, but `===` checks both value and type, so `10 === "10"` returns `false`.

---

