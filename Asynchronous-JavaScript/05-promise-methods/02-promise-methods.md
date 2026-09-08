# Promise Methods

---

| Method                 | Behavior                                     |
| :--------------------- | :------------------------------------------- |
| `Promise.all()`        | Waits for all; rejects if one fails          |
| `Promise.allSettled()` | Waits for all, regardless of success/failure |
| `Promise.race()`       | Returns the first settled Promise            |

---

## Promise.all()

```bash
const results = await Promise.all([
    fetchUsers(),
    fetchPosts()
]);
```

Both operations run concurrently. If one rejects, `Promise.all()` rejects.

---

## Promise.allSettled()

```bash
const results = await Promise.allSettled([
    fetchUsers(),
    fetchPosts()
]);
```

Returns the result of every Promise, whether fulfilled or rejected.

---

## Promise.race()

```bash
const result = await Promise.race([
    fetchFromServerA(),
    fetchFromServerB()
]);
```

Returns whichever Promise settles first.

---

> **Remember:** `all` → everyone must succeed, `allSettled` → everyone finishes, `race` → first one wins.
