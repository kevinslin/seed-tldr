---
id: common.tabula
title: Tabula
desc: ''
updated: 1623965016152
created: 1623965016152
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tabula

> Extract tables from PDF files.
> More information: <https://tabula.technology>.

- Extract all tables from a PDF to a CSV file:

`tabula -o {{file.csv}} {{file.pdf}}`

- Extract all tables from a PDF to a JSON file:

`tabula --format JSON -o {{file.json}} {{file.pdf}}`

- Extract tables from pages 1, 2, 3, and 6 of a PDF:

`tabula --pages {{1-3,6}} {{file.pdf}}`

- Extract tables from page 1 of a PDF, guessing which portion of the page to examine:

`tabula --guess --pages {{1}} {{file.pdf}}`

- Extract all tables from a PDF, using ruling lines to determine cell boundaries:

`tabula --spreadsheet {{file.pdf}}`

- Extract all tables from a PDF, using blank space to determine cell boundaries:

`tabula --no-spreadsheet {{file.pdf}}`

