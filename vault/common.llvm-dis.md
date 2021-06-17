---
id: common.llvm-dis
title: Llvm Dis
desc: ''
updated: 1623965306195
created: 1623965306195
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# llvm-dis

> Converts LLVM bitcode files into human-readable LLVM Intermediate Representation (IR).
> More information: <https://www.llvm.org/docs/CommandGuide/llvm-dis.html>.

- Convert a bitcode file as LLVM IR and write the result to stdout:

`llvm-dis {{path/to/input.bc}} -o -`

- Convert a bitcode file to an LLVM IR file with the same filename:

`llvm-dis {{path/to/file.bc}}`

- Convert a bitcode file to LLVM IR, writing the result to the specified file:

`llvm-dis {{path/to/input.bc}} -o {{path/to/output.ll}}`

