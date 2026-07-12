# verifikasi webhook

Signature check dulu sebelum proses — jangan trust body.

```ts
// dipakai di project
export const cn = (...c) => c.filter(Boolean).join(' ')
```
