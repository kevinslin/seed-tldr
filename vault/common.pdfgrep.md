---
id: common.pdfgrep
title: Pdfgrep
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
# pdfgrep

> Search text in PDF files.
> More information: <https://pdfgrep.org>.

- Find lines that match pattern in a PDF:

`pdfgrep {{pattern}} {{file.pdf}}`

- Include file name and page number for each matched line:

`pdfgrep --with-filename --page-number {{pattern}} {{file.pdf}}`

- Do a case-insensitive search for lines that begin with "foo" and return the first 3 matches:

`pdfgrep --max-count {{3}} --ignore-case {{'^foo'}} {{file.pdf}}`

- Find pattern in files with a `.pdf` extension in the current directory recursively:

`pdfgrep --recursive {{pattern}}`

- Find pattern on files that match a specific glob in the current directory recursively:

`pdfgrep --recursive --include {{'*book.pdf'}} {{pattern}}`

