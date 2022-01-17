---
id: common.mat2
title: Mat2
desc: ''
updated: 1642441815046
created: 1642441815046
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mat2

> Anonymise various file formats by removing metadata.
> More information: <https://0xacab.org/jvoisin/mat2>.

- List supported file formats:

`mat2 --list`

- Remove metadata from a file:

`mat2 {{path/to/file}}`

- Remove metadata from a file and print detailed output to the console:

`mat2 --verbose {{path/to/file}}`

- Show metadata in a file without removing it:

`mat2 --show {{path/to/file}}`

- Partially remove metadata from a file:

`mat2 --lightweight {{path/to/file}}`

