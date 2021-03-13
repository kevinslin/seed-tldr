---
id: common.pdflatex
title: Pdflatex
desc: ''
updated: 1615655543077
created: 1615655543077
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pdflatex

> Compile a PDF document from LaTeX source files.
> More information: <https://linux.die.net/man/1/pdflatex>.

- Compile a PDF document:

`pdflatex {{source.tex}}`

- Compile a PDF document specifying an output directory:

`pdflatex -output-directory={{path/to/directory}} {{source.tex}}`

- Compile a PDF document, halting on each error:

`pdflatex -halt-on-error {{source.tex}}`

