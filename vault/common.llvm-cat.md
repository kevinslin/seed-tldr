---
id: common.llvm-cat
title: Llvm Cat
desc: ''
updated: 1642441815041
created: 1642441815041
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# llvm-cat

> Concatenate LLVM Bitcode (`.bc`) files.
> More information: <https://github.com/llvm/llvm-project/blob/main/llvm/tools/llvm-cat/llvm-cat.cpp>.

- Concatenate Bitcode files:

`llvm-cat {{path/to/file1.bc}} {{path/to/file2.bc}} -o {{path/to/out.bc}}`

