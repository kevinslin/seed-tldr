---
id: common.wasm2wat
title: Wasm2wat
desc: ''
updated: 1615663978739
created: 1615663978739
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wasm2wat

> Convert a file from the WebAssembly binary format to the text format.

- Convert a file to the text format and display it to the console:

`wasm2wat {{file.wasm}}`

- Write the output to a given file:

`wasm2wat {{file.wasm}} -o {{file.wat}}`

