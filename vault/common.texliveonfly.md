---
id: common.texliveonfly
title: Texliveonfly
desc: ''
updated: 1623965306213
created: 1623965306213
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# texliveonfly

> Downloads missing TeX Live packages while compiling `.tex` files.
> More information: <https://ctan.org/pkg/texliveonfly>.

- Download missing packages while compiling:

`texliveonfly {{source.tex}}`

- Use a specific compiler (defaults to `pdflatex`):

`texliveonfly --compiler={{compiler}} {{source.tex}}`

- Use a custom TeX Live `bin` folder:

`texliveonfly --texlive_bin={{path/to/texlive_bin}} {{source.tex}}`

