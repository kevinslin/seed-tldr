---
id: common.xetex
title: Xetex
desc: ''
updated: 1642441815084
created: 1642441815084
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xetex

> Compile a PDF document from XeTeX source files.
> More information: <https://www.tug.org/xetex/>.

- Compile a PDF document:

`xetex {{source.tex}}`

- Compile a PDF document, specifying an output directory:

`xetex -output-directory={{path/to/directory}} {{source.tex}}`

- Compile a PDF document, exiting if errors occur:

`xetex -halt-on-error {{source.tex}}`

