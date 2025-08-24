

# 🖨️ Input & Output in JavaScript

## 📝 Definition

- **Output** → displaying data to the user.
    
- **Input** → receiving data from the user.
    

👉 Think of it like **talking with a friend**:

- You 🗣️ (output) → show/print something.
    
- Your friend 👂 (input) → replies with their answer.
    

---

## 🔥 Output in JavaScript

### 1️⃣ `console.log()`

- Prints messages in the **browser console** (mainly for developers).
    

```js
console.log("Hello Ranjan 💕");
console.log(10 + 5);
```

Output (in console):  
Hello Ranjan 💕  
15

---

### 2️⃣ `alert()`

- Shows a **popup box** with a message.
    

```js
alert("Welcome cutie 🌸");
```

---

### 3️⃣ `document.write()`

- Prints directly on the **webpage**.
    

```js
document.write("This is on the page ✨");
```

---

## 🔥 Input in JavaScript

### 1️⃣ `prompt()`

- Takes input from the user using a popup box.
    

```js
let name = prompt("Enter your name:");
console.log("Hello " + name + " 💖");
```

If user enters: `Ranjan`  
Output:  
Hello Ranjan 💖

---

### 2️⃣ `confirm()`

- Asks user to **confirm or cancel** (returns true/false).
    

```js
let isOk = confirm("Do you want to continue?");
console.log(isOk);
```

If user clicks OK → `true`  
If user clicks Cancel → `false`

---

## ⚡ Input always comes as String

- When using `prompt()`, the value is always **string**.
    
- To convert:
    
    - `Number(value)` → number
        
    - `parseInt(value)` → integer
        
    - `parseFloat(value)` → decimal
        

```js
let num1 = Number(prompt("Enter first number:"));
let num2 = Number(prompt("Enter second number:"));
console.log("Sum = " + (num1 + num2));
```

---

## 🌟 Summary

- **Output** → `console.log()`, `alert()`, `document.write()`
    
- **Input** → `prompt()`, `confirm()`
    
- Input from prompt is **string** → convert to number if needed
    
- Used for **interaction between user and program** 💕
    
---
