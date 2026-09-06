# Data Types

JavaScript has primitive and non-primitive data types.

---

## Primitive

```bash
let name = "Rago";       // String
let age = 21;            // Number
let isStudent = true;    // Boolean
let x;                   // Undefined
let y = null;             // Null
let id = 123n;            // BigInt
let key = Symbol("id");   // Symbol
```

### Main primitives to remember:

- String
- Number
- Boolean
- Undefined
- Null
- BigInt
- Symbol

---

## Non-Primitive

Objects store collections of data.

```bash
const user = {
    name: "Rago",
    age: 21
};

const numbers = [1, 2, 3];
```

Arrays and functions are also objects in JavaScript.

---

## typeof

Used to check the type of a value.

```bash
typeof "hello";   // "string"
typeof 42;        // "number"
typeof true;      // "boolean"
typeof undefined; // "undefined"
typeof {};        // "object"
```

### One weird JavaScript fact:

```bash
typeof null; // "object"
```

This is a historical JavaScript quirk.

---

> **Remember:** Primitive values are basic single values; objects can contain multiple values.
