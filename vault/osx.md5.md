---
id: osx.md5
title: Osx
desc: ''
updated: 1623965306235
created: 1623965306235
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# md5

> Calculate MD5 cryptographic checksums.

- Calculate the MD5 checksum for a file:

`md5 {{filename}}`

- Calculate MD5 checksums for multiple files:

`md5 {{filename1}} {{filename2}}`

- Output only the md5 checksum (no filename):

`md5 -q {{filename}}`

- Print a checksum of the given string:

`md5 -s {{string}}`

