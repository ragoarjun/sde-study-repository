# Object Destructuring & Spread

---

## Destructuring

Extract properties into variables.

```bash
const user = {
    name: "Rago",
    age: 21
};

const { name, age } = user;

console.log(name); // Rago
console.log(age);  // 21
```

---

## Spread ...

Copies or combines object properties.

```bash
const user = {
    name: "Rago",
    age: 21
};

const updatedUser = {
    ...user,
    age: 22
};

console.log(updatedUser);
// { name: "Rago", age: 22 }
```

---

> **Remember:** Destructuring → extract. Spread → copy/expand.
