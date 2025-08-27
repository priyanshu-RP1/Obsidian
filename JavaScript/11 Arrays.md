
# 📌 Arrays in JavaScript

### 🔹 What is an Array?

- An **array** is a special type of object in JavaScript that stores **multiple values** in a single variable.
    
- Arrays are created using **square brackets `[]`**.
    

```js
let student = ["Ranjan", "Hemraj", "Prithak", "Ksirsh", "Noob Dragon"];
```

---

### 🔹 Accessing Elements (Indexing)

- Array indexing starts from **0**.
    
- Use `[index]` to access elements.
    

```js
console.log(student[0]); // "Ranjan"
console.log(student[1]); // "Hemraj"
```

---

### 🔹 Array Length

- `.length` gives the total number of elements.
    

```js
console.log(student.length); // 5
```

---

### 🔹 Printing Arrays

```js
console.log(student); // prints the whole array
```

---

### ❓ Q1: Print all student names

```js
for (let i = 0; i < student.length; i++) {
    console.log(student[i]);
}
```

---

### ❓ Q2: Print a specific student (example: 2nd student)

```js
console.log(student[1]); // Hemraj
```

---

next is [[JavaScript/12 Array Methods|12 Array Methods]]
