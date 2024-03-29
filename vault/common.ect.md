---
id: common.ect
title: Ect
desc: ''
updated: 1642441815012
created: 1642441815012
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ect

> Efficient Compression Tool.
> File optimizer written in C++. It supports `.png`, `.jpg`, `.gzip` and `.zip` files.
> More information: <https://github.com/fhanau/Efficient-Compression-Tool>.

- Compress a file:

`ect {{path/to/file.png}}`

- Compress a file with specified compression level and multithreading (1=Fastest (Worst), 9=Slowest (Best), default is 3):

`ect -{{9}} --mt-deflate {{path/to/file.zip}}`

- Compress all files in a directory recursively:

`ect -recurse {{path/to/directory}}`

- Compress a file, keeping the original modification time:

`ect -keep {{path/to/file.png}}`

- Compress a file, stripping metadata:

`ect -strip {{path/to/file.png}}`

