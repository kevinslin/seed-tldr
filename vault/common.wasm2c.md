---
id: common.wasm2c
title: Wasm2c
desc: ''
updated: 1615663978739
created: 1615663978739
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wasm2c

> Convert a file from the WebAssembly binary format to a C source file and header.

- Convert a file to a C source file and header and display it to the console:

`wasm2c {{file.wasm}}`

- Write the output to a given file (`file.h` gets additionally generated):

`wasm2c {{file.wasm}} -o {{file.c}}`

