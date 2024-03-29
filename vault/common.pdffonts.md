---
id: common.pdffonts
title: Pdffonts
desc: ''
updated: 1642441815056
created: 1642441815056
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pdffonts

> Portable Document Format (PDF) file fonts information viewer.
> More information: <https://www.xpdfreader.com/pdffonts-man.html>.

- Print PDF file fonts information:

`pdffonts {{path/to/file.pdf}}`

- Specify user password for PDF file to bypass security restrictions:

`pdffonts -upw {{password}} {{path/to/file.pdf}}`

- Specify owner password for PDF file to bypass security restrictions:

`pdffonts -opw {{password}} {{path/to/file.pdf}}`

- Print additional information on location of the font that will be used when the PDF file is rasterized:

`pdffonts -loc {{path/to/file.pdf}}`

- Print additional information on location of the font that will be used when the PDF file is converted to PostScript:

`pdffonts -locPS {{path/to/file.pdf}}`

