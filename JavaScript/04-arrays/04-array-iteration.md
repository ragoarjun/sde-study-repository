# Array Iteration

---

## forEach()

Runs a function once for every element.

```bash
const nums = [10, 20, 30];

nums.forEach(num => {
    console.log(num);
});
```

---

## forEach() vs map()

| Feature                   | forEach()    | map()          |
| :------------------------ | :----------- | :------------- |
| **Runs on every element** | Yes          | Yes            |
| **Returns new array**     | No           | Yes            |
| **Used for**              | Side effects | Transformation |

```bash
const nums = [1, 2, 3];

nums.forEach(num => console.log(num));

const doubled = nums.map(num => num * 2);
```

---

> **Remember:** `forEach()` → do something. `map()` → create a transformed array.
