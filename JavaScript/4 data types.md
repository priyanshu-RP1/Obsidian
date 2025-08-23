

# 🌈 JavaScript Data Types  

## 📝 What are Data Types?  
- A **data type** tells us what kind of value is stored in a variable.  
- Example: storing numbers, text, true/false values, etc.  

👉 Think of variables as **boxes 📦** and data types as the **kind of thing inside the box** (toys, clothes, books).  

---

## 🔥 Types of Data in JavaScript  

### 1️⃣ Primitive Data Types (basic, single value)  
Primitive = **small & simple data types**. They are **immutable** (cannot be changed directly).  

#### 🔹 Number  
For numbers (integers & decimals).  
```js
let age = 21;  
let pi = 3.14;  


#### 🔹 String

For text (inside quotes `" "` or `' '`).

```js
let name = "Ranjan";  
let city = 'Delhi';  
```

#### 🔹 Boolean

True/false values.

```js
let isMarried = false;  
let isStudent = true;  
```

#### 🔹 Undefined

Variable declared but **no value assigned**.

```js
let x;  
console.log(x); // undefined
```

#### 🔹 Null

Intentionally empty value (nothing).

```js
let data = null;  
```

#### 🔹 Symbol (ES6)

Unique value (used in special cases like object keys).

```js
let id1 = Symbol("id");  
let id2 = Symbol("id");  
console.log(id1 === id2); // false (always unique)
```

#### 🔹 BigInt (ES11)

For very large numbers beyond normal Number limit.

```js
let big = 123456789012345678901234567890n;  
```

---

### 2️⃣ Non-Primitive Data Types (complex)

These can hold multiple values and are **mutable**.

#### 🔹 Object

Collection of key-value pairs.

```js
let person = {  
  name: "Ranjan",  
  age: 21,  
  city: "Delhi"  
};  
```

#### 🔹 Array

Ordered collection (list) of values.

```js
let fruits = ["apple", "banana", "mango"];  
```

#### 🔹 Function

Block of reusable code.

```js
function greet() {  
  console.log("Hello Ranjan 💕");  
}  
greet();
```

---

## ⚖️ Primitive vs Non-Primitive

|Feature|Primitive|Non-Primitive|
|---|---|---|
|Stores|Single value|Multiple values|
|Mutability|Immutable|Mutable|
|Examples|Number, String, Boolean, Null, Undefined, Symbol, BigInt|Object, Array, Function|

---

## 💡 Type Checking

Use `typeof` operator to check data type.

```js
console.log(typeof 42);         // number  
console.log(typeof "Ranjan");   // string  
console.log(typeof true);       // boolean  
console.log(typeof null);       // object (special case/bug in JS)  
console.log(typeof undefined);  // undefined  
console.log(typeof [1,2,3]);    // object (array is also object)  
```
---
