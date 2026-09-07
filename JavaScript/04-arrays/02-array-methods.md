# Array Methods

Useful methods for working with arrays.

---

| Method        | Purpose                        |
| :------------ | :----------------------------- |
| `slice()`     | Extracts part of an array      |
| `splice()`    | Adds/removes elements          |
| `includes()`  | Checks if value exists         |
| `indexOf()`   | Finds index of a value         |
| `find()`      | Returns first matching element |
| `findIndex()` | Returns index of first match   |

---

## slice()

Does not modify the original array.

```bash
const nums = [10, 20, 30, 40];

nums.slice(1, 3); // [20, 30]
```

---

## splice()

Modifies the original array.

```bash
const nums = [10, 20, 30, 40];

nums.splice(1, 2);

console.log(nums); // [10, 40]
```

---

## includes() & indexOf()

```bash
const nums = [10, 20, 30];

nums.includes(20); // true
nums.indexOf(30);  // 2
```

---

## find()

Returns the first element that matches the condition.

```bash
const nums = [10, 20, 30, 40];

nums.find(num => num > 20); // 30
```

---

## findIndex()

```bash
nums.findIndex(num => num > 20); // 2
```

---

> **Remember:** `slice()` → doesn't modify. `splice()` → modifies.
