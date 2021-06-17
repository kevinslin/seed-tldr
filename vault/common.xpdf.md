---
id: common.xpdf
title: Xpdf
desc: ''
updated: 1623965306216
created: 1623965306216
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xpdf

> Portable Document Format (PDF) file viewer.
> More information: <https://www.xpdfreader.com/xpdf-man.html>.

- Open a PDF file:

`xpdf {{path/to/file.pdf}}`

- Open a specific page in a PDF file:

`xpdf {{path/to/file.pdf}} :{{page_number}}`

- Open a compressed PDF file:

`xpdf {{path/to/file.pdf.tar}}`

- Open a PDF file in fullscreen mode:

`xpdf -fullscreen {{path/to/file.pdf}}`

- Specify the initial zoom:

`xpdf -z {{75}}% {{path/to/file.pdf}}`

- Specify the initial zoom at page width or full page:

`xpdf -z {{page|width}} {{path/to/file.pdf}}`

