# Callbacks

A callback is a function passed to another function to be executed later.

```bash
function greet(name, callback) {
    console.log("Hello " + name);
    callback();
}

function done() {
    console.log("Done");
}

greet("Rago", done);
```

---

## Asynchronous Callback

```bash
console.log("Start");

setTimeout(() => {
    console.log("Done");
}, 1000);

console.log("End");

// Start
// End
// Done
```

The callback runs after the timer finishes.

---

> **Remember:** Callback = pass a function to be called later.
