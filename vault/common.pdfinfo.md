---
id: common.pdfinfo
title: Pdfinfo
desc: ''
updated: 1623965016142
created: 1623965016142
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pdfinfo

> Portable Document Format (PDF) file information viewer.
> More information: <https://www.xpdfreader.com/pdfinfo-man.html>.

- Print PDF file information:

`pdfinfo {{path/to/file.pdf}}`

- Specify user password for PDF file to bypass security restrictions:

`pdfinfo -upw {{password}} {{path/to/file.pdf}}`

- Specify owner password for PDF file to bypass security restrictions:

`pdfinfo -opw {{password}} {{path/to/file.pdf}}`

