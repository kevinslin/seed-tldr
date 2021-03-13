---
id: common.dot
title: Dot
desc: ''
updated: 1615663978706
created: 1615663978706
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dot

> A command-line tool to produce layered drawings of directed graphs.

- Render an image file and determine output filename based on input filename and selected format:

`dot -Tpng -O {{path/to/file.dot}}`

- Create an SVG from DOT file:

`dot -Tsvg -o {{path/to/out_file.svg}} {{path/to/file.dot}}`

