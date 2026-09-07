# Object Methods & this

A function inside an object is called a method.

```bash
const user = {
    name: "Rago",

    greet() {
        console.log("Hello " + this.name);
    }
};

user.greet(); // Hello Rago
```

---

## this

`this` refers to the object that calls the method.

```bash
const user = {
    name: "Rago",

    greet() {
        console.log(this.name);
    }
};

user.greet(); // Rago
```

---

> **Remember:** In `user.greet()`, `this` refers to `user`.
