# Truthy & Falsy

In a condition, JavaScript treats some values as true or false.

---

## Falsy Values

These are the main falsy values:

| Value       | Meaning       |
| :---------- | :------------ |
| `false`     | Boolean false |
| `0`         | Zero          |
| `-0`        | Negative zero |
| `""`        | Empty string  |
| `null`      | No value      |
| `undefined` | Not assigned  |
| `NaN`       | Not a number  |

Everything else is truthy.

```bash
if ("hello") {
    console.log("Runs");
}

if (0) {
    console.log("Doesn't run");
}
```

---

## Common Usage

```bash
const username = "";

if (!username) {
    console.log("Username required");
}
```

---

## Important

Empty arrays and objects are truthy:

```bash
Boolean([]); // true
Boolean({}); // true
```
