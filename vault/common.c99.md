---
id: common.c99
title: C99
desc: ''
updated: 1623965016115
created: 1623965016115
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# c99

> Compiles C programs according to the ISO C standard.
> More information: <https://manned.org/c99>.

- Compile source file(s) and create an executable:

`c99 {{file.c}}`

- Compile source file(s) and create an executable with a custom name:

`c99 -o {{executable_name}} {{file.c}}`

- Compile source file(s) and create object file(s):

`c99 -c {{file.c}}`

- Compile source file(s), link with object file(s), and create an executable:

`c99 {{file.c}} {{file.o}}`

