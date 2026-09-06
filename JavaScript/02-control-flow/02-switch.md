# Switch

Used when comparing one value against multiple possible cases.

```bash
const day = 2;

switch (day) {
    case 1:
        console.log("Monday");
        break;

    case 2:
        console.log("Tuesday");
        break;

    default:
        console.log("Invalid day");
}
```

---

## Important

| Keyword   | Purpose                 |
| :-------- | :---------------------- |
| `case`    | Value to match          |
| `break`   | Stops the switch        |
| `default` | Runs if no case matches |

Without `break`, execution continues into the next case.

```bash
const x = 1;

switch (x) {
    case 1:
        console.log("One");
    case 2:
        console.log("Two");
}
```

### Output:

```bash
One
Two
```

---

> Use `switch` when you have many fixed values to compare.
