---
id: linux.lrunzip
title: Lrunzip
desc: ''
updated: 1615663978749
created: 1615663978749
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lrunzip

> A large file decompression program.
> See also `lrzip`, `lrztar`, `lrzuntar`.

- Decompress a file:

`lrunzip {{filename.lrz}}`

- Decompress a file using a specific number of processor threads:

`lrunzip -p {{8}} {{filename.lrz}}`

- Decompress a file and silently overwrite files if they exist:

`lrunzip -f {{filename.lrz}}`

- Keep broken or damaged files instead of deleting them when decompressing:

`lrunzip -K {{filename.lrz}}`

- Specify output file name and/or path:

`lrunzip -o {{outfilename}} {{filename.lrz}}`

