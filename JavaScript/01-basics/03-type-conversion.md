# Operators

Operators perform operations on values.

---

| Type           | Operators                               | Example                         |
| :------------- | :-------------------------------------- | :------------------------------ |
| **Arithmetic** | `+` `-` `*` `/` `%` `**`                | `10 % 3 → 1`                    |
| **Assignment** | `=` `+=` `-=` `*=` `/=`                 | `x += 2`                        |
| **Comparison** | `==` `===` `!=` `!==` `>` `<` `>=` `<=` | `5 === 5`                       |
| **Logical**    | `&&` `\|\|` `!`                         | `age > 18 && active`            |
| **Unary**      | `++` `--` `typeof` `!`                  | `typeof name`                   |
| **Ternary**    | `? :`                                   | `age >= 18 ? "Adult" : "Minor"` |

---

## Arithmetic

```bash
10 + 3;  // 13
10 - 3;  // 7
10 * 3;  // 30
10 / 3;  // 3.333...
10 % 3;  // 1
2 ** 3;  // 8
```

---

## Comparison

```bash
5 == "5";   // true
5 === "5";  // false

5 != "5";   // false
5 !== "5";  // true
```

Use `===` and `!==` instead of `==` and `!=` in most cases.

---

## Logical

```bash
true && true;   // true
true || false;  // true
!true;          // false
```

---

## Ternary

Short form of `if...else`.

```bash
const age = 20;

const result = age >= 18 ? "Adult" : "Minor";
```
