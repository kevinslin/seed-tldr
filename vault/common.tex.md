---
id: common.tex
title: Tex
desc: ''
updated: 1642441815075
created: 1642441815075
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tex

> Compile a DVI document from TeX source files.
> More information: <https://www.tug.org/begin.html>.

- Compile a DVI document:

`tex {{source.tex}}`

- Compile a DVI document, specifying an output directory:

`tex -output-directory={{path/to/directory}} {{source.tex}}`

- Compile a DVI document, exiting on each error:

`tex -halt-on-error {{source.tex}}`

