---
id: common.pdfposter
title: Pdfposter
desc: ''
updated: 1623965306202
created: 1623965306202
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pdfposter

> Convert a large-sheeted pdf into multiple A4 pages for printing.
> More information: <https://pdfposter.readthedocs.io>.

- Convert an A2 poster into 4 A4 pages:

`pdfposter --poster-size a2 {{input_file.pdf}} {{output_file.pdf}}`

- Scale an A4 poster to A3 and then generate 2 A4 pages:

`pdfposter --scale 2 {{input_file.pdf}} {{output_file.pdf}}`

