---
id: common.diff-pdf
title: Diff Pdf
desc: ''
updated: 1643296751545
created: 1643296751545
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# diff-pdf

> Tool for comparing two PDFs.
> More information: <https://github.com/vslavik/diff-pdf>.

- Compare PDFs, indicating changes using return codes (`0` = no difference, `1` = PDFs differ):

`diff-pdf {{path/to/a.pdf}} {{path/to/b.pdf}}`

- Compare PDFs, outputting a PDF with visually highlighted differences:

`diff-pdf --output-diff={{path/to/diff.pdf}} {{path/to/a.pdf}} {{path/to/b.pdf}}`

- Compare PDFs, viewing differences in a simple GUI:

`diff-pdf --view {{path/to/a.pdf}} {{path/to/b.pdf}}`

