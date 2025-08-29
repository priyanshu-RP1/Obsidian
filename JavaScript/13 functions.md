
# 📌 Functions in JavaScript

### 🔹 What is a Function?

- A **function** is a block of code designed to perform a specific task.
    
- Functions help us **reuse code** (write once, use many times).
    
- To use a function:
    
    1. **Define** it
        
    2. **Call/Invoke** it
        

---

### 🔹 Function Syntax

```js
function functionName(parameters) {
    // code to execute
    return value; // (optional)
}
```

---

### 🔹 Example 1: Function with Parameter

```js
function greet(a) {  
    console.log("Namaste", a, "Ji");  
}

let name = prompt("Enter your name cutie");
greet(name); // function call
```

➡️ Here:

- `a` → parameter (input for function).
    
- `greet(name)` → function call (we pass argument `name`).
    

---

### 🔹 Example 2: Function with Return Value

```js
function add(a, b, c) {
    let answer = a + b + c;
    return answer;
}

let x = Number(prompt("Enter first number:"));
let y = Number(prompt("Enter second number:"));
let z = Number(prompt("Enter third number:"));

let result = add(x, y, z); 
console.log(result);
```

➡️ Here:

- `add(a, b, c)` → function definition.
    
- `return answer` → sends result back to where function was called.
    
- `result = add(x, y, z)` → stores returned value in variable.
    

---

### 🔹 Why Functions?

✅ Reusable → write once, call many times  
✅ Organized → breaks program into smaller parts  
✅ Reduces repetition  
✅ Makes debugging easier

---

a short way of writing these fucntions is [[14 Arrow Function]]