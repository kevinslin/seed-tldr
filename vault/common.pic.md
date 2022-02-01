---
id: common.pic
title: Pic
desc: ''
updated: 1642441815057
created: 1642441815057
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pic

> Picture preprocessor for the groff (GNU Troff) document formatting system.
> See also `groff` and `troff`.
> More information: <https://manned.org/pic>.

- Process input with pictures, saving the output for future typesetting with groff to PostScript:

`pic {{path/to/input.pic}} > {{path/to/output.roff}}`

- Typeset input with pictures to PDF using the [me] macro package:

`pic -T {{pdf}} {{path/to/input.pic}} | groff -{{me}} -T {{pdf}} > {{path/to/output.pdf}}`

