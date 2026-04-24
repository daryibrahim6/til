# .gitignore negation

`*.log` lalu `!keep.log` — exception butuh parent dir yang tidak ke-ignore.

```ts
// dipakai di project
export const cn = (...c) => c.filter(Boolean).join(' ')
```
