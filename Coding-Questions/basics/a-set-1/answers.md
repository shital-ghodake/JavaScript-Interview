Here are the answers to the **Basic Coding Questions (Set 1)** for **JavaScript**:

---

### 1. **Write a function to return the sum of two numbers.**
```javascript
function sum(a, b) {
    return a + b;
}
```

---

### 2. **Write a function that takes a number and returns whether it is even or odd.**
```javascript
function isEvenOrOdd(num) {
    return num % 2 === 0 ? 'Even' : 'Odd';
}
```

---

### 3. **Write a function to find the largest of three numbers.**
```javascript
function findLargest(a, b, c) {
    return Math.max(a, b, c);
}
```

---

### 4. **Write a function to check if a string is a palindrome.**
```javascript
function isPalindrome(str) {
    return str === str.split('').reverse().join('');
}
```

---

### 5. **Write a function to reverse a string.**
```javascript
function reverseString(str) {
    return str.split('').reverse().join('');
}
```

---

### 6. **Write a function to count the number of vowels in a string.**
```javascript
function countVowels(str) {
    const vowels = 'aeiouAEIOU';
    return str.split('').filter(char => vowels.includes(char)).length;
}
```

---

### 7. **Write a function to find the factorial of a number.**
```javascript
function factorial(n) {
    if (n === 0 || n === 1) return 1;
    return n * factorial(n - 1);
}
```

---

### 8. **Write a function to calculate the area of a circle.**
```javascript
function areaOfCircle(radius) {
    return Math.PI * Math.pow(radius, 2);
}
```

---

### 9. **Write a function to check if a number is a prime number.**
```javascript
function isPrime(num) {
    if (num < 2) return false;
    for (let i = 2; i < num; i++) {
        if (num % i === 0) return false;
    }
    return true;
}
```

---

### 10. **Write a function to convert a string to uppercase.**
```javascript
function toUpperCase(str) {
    return str.toUpperCase();
}
```

---

### 11. **Write a function to find the square of a number.**
```javascript
function square(num) {
    return num * num;
}
```

---

### 12. **Write a function that returns the sum of an array of numbers.**
```javascript
function sumArray(arr) {
    return arr.reduce((sum, num) => sum + num, 0);
}
```

---

### 13. **Write a function to count how many times a given character appears in a string.**
```javascript
function countCharacter(str, char) {
    return str.split(char).length - 1;
}
```

---

### 14. **Write a function to find the index of the first occurrence of a character in a string.**
```javascript
function indexOfCharacter(str, char) {
    return str.indexOf(char);
}
```

---

### 15. **Write a function to merge two arrays.**
```javascript
function mergeArrays(arr1, arr2) {
    return arr1.concat(arr2);
}
```

---

### 16. **Write a function to remove duplicate values from an array.**
```javascript
function removeDuplicates(arr) {
    return [...new Set(arr)];
}
```

---

### 17. **Write a function to check if an array contains a specific value.**
```javascript
function contains(arr, value) {
    return arr.includes(value);
}
```

---

### 18. **Write a function to sort an array of numbers in ascending order.**
```javascript
function sortArray(arr) {
    return arr.sort((a, b) => a - b);
}
```

---

### 19. **Write a function to generate a random number between two values (inclusive).**
```javascript
function getRandom(min, max) {
    return Math.floor(Math.random() * (max - min + 1)) + min;
}
```

---

### 20. **Write a function to check if an array is empty.**
```javascript
function isArrayEmpty(arr) {
    return arr.length === 0;
}
```

---

### 21. **Write a function to check if a string contains a substring.**
```javascript
function containsSubstring(str, sub) {
    return str.includes(sub);
}
```

---

### 22. **Write a function to find the length of a string without using the `.length` property.**
```javascript
function stringLength(str) {
    return str.split('').reduce(count => count + 1, 0);
}
```

---

### 23. **Write a function to convert a number to a string.**
```javascript
function numberToString(num) {
    return num.toString();
}
```

---

### 24. **Write a function to concatenate two strings.**
```javascript
function concatenateStrings(str1, str2) {
    return str1 + str2;
}
```

---

### 25. **Write a function to find the maximum number in an array.**
```javascript
function findMax(arr) {
    return Math.max(...arr);
}
```

---

