### **Answers for JavaScript Basics - MCQ Set 3**

Here are the answers to the questions from Set 3, along with explanations:

---

#### **Question 1**  
**Answer**: 2. `"undefined", "object"`  
*Explanation*: `typeof undefined` is `"undefined"`, while `typeof null` is `"object"` due to a legacy quirk in JavaScript.

---

#### **Question 2**  
**Answer**: 1, 2, 3  
*Explanation*: `false`, `""`, and `0` are falsy values in JavaScript. `"false"` is a truthy string.

---

#### **Question 3**  
**Answer**: 1. `true`  
*Explanation*: The variable `x` is `undefined`, and the strict equality check (`===`) confirms it.

---

#### **Question 4**  
**Answer**: 1, 2, 3  
*Explanation*: All options convert a number to a string except `Number.toString(num)` (invalid syntax).

---

#### **Question 5**  
**Answer**: 3. `5`  
*Explanation*: The `-` operator converts `"10"` to a number and performs subtraction.

---

#### **Question 6**  
**Answer**:  
```javascript
return n * factorial(n - 1);
```

---

#### **Question 7**  
**Answer**: 1. `{ a: 1, b: 2 }`  
*Explanation*: `Object.freeze()` prevents adding new properties to the object.

---

#### **Question 8**  
**Answer**: 1, 2, 3  
*Explanation*: `let`, `const`, arrow functions, and template literals are ES6 features. `var` is pre-ES6.

---

#### **Question 9**  
**Answer**: 2. `false`  
*Explanation*: Strict equality (`===`) checks for both value and type. `10` (number) is not equal to `"10"` (string).

---

#### **Question 10**  
**Answer**: 1, 3  
*Explanation*: `concat()` and the spread operator (`...`) merge arrays. `push()` and `splice()` modify arrays but do not merge them.

---

#### **Question 11**  
**Answer**: 2. `[10, undefined, 30]`  
*Explanation*: The `delete` operator removes the element but leaves a hole (undefined) in the array.

---

#### **Question 12**  
**Answer**: 2. `false`  
*Explanation*: The empty string `""` is falsy, so `!!""` evaluates to `false`.

---

#### **Question 13**  
**Answer**: 1. `6, 5`  
*Explanation*: The `a++` operator increments `a` after its current value (`5`) is assigned to `b`.

---

#### **Question 14**  
**Answer**: 1. Syntax error: variable redeclaration.  
*Explanation*: A `const` variable cannot be declared with the same name as an existing `let` variable in the same scope.

---

#### **Question 15**  
**Answer**:  
```javascript
if (vowels.includes(char)) {
    count++;
}
```

---

#### **Question 16**  
**Answer**: 1, 2, 3  
*Explanation*: JSON supports `String`, `Number`, and `Boolean` data types, but not `Function`.

---

#### **Question 17**  
**Answer**: 2. `[1, 2, 4]`  
*Explanation*: `splice(2, 1)` removes one element at index 2.

---

#### **Question 18**  
**Answer**: 2. Combine all elements of an array into a single value.  
*Explanation*: `reduce()` iterates over an array and applies a reducer function to accumulate a single result.

---

#### **Question 19**  
**Answer**: 2. `6`  
*Explanation*: The array length becomes `6` because setting `arr[5]` creates empty slots for indexes `3` and `4`.

---

#### **Question 20**  
**Answer**: 1, 2, 3  
*Explanation*: `Object.assign()`, the spread operator, and `JSON.parse(JSON.stringify())` create copies of objects. `obj.clone()` is invalid.

---

#### **Question 21**  
**Answer**: 1. `true`  
*Explanation*: Both `NaN` and `Infinity` are of type `number`.

---

#### **Question 22**  
**Answer**: 3. Returns `undefined` due to automatic semicolon insertion.  
*Explanation*: The `return` statement is automatically terminated due to a line break, so the object is not returned.

---

#### **Question 23**  
**Answer**: 1. `10`  
*Explanation*: The `*` operator converts `"5"` to a number and performs multiplication.

---

#### **Question 24**  
**Answer**: 1, 2, 3  
*Explanation*: `Object.keys()`, `Object.values()`, and `Object.entries()` are valid methods to iterate over object properties. `Object.forEach()` does not exist.

---

#### **Question 25**  
**Answer**: 2. `true, false`  
*Explanation*: `1 < 2 < 3` is `true` because `true < 3` evaluates as `1 < 3`. However, `3 > 2 > 1` is `false` because `true > 1` evaluates as `1 > 1`.

---

