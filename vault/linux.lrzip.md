---
id: linux.lrzip
title: Lrzip
desc: ''
updated: 1615663978749
created: 1615663978749
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lrzip

> A large file compression program.
> See also `lrunzip`, `lrztar`, `lrzuntar`.

- Compress a file with LZMA - slow compression, fast decompression:

`lrzip {{filename}}`

- Compress a file with BZIP2 - good middle ground for compression/speed:

`lrzip -b {{filename}}`

- Compress with ZPAQ - extreme compression, but very slow:

`lrzip -z {{filename}}`

- Compress with LZO - light compression, extremely fast decompression:

`lrzip -l {{filename}}`

- Compress a file and password protect/encrypt it:

`lrzip -e {{filename}}`

- Override the number of processor threads to use:

`lrzip -p {{8}} {{filename}}`

