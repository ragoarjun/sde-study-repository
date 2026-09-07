# Some & Every

Used to test whether array elements satisfy a condition.

---

| Method    | Returns true when...         |
| :-------- | :--------------------------- |
| `some()`  | At least one element matches |
| `every()` | All elements match           |

---

## some()

```bash
const nums = [1, 3, 5, 6];

nums.some(num => num % 2 === 0); // true
```

---

## every()

```bash
const nums = [2, 4, 6, 8];

nums.every(num => num % 2 === 0); // true
```

---

> **Remember:** `some()` → at least one. `every()` → all.
