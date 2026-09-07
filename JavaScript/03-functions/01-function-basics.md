# Functions

A function is a reusable block of code.

```bash
function greet() {
    console.log("Hello");
}

greet();
```

---

## Parameters & Arguments

- **Parameters** are variables defined in the function.
- **Arguments** are the actual values passed to it.

```bash
function greet(name) {
    console.log("Hello " + name);
}

greet("Rago");
```

---

## Return

`return` sends a value back from the function.

```bash
function add(a, b) {
    return a + b;
}

const result = add(10, 20);

console.log(result); // 30
```

---

> **Remember:** `return` ends the function and sends a value back.
