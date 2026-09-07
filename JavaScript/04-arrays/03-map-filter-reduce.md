# Map, Filter & Reduce

---

| Method     | Purpose                         | Returns      |
| :--------- | :------------------------------ | :----------- |
| `map()`    | Transform every element         | New array    |
| `filter()` | Keep matching elements          | New array    |
| `reduce()` | Combine elements into one value | Single value |

---

## map()

Transforms every element.

```bash
const nums = [1, 2, 3];

const doubled = nums.map(num => num * 2);

console.log(doubled); // [2, 4, 6]
```

---

## filter()

Keeps elements that satisfy a condition.

```bash
const nums = [1, 2, 3, 4];

const even = nums.filter(num => num % 2 === 0);

console.log(even); // [2, 4]
```

---

## reduce()

Reduces an array to a single value.

```bash
const nums = [1, 2, 3, 4];

const sum = nums.reduce((total, num) => total + num, 0);

console.log(sum); // 10
```

---

> **Remember:**
>
> - `map` → transform
> - `filter` → select
> - `reduce` → combine
