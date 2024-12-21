### **Answers for JavaScript Basics - MCQ Set 5**

Here are the answers for the questions in **Set 5**:

---

#### **Question 1**  
**Answer**: 3. `addEventListener()`  
*Explanation*: `addEventListener()` is the standard method to attach event listeners to DOM elements in JavaScript.

---

#### **Question 2**  
**Answer**: 2. `[1, 2]`  
*Explanation*: The `length` property of the array is set to `2`, truncating the array to the first two elements.

---

#### **Question 3**  
**Answer**: 1, 2, 3  
*Explanation*: `this` can refer to various objects in JavaScript: an `Object`, `Function`, or `Window`, depending on the context.

---

#### **Question 4**  
**Answer**: 2. `1`  
*Explanation*: `newObj.a` refers to `a` from the prototype (`obj`), which is `1`, so it logs `1`.

---

#### **Question 5**  
**Answer**: 2. `[]`  
*Explanation*: Setting `arr.length = 0` clears the array completely.

---

#### **Question 6**  
**Answer**: 4. `includes()`  
*Explanation*: The `includes()` method checks if a string contains a specified substring.

---

#### **Question 7**  
**Answer**: 3. `20 20`  
*Explanation*: Both `x` and `y` are assigned the value `20`.

---

#### **Question 8**  
**Answer**: 5. `[]`  
*Explanation*: An empty array `[]` is a truthy value in JavaScript, unlike the other falsy values like `0`, `false`, and `null`.

---

#### **Question 9**  
**Answer**: 4. It can store data that is persisted across browser sessions.  
*Explanation*: `localStorage` stores data that persists even when the browser is closed and reopened.

---

#### **Question 10**  
**Answer**: 1. `true`  
*Explanation*: The `==` operator performs type coercion, so `x == y` evaluates to `true` because both values are considered equal after conversion.

---

#### **Question 11** (Code Completion)  
**Answer**:  
```javascript
function factorial(n) {
    if (n === 0) {
        return 1;
    }
    return n * factorial(n - 1);  // Recursive call
}
```
*Explanation*: The function computes the factorial of a number recursively by multiplying the number with the result of the factorial of one less than the current number.

---

#### **Question 12**  
**Answer**: 2. `1`  
*Explanation*: The `Object.freeze()` method prevents changes to the object. Therefore, the property `a` cannot be modified, and it retains its initial value `1`.

---

#### **Question 13**  
**Answer**: 1. `true`  
*Explanation*: The `&&` (AND) operator returns `true` only if both conditions are true, which they are in this case (`5 > 3` and `3 > 1`).

---

#### **Question 14**  
**Answer**: 1. `true`  
*Explanation*: The `==` operator performs type coercion, so `x == y` evaluates to `true` because both `0` and `"0"` are treated as equivalent.

---

#### **Question 15**  
**Answer**: 4. All of the above  
*Explanation*: All of the mentioned options are valid ways to define anonymous functions in JavaScript.

---

#### **Question 16**  
**Answer**: 1. `split()`  
*Explanation*: The `split()` method is used to convert a string into an array based on a specified delimiter.

---

#### **Question 17**  
**Answer**: 1. Convert a JSON object to a string  
*Explanation*: The `JSON.stringify()` method converts a JavaScript object or value to a JSON string.

---

#### **Question 18**  
**Answer**: 1. `[1, 2, 3]`  
*Explanation*: The `pop()` method removes the last element from an array, which in this case is `4`, leaving `[1, 2, 3]`.

---

#### **Question 19**  
**Answer**: 1. `[0, 1, 2, 3]`  
*Explanation*: The `unshift()` method adds one or more elements to the beginning of an array, so the array becomes `[0, 1, 2, 3]`.

---

#### **Question 20**  
**Answer**: 2. `let myFunc = () => {}`  
*Explanation*: This is the correct syntax for defining an arrow function in JavaScript.

---

#### **Question 21**  
**Answer**: 1. `1`  
*Explanation*: `Object.assign()` creates a shallow copy of the object. Modifying `copy.a` does not affect `obj.a`.

---

#### **Question 22**  
**Answer**: 2. `123.45`  
*Explanation*: `parseFloat()` converts a string to a floating-point number, and since the string `"123.45"` is a valid number, the output is `123.45`.

---

#### **Question 23**  
**Answer**: 2. `{ 0: 1, 1: 2, 2: 3 }`  
*Explanation*: The `arguments` object is an array-like object that contains all the arguments passed to a function. It is not a true array but can be accessed like an array with indexed values.

---

#### **Question 24** (Code Error Identification)  
**Answer**: 2. `y` is undefined  
*Explanation*: The variable `y` is not declared with `let`, `const`, or `var`, so it implicitly becomes a global variable and is technically not a syntax error, but it can lead to unexpected behavior.

---

#### **Question 25**  
**Answer**: 2. `"hello"`  
*Explanation*: Strings in JavaScript are immutable. Trying to change an individual character of a string using indexing will not modify the original string.

---

