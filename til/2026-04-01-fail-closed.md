# fail closed auth

Env admin kosong → 401, bukan open — default aman.

```ts
// dipakai di project
export const cn = (...c) => c.filter(Boolean).join(' ')
```
