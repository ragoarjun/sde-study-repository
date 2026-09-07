# Function Expressions & Arrow Functions

---

## Function Expression

A function can be stored inside a variable.

```bash
const add = function(a, b) {
    return a + b;
};

console.log(add(2, 3)); // 5
```

---

## Arrow Function

Shorter syntax for writing functions.

```bash
const add = (a, b) => {
    return a + b;
};
```

For a single expression, `return` can be omitted:

```bash
const add = (a, b) => a + b;
```

---

## Quick Comparison

| Type           | Example                         |
| :------------- | :------------------------------ |
| **Function**   | `function add(a, b) {}`         |
| **Expression** | `const add = function(a, b) {}` |
| **Arrow**      | `const add = (a, b) => a + b`   |

---

> **Remember:** Arrow functions are commonly used with array methods like `map()` and `filter()`.
