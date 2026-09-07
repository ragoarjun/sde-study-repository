# String Patterns

---

## Reverse a String

```bash
const str = "hello";

const reversed = str.split("").reverse().join("");

console.log(reversed); // "olleh"
```

---

## Convert String to Array

```bash
const str = "hello world";

const words = str.split(" ");

console.log(words); // ["hello", "world"]
```

---

## Convert Array to String

```bash
const words = ["hello", "world"];

const str = words.join(" ");

console.log(str); // "hello world"
```

---

## Check a Substring

```bash
const str = "JavaScript";

str.includes("Script"); // true
str.startsWith("Java"); // true
str.endsWith("Script");  // true
```

---

> **Remember:** `split()` → string to array, `join()` → array to string.
