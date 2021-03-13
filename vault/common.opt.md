---
id: common.opt
title: Opt
desc: ''
updated: 1615663978728
created: 1615663978728
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# opt

> A tool that takes LLVM source files and runs specified optimizations and/or analyses on them.
> More information: <https://llvm.org/docs/CommandGuide/opt.html>.

- Run an optimization or analysis on a bitcode file:

`opt -{{passname}} {{path/to/file.bc}} -S -o {{file_opt.bc}}`

- Output the Control Flow Graph of a function to a `.dot` file:

`opt {{-dot-cfg}} -S {{path/to/file.bc}} -disable-output`

- Optimize the program at level 2 and output the result to another file:

`opt -O2 {{path/to/file.bc}} -S -o {{path/to/output_file.bc}}`

