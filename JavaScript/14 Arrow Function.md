
# 📌 Arrow Functions in JavaScript

### 🔹 What are Arrow Functions?

- A **compact way** to write functions in JavaScript.
    
- Introduced in **ES6**.
    
- Uses the `=>` (fat arrow) syntax.
    
- Makes code **shorter & cleaner**.
    

---

### 🔹 Syntax

```js
// Normal function
function greet(name) {
    console.log("Hello", name);
}

// Arrow function
let greet = (name) => {
    console.log("Hello", name);
};
```

---

### 🔹 Example 1: Arrow Function with One Parameter

```js
var noob = (b) => {
    console.log(b, "is a noob");
};

var name = "ranjan";
noob(name); // Output: ranjan is a noob
```

---

### 🔹 Example 2: Arrow Function with Multiple Parameters

```js
let add = (a, b) => {
    return a + b;
};

console.log(add(5, 10)); // 15
```

---

### 🔹 Example 3: Arrow Function without Parameters

```js
let hello = () => {
    console.log("Hello cutie ❤️");
};

hello(); // Output: Hello cutie ❤️
```

---

### 🔹 Example 4: Single-line Arrow Function (Implicit Return)

- If the function body has only **one line**, you can skip `{}` and `return`.
    

```js
let square = (n) => n * n;

console.log(square(6)); // 36
```

---

### 🔹 Why use Arrow Functions?

✅ Shorter syntax  
✅ Cleaner for simple tasks  
✅ Useful inside array methods (`map`, `filter`, `forEach`)

---
