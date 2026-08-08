# discriminated union untuk state machine

`type S = {kind:'idle'}|{kind:'loading'}|{kind:'ok',data:T}|{kind:'err',e:string}` — impossible state jadi unrepresentable.
