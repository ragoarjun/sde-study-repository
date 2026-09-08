# Promise Chaining

`.then()` returns a new Promise, so multiple asynchronous operations can be chained.

```bash
getUser()
    .then(user => getPosts(user))
    .then(posts => getComments(posts))
    .then(comments => console.log(comments))
    .catch(error => console.log(error));
```

Each `.then()` receives the result returned by the previous `.then()`.

```bash
Promise.resolve(10)
    .then(x => x * 2)
    .then(x => x + 5)
    .then(result => console.log(result));

// 25
```

---

## Error Handling

One `.catch()` can handle errors from the chain.

```bash
doSomething()
    .then(result => doNext(result))
    .then(result => doFinal(result))
    .catch(error => console.log(error));
```

---

> **Remember:** Return from `.then()` → pass the result to the next `.then()`.
