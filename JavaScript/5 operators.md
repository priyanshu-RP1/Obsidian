

# 🔢 JavaScript Operators  

## 📝 Definition  
- **Operators** are special symbols that perform operations on values (operands).  
- Example: `+`, `-`, `*`, `/`  
👉 Think of operators as **tools 🛠️** that help us work with data.  

---

# 🔥 Types of Operators in JavaScript  

## 1️⃣ Arithmetic Operators  
Used to perform basic math operations.  

| Operator | Description         | Example (`a=10, b=5`) | Result |
| -------- | ------------------- | --------------------- | ------ |
| `+`      | Addition            | `a + b`               | 15     |
| `-`      | Subtraction         | `a - b`               | 5      |
| `*`      | Multiplication      | `a * b`               | 50     |
| `/`      | Division            | `a / b`               | 2      |
| `%`      | Modulus (remainder) | `a % b`               | 0      |
| `**`     | Exponentiation      | `a ** b`              | 100000 |

```js
let a = 10, b = 5;
console.log(a + b);  // 15
console.log(a % b);  // 0


---

### 2️⃣ Assignment Operators

Used to assign values to variables.

|Operator|Meaning|Example|Result|
|---|---|---|---|
|`=`|Assign|`x = 5`|5|
|`+=`|Add and assign|`x += 2`|x = x+2|
|`-=`|Subtract and assign|`x -= 2`|x = x-2|
|`*=`|Multiply and assign|`x *= 2`|x = x*2|
|`/=`|Divide and assign|`x /= 2`|x = x/2|
|`%=`|Modulus and assign|`x %= 2`|x = x%2|

```js
let x = 10;
x += 5;   // 15
x *= 2;   // 30
```

---

## 3️⃣ Comparison Operators

Used to compare two values (returns `true` or `false`).

|Operator|Description|Example (`a=10, b=5`)|Result|
|---|---|---|---|
|`==`|Equal to (loose)|`a == "10"`|true|
|`===`|Strict equal (type + value)|`a === "10"`|false|
|`!=`|Not equal|`a != b`|true|
|`!==`|Strict not equal|`a !== "10"`|true|
|`>`|Greater than|`a > b`|true|
|`<`|Less than|`a < b`|false|
|`>=`|Greater or equal|`a >= 10`|true|
|`<=`|Less or equal|`b <= 5`|true|

```js
let a = 10, b = 5;
console.log(a == "10");   // true
console.log(a === "10");  // false
```

---

## 4️⃣ Logical Operators

Used to combine conditions (returns `true`/`false`).

|Operator|Description|Example (`a=10, b=5`)|Result|
|---|---|---|---|
|`&&`|Logical AND|`(a>5 && b<10)`|true|
|`||`|Logical OR|
|`!`|Logical NOT|`!(a>5)`|false|

```js
let a = 10, b = 5;
console.log(a > 5 && b < 10); // true
console.log(!(a > 5));        // false
```

---

## 5️⃣ Unary Operators

Work on a **single operand**.

|Operator|Description|Example (`a=10`)|Result|
|---|---|---|---|
|`++`|Increment (add 1)|`a++`|11|
|`--`|Decrement (subtract 1)|`a--`|9|
|`typeof`|Returns type of variable|`typeof a`|number|

```js
let a = 10;
console.log(++a); // 11
console.log(typeof a); // number
```
---
## 6️⃣ Ternary Operator (Conditional)

- Short form of `if-else`.
    
- Syntax: `condition ? valueIfTrue : valueIfFalse`
    

```js
let age = 18;
let result = (age >= 18) ? "Adult" : "Minor";
console.log(result);  // Adult
```

---

## 7️⃣ Bitwise Operators (Advanced)

Operate on binary numbers (0s & 1s).

|Operator|Meaning|
|---|---|
|`&`|AND|
|`|`|
|`^`|XOR|
|`~`|NOT|
|`<<`|Left shift|
|`>>`|Right shift|

```js
let a = 5, b = 1;
console.log(a & b); // 1
console.log(a | b); // 5
```

---

## 🌟 Summary

- **Arithmetic** → Math operations
    
- **Assignment** → Assign/update values
    
- **Comparison** → Compare values (`true`/`false`)
    
- **Logical** → Combine conditions
    
- **Unary** → Work on single value
    
- **Ternary** → Short `if-else`
    
- **Bitwise** → Work on binary values
    
---
