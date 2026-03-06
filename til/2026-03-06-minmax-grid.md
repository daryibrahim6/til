# minmax(0,1fr) di grid

Track `1fr` = minmax(auto) — konten intrinsic gak bisa shrink. `minmax(0,1fr)` fix overflow.

```ts
// dipakai di project
export const cn = (...c) => c.filter(Boolean).join(' ')
```
