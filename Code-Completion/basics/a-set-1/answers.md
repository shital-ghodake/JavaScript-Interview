Here are the answers for the **JavaScript Code Completion Questions (Basic Level)**:

---

#### 1. **Complete the function to return the sum of two numbers:**
```javascript
function sum(a, b) {
    return a + b;
}
console.log(sum(2, 3)); // Expected output: 5
```
**Answer:** A) `return a + b`

---

#### 2. **Complete the function to check if a number is even:**
```javascript
function isEven(num) {
    return num % 2 === 0;
}
console.log(isEven(4)); // Expected output: true
console.log(isEven(7)); // Expected output: false
```
**Answer:** A) `return num % 2 === 0`

---

#### 3. **Complete the function to concatenate two strings:**
```javascript
function concatenate(str1, str2) {
    return str1 + " " + str2;
}
console.log(concatenate("Hello", " World")); // Expected output: "Hello World"
```
**Answer:** A) `return str1 + " " + str2`

---

#### 4. **Complete the function to find the maximum number in an array:**
```javascript
function findMax(arr) {
    return Math.max(...arr);
}
console.log(findMax([1, 2, 3, 4, 5])); // Expected output: 5
```
**Answer:** A) `return Math.max(...arr)`

---

#### 5. **Complete the function to count the number of vowels in a string:**
```javascript
function countVowels(str) {
    let count = 0;
    for (let i = 0; i < str.length; i++) {
        if (str[i] === "a" || str[i] === "e" || str[i] === "i" || str[i] === "o" || str[i] === "u") {
            count++;
        }
    }
    return count;
}
console.log(countVowels("Hello World")); // Expected output: 3
```
**Answer:** A) `str[i] === "a" || str[i] === "e" || str[i] === "i" || str[i] === "o" || str[i] === "u"`

---

#### 6. **Complete the function to reverse a string:**
```javascript
function reverseString(str) {
    return str.split("").reverse().join("");
}
console.log(reverseString("JavaScript")); // Expected output: "tpircSavaJ"
```
**Answer:** A) `return str.split("").reverse().join("")`

---

#### 7. **Complete the function to return a string in uppercase:**
```javascript
function toUpperCase(str) {
    return str.toUpperCase();
}
console.log(toUpperCase("hello")); // Expected output: "HELLO"
```
**Answer:** A) `return str.toUpperCase()`

---

#### 8. **Complete the function to find the length of a string:**
```javascript
function stringLength(str) {
    return str.length;
}
console.log(stringLength("Hello")); // Expected output: 5
```
**Answer:** A) `return str.length`

---

#### 9. **Complete the function to check if a string is a palindrome:**
```javascript
function isPalindrome(str) {
    let reversed = str.split("").reverse().join("");
    return str === reversed;
}
console.log(isPalindrome("racecar")); // Expected output: true
console.log(isPalindrome("hello")); // Expected output: false
```
**Answer:** A) `return str === reversed`

---

#### 10. **Complete the function to sum all elements in an array:**
```javascript
function sumArray(arr) {
    return arr.reduce((acc, val) => acc + val, 0);
}
console.log(sumArray([1, 2, 3, 4])); // Expected output: 10
```
**Answer:** A) `0`

---

#### 11. **Complete the function to return the first element of an array:**
```javascript
function firstElement(arr) {
    return arr[0];
}
console.log(firstElement([1, 2, 3, 4])); // Expected output: 1
```
**Answer:** A) `return arr[0]`

---

#### 12. **Complete the function to remove duplicates from an array:**
```javascript
function removeDuplicates(arr) {
    return Array.from(new Set(arr));
}
console.log(removeDuplicates([1, 2, 2, 3, 4, 4])); // Expected output: [1, 2, 3, 4]
```
**Answer:** A) `Array.from(new Set(arr))`

---

#### 13. **Complete the function to find if a number exists in an array:**
```javascript
function contains(arr, num) {
    return arr.indexOf(num) !== -1;
}
console.log(contains([1, 2, 3], 2)); // Expected output: true
console.log(contains([1, 2, 3], 4)); // Expected output: false
```
**Answer:** A) `return arr.indexOf(num) !== -1`

---

#### 14. **Complete the function to get the second-largest number from an array:**
```javascript
function secondLargest(arr) {
    arr.sort((a, b) => b - a);
    return arr[1];
}
console.log(secondLargest([1, 2, 3, 4, 5])); // Expected output: 4
```
**Answer:** A) `return arr[1]`

---

#### 15. **Complete the function to find the index of a value in a string:**
```javascript
function findIndex(str, char) {
    return str.indexOf(char);
}
console.log(findIndex("hello", "e")); // Expected output: 1
```
**Answer:** A) `return str.indexOf(char)`

---

#### 16. **Complete the function to convert a number to a string:**
```javascript
function numberToString(num) {
    return num.toString();
}
console.log(numberToString(123)); // Expected output: "123"
```
**Answer:** A) `return num.toString()`

---

#### 17. **Complete the function to convert a string into an array of characters:**
```javascript
function stringToArray(str) {
    return str.split('');
}
console.log(stringToArray("hello")); // Expected output: ['h', 'e', 'l', 'l', 'o']
```
**Answer:** A) `return str.split('')`

---

#### 18. **Complete the function to find if a number is prime:**
```javascript
function isPrime(num) {
    for (let i = 2; i < num; i++) {
        if (num % i === 0) return false;
    }
    return num > 1;
}
console.log(isPrime(5)); // Expected output: true
console.log(isPrime(4)); // Expected output: false
```
**Answer:** A) `if (num % i === 0) return false`

---

#### 19. **Complete the function to flatten an array of arrays:**
```javascript
function flattenArray(arr) {
    return arr.reduce((acc, val) => acc.concat(val), []);
}
console.log(flattenArray([[1, 2], [3, 4], [5, 6]])); // Expected output: [1, 2, 3, 4, 5, 6]
```
**Answer:** A) `[]`

---

#### 20. **Complete the function to check if a string starts with a certain character:**
```javascript
function startsWith(str, char) {
    return str.charAt(0) === char;
}
console.log(startsWith("hello", "h")); // Expected output: true
console.log(startsWith("world", "w")); // Expected output: true
```
**Answer:** A) `return str.charAt(0) === char`

---

These are the answers to the code completion questions. Let me know if you need further clarification or more questions!
