# Callback Hell

Callback Hell happens when multiple asynchronous operations are nested inside each other.

```bash
getUser(user => {
    getPosts(user, posts => {
        getComments(posts, comments => {
            getLikes(comments, likes => {
                console.log(likes);
            });
        });
    });
});
```

As nesting grows, code becomes:

- Hard to read
- Hard to maintain
- Hard to handle errors

This is also called the **Pyramid of Doom**.

---

## Solution

Promises and `async`/`await` provide cleaner ways to handle asynchronous code.

```text
Callbacks
    ↓
Promises
    ↓
async/await
```

---

> **Remember:** Callback Hell = deeply nested callbacks making async code difficult to manage.
