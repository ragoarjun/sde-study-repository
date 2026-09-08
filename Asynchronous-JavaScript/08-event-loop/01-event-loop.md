# Event Loop

The Event Loop allows JavaScript to handle asynchronous operations without blocking the main thread.

```bash
console.log("Start");

setTimeout(() => {
    console.log("Timeout");
}, 0);

console.log("End");

// Start
// End
// Timeout
```

---

## How?

```text
Call Stack
    ↓
Web APIs / Runtime
    ↓
Callback Queue
    ↓
Event Loop
    ↓
Call Stack
```

The synchronous code runs first. The callback waits until the Call Stack is empty.

---

## Promise vs Timer

```bash
console.log("Start");

setTimeout(() => console.log("Timer"), 0);

Promise.resolve().then(() => console.log("Promise"));

console.log("End");

// Start
// End
// Promise
// Timer
```

Promise callbacks use the **microtask queue**, which is processed before the timer callback (**macrotask queue**).

---

> **Remember:** JavaScript is single-threaded, but the Event Loop allows it to handle asynchronous work.
