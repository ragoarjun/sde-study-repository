# Array Sort

`sort()` sorts the elements of an array.  
By default, JavaScript converts elements to strings and sorts them lexicographically.

```bash
const nums = [10, 2, 5];

nums.sort();

console.log(nums); // [10, 2, 5]
```

For numbers, use a comparator.

---

## Ascending

```bash
nums.sort((a, b) => a - b);
```

---

## Descending

```bash
nums.sort((a, b) => b - a);
```

---

| Comparator        | Order      |
| :---------------- | :--------- |
| `(a, b) => a - b` | Ascending  |
| `(a, b) => b - a` | Descending |

---

> **Remember:** `sort()` modifies the original array.
