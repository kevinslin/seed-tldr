---
id: common.bzip2
title: Bzip2
desc: ''
updated: 1615663978701
created: 1615663978701
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bzip2

> A block-sorting file compressor.
> More information: <http://bzip.org>.

- Compress a file:

`bzip2 {{path/to/file_to_compress}}`

- Decompress a file:

`bzip2 -d {{path/to/compressed_file.bz2}}`

- Decompress a file to standard output:

`bzip2 -dc {{path/to/compressed_file.bz2}}`

