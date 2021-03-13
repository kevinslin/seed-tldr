---
id: common.m4
title: M4
desc: ''
updated: 1615663978722
created: 1615663978722
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# m4

> Macro processor.
> More information: <https://www.gnu.org/software/m4>.

- Process macros in a file:

`m4 {{path/to/file}}`

- Define a macro before processing files:

`m4 -D{{macro_name}}={{macro_value}} {{path/to/file}}`

