---
id: common.tbl
title: Tbl
desc: ''
updated: 1642441815075
created: 1642441815075
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tbl

> Table preprocessor for the groff (GNU Troff) document formatting system.
> See also `groff` and `troff`.
> More information: <https://manned.org/tbl>.

- Process input with tables, saving the output for future typesetting with groff to PostScript:

`tbl {{path/to/input_file}} > {{path/to/output.roff}}`

- Typeset input with tables to PDF using the [me] macro package:

`tbl -T {{pdf}} {{path/to/input.tbl}} | groff -{{me}} -T {{pdf}} > {{path/to/output.pdf}}`

