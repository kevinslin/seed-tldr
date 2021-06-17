---
id: common.pdfunite
title: Pdfunite
desc: ''
updated: 1623965306203
created: 1623965306203
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pdfunite

> PDF merging utility.
> More information: <https://github.com/mtgrosser/pdfunite>.

- Merge 2 PDFs into a single PDF:

`pdfunite {{path/to/fileA.pdf}} {{path/to/fileB.pdf}} {{path/to/merged_output.pdf}}`

- Merge a directory of PDFs into a single PDF:

`pdfunite {{path/to/directory/*.pdf}} {{path/to/merged_output.pdf}}`

