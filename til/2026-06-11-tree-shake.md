# tree shaking

Import named, bukan `import *` — bundle cuma bawa yang dipakai.

```ts
// dipakai di project
export const cn = (...c) => c.filter(Boolean).join(' ')
```
