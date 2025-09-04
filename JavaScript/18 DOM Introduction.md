
# 🌸 Introduction to DOM

## 1. What is DOM?

- **DOM** stands for **Document Object Model**.
    
- When a **web page is loaded**, the browser creates a **tree-like structure** of the HTML document.
    
- This tree is called the **DOM Tree**.
    
- Each **HTML element, attribute, or text** becomes a **node** in this tree.
    

👉 Think of it like a **family tree of your webpage** 💖 where:

- `window` → the big house 🏠
    
- `document` → the front door 🚪
    
- `html` → the whole family 🌳
    
- `head` & `body` → two main branches 🌿
    
- Elements (`h1`, `p`, `img`, etc.) → the children 👶
    

---

## 2. DOM Tree Example

For a simple HTML like this:

```html
<html>
  <head>
    <title>My Page</title>
  </head>
  <body>
    <h1>Hello World</h1>
    <p>Welcome to DOM</p>
  </body>
</html>
```

The DOM Tree looks like:

```DOM TREE
window
 └── document
      └── html
          ├── head
          │   └── title
          └── body
              ├── h1
              └── p
```

---

## 3. Types of Nodes

- **Document Node** → The root (`document`)
    
- **Element Node** → HTML tags (`div`, `p`, `h1`, etc.)
    
- **Attribute Node** → Attributes inside tags (`class="box"`)
    
- **Text Node** → The actual text inside elements (`Hello World`)
    

---

## 4. Why DOM is Important?

- JavaScript uses the DOM to **interact with the webpage**.
    
- With DOM, you can:
    
    - **Change content** (update text/images)
        
    - **Change styles** (colors, fonts, layout)
        
    - **Add / remove elements** (like creating new buttons)
        
    - **Handle events** (click, hover, typing)
        

👉 DOM makes your webpage **dynamic & interactive** instead of static ✨

---

## 5. Relationship in DOM

DOM has **parent-child-sibling** relationships, just like a real family:

- **Parent** → The element that contains another element.
    
- **Child** → The element inside a parent.
    
- **Siblings** → Elements with the same parent.
    

Example:

```html
<div>
  <p>Paragraph 1</p>
  <p>Paragraph 2</p>
</div>
```

Here:

- `div` = parent
    
- both `p` = children
    
- the two `p` tags = siblings
    

---

💡 **In short:** DOM = _the bridge between HTML & JavaScript_ 🚀.  
It’s how JS “sees” and “controls” the webpage 🌸.

---
