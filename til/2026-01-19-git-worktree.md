# git worktree — 2 branch aktif tanpa stash

Buat hotfix tanpa ganggu working tree utama:

```bash
git worktree add ../proj-fix fix/login
```
Folder baru, branch beda, share .git yang sama.

> tambahan: kerjain — 05 Jan
