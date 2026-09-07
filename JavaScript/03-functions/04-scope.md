# Scope

Scope determines where a variable can be accessed.

---

| Scope        | Accessible          |
| :----------- | :------------------ |
| **Global**   | Everywhere          |
| **Function** | Inside the function |
| **Block**    | Inside `{ }`        |

---

## Function Scope

```bash
function test() {
    let x = 10;
    console.log(x); // Works
}

console.log(x); // Error
```

---

## Block Scope

`let` and `const` are block scoped.

```bash
if (true) {
    let x = 10;
    const y = 20;
}

console.log(x); // Error
console.log(y); // Error
```

`var` is not block scoped.

```bash
if (true) {
    var x = 10;
}

console.log(x); // 10
```

---

> **Remember:** `let` and `const` → block scoped. `var` → function scoped.
