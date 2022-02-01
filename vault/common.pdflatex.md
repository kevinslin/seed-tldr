---
id: common.pdflatex
title: Pdflatex
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
# pdflatex

> Compile a PDF document from LaTeX source files.
> More information: <https://manned.org/pdflatex>.

- Compile a PDF document:

`pdflatex {{source.tex}}`

- Compile a PDF document specifying an output directory:

`pdflatex -output-directory={{path/to/directory}} {{source.tex}}`

- Compile a PDF document, exiting on each error:

`pdflatex -halt-on-error {{source.tex}}`

