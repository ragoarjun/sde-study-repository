# Object Basics

Objects store data as key-value pairs.

```bash
const user = {
    name: "Rago",
    age: 21
};
```

---

## Access Values

```bash
user.name;      // "Rago"
user["age"];    // 21
```

---

## Add / Update / Delete

```bash
user.city = "Chennai";  // Add
user.age = 22;          // Update

delete user.city;       // Delete
```

---

## Check Property

```bash
"name" in user; // true
```

---

> **Remember:** `object.key` and `object["key"]` both access properties.
