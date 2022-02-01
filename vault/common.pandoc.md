---
id: common.pandoc
title: Pandoc
desc: ''
updated: 1642441815055
created: 1642441815055
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pandoc

> Convert documents between various formats.
> More information: <https://pandoc.org>.

- Convert file to PDF (the output format is determined by file extension):

`pandoc {{input.md}} -o {{output.pdf}}`

- Force conversion to use a specific format:

`pandoc {{input.docx}} --to {{gfm}} -o {{output.md}}`

- Convert to a standalone file with the appropriate headers/footers (for LaTeX, HTML, etc.):

`pandoc {{input.md}} -s -o {{output.tex}}`

- List all supported input formats:

`pandoc --list-input-formats`

- List all supported output formats:

`pandoc --list-output-formats`

