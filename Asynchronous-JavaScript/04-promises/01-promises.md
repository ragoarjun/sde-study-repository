# Promises

A Promise represents the eventual result of an asynchronous operation.

---

## Promise States

| State       | Meaning                |
| :---------- | :--------------------- |
| `pending`   | Still running          |
| `fulfilled` | Completed successfully |
| `rejected`  | Failed                 |

```bash
const promise = new Promise((resolve, reject) => {
    const success = true;

    if (success) {
        resolve("Done");
    } else {
        reject("Failed");
    }
});
```

---

## .then() and .catch()

```bash
promise
    .then(result => console.log(result))
    .catch(error => console.log(error));
```

- `resolve()` → success
- `reject()` → failure
- `.then()` → handle success
- `.catch()` → handle failure

---

## Why Promises?

They make asynchronous code easier to manage than deeply nested callbacks.

---

> **Remember:** A Promise is basically JavaScript saying: "I'll give you the result later."
