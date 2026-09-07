# String Methods

---

| Method          | Purpose                       |
| :-------------- | :---------------------------- |
| `toUpperCase()` | Converts to uppercase         |
| `toLowerCase()` | Converts to lowercase         |
| `trim()`        | Removes spaces from both ends |
| `includes()`    | Checks if substring exists    |
| `indexOf()`     | Returns index of substring    |
| `slice()`       | Extracts part of a string     |
| `split()`       | Converts string into an array |
| `replace()`     | Replaces a match              |

```bash
const text = "  Hello World  ";

text.toUpperCase();          // "  HELLO WORLD  "
text.toLowerCase();          // "  hello world  "
text.trim();                 // "Hello World"
text.includes("World");      // true
text.indexOf("World");       // 8
text.slice(2, 7);            // "Hello"
text.split(" ");             // ["", "", "Hello", "World", "", ""]
text.replace("World", "JS"); // "  Hello JS  "
```

---

> **Remember:** String methods return a new string; they don't modify the original string.
