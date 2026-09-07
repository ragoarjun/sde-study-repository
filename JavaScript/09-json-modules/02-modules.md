# Modules

Modules let you split JavaScript code into separate files.

---

## Named Export

```bash
// math.js
export const add = (a, b) => a + b;
```

Import it:

```bash
// app.js
import { add } from "./math.js";

console.log(add(2, 3)); // 5
```

---

## Default Export

```bash
// math.js
export default function add(a, b) {
    return a + b;
}
```

Import it:

```bash
import add from "./math.js";
```

---

## Named vs Default

| Feature               | Named            | Default              |
| :-------------------- | :--------------- | :------------------- |
| **Export**            | `export { add }` | `export default add` |
| **Import**            | `import { add }` | `import add`         |
| **Multiple per file** | Yes              | One                  |

---

> **Remember:** Modules help organize and reuse code across files.
