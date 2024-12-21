Here is the next set of **JavaScript Code Completion Questions** for **Intermediate Level**:

---

### 21. **Complete the function to merge two arrays:**
```javascript
function mergeArrays(arr1, arr2) {
    return [...arr1, ...arr2];
}
console.log(mergeArrays([1, 2], [3, 4])); // Expected output: [1, 2, 3, 4]
```

---

### 22. **Complete the function to check if a string contains a specific substring:**
```javascript
function containsSubstring(str, sub) {
    return str.includes(sub);
}
console.log(containsSubstring("JavaScript", "Script")); // Expected output: true
console.log(containsSubstring("JavaScript", "Python")); // Expected output: false
```

---

### 23. **Complete the function to find the factorial of a number:**
```javascript
function factorial(num) {
    if (num === 0 || num === 1) return 1;
    return num * factorial(num - 1);
}
console.log(factorial(5)); // Expected output: 120
```

---

### 24. **Complete the function to check if an object is empty:**
```javascript
function isEmpty(obj) {
    return Object.keys(obj).length === 0;
}
console.log(isEmpty({})); // Expected output: true
console.log(isEmpty({ name: "John" })); // Expected output: false
```

---

### 25. **Complete the function to count occurrences of a character in a string:**
```javascript
function countOccurrences(str, char) {
    return str.split(char).length - 1;
}
console.log(countOccurrences("hello", "l")); // Expected output: 2
```

---

### 26. **Complete the function to find the intersection of two arrays:**
```javascript
function intersect(arr1, arr2) {
    return arr1.filter(value => arr2.includes(value));
}
console.log(intersect([1, 2, 3], [3, 4, 5])); // Expected output: [3]
```

---

### 27. **Complete the function to check if an array is sorted in ascending order:**
```javascript
function isSorted(arr) {
    for (let i = 0; i < arr.length - 1; i++) {
        if (arr[i] > arr[i + 1]) return false;
    }
    return true;
}
console.log(isSorted([1, 2, 3])); // Expected output: true
console.log(isSorted([3, 2, 1])); // Expected output: false
```

---

### 28. **Complete the function to remove falsy values from an array:**
```javascript
function removeFalsyValues(arr) {
    return arr.filter(Boolean);
}
console.log(removeFalsyValues([0, 1, false, 2, '', 3])); // Expected output: [1, 2, 3]
```

---

### 29. **Complete the function to check if a number is an integer:**
```javascript
function isInteger(num) {
    return Number.isInteger(num);
}
console.log(isInteger(4)); // Expected output: true
console.log(isInteger(4.5)); // Expected output: false
```

---

### 30. **Complete the function to get a random number between two values:**
```javascript
function getRandomBetween(min, max) {
    return Math.floor(Math.random() * (max - min + 1)) + min;
}
console.log(getRandomBetween(1, 10)); // Expected output: Random number between 1 and 10
```

---

### 31. **Complete the function to find the index of a number in an array:**
```javascript
function findIndexOfNumber(arr, num) {
    return arr.indexOf(num);
}
console.log(findIndexOfNumber([1, 2, 3], 2)); // Expected output: 1
```

---

### 32. **Complete the function to add a property to an object:**
```javascript
function addProperty(obj, key, value) {
    obj[key] = value;
    return obj;
}
console.log(addProperty({ name: "John" }, "age", 30)); // Expected output: { name: "John", age: 30 }
```

---

### 33. **Complete the function to find the common values between two arrays:**
```javascript
function commonValues(arr1, arr2) {
    return arr1.filter(value => arr2.includes(value));
}
console.log(commonValues([1, 2, 3], [2, 3, 4])); // Expected output: [2, 3]
```

---

### 34. **Complete the function to find the longest string in an array:**
```javascript
function longestString(arr) {
    return arr.reduce((a, b) => a.length > b.length ? a : b);
}
console.log(longestString(["apple", "banana", "cherry"])); // Expected output: "banana"
```

---

### 35. **Complete the function to find if a value is an array:**
```javascript
function isArray(value) {
    return Array.isArray(value);
}
console.log(isArray([1, 2, 3])); // Expected output: true
console.log(isArray("hello")); // Expected output: false
```

---

### 36. **Complete the function to remove a specific value from an array:**
```javascript
function removeValue(arr, val) {
    return arr.filter(item => item !== val);
}
console.log(removeValue([1, 2, 3, 4], 3)); // Expected output: [1, 2, 4]
```

---

### 37. **Complete the function to return the second smallest number in an array:**
```javascript
function secondSmallest(arr) {
    arr.sort((a, b) => a - b);
    return arr[1];
}
console.log(secondSmallest([10, 5, 20, 8])); // Expected output: 8
```

---

### 38. **Complete the function to find if an object has a specific property:**
```javascript
function hasProperty(obj, prop) {
    return obj.hasOwnProperty(prop);
}
console.log(hasProperty({ name: "John" }, "name")); // Expected output: true
console.log(hasProperty({ name: "John" }, "age")); // Expected output: false
```

---

### 39. **Complete the function to square all numbers in an array:**
```javascript
function squareArray(arr) {
    return arr.map(num => num * num);
}
console.log(squareArray([1, 2, 3])); // Expected output: [1, 4, 9]
```

---

### 40. **Complete the function to find the largest number in an array:**
```javascript
function findLargest(arr) {
    return Math.max(...arr);
}
console.log(findLargest([1, 2, 3, 4, 5])); // Expected output: 5
```

---

