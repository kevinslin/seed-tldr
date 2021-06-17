---
id: common.inkmake
title: Inkmake
desc: ''
updated: 1623965306193
created: 1623965306193
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# inkmake

> GNU Makefile-style SVG exporting using Inkscape's backend.
> More information: <https://github.com/wader/inkmake>.

- Export an SVG file executing the specified Inkfile:

`inkmake {{path/to/Inkfile}}`

- Execute an Inkfile and show detailed information:

`inkmake --verbose {{path/to/Inkfile}}`

- Execute an Inkfile, specifying SVG input file(s) and an output file:

`inkmake --svg {{path/to/file.svg}} --out {{path/to/output_image}} {{path/to/Inkfile}}`

- Specify a custom Inkscape binary to use as the backend:

`inkmake --inkscape {{/Applications/Inkscape.app/Contents/Resources/bin/inkscape}} {{path/to/Inkfile}}`

- Display help:

`inkmake --help`

