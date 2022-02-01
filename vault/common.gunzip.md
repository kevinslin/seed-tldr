---
id: common.gunzip
title: Gunzip
desc: ''
updated: 1642441815031
created: 1642441815031
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gunzip

> Extract file(s) from a gzip (.gz) archive.
> More information: <https://manned.org/gunzip>.

- Extract a file from an archive, replacing the original file if it exists:

`gunzip {{archive.tar.gz}}`

- Extract a file to a target destination:

`gunzip --stdout {{archive.tar.gz}} > {{archive.tar}}`

- Extract a file and keep the archive file:

`gunzip --keep {{archive.tar.gz}}`

- List the contents of a compressed file:

`gunzip --list {{file.txt.gz}}`

