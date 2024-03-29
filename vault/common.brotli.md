---
id: common.brotli
title: Brotli
desc: ''
updated: 1642441814999
created: 1642441814999
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# brotli

> Compress/uncompress files with Brotli compression.
> More information: <https://github.com/google/brotli>.

- Compress a file, creating a compressed version next to the file:

`brotli {{file.ext}}`

- Decompress a file, creating an uncompressed version next to the file:

`brotli -d {{file.ext}}.br`

- Compress a file specifying the output filename:

`brotli {{file.ext}} -o {{compressed_file.ext.br}}`

- Decompress a Brotli file specifying the output filename:

`brotli -d {{compressed_file.ext.br}} -o {{file.ext}}`

- Specify the compression level. 1=Fastest (Worst), 11=Slowest (Best):

`brotli -q {{11}} {{file.ext}} -o {{compressed_file.ext.br}}`

