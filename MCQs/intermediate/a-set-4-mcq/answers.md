Here are the answers for **Intermediate JavaScript - Set 4**:

---

### **JavaScript Intermediate - Set 4 - Answers**

---

#### **Question 1**  
**Answer:** 3. `Promise { 1 }`

Explanation: The `async` function always returns a promise. Even though the value `1` is returned from the function, it is wrapped in a promise, which is logged as `Promise { 1 }`.

---

#### **Question 2**  
**Answer:** 4. All of the above

Explanation: All three methods — `try...catch`, `catch()` method of a promise, and `async/await` — are ways to handle errors in JavaScript.

---

#### **Question 3**  
**Answer:** 2. `1 3 2`

Explanation: The `await` pauses the `test()` function's execution until the promise resolves, allowing `console.log(3)` to execute first, followed by `console.log(1)` and then `console.log(2)` after the promise is resolved.

---

#### **Question 4**  
**Answer:** 2. `10`

Explanation: The `inner()` function forms a closure and has access to the `x` variable defined in the outer function (`outer()`), so it logs `10`.

---

#### **Question 5**  
**Answer:** 1. `'11'`

Explanation: The `+` operator is used for string concatenation when one of the operands is a string. Therefore, `1 + '1'` results in the string `'11'`.

---

#### **Question 6**  
**Answer:** 1. `2 1`

Explanation: `console.log(2)` is executed first, and then the `setTimeout()` function is executed asynchronously, logging `1` after the current call stack is cleared.

---

#### **Question 7**  
**Answer:** 3. `setTimeout` executes code asynchronously after a specified delay.

Explanation: `setTimeout()` schedules the execution of a function after a delay in the event loop, which is asynchronous.

---

#### **Question 8**  
**Answer:** 3. `3`

Explanation: The inner function `inner()` updates `a` to `3` and it is immediately executed within the `test()` function.

---

#### **Question 9**  
**Answer:** 1. `[0, 1, 2, 3, 4]`

Explanation: `push(4)` adds `4` to the end of the array, and `unshift(0)` adds `0` to the beginning. The final array is `[0, 1, 2, 3, 4]`.

---

#### **Question 10**  
**Answer:** 1. To stop the execution of the default action of an event.

Explanation: `event.preventDefault()` prevents the default behavior of an event, such as submitting a form or following a link.

---

#### **Question 11**  
**Answer:** 1. `1 3 2`

Explanation: The `await` causes the function `foo()` to pause, allowing `console.log(3)` to run first, followed by `console.log(1)` and `console.log(2)` when the promise is resolved.

---

#### **Question 12**  
**Answer:** 1. `20 10`

Explanation: Inside the `test()` function, the `x` variable is assigned `20`, so `console.log(x)` inside the function logs `20`. The `x` outside remains `10`.

---

#### **Question 13**  
**Answer:** 1. A closure allows a function to access variables from an outer scope even after the outer function has returned.

Explanation: Closures retain access to their outer function's variables, even after the outer function has finished execution.

---

#### **Question 14**  
**Answer:** 1. `1`

Explanation: The `x` variable is declared outside the function and logged inside the `test()` function, which outputs `1`.

---

#### **Question 15**  
**Answer:** 3. `??`

Explanation: The `??` (nullish coalescing) operator is used to handle `null` and `undefined` values, returning the right-hand operand if the left-hand operand is `null` or `undefined`.

---

#### **Question 16**  
**Answer:** 1. `10`

Explanation: The `inner()` function is a closure that retains access to the `x` variable from the outer `test()` function, which has been assigned the value `10`.

---

#### **Question 17**  
**Answer:** 2. `[3, 4]`

Explanation: The `filter()` method creates a new array with elements that satisfy the condition `num > 2`, resulting in `[3, 4]`.

---

#### **Question 18**  
**Answer:** 2. `Bob`

Explanation: Since `y` is a reference to `x`, modifying `y.name` also modifies `x.name`, resulting in `'Bob'`.

---

#### **Question 19**  
**Answer:** 1. `10`

Explanation: The `setTimeout()` function schedules `x = 20` to execute asynchronously, so `console.log(x)` prints `10` first, and then `x = 20` is logged after 1 second.

---

#### **Question 20**  
**Answer:** 1. `split()`

Explanation: The `split()` method can be used to convert a string into an array by splitting it based on a specified separator.

---

#### **Question 21** (Code Completion)  
**Answer:**
```javascript
function addNumbers(arr) {
    return arr.reduce((total, num) => total + num, 0);
}
console.log(addNumbers([1, 2, 3, 4])); // Output should be 10
```

Explanation: The `reduce()` method is used to calculate the sum of all the elements in the array.

---

#### **Question 22**  
**Answer:** 1. `Something went wrong`

Explanation: The `throw` statement creates an error, which is then caught by the `catch` block, and `console.log(e.message)` logs the error message.

---

#### **Question 23**  
**Answer:** 2. `setInterval` executes a function repeatedly at a specified time interval.

Explanation: `setInterval()` runs a function repeatedly after a specified delay.

---

#### **Question 24**  
**Answer:** 1. `10`

Explanation: The `inner()` function modifies `num` locally, and the value is not reflected in the outer `num`, so the final output is `10`.

---

#### **Question 25**  
**Answer:** 1. `60`

Explanation: The destructuring assignment assigns values from the array `arr` to variables `x`, `y`, and `z`, and their sum is `10 + 20 + 30 = 60`.

---

