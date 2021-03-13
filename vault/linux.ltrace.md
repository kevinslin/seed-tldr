---
id: linux.ltrace
title: Ltrace
desc: ''
updated: 1615663978749
created: 1615663978749
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ltrace

> Display dynamic library calls of a process.
> More information: <https://linux.die.net/man/1/ltrace>.

- Print (trace) library calls of a program binary:

`ltrace ./{{program}}`

- Count library calls. Print a handy summary at the bottom:

`ltrace -c {{path/to/program}}`

- Trace calls to malloc and free, omit those done by libc:

`ltrace -e malloc+free-@libc.so* {{path/to/program}}`

- Write to file instead of terminal:

`ltrace -o {{file}} {{path/to/program}}`

