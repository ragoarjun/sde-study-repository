# Ternary Operator

A short way to write `if...else`.

```bash
const age = 20;

const result = age >= 18 ? "Adult" : "Minor";

console.log(result); // Adult
```

---

## Syntax

```bash
condition ? valueIfTrue : valueIfFalse
```

### Same logic with if...else:

```bash
if (age >= 18) {
    result = "Adult";
} else {
    result = "Minor";
}
```

---

> **Use:** Good for simple conditions. Avoid nested ternaries—they get ugly fast.
