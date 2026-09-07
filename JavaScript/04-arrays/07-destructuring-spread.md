# Destructuring & Spread

---

## Destructuring

Extract values from an array into variables.

```bash
const nums = [10, 20, 30];

const [a, b, c] = nums;

console.log(a); // 10
console.log(b); // 20
```

---

## Spread ...

Expands the elements of an array.

```bash
const a = [1, 2];
const b = [3, 4];

const nums = [...a, ...b];

console.log(nums); // [1, 2, 3, 4]
```

Can also copy an array:

```bash
const copy = [...nums];
```

---

> **Remember:** Destructuring → extract. Spread → expand/copy.
