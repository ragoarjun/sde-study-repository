# Modern JavaScript

Common ES6+ features used in modern JavaScript.

---

## Destructuring

```bash
const user = { name: "Rago", age: 21 };

const { name, age } = user;
```

---

## Spread

```bash
const a = [1, 2];
const b = [...a, 3];

console.log(b); // [1, 2, 3]
```

---

## Rest

```bash
function add(...nums) {
    return nums.length;
}
```

---

## Optional Chaining

```bash
user.profile?.name;
```

---

## Nullish Coalescing

```bash
const name = null;

console.log(name ?? "Guest"); // Guest
```

---

## Template Literals

```bash
const name = "Rago";

console.log(`Hello, ${name}`);
```

---

> **Remember:** These features make modern JavaScript shorter and easier to work with.
