# Fetch API

`fetch()` is used to make HTTP requests. It returns a Promise.

---

## GET Request

```bash
const response = await fetch("[https://api.example.com/users](https://api.example.com/users)");

const data = await response.json();

console.log(data);
```

---

## POST Request

```bash
const response = await fetch("[https://api.example.com/users](https://api.example.com/users)", {
    method: "POST",
    headers: {
        "Content-Type": "application/json"
    },
    body: JSON.stringify({
        name: "Rago"
    })
});
```

---

## Error Handling

```bash
try {
    const response = await fetch(url);

    if (!response.ok) {
        throw new Error("Request failed");
    }

    const data = await response.json();
} catch (error) {
    console.log(error);
}
```

---

> **Remember:** `fetch()` → Promise → `response.json()` → data.
