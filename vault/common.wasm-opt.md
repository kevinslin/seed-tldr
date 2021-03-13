---
id: common.wasm-opt
title: Wasm Opt
desc: ''
updated: 1615655543092
created: 1615655543092
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# wasm-opt

> Optimize WebAssembly binary files.

- Apply default optimizations and write to a given file:

`wasm-opt -O {{input.wasm}} -o {{output.wasm}}`

- Apply all optimizations and write to a given file (takes more time, but generates optimal code):

`wasm-opt -O4 {{input.wasm}} -o {{output.wasm}}`

- Optimize a file for size:

`wasm-opt -Oz {{input.wasm}} -o {{output.wasm}}`

- Print the textual representation of the binary to console:

`wasm-opt {{input.wasm}} --print`

