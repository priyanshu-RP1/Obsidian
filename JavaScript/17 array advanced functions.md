

# 📘 Array Advanced Functions (Higher-Order Functions in JS)

Arrays in JavaScript have special functions that take another function (callback) as an argument.  
These are called **higher-order functions**. They don’t change the original array, instead they return something new (except `forEach`).

---

## 1. 🔹 forEach()

- Loops through each element in the array.
    
- Executes the given function once per element.
    
- Does **not** return a new array.
    

```js
let chocolates = ["Dairy Milk", "KitKat", "Perk"];

chocolates.forEach(function(item, index, array) {
  console.log("Chocolate:", item);
  console.log("Position:", index);
  console.log("Full array:", array);
});
```

---

## 2. 🔹 map()

- Creates a **new array**.
    
- Applies the given function to every element.
    
- Original array remains unchanged.
    

```js
let numbers = [2, 3, 4, 5];
let doubled = numbers.map(num => num * 2);

console.log(doubled); // [4, 6, 8, 10]
```

---

## 3. 🔹 filter()

- Creates a **new array** with elements that pass a condition (true).
    
- Skips elements where condition is false.
    

```js
let marks = [89, 92, 75, 99, 68];
let aboveNinety = marks.filter(num => num > 90);

console.log(aboveNinety); // [92, 99]
```

---

## 4. 🔹 reduce()

- Reduces the array into **a single value**.
    
- Uses an **accumulator** (total so far) and the **current value**.
    

```js
let nums = [1, 2, 3, 4, 5];

let sum = nums.reduce(function(acc, curr) {
  return acc + curr;
}, 0);

console.log(sum); // 15
```

---

✨ Summary:

- `forEach` → just loop, no new array.
    
- `map` → makes a new array by transforming elements.
    
- `filter` → makes a new array with only elements that match a condition.
    
- `reduce` → combines all elements into one result (sum, product, etc.).
    

---
