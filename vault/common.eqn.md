---
id: common.eqn
title: Eqn
desc: ''
updated: 1642441815013
created: 1642441815013
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# eqn

> Equation preprocessor for the groff (GNU Troff) document formatting system.
> See also `troff` and `groff`.
> More information: <https://manned.org/eqn>.

- Process input with equations, saving the output for future typesetting with groff to PostScript:

`eqn {{path/to/input.eqn}} > {{path/to/output.roff}}`

- Typeset an input file with equations to PDF using the [me] macro package:

`eqn -T {{pdf}} {{path/to/input.eqn}} | groff -{{me}} -T {{pdf}} > {{path/to/output.pdf}}`

