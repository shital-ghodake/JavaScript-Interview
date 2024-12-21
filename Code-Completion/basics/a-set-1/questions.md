Sure! Here’s a set of **JavaScript code completion questions** starting with basic topics.
These will test your knowledge of syntax, logic, and practical JavaScript usage.

---

### **JavaScript Code Completion Questions (Basic Level)**

---

#### 1. **Complete the function to return the sum of two numbers:**

```javascript
function sum(a, b) {
    ________;
}
console.log(sum(2, 3)); // Expected output: 5
```
- A) `return a + b`
- B) `return a - b`
- C) `return a * b`
- D) `return a / b`

---

#### 2. **Complete the function to check if a number is even:**

```javascript
function isEven(num) {
    ________;
}
console.log(isEven(4)); // Expected output: true
console.log(isEven(7)); // Expected output: false
```
- A) `return num % 2 === 0`
- B) `return num % 2 === 1`
- C) `return num % 2 != 0`
- D) `return num % 2 === 2`

---

#### 3. **Complete the function to concatenate two strings:**

```javascript
function concatenate(str1, str2) {
    ________;
}
console.log(concatenate("Hello", " World")); // Expected output: "Hello World"
```
- A) `return str1 + " " + str2`
- B) `return str1 + str2`
- C) `return str1 - str2`
- D) `return str1 * str2`

---

#### 4. **Complete the function to find the maximum number in an array:**

```javascript
function findMax(arr) {
    ________;
}
console.log(findMax([1, 2, 3, 4, 5])); // Expected output: 5
```
- A) `return Math.max(...arr)`
- B) `return arr.sort()[arr.length - 1]`
- C) `return arr[0]`
- D) `return arr[0] + arr[1]`

---

#### 5. **Complete the function to count the number of vowels in a string:**

```javascript
function countVowels(str) {
    let count = 0;
    for (let i = 0; i < str.length; i++) {
        if (str[i] ________) {
            count++;
        }
    }
    return count;
}
console.log(countVowels("Hello World")); // Expected output: 3
```
- A) `str[i] === "a" || str[i] === "e" || str[i] === "i" || str[i] === "o" || str[i] === "u"`
- B) `str[i] === "a" || str[i] === "b"`
- C) `str[i] === "a" || str[i] === "b" || str[i] === "c"`
- D) `str[i] === "v" || str[i] === "w"`

---

#### 6. **Complete the function to reverse a string:**

```javascript
function reverseString(str) {
    ________;
}
console.log(reverseString("JavaScript")); // Expected output: "tpircSavaJ"
```
- A) `return str.split("").reverse().join("")`
- B) `return str.reverse()`
- C) `return str.split("").join("")`
- D) `return str.reverse().split("")`

---

#### 7. **Complete the function to return a string in uppercase:**

```javascript
function toUpperCase(str) {
    ________;
}
console.log(toUpperCase("hello")); // Expected output: "HELLO"
```
- A) `return str.toUpperCase()`
- B) `return str.toLowerCase()`
- C) `return str.split("").reverse().join("")`
- D) `return str.charAt().toUpperCase()`

---

#### 8. **Complete the function to find the length of a string:**

```javascript
function stringLength(str) {
    ________;
}
console.log(stringLength("Hello")); // Expected output: 5
```
- A) `return str.length`
- B) `return str.length()`
- C) `return str.size`
- D) `return str.charCodeAt()`

---

#### 9. **Complete the function to check if a string is a palindrome:**

```javascript
function isPalindrome(str) {
    let reversed = str.split("").reverse().join("");
    ________;
}
console.log(isPalindrome("racecar")); // Expected output: true
console.log(isPalindrome("hello")); // Expected output: false
```
- A) `return str === reversed`
- B) `return reversed === "racecar"`
- C) `return str === "hello"`
- D) `return str !== reversed`

---

#### 10. **Complete the function to sum all elements in an array:**

```javascript
function sumArray(arr) {
    return arr.reduce((acc, val) => acc + val, ________);
}
console.log(sumArray([1, 2, 3, 4])); // Expected output: 10
```
- A) `0`
- B) `1`
- C) `[]`
- D) `""`

---

#### 11. **Complete the function to return the first element of an array:**

```javascript
function firstElement(arr) {
    ________;
}
console.log(firstElement([1, 2, 3, 4])); // Expected output: 1
```
- A) `return arr[0]`
- B) `return arr.slice(0, 1)`
- C) `return arr[1]`
- D) `return arr.pop()`

---

#### 12. **Complete the function to remove duplicates from an array:**

```javascript
function removeDuplicates(arr) {
    return ________;
}
console.log(removeDuplicates([1, 2, 2, 3, 4, 4])); // Expected output: [1, 2, 3, 4]
```
- A) `Array.from(new Set(arr))`
- B) `arr.filter((item, index) => arr.indexOf(item) === index)`
- C) `arr.unique()`
- D) `arr.map((item, index) => item)`

---

#### 13. **Complete the function to find if a number exists in an array:**

```javascript
function contains(arr, num) {
    ________;
}
console.log(contains([1, 2, 3], 2)); // Expected output: true
console.log(contains([1, 2, 3], 4)); // Expected output: false
```
- A) `return arr.indexOf(num) !== -1`
- B) `return arr.includes(num)`
- C) `return arr.indexOf(num) === -1`
- D) `return arr.contains(num)`

---

#### 14. **Complete the function to get the second-largest number from an array:**

```javascript
function secondLargest(arr) {
    arr.sort((a, b) => b - a);
    ________;
}
console.log(secondLargest([1, 2, 3, 4, 5])); // Expected output: 4
```
- A) `return arr[1]`
- B) `return arr[arr.length - 2]`
- C) `return arr[0]`
- D) `return arr.pop()`

---

#### 15. **Complete the function to find the index of a value in a string:**

```javascript
function findIndex(str, char) {
    ________;
}
console.log(findIndex("hello", "e")); // Expected output: 1
```
- A) `return str.indexOf(char)`
- B) `return str.lastIndexOf(char)`
- C) `return str.search(char)`
- D) `return str.find(char)`

---

#### 16. **Complete the function to convert a number to a string:**

```javascript
function numberToString(num) {
    ________;
}
console.log(numberToString(123)); // Expected output: "123"
```
- A) `return num.toString()`
- B) `return String(num)`
- C) `return num + ""`
- D) `return num.toString(10)`

---

#### 17. **Complete the function to convert a string into an array of characters:**

```javascript
function stringToArray(str) {
    ________;
}
console.log(stringToArray("hello")); // Expected output: ['h', 'e', 'l', 'l', 'o']
```
- A) `return str.split('')`
- B) `return [...str]`
- C) `return str.split(' ')`
- D) `return Array.from(str)`

---

#### 18. **Complete the function to find if a number is prime:**

```javascript
function isPrime(num) {
    for (let i = 2; i < num; i++) {
        ________;
    }
    return num > 1;
}
console.log(isPrime(5)); // Expected output: true
console.log(isPrime(4)); // Expected output: false
```
- A) `if (num % i === 0) return false`
- B) `if (num / i === 0) return true`
- C) `if (i % num === 0) return true`
- D) `if (num % i !== 0) return false`

---

#### 19. **Complete the function to flatten an array of arrays:**

```javascript
function flattenArray(arr) {
    return arr.reduce((acc, val) => acc.concat(val), ________);
}
console.log(flattenArray([[1, 2], [3, 4], [5, 6]])); // Expected output: [1, 2, 3, 4, 5, 6]
```
- A) `[]`
- B) `0`
- C) `""`
- D) `null`

---

#### 20. **Complete the function to check if a string starts with a certain character:**

```javascript
function startsWith(str, char) {
    ________;
}
console.log(startsWith("hello", "h")); // Expected output: true
console.log(startsWith("world", "w")); // Expected output: true
```
- A) `return str.charAt(0) === char`
- B) `return str.indexOf(char) === 0`
- C) `return str.startsWith(char)`
- D) `return str[0] === char`

---

