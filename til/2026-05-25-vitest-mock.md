# vi.mock hoisting

vi.mock di-hoist — factory function, gak bisa reference luar langsung.

```ts
// dipakai di project
export const cn = (...c) => c.filter(Boolean).join(' ')
```
