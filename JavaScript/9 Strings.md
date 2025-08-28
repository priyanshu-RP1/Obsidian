
# 📌 Strings in JavaScript

### 🔹 What is a String?

- A **string** is a sequence of characters used to represent text.
    
- In JS, you can create strings using **single quotes (`'`)**, **double quotes (`"`)**, or **template literals (`` ` ``).**
    

```js
let str1 = "Hello World";
let str2 = 'JavaScript is fun';
let name = `Priyanshu Ranjan`; // template literal
```

---
### 🔹 Template Literals

- Introduced in **ES6**.
    
- Allow **string interpolation** (inserting variables directly).
    
- Use **backticks (`` ` ``)**.
    

```js
let name = "Priyanshu Ranjan";
console.log(`Hello ${name}, how are you?`);
```

---

### 🔹 String Length

- `.length` property gives the total number of characters in a string.
    

```js
let msg = "kaise ho bhai";
console.log(msg.length); // 13
```

---

### 🔹 String Indexing

- Strings are **indexed (0-based)** like arrays.
    
- You can access characters using `[]`.
    

```js
let str = "o bhai ye kya ho";
console.log(str[0]); // 'o'
console.log(str[7]); // 'y'
```

---

next is [[10 String Methods]]