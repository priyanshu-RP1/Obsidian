
# 📌 Array Methods in JavaScript

## 🔥 Quick Cheat-Sheet

|Method|Purpose (Short)|
|---|---|
|`push()`|Add element at end|
|`pop()`|Remove element from end|
|`unshift()`|Add element at start|
|`shift()`|Remove element from start|
|`concat()`|Join two arrays|
|`slice()`|Copy part of array (does not modify)|
|`splice()`|Add/remove elements (modifies original)|
|`indexOf()`|First index of element|
|`lastIndexOf()`|Last index of element|
|`includes()`|Check if value exists|
|`forEach()`|Loop through each element|
|`map()`|Create new array with function applied|
|`filter()`|Return elements that pass condition|
|`reduce()`|Reduce array to single value|
|`sort()`|Sort array (custom compare for numbers)|
|`reverse()`|Reverse array order|

---

## 🔎 Detailed Explanations

### 🔹 1. `push()` & `pop()`

- `push()` → adds element at the **end**.
    
- `pop()` → removes element from the **end**.
    

```js
let arr = [1, 2, 3];
arr.push(4);  
console.log(arr); // [1, 2, 3, 4]

arr.pop();  
console.log(arr); // [1, 2, 3]
```

---

### 🔹 2. `unshift()` & `shift()`

- `unshift()` → adds element at the **start**.
    
- `shift()` → removes element from the **start**.
    

```js
let arr = [2, 3];
arr.unshift(1);  
console.log(arr); // [1, 2, 3]

arr.shift();  
console.log(arr); // [2, 3]
```

---

### 🔹 3. `concat()`

- Joins two or more arrays.
    

```js
let a = [1, 2];
let b = [3, 4];
let c = a.concat(b);
console.log(c); // [1, 2, 3, 4]
```

joining 3 or 4 example - 
```javascript
let arr1 = ["apple", "banana"];
let arr2 = ["mango", "orange"];
let arr3 = ["grapes", "kiwi"];

let allFruits = arr1.concat(arr2, arr3);
console.log(allFruits);
// ["apple", "banana", "mango", "orange", "grapes", "kiwi"]
```

---

### 🔹 4. `slice(start, end)`

- Returns a **portion** of the array (end not included).
    
- Does **not** change original array.
    

```js
let arr = [10, 20, 30, 40];
console.log(arr.slice(1, 3)); // [20, 30]
```

---

### 🔹 5. `splice(start, deleteCount, ...items)`

- Adds/removes elements. **Changes original array**.
    

```js
let arr = [1, 2, 3, 4];
arr.splice(1, 2, "x", "y"); 
console.log(arr); // [1, "x", "y", 4]
```

---

### 🔹 6. `indexOf()` & `lastIndexOf()`

- Finds index of element.
    

```js
let arr = ["a", "b", "c", "b"];
console.log(arr.indexOf("b"));      // 1
console.log(arr.lastIndexOf("b"));  // 3
```

---

### 🔹 7. `includes()`

- Checks if value exists → returns `true/false`.
    

```js
let arr = [1, 2, 3];
console.log(arr.includes(2)); // true
```

---

### 🔹 8. `forEach()`

- Runs a function for each element.
    

```js
let arr = [1, 2, 3];
arr.forEach(num => console.log(num * 2));
// 2, 4, 6
```

---

### 🔹 9. `map()`

- Creates a **new array** by applying a function.
    

```js
let arr = [1, 2, 3];
let doubled = arr.map(num => num * 2);
console.log(doubled); // [2, 4, 6]
```

---

### 🔹 10. `filter()`

- Returns new array with only elements that pass condition.
    

```js
let arr = [10, 20, 30, 40];
let big = arr.filter(num => num > 20);
console.log(big); // [30, 40]
```

---

### 🔹 11. `reduce()`

- Reduces array to a single value.
    

```js
let arr = [1, 2, 3, 4];
let sum = arr.reduce((acc, curr) => acc + curr, 0);
console.log(sum); // 10
```

---

### 🔹 12. `sort()`

- Sorts array (as **strings by default**).
    

```js
let arr = [20, 100, 3, 15];
console.log(arr.sort()); // [100, 15, 20, 3] (wrong for numbers!)

console.log(arr.sort((a, b) => a - b)); // [3, 15, 20, 100]
```

---

### 🔹 13. `reverse()`

- Reverses the array order.
    

```js
let arr = [1, 2, 3];
console.log(arr.reverse()); // [3, 2, 1]
```
---
