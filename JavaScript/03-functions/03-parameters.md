# Parameters

Parameters are values a function receives.

```bash
function greet(name) {
    console.log("Hello " + name);
}

greet("Rago"); // Hello Rago
```

---

## Default Parameters

Used when an argument is not provided.

```bash
function greet(name = "Guest") {
    console.log("Hello " + name);
}

greet();       // Hello Guest
greet("Rago"); // Hello Rago
```

---

## Rest Parameter

Collects multiple arguments into an array.

```bash
function add(...numbers) {
    return numbers.reduce((sum, n) => sum + n, 0);
}

add(1, 2, 3); // 6
```

---

> **Remember:** `...numbers` inside function parameters collects arguments into an array.
