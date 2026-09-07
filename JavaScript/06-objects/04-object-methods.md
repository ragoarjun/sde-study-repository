# Object Methods

Useful methods for working with objects.

---

| Method             | Returns                       |
| :----------------- | :---------------------------- |
| `Object.keys()`    | Array of keys                 |
| `Object.values()`  | Array of values               |
| `Object.entries()` | Array of `[key, value]` pairs |

```bash
const user = {
    name: "Rago",
    age: 21
};

Object.keys(user);
// ["name", "age"]

Object.values(user);
// ["Rago", 21]

Object.entries(user);
// [["name", "Rago"], ["age", 21]]
```

---

## Loop Through an Object

```bash
for (const [key, value] of Object.entries(user)) {
    console.log(key, value);
}
```

---

> **Remember:** `keys()` → keys, `values()` → values, `entries()` → both.
