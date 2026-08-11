# Konva transformer + React refs

Saat list re-render, ref nunjuk node BARU tapi Transformer masih attach node lama → shape 'menghilang' pas di-drag. Fix: re-attach tiap render.

> tambahan: benerin — 04 Aug

> tambahan: riset — 11 Aug
