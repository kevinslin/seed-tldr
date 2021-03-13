---
id: linux.pdfgrep
title: Pdfgrep
desc: ''
updated: 1615655543107
created: 1615655543107
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pdfgrep

> Search text in PDF files.

- Find lines that match pattern in a PDF:

`pdfgrep {{pattern}} {{file.pdf}}`

- Include file name and page number for each matched line:

`pdfgrep --with-filename --page-number {{pattern}} {{file.pdf}}`

- Do a case insensitive search for lines that begin with "foo" and return the first 3 matches:

`pdfgrep --max-count {{3}} --ignore-case {{'^foo'}} {{file.pdf}}`

- Find pattern in files with a `.pdf` extension in the current directory recursively:

`pdfgrep --recursive {{pattern}}`

- Find pattern on files that match a specific glob in the current directory recursively:

`pdfgrep --recursive --include {{'*book.pdf'}} {{pattern}}`

