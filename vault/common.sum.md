---
id: common.sum
title: Sum
desc: ''
updated: 1615663978735
created: 1615663978735
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sum

> Compute checksums and the number of blocks for a file.
> A predecessor to the more modern `cksum`.

- Compute a checksum with BSD-compatible algorithm and 1024-byte blocks:

`sum {{file}}`

- Compute a checksum with System V-compatible algorithm and 512-byte blocks:

`sum --sysv {{file}}`

