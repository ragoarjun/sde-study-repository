# Loops

Used to repeat code.

---

| Loop         | Use                         |
| :----------- | :-------------------------- |
| `for`        | Known number of iterations  |
| `while`      | Run while condition is true |
| `do...while` | Run at least once           |
| `for...of`   | Iterate over values         |
| `for...in`   | Iterate over object keys    |

---

## for

```bash
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```

---

## while

```bash
let i = 0;

while (i < 5) {
    console.log(i);
    i++;
}
```

---

## do...while

Runs at least once.

```bash
let i = 0;

do {
    console.log(i);
    i++;
} while (i < 5);
```

---

## for...of

Used for values.

```bash
const nums = [10, 20, 30];

for (const num of nums) {
    console.log(num);
}
```

---

## for...in

Used for keys/properties.

```bash
const user = { name: "Rago", age: 21 };

for (const key in user) {
    console.log(key);
}
```

---

> **Remember:** `for...of` → values, `for...in` → keys.
