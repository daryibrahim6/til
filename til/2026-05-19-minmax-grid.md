# grid minmax(0,1fr) — fix overflow

`1fr` = `minmax(auto,1fr)` — track gak bisa shrink di bawah content width → canvas/chart fixed-size bikin horizontal scroll. `minmax(0,1fr)` + `min-w-0` di item = fix.
