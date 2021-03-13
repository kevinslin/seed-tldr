---
id: common.lzop
title: Lzop
desc: ''
updated: 1615663978722
created: 1615663978722
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lzop

> Compress or decompress files with LZO compression.
> More information: <https://www.lzop.org/>.

- Compress a file into a new file with the `.lzo` suffix:

`lzop {{file}}`

- Decompress a file:

`lzop -d {{file}}.lzo`

- Compress a file, while specifying the compression level. 0 = Worst, 9 = Best (Default level is 3):

`lzop -{{level}} {{file}}`

