# server actions

`'use server'` — mutate tanpa bikin route, tetap validasi input.

```ts
// dipakai di project
export const cn = (...c) => c.filter(Boolean).join(' ')
```
