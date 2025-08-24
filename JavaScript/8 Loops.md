
# 🔄 Loops in JavaScript

## 📝 Definition

- **Loops** are used to **repeat a block of code again and again** until a condition is met.  
    👉 Imagine you want to eat 10 chocolates 🍫 one after another → instead of saying "eat chocolate" 10 times, you use a loop.
    

---

## 🔥 Types of Loops

### 1️⃣ For Loop

- Used when we **know how many times** we want to repeat something.
    
- Syntax:
    

```js
for (initialization; condition; increment/decrement) {
   // work to do
}
```

#### Example 1: Multiplication Table

```js
let m = prompt("Enter the Number of Multiplication u need ");
let mul = Number(m);
for (let i = 1; i <= 10; i++) {
    console.log(mul, " X ", i, " = ", mul * i);
}
```

👉 Prints table of given number.

#### Example 2: Counting Backwards

```js
var input = prompt("Enter a number to start negative counting numbers from ");
for (var num = Number(input); num != 0; num--) {
    console.log(num);
}
```

👉 Prints numbers in reverse until 1.

---

### 2️⃣ While Loop

- Used when we **don’t know the exact number of repetitions**, but have a **condition**.
    
- Syntax:
    

```js
while (condition) {
   // work to do
}
```

#### Example 1: Print numbers until 100

```js
var ff = prompt("Enter a number ");
let numm = Number(ff);
while (numm <= 100) {
    console.log(numm++);
}
console.log("while loop example finished ✨");
```

👉 Prints from given number to 100.

#### Example 2: Multiplication Table (again with while)

```js
let a = 1;
while (a <= 10) {
    console.log(mul, " X ", a, " = ", mul * a);
    a++;
}
```

👉 Prints multiplication table using while loop.

---

### 3️⃣ Do...While Loop

- Runs the block of code **at least once** → then checks condition.
    
- Syntax:
    

```js
do {
   // work to do
} while (condition);
```

#### Example: Countdown

```js
let aa = prompt("Enter a number ");
let nummm = Number(aa);
do {
    console.log(nummm - 1);
    nummm--;
} while (nummm >= 0);
```

👉 Always prints at least once, then counts down to 0.

---

## 🌟 Summary

- **For Loop** → when we know how many times.
    
- **While Loop** → runs until a condition is true.
    
- **Do...While Loop** → runs **at least once**, then checks condition.
    

👉 Loops = save time + avoid writing repetitive code 💕
