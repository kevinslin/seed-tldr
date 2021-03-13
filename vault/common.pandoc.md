---
id: common.pandoc
title: Pandoc
desc: ''
updated: 1615655543077
created: 1615655543077
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pandoc

> Convert documents between various formats.
> More information: <https://pandoc.org>.

- Convert file to pdf (the output format is determined by file extension):

`pandoc {{input.md}} -o {{output.pdf}}`

- Force conversion to use a specific format:

`pandoc {{input.docx}} --to {{gfm}} -o {{output.md}}`

- Convert to a standalone file with the appropriate headers/footers (for LaTeX, HTML, etc.):

`pandoc {{input.md}} -s -o {{output.tex}}`

- List all supported input formats:

`pandoc --list-input-formats`

- List all supported output formats:

`pandoc --list-output-formats`

