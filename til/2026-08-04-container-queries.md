# container queries

`@container (min-width:400px)` — style berdasar parent, bukan viewport.

```ts
// dipakai di project
export const cn = (...c) => c.filter(Boolean).join(' ')
```

> tambahan: polish — 13 Aug
