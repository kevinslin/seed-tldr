---
id: common.pdf-parser
title: Pdf Parser
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
# pdf-parser

> Identify fundamental elements of a PDF file without rendering it.
> More information: <https://blog.didierstevens.com/programs/pdf-tools>.

- Display statistics for a PDF file:

`pdf-parser --stats {{path/to/file.pdf}}`

- Display objects of type `/Font` in a PDF file:

`pdf-parser --type={{/Font}} {{path/to/file.pdf}}`

- Search for strings in indirect objects:

`pdf-parser --search={{search_string}} {{path/to/file.pdf}}`

