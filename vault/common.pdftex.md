---
id: common.pdftex
title: Pdftex
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
# pdftex

> Compile a PDF document from TeX source files.
> More information: <https://www.tug.org/applications/pdftex/>.

- Compile a PDF document:

`pdftex {{source.tex}}`

- Compile a PDF document, specifying an output directory:

`pdftex -output-directory={{path/to/directory}} {{source.tex}}`

- Compile a PDF document, exiting on each error:

`pdftex -halt-on-error {{source.tex}}`

