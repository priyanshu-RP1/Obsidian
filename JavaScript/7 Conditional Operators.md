
# 🌟 Conditional Statements in JavaScript


- Conditional statements are used to **make decisions** in code.
    
- They allow your program to **execute certain code only if a condition is true**.  
    👉 Think of them like **traffic signals 🚦**:
    
- Green → go one way
    
- Red → stop or choose another path
    

---

## 🔥 Types of Conditional Statements

### 1️⃣ if Statement

Runs a block of code **only if the condition is true**.

```js
let age = 18;

if (age >= 18) {
  console.log("You are an adult 💕");
}
```

Output:  
You are an adult 💕

---

### 2️⃣ if...else Statement

If condition is true → run first block.  
If false → run the `else` block.

```js
let age = 16;

if (age >= 18) {
  console.log("You are an adult 💕");
} else {
  console.log("You are a minor 🍼");
}
```

Output:  
You are a minor 🍼

---

### 3️⃣ if...else if...else Statement

Used when we have **multiple conditions**.

```js
let marks = 75;

if (marks >= 90) {
  console.log("Grade: A+ 🌟");
} else if (marks >= 75) {
  console.log("Grade: A 😍");
} else if (marks >= 50) {
  console.log("Grade: B 🙂");
} else {
  console.log("Grade: F ❌");
}
```

Output:  
Grade: A 😍

---

### 4️⃣ switch Statement

Used when we want to check a variable against **multiple possible values**.  
Cleaner than multiple `if...else if`.

```js
let day = 3;

switch (day) {
  case 1:
    console.log("Monday 🌸");
    break;
  case 2:
    console.log("Tuesday 🌼");
    break;
  case 3:
    console.log("Wednesday 🌈");
    break;
  default:
    console.log("Invalid day ❌");
}
```

Output:  
Wednesday 🌈

---

### 5️⃣ Ternary Operator (Short If-Else)

Shorthand way of writing simple conditions.

```js
let age = 20;
let result = (age >= 18) ? "Adult ✅" : "Minor ❌";
console.log(result);
```

Output:  
Adult ✅

---

## 🌟 Summary

- **if** → checks one condition
    
- **if...else** → two-way choice
    
- **if...else if...else** → multiple conditions
    
- **switch** → many values (cleaner than multiple ifs)
    
- **ternary** → short if-else
    

👉 Conditional statements are the **decision makers** of programs 💡

---
