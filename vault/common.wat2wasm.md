---
id: common.wat2wasm
title: Wat2wasm
desc: ''
updated: 1623965306215
created: 1623965306215
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wat2wasm

> Convert a file from the WebAssembly text format to the binary format.
> More information: <https://github.com/WebAssembly/wabt>.

- Parse and check a file for errors:

`wat2wasm {{file.wat}}`

- Write the output binary to a given file:

`wat2wasm {{file.wat}} -o {{file.wasm}}`

- Display simplified representation of every byte:

`wat2wasm -v {{file.wat}}`

