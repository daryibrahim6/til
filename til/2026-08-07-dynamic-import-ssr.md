# dynamic(ssr:false) untuk canvas lib

react-konva/jscanify butuh window — `next/dynamic` + `ssr:false` atau lazy `import()` di handler. Jangan di top-level render.
