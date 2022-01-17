---
id: common.grap
title: Grap
desc: ''
updated: 1642441815031
created: 1642441815031
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# grap

> A charting preprocessor for the groff (GNU Troff) document formatting system.
> See also `pic` and `groff`.
> More information: <https://manned.org/grap>.

- Process a `grap` file and save the output file for future processing with `pic` and `groff`:

`grap {{path/to/input.grap}} > {{path/to/output.pic}}`

- Typeset a `grap` file to PDF using the [me] macro package, saving the output to a file:

`grap {{path/to/input.grap}} | pic -T {{pdf}} | groff -{{me}} -T {{pdf}} > {{path/to/output.pdf}}`

