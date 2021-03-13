---
id: common.nl
title: Nl
desc: ''
updated: 1615663978726
created: 1615663978726
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nl

> A utility for numbering lines, either from a file, or from standard input.

- Number non-blank lines in a file:

`nl {{file}}`

- Read from standard output:

`cat {{file}} | nl {{options}} -`

- Number only the lines with printable text:

`nl -t {{file}}`

- Number all lines including blank lines:

`nl -b a {{file}}`

- Number only the body lines that match a basic regular expression (BRE) pattern:

`nl -b p'FooBar[0-9]' {{file}}`

