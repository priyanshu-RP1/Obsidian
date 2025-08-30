
# 📒 JavaScript `forEach()` Notes

## 🌸 What is `forEach`?

- `forEach()` is a **built-in array method** in JavaScript.
    
- It runs a function **once for every element** in the array.
    
- You use it to loop through an array without writing extra setup (`i = 0`, `i++`, etc.).
    

---

## 🌸 Syntax

```js
array.forEach(function(item, index, array) {
    // your work here
});
```

### Parameters (given automatically by JS 🎁):

1. **item** → current element of array
    
2. **index** → position of the current element (0, 1, 2, …)
    
3. **array** → the whole array itself
    

👉 You don’t have to use all three, you can use only what you need.

---

## 🌸 Example 1: Simplest use

```js
let chocolates = ["Dairy Milk", "KitKat", "Perk"];

chocolates.forEach(function(item) {
    console.log("I am eating:", item);
});
```

### Output:

```
I am eating: Dairy Milk
I am eating: KitKat
I am eating: Perk
```

---

## 🌸 Example 2: Using item + index + array

```js
let chocolates = ["Dairy Milk", "KitKat", "Perk"];

chocolates.forEach(function(item, index, array) {
    console.log("Chocolate:", item);   // current item
    console.log("Position:", index);   // its number
    console.log("Full box:", array);   // the full array
    console.log("----");
});
```

---

## 🌸 Example 3: Arrow function (shorter way ✨)

```js
let chocolates = ["Dairy Milk", "KitKat", "Perk"];

chocolates.forEach((item, index) => {
    console.log(index + ": " + item);
});
```

---

## 🌸 Difference from Normal `for` loop

|Normal `for` Loop|`forEach`|
|---|---|
|You write start, condition, increment (`i = 0; i < length; i++`)|No setup needed, JS handles it|
|Need to manually get element (`array[i]`)|Auto gives `item, index, array`|
|Can use `break` / `continue`|Can’t break early (runs for all elements)|
|More typing|Cleaner & shorter|

---

## 🌸 When to use

- Use `forEach` when you want to **do something with every element** of an array.
    
- Use normal `for` when you need **to break or skip** in the middle.
    

---

