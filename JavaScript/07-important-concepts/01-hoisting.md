# Hoisting

JavaScript moves certain declarations to the top of their scope during execution.

---

## var

```bash
console.log(x); // undefined

var x = 10;
```

The declaration is hoisted, but the value is not.

---

## let and const

```bash
console.log(x); // ReferenceError

let x = 10;
```

They are hoisted but cannot be accessed before declaration because of the Temporal Dead Zone (TDZ).

---

## Function Declaration

Function declarations can be called before they appear in the code.

```bash
greet(); // Hello

function greet() {
    console.log("Hello");
}
```

---

> **Remember:** `var` → `undefined` before declaration. `let`/`const` → error. Function declarations → usable before declaration.
