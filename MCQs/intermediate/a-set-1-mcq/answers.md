Here are the answers for **Intermediate Set-1** questions:

---

### **JavaScript Intermediate - Set 1 - Answers**

---

#### **Question 1**  
**Answer:** 1. `let` and `const` are block-scoped, whereas `var` is function-scoped.

---

#### **Question 2**  
**Answer:** 1. `10`

Explanation: `var` is function-scoped, so `x` is accessible outside the `if` block. The value `10` is assigned to `x` inside the block, and it is logged outside the block as well.

---

#### **Question 3**  
**Answer:** 1. `5`

Explanation: `x++` is a post-increment operator, so `y` gets the value `5` before `x` is incremented.

---

#### **Question 4**  
**Answer:** 2. `undefined`

Explanation: Due to hoisting, the declaration of `var name` is moved to the top, but the assignment happens after the `console.log` call. So it logs `undefined`.

---

#### **Question 5**  
**Answer:** 1. Arrow functions do not have their own `this` value and inherit `this` from the surrounding context.

---

#### **Question 6**  
**Answer:** 2. `2`

Explanation: The `bar` function is a closure, and it remembers the value of `x` from its outer function (`foo`).

---

#### **Question 7**  
**Answer:** 1. `function myFunc(...args) {}`

Explanation: The `...args` syntax is used to accept a variable number of arguments in a function.

---

#### **Question 8**  
**Answer:** 1. `const` variables must be initialized at the time of declaration.

Explanation: `const` requires an initial value when declared.

---

#### **Question 9**  
**Answer:** 2. `7`

Explanation: The default parameter value of `b` is used, so the sum is `5 + 2 = 7`.

---

#### **Question 10**  
**Answer:** 1. `10`

Explanation: `x++` is a post-increment operation, so `y` is assigned the value `10`, and then `x` becomes `11`.

---

#### **Question 11** (Code Completion)  
**Answer:**  
```javascript
function calculateSum(...args) {
    let total = 0;
    args.forEach(num => total += num);
    return total;
}
```

---

#### **Question 12**  
**Answer:** 2. `false`

Explanation: `===` checks both type and value. Since `a` is a number and `b` is a string, the comparison returns `false`.

---

#### **Question 13**  
**Answer:** 1. `true`

Explanation: `==` checks only the value, so it performs type coercion, and `5 == '5'` is true.

---

#### **Question 14**  
**Answer:** 4. All of the above

Explanation: All three ways are valid ways to declare a function in JavaScript.

---

#### **Question 15**  
**Answer:** 3. Block scope

Explanation: Variables declared with `let` are block-scoped, which means they are confined to the block in which they are defined.

---

#### **Question 16**  
**Answer:** 1. `20 10`

Explanation: `let a = 20;` is scoped inside the `if` block, so `console.log(a)` inside the block logs `20`. The `a` outside the block remains `10`.

---

#### **Question 17**  
**Answer:** 3. `bind()`

Explanation: `bind()` creates a new function that, when called, has its `this` value set to the provided value.

---

#### **Question 18**  
**Answer:** 1. `undefined`

Explanation: The variable `myVar` is declared but not initialized, so its type is `undefined`.

---

#### **Question 19**  
**Answer:** 3. `20 20`

Explanation: `x` is assigned `20` inside the `test` function, and since there is no local variable `x`, the global `x` is updated.

---

#### **Question 20**  
**Answer:** 2. `6`

Explanation: The function `multiply(2, 3)` correctly returns `2 * 3 = 6`.

---

#### **Question 21**  
**Answer:** 1. Functions in JavaScript are first-class objects.

Explanation: Functions are first-class citizens in JavaScript, meaning they can be assigned to variables, passed as arguments, and returned from other functions.

---

#### **Question 22**  
**Answer:** 1. `15`

Explanation: `add.bind(null, 5)` creates a function that always passes `5` as the first argument, so when `addNum(10)` is called, it returns `5 + 10 = 15`.

---

#### **Question 23**  
**Answer:** 1. `[1, 2, 100, 4]`

Explanation: The third element of the array is updated to `100` using `numbers[2] = 100;`.

---

#### **Question 24**  
**Answer:** 3. `10 10`

Explanation: The value of `x` inside the `myFunc` function is updated to `10`. Since no new scope is created inside the function, the updated value is reflected globally.

---

#### **Question 25**  
**Answer:** 3. `Error`

Explanation: `let` has block scope, so `x` is not accessible outside the `if` block, resulting in an error.

---

