# satisfies — narrowing tanpa kehilangan literal

`const config = { mode: 'kiss' } satisfies Config` — type dicek tapi literal 'kiss' tetap ke-infer. Combo terbaik vs annotation biasa.
