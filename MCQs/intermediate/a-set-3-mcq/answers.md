Here are the answers for **Intermediate JavaScript - Set 3**:

---

### **JavaScript Intermediate - Set 3 - Answers**

---

#### **Question 1**  
**Answer:** 2. `[10, 2, 3]`

Explanation: Arrays are reference types in JavaScript, so both `a` and `b` refer to the same array. When `b[0]` is updated to `10`, the change is reflected in `a`.

---

#### **Question 2**  
**Answer:** 1. `1`

Explanation: `Object.freeze()` makes an object immutable. The assignment `obj2.a = 2` has no effect on the frozen object, and `obj.a` remains `1`.

---

#### **Question 3**  
**Answer:** 2. `2`

Explanation: The `setTimeout()` function is asynchronous, so it will log the value of `x` after the outer function finishes executing, where `x` is `2`.

---

#### **Question 4**  
**Answer:** 2. Promises are always resolved asynchronously, regardless of how they are executed.

Explanation: Even if a promise is resolved synchronously, its handlers are executed asynchronously.

---

#### **Question 5**  
**Answer:** 2. `10`

Explanation: The `func()` is returning the `inner` function, which logs the value of `a` from the closure. Since `a = 10`, it logs `10`.

---

#### **Question 6**  
**Answer:** 1. `[1, 2, 3]`

Explanation: The spread operator `[...]` creates a new array, so `a` remains unchanged.

---

#### **Question 7**  
**Answer:** 1. `addEventListener()`

Explanation: `addEventListener()` is the standard method to attach event handlers in JavaScript.

---

#### **Question 8**  
**Answer:** 2. `[2, 4, 6]`

Explanation: The `map()` method creates a new array by applying the function to each element, multiplying each number by `2`.

---

#### **Question 9**  
**Answer:** 2. `10`

Explanation: The variable `a` inside the block scope is `10`, so the `console.log(a)` inside the block logs `10`.

---

#### **Question 10**  
**Answer:** 1. `3`

Explanation: The `writable: false` property prevents `c` from being modified. Therefore, `obj.c` remains `3` despite the attempt to set `c` to `4`.

---

#### **Question 11**  
**Answer:** 2. `10`

Explanation: `x` inside the `test` function is `10`, so the `inner()` function logs `10`.

---

#### **Question 12**  
**Answer:** 2. `'11'`

Explanation: JavaScript performs string concatenation when a number is added to a string. `1 + '1'` results in `'11'`.

---

#### **Question 13**  
**Answer:** 1. `1`

Explanation: `Object.create()` creates a new object with the properties of the `obj` object. The original `obj` is unchanged, so `obj.a` is still `1`.

---

#### **Question 14**  
**Answer:** 4. `var function foo() {};`

Explanation: The correct syntax for declaring a function using `var` is `var foo = function() {};`.

---

#### **Question 15**  
**Answer:** 2. `false`

Explanation: The `===` operator checks both value and type, so `10` (a number) is not equal to `20` (another number).

---

#### **Question 16**  
**Answer:** 2. `2`

Explanation: Objects in JavaScript are reference types. The value of `x` inside `b` changes `a.x` to `2`.

---

#### **Question 17**  
**Answer:** 1. `1 3`

Explanation: The array destructuring `[a, , b]` skips the second element (`2`) and assigns `a = 1` and `b = 3`.

---

#### **Question 18**  
**Answer:** 2. `10`

Explanation: The `call()` method calls the `foo` function with `obj` as the context, setting `obj.a = 10`.

---

#### **Question 19**  
**Answer:** 4. All of the above

Explanation: In JavaScript, modules can be imported using `import` and `require()`, depending on the environment (ES6 or CommonJS).

---

#### **Question 20**  
**Answer:** 1. `true`

Explanation: The `==` operator performs type coercion, so the array `[1, 2]` is converted to a string `'1,2'`, which equals `'1,2'`.

---

#### **Question 21** (Code Completion)  
**Answer:**
```javascript
function sum() {
    return Array.from(arguments).reduce((total, num) => total + num, 0);
}
console.log(sum(1, 2, 3, 4)); // Output should be 10
```

Explanation: `Array.from(arguments)` converts the arguments object into an array, and `reduce()` calculates the sum.

---

#### **Question 22**  
**Answer:** 1. `10`

Explanation: `Object.create()` creates a new object that inherits from `obj`. The inherited `x` property is accessed.

---

#### **Question 23**  
**Answer:** 1. `7`

Explanation: The function `test(3, 4)` adds `3` and `4` to return `7`.

---

#### **Question 24**  
**Answer:** 2. `3`

Explanation: The `find()` method returns the first element that satisfies the condition (`num > 2`), which is `3`.

---

#### **Question 25**  
**Answer:** 1. `3`

Explanation: The object `obj` has `a: 1` and `b: 2`, and the destructuring assigns the values `a` and `b`. So `a + b = 3`.

---

