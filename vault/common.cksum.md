---
id: common.cksum
title: Cksum
desc: ''
updated: 1642441815002
created: 1642441815002
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cksum

> Calculates CRC checksums and byte counts of a file.
> Note, on old UNIX systems the CRC implementation may differ.
> More information: <https://www.gnu.org/software/coreutils/cksum>.

- Display a 32-bit checksum, size in bytes and filename:

`cksum {{path/to/file}}`

