
# 📌 Callback Functions in JavaScript

### 🔹 What is a Callback Function?

- A **callback function** is simply a function that is **passed as an argument** to another function.
    
- The other function can then **call it later** when needed.
    
- It’s called _“callback”_ because the function “calls back” the code you gave it.
    

---

### 🔹 Why do we need Callbacks?

✅ Helps us **reuse functions**  
✅ Used in **asynchronous code** (like `setTimeout`, APIs, file reading)  
✅ Lets us decide _what happens after a task finishes_

---

### 🔹 Example 1: Basic Callback

```js
function greet(name, callback) {
    console.log("Namaste " + name);
    callback(); // calling the function passed as argument
}

function sayBye() {
    console.log("Take care, bye ❤️");
}

greet("Ranjan", sayBye);

// Output:
// Namaste Ranjan
// Take care, bye ❤️
```

➡️ Here:

- `sayBye` is passed as a **callback** into `greet`.
    
- Inside `greet`, `callback()` is executed after greeting.
    

---

### 🔹 Example 2: Callback with Parameters

```js
function calculate(a, b, operation) {
    return operation(a, b); // callback decides the operation
}

function add(x, y) {
    return x + y;
}

function multiply(x, y) {
    return x * y;
}

console.log(calculate(5, 3, add));      // 8
console.log(calculate(5, 3, multiply)); // 15
```

➡️ Here:

- `calculate` is a general function.
    
- The **callback** (`add` or `multiply`) decides _how_ the numbers are handled.
    

---

### 🔹 Example 3: Asynchronous Callback (`setTimeout`)

```js
console.log("Start");

setTimeout(() => {
    console.log("This runs after 2 seconds ⏳");
}, 2000);

console.log("End");

// Output:
// Start
// End
// This runs after 2 seconds ⏳
```

➡️ Here:

- The arrow function inside `setTimeout` is a **callback**.
    
- It runs only **after the timer finishes** (2 seconds).
    

---

### 🔹 Key Points to Remember

- A **callback** is just a function passed into another function.
    
- Useful in **asynchronous operations** (timers, fetching data, events).
    
- Helps in writing **flexible functions** (like `calculate` example).
    

---
