
---

# 🌸 Variables in JavaScript  

## 📝 What are Variables?  
- A **variable** is like a **box** 📦 where we store information (data) to use later in our program.  
- Instead of repeating values again & again, we store them in variables and use the variable name.  

✨ Example:  
```js
let name = "Ranjan";  
console.log(name);  


👉 Output:

```
Ranjan
```

---

## 🔑 Ways to Declare Variables

JavaScript gives us **3 keywords** to declare variables:

### 1️⃣ `var` (Old Way ❌ - mostly avoided now)

- Introduced in early JavaScript.
    
- Problem: variables declared with `var` are **function-scoped** (can cause bugs).
    
- Avoid using it in modern code.
    

```js
var age = 20;  
console.log(age);
```

---

### 2️⃣ `let` (Modern Way ✅)

- **Block-scoped** (works only inside `{ }`).
    
- Value **can be changed** later.
    

```js
let city = "Delhi";  
console.log(city);  

city = "Bangalore"; // reassigned  
console.log(city);  
```

👉 Output:

```
Delhi  
Bangalore
```

---

### 3️⃣ `const` (Constant ✅)

- **Block-scoped** like `let`.
    
- Value **cannot be changed** once assigned.
    

```js
const pi = 3.14;  
console.log(pi);  

// pi = 4; ❌ Error → Assignment to constant variable not allowed
```

---

## ⚖️ Difference Between `var`, `let`, and `const`

|Feature|var|let|const|
|---|---|---|---|
|Scope|Function|Block|Block|
|Redeclare|✅ Yes|❌ No|❌ No|
|Reassign|✅ Yes|✅ Yes|❌ No|
|Hoisting|✅ Yes|❌ No|❌ No|

---

## 🎀 Variable Naming Rules

When naming variables, follow these rules:  
✅ Allowed:

- Must **start with a letter, underscore `_`, or dollar `$`**
    
- Can contain numbers (but not at the start)
    
- Case-sensitive (`name` and `Name` are different)
    

❌ Not Allowed:

- Cannot use spaces
    
- Cannot use reserved keywords (`let`, `for`, `if`, etc.)
    

✨ Examples:

```js
let firstName = "Ranjan";  // ✅ Good
let _score = 100;          // ✅ Good
let $price = 99;           // ✅ Good
let 1user = "wrong";       // ❌ Error
```

---

## 💡 Why Do We Need Variables?

- Store user input
    
- Store results of calculations
    
- Make code reusable and easier to read
    
- Control flow of data in apps
    

---
