# Higher-Order Functions

A function that takes another function as an argument or returns a function.

---

## Takes a Function

```bash
function calculate(a, b, operation) {
    return operation(a, b);
}

const add = (a, b) => a + b;

console.log(calculate(2, 3, add)); // 5
```

Here, `calculate()` is a higher-order function because it receives `operation` as a function.

---

## Returns a Function

```bash
function multiplier(x) {
    return function(y) {
        return x * y;
    };
}

const double = multiplier(2);

console.log(double(5)); // 10
```

---

> **Remember:** Functions can be passed around like values in JavaScript.
