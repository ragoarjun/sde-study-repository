# Optional Chaining & Nullish Coalescing

---

## Optional Chaining ?.

Safely access nested properties without getting an error if something is `null` or `undefined`.

```bash
const user = {
    profile: {
        name: "Rago"
    }
};

user.profile?.name; // "Rago"
user.address?.city; // undefined
```

---

## Nullish Coalescing ??

Provides a fallback when the value is `null` or `undefined`.

```bash
const name = null;

const result = name ?? "Guest";

console.log(result); // "Guest"
```

---

## ?? vs ||

`||` also treats `0`, `""`, and `false` as missing.

```bash
0 || 10;  // 10
0 ?? 10;  // 0

"" || "Guest"; // "Guest"
"" ?? "Guest"; // ""
```

---

> **Remember:** `?.` → safely access. `??` → fallback for `null`/`undefined`.
