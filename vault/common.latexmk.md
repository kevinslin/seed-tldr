---
id: common.latexmk
title: Latexmk
desc: ''
updated: 1623965306195
created: 1623965306195
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# latexmk

> Compile LaTeX source files into finished documents.
> Automatically does multiple runs when needed.
> More information: <https://mg.readthedocs.io/latexmk.html>.

- Compile a DVI (Device Independent file) document from every source:

`latexmk`

- Compile a DVI document from a specific source file:

`latexmk {{source.tex}}`

- Compile a pdf document:

`latexmk -pdf {{source.tex}}`

- Force the generation of a document even if there are errors:

`latexmk -f {{source.tex}}`

- Clean up temporary tex files created for a specific tex file:

`latexmk -c {{source.tex}}`

- Clean up all temporary tex files in the current directory:

`latexmk -c`

