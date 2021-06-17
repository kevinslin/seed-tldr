---
id: common.md5sum
title: Common
desc: ''
updated: 1623965016136
created: 1623965016136
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# md5sum

> Calculate MD5 cryptographic checksums.
> More information: <https://www.gnu.org/software/coreutils/md5sum>.

- Calculate the MD5 checksum for a file:

`md5sum {{filename1}}`

- Calculate MD5 checksums for multiple files:

`md5sum {{filename1}} {{filename2}}`

- Read a file of MD5SUMs and verify all files have matching checksums:

`md5sum -c {{filename.md5}}`

- Calculate a MD5 checksum from the standard input:

`echo "{{text}}" | md5sum`

