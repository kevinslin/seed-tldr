---
id: osx.md5
title: Osx
desc: ''
updated: 1615663978760
created: 1615663978760
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

