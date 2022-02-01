---
id: common.llvm-as
title: Llvm As
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
# llvm-as

> LLVM Intermediate Representation (`.ll`) to Bitcode (`.bc`) assembler.
> More information: <https://llvm.org/docs/CommandGuide/llvm-as.html>.

- Assemble an IR file:

`llvm-as -o {{path/to/out.bc}} {{path/to/source.ll}}`

- Assemble an IR file and include a module hash in the produced Bitcode file:

`llvm-as --module-hash -o {{path/to/out.bc}} {{path/to/source.ll}}`

- Read an IR file from `stdin` and assemble it:

`cat {{path/to/source.ll}} | llvm-as -o {{path/to/out.bc}}`

