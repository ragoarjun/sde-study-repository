# Error Handling

Used to handle errors without crashing the program.

---

| Keyword   | Purpose                      |
| :-------- | :--------------------------- |
| `try`     | Code that may cause an error |
| `catch`   | Handles the error            |
| `finally` | Always runs                  |
| `throw`   | Creates a custom error       |

```bash
try {
    const result = riskyFunction();
} catch (error) {
    console.log(error.message);
} finally {
    console.log("Done");
}
```

---

## Throw an Error

```bash
function divide(a, b) {
    if (b === 0) {
        throw new Error("Cannot divide by zero");
    }

    return a / b;
}
```

---

> **Remember:** `try` → attempt, `catch` → handle, `finally` → always runs, `throw` → create error.
