---
id: common.qpdf
title: Qpdf
desc: ''
updated: 1615663978731
created: 1615663978731
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qpdf

> Versatile PDF transformation software.
> More information: <https://github.com/qpdf/qpdf>.

- Extract pages 1-3, 5 and 6-10 from a PDF file and save them as another one:

`qpdf --empty --pages {{input.pdf}} {{1-3,5,6-10}} -- {{output.pdf}}`

- Merge (concatenate) all the pages of a list of PDF files and save the result as a new PDF:

`qpdf --empty --pages {{file1.pdf}} {{file2.pdf}} {{file3.pdf}} -- {{output.pdf}}`

- Merge (concatenate) given pages from a list of PDF files and save the result as a new PDF:

`qpdf --empty --pages {{file1.pdf}} {{1,6-8}} {{file2.pdf}} {{3,4,5}} -- {{output.pdf}}`

- Write each group of n pages to a separate output file with a given filename pattern:

`qpdf --split-pages=n {{input.pdf}} {{out_%d.pdf}}`

- Rotate certain pages of a pdf with a given angle:

`qpdf --rotate={{90:2,4,6}} --rotate={{180:7-8}} {{input.pdf}} {{output.pdf}}`

- Remove the password from a password protected file:

`qpdf --password={{password}} --decrypt {{input.pdf}} {{output.pdf}}`
