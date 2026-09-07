# JSON

JSON (JavaScript Object Notation) is a common format for storing and transferring data.

```bash
const user = {
    name: "Rago",
    age: 21
};
```

---

## Object → JSON

```bash
const json = JSON.stringify(user);

console.log(json);
// {"name":"Rago","age":21}
```

---

## JSON → Object

```bash
const obj = JSON.parse(json);

console.log(obj.name); // Rago
```

---

| Method             | Converts             |
| :----------------- | :------------------- |
| `JSON.stringify()` | Object → JSON string |
| `JSON.parse()`     | JSON string → Object |

---

> **Remember:** APIs commonly send/receive data as JSON.
