# Variables

A variable is a named reference to a value.

```bash
let age = 21;
const name = "Rago";
```

---

## var

- Function scoped
- Can be reassigned
- Can be redeclared

```bash
var x = 10;
x = 20;
var x = 30;
```

---

## let

- Block scoped
- Can be reassigned
- Cannot be redeclared in the same scope

```bash
let x = 10;
x = 20;
// let x = 30; // Error
```

---

## const

- Block scoped
- Cannot be reassigned
- Cannot be redeclared

```bash
const x = 10;
// x = 20; // Error
```

---

## Use

```bash
const by default → let when the value changes → avoid var.
```
