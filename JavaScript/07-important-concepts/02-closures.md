# Closures

A closure happens when a function remembers variables from its outer scope, even after the outer function finishes.

```bash
function outer() {
    let count = 0;

    return function () {
        count++;
        return count;
    };
}

const counter = outer();

counter(); // 1
counter(); // 2
counter(); // 3
```

`counter()` still has access to `count`.

---

## Why?

The inner function closes over the variables it needs from the outer scope.

---

> **Remember:** Closure = function + remembered outer variables.
