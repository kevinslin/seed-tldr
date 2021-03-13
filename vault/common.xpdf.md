---
id: common.xpdf
title: Xpdf
desc: ''
updated: 1615655543094
created: 1615655543094
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

