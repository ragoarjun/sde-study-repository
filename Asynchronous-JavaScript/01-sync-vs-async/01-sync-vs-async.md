# Synchronous vs Asynchronous

---

## Synchronous

Code runs one line at a time. Each operation waits for the previous one to finish.

```bash
console.log("One");
console.log("Two");
console.log("Three");

// One
// Two
// Three
```

---

## Asynchronous

Code can start an operation and continue executing without waiting for it to finish.

```bash
console.log("One");

setTimeout(() => {
    console.log("Two");
}, 1000);

console.log("Three");

// One
// Three
// Two
```

---

## Comparison

| Synchronous              | Asynchronous                       |
| :----------------------- | :--------------------------------- |
| Runs sequentially        | Doesn't block execution            |
| Waits for each operation | Can continue while waiting         |
| Simple operations        | Timers, API calls, file operations |

---

> **Remember:** Async JavaScript lets your program handle slow operations without blocking everything else.
