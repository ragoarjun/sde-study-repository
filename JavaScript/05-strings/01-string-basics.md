# String Basics

A string is a sequence of characters.

```bash
const name = "Rago";
const message = 'Hello';
```

---

## Access Characters

```bash
const word = "Hello";

word[0]; // "H"
word[4]; // "o"
word.length; // 5
```

---

## Template Literals

Use backticks `` ` `` to insert variables easily.

```bash
const name = "Rago";
const age = 21;

const message = `My name is ${name} and I am${age}.`;
```

---

## Strings Are Immutable

You cannot directly change a character in a string.

```bash
let word = "Hello";

word[0] = "Y";

console.log(word); // "Hello"
```

---

> **Remember:** Strings are indexed from 0 and are immutable.
