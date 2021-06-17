---
id: common.dot
title: Dot
desc: ''
updated: 1623965016121
created: 1623965016121
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dot

> A command-line tool to produce layered drawings of directed graphs.
> More information: <https://www.graphviz.org/pdf/dotguide.pdf>.

- Render an image file and determine output filename based on input filename and selected format:

`dot -Tpng -O {{path/to/file.dot}}`

- Create an SVG from DOT file:

`dot -Tsvg -o {{path/to/out_file.svg}} {{path/to/file.dot}}`

