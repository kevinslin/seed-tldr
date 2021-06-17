---
id: common.wasm-objdump
title: Wasm Objdump
desc: ''
updated: 1623965016155
created: 1623965016155
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wasm-objdump

> Display information from WebAssembly binaries.

- Display the section headers of a given binary:

`wasm-objdump -h {{file.wasm}}`

- Display the entire disassembled output of a given binary:

`wasm-objdump -d {{file.wasm}}`

- Display the details of each section:

`wasm-objdump --details {{file.wasm}}`

- Display the details of a given section:

`wasm-objdump --section '{{import}}' --details {{file.wasm}}`

