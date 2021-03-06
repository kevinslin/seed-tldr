---
id: common.b2sum
title: B2sum
desc: ''
updated: 1623965306174
created: 1623965306174
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# b2sum

> Calculate BLAKE2 cryptographic checksums.
> More information: <https://www.gnu.org/software/coreutils/b2sum>.

- Calculate the BLAKE2 checksum for a file:

`b2sum {{filename1}}`

- Calculate BLAKE2 checksums for multiple files:

`b2sum {{filename1}} {{filename2}}`

- Read a file of BLAKE2 sums and filenames and verify all files have matching checksums:

`b2sum -c {{filename.b2}}`

- Calculate the BLAKE2 checksum from stdin:

`{{somecommand}} | b2sum`

