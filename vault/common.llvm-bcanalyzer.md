---
id: common.llvm-bcanalyzer
title: Llvm Bcanalyzer
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
# llvm-bcanalyzer

> LLVM Bitcode (`.bc`) analyzer.
> More information: <https://llvm.org/docs/CommandGuide/llvm-bcanalyzer.html>.

- Print statistics about a Bitcode file:

`llvm-bcanalyzer {{path/to/file.bc}}`

- Print an SGML representation and statistics about a Bitcode file:

`llvm-bcanalyzer -dump {{path/to/file.bc}}`

- Read a Bitcode file from `stdin` and analyze it:

`cat {{path/to/file.bc}} | llvm-bcanalyzer`

