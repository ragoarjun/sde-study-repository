# Break & Continue

Used to control loop execution.

---

| Keyword    | What it does                |
| :--------- | :-------------------------- |
| `break`    | Stops the loop completely   |
| `continue` | Skips the current iteration |

---

## break

```bash
for (let i = 0; i < 5; i++) {
    if (i === 3) break;
    console.log(i);
}

// 0 1 2
```

---

## continue

```bash
for (let i = 0; i < 5; i++) {
    if (i === 2) continue;
    console.log(i);
}

// 0 1 3 4
```

---

> **Remember:** `break` → exit loop, `continue` → skip iteration.
