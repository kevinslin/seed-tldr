---
id: common.ect
title: Ect
desc: ''
updated: 1615663978707
created: 1615663978707
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ect

> Efficient Compression Tool (or ECT) is a C++ file optimizer. It supports PNG, JPEG, GZIP and ZIP files.
> More information: <https://github.com/fhanau/Efficient-Compression-Tool>.

- Compress a file:

`ect {{filename.png}}`

- Compress a file with the highest compression level and multithreading:

`ect -9 --mt-deflate {{filename.png}}`

- Compress all the files in a directory recursively, keeping the original modification time:

`ect -keep -recurse {{directory}}`

