Here are the answers for **Intermediate JavaScript - Set 2**:

---

### **JavaScript Intermediate - Set 2 - Answers**

---

#### **Question 1**  
**Answer:** 2. `20`

Explanation: The variable `x` is shadowed inside the `test` function. The inner function `inner` logs the `x` from its own scope, which is `20`.

---

#### **Question 2**  
**Answer:** 2. The event loop handles asynchronous code only after the stack is empty.

Explanation: The event loop processes the callback functions of asynchronous code only after the call stack is empty.

---

#### **Question 3**  
**Answer:** 2. `12`

Explanation: The post-increment `a++` sets `b = 5`, then `a` becomes `6`. The pre-increment `++a` makes `a = 7`. Thus, `b + c` equals `5 + 7 = 12`.

---

#### **Question 4**  
**Answer:** 1. A `const` declaration creates a block-scoped variable that cannot be reassigned.

Explanation: `const` creates a block-scoped variable whose value cannot be changed after initialization.

---

#### **Question 5**  
**Answer:** 2. `[10, 2, 3, 4]`

Explanation: The first element is updated to `10`, and then `4` is pushed into the array.

---

#### **Question 6**  
**Answer:** 2. `window` (in browsers)

Explanation: In non-strict mode, the value of `this` in a regular function call is the global object (`window` in browsers).

---

#### **Question 7**  
**Answer:** 3. `30`

Explanation: The `x` variable inside the innermost function is logged, which has a value of `30`.

---

#### **Question 8**  
**Answer:** 2. Returns `7`

Explanation: The default value for `b` is `5`, so the sum is `2 + 5 = 7`.

---

#### **Question 9**  
**Answer:** 2. `setTimeout()` executes code asynchronously after the specified delay.

Explanation: `setTimeout()` schedules a function to be executed asynchronously after a specified delay.

---

#### **Question 10**  
**Answer:** 2. `12`

Explanation: JavaScript follows the order of operations (PEMDAS). First, `b * 2` is evaluated (`5 * 2 = 10`), and then `a + 10` is computed (`2 + 10 = 12`).

---

#### **Question 11** (Code Completion)  
**Answer:**  
```javascript
function factorial(n) {
    if (n <= 1) return 1;
    return n * factorial(n - 1);
}
```

---

#### **Question 12**  
**Answer:** 3. `15`

Explanation: The inner function `inner()` logs the `x` from its local scope, which is `15`.

---

#### **Question 13**  
**Answer:** 4. `let obj = object();`

Explanation: `object()` is not a valid method in JavaScript. The correct ways to create an object are `let obj = {};` or `let obj = new Object();`.

---

#### **Question 14**  
**Answer:** 1. `10`

Explanation: Since `b` has a default value of `2`, the result of `5 * 2 = 10`.

---

#### **Question 15**  
**Answer:** 2. A closure has access to variables in its outer scope.

Explanation: A closure remembers and can access variables from its lexical scope, even if it is executed outside of that scope.

---

#### **Question 16**  
**Answer:** 1. `{ a: 1, b: 2, c: 3 }`

Explanation: The `spread operator` copies the properties of `obj` into `newObj` and adds the property `c: 3`.

---

#### **Question 17**  
**Answer:** 1. `10`

Explanation: The `reduce()` method sums up all elements of the array. `1 + 2 + 3 + 4 = 10`.

---

#### **Question 18**  
**Answer:** 1. `5`

Explanation: The `add()` function adds the first two arguments, `2 + 3 = 5`.

---

#### **Question 19**  
**Answer:** 2. `35`

Explanation: The `newPerson` object is assigned the reference of `person`. Since objects are mutable, changing `newPerson.age` also changes `person.age`.

---

#### **Question 20**  
**Answer:** 2. `indexOf()`

Explanation: `indexOf()` is used to find the index of an element in an array.

---

#### **Question 21**  
**Answer:** 2. `false`

Explanation: `===` compares both value and type, so `10` (a number) is not equal to `'10'` (a string).

---

#### **Question 22**  
**Answer:** 2. `{ b: 2 }`

Explanation: The `delete` operator removes the property `a` from `obj`, so only `{ b: 2 }` remains.

---

#### **Question 23**  
**Answer:** 3. `9`

Explanation: The `foo(3)` call calculates `3 * 3 = 9`.

---

#### **Question 24**  
**Answer:** 2. `[1, 2]`

Explanation: Setting the `length` property of the array to `2` truncates the array to the first two elements.

---

#### **Question 25**  
**Answer:** 3. `12`

Explanation: The pre-increment `++x` increases `x` to `6`, and then `y = 6 * 2 = 12`.

---

