
# 📌 String Methods in JavaScript

### 🔹 1. `toUpperCase()` & `toLowerCase()`

- Changes the case of letters.
    

```js
let str = "Hello World";
console.log(str.toUpperCase()); // "HELLO WORLD"
console.log(str.toLowerCase()); // "hello world"
```

---

### 🔹 2. `trim()`

- Removes spaces from **both ends** of a string.
    

```js
let str = "   Ranjan   ";
console.log(str.trim()); // "Ranjan"
```

---

### 🔹 3. `slice(start, end)`

- Extracts part of a string.
    
- `end` is not included.
    

```js
let str = "Priyanshu";
console.log(str.slice(0, 4)); // "Priy"
console.log(str.slice(4));    // "anshu"
```

---

### 🔹 4. `substring(start, end)`

- Similar to `slice`, but does not allow negative indexes.
    

```js
let str = "JavaScript";
console.log(str.substring(0, 4)); // "Java"
```

---

### 🔹 5. `replace(old, new)`

- Replaces the first occurrence of a value.
    

```js
let str = "Hello bro";
console.log(str.replace("bro", "bhai")); // "Hello bhai"
```

---

### 🔹 6. `replaceAll(old, new)`

- Replaces **all** occurrences of a value.
    

```js
let str = "ha ha ha";
console.log(str.replaceAll("ha", "he")); // "he he he"
```

---

### 🔹 7. `concat()`

- Joins two or more strings.
    

```js
let str1 = "Hello";
let str2 = "World";
console.log(str1.concat(" ", str2)); // "Hello World"
```

---

### 🔹 8. `charAt(index)` & `charCodeAt(index)`

- Get character or ASCII code at a position.
    

```js
let str = "ABC";
console.log(str.charAt(1));     // "B"
console.log(str.charCodeAt(1)); // 66
```

---

### 🔹 9. `indexOf(value)` & `lastIndexOf(value)`

- Finds position of first/last occurrence.
    

```js
let str = "hello hello";
console.log(str.indexOf("lo"));     // 3
console.log(str.lastIndexOf("lo")); // 9
```

---

### 🔹 10. `includes(value)`

- Checks if a string contains a value. Returns `true/false`.
    

```js
let str = "JavaScript is fun";
console.log(str.includes("fun"));  // true
console.log(str.includes("hard")); // false
```

---

### 🔹 11. `split(separator)`

- Splits a string into an array.
    

```js
let str = "a,b,c,d";
console.log(str.split(",")); // ["a", "b", "c", "d"]
```

---

### 🔹 12. `repeat(n)`

- Repeats a string **n times**.
    

```js
let str = "ha ";
console.log(str.repeat(3)); // "ha ha ha "
```

---
