# AbortController untuk fetch timeout

```ts
const c = new AbortController();
setTimeout(() => c.abort(), 120_000);
fetch(url, {signal: c.signal})
```
fetch native gak punya timeout — wajib manual.
