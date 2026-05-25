# git stash: apply vs pop

`pop` = apply + drop. Kalau conflict, stash tetap kesimpan. `apply` keep stash di list.

```ts
// dipakai di project
export const cn = (...c) => c.filter(Boolean).join(' ')
```
