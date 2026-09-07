# Array Basics

An array stores multiple values in a single variable.

```bash
const fruits = ["apple", "banana", "mango"];
```

---

## Access & Modify

```bash
fruits[0];        // "apple"

fruits[1] = "orange";
```

---

## Common Properties & Methods

| Method      | Purpose               |
| :---------- | :-------------------- |
| `length`    | Number of elements    |
| `push()`    | Add to end            |
| `pop()`     | Remove from end       |
| `unshift()` | Add to beginning      |
| `shift()`   | Remove from beginning |

```bash
const nums = [1, 2, 3];

nums.push(4);    // [1, 2, 3, 4]
nums.pop();      // [1, 2, 3]
nums.unshift(0); // [0, 1, 2, 3]
nums.shift();    // [1, 2, 3]
```

---

> **Remember:** Array indexing starts at 0.
