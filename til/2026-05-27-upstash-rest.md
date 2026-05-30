# Upstash Redis REST di serverless

REST client = fetch, gak perlu koneksi persist — cocok di edge/serverless. Return null client kalau env kosong → fail-closed di production.

> tambahan: fix — 30 May
