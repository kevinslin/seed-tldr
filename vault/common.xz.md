---
id: common.xz
title: Xz
desc: ''
updated: 1615663978740
created: 1615663978740
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xz

> Compress or decompress .xz and .lzma files.
> More information: <https://tukaani.org/xz/format.html>.

- Compress a file to the xz file format:

`xz {{file}}`

- Decompress a xz file:

`xz -d {{file.xz}}`

- Compress a file to the lzma file format:

`xz --format=lzma {{file}}`

- Decompress an lzma file:

`xz -d --format=lzma {{file.lzma}}`

- Decompress a file and write to stdout:

`xz -dc {{file.xz}}`

- Compress a file, but don't delete the original:

`xz -k {{file}}`

- Compress a file using the fastest compression:

`xz -0 {{file}}`

- Compress a file using the best compression:

`xz -9 {{file}}`

