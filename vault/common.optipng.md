---
id: common.optipng
title: Optipng
desc: ''
updated: 1642441815054
created: 1642441815054
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# optipng

> PNG file optimization utility.
> More information: <http://optipng.sourceforge.net>.

- Compress a PNG with default settings:

`optipng {{path/to/file.png}}`

- Compress a PNG with the best compression:

`optipng -o{{7}} {{path/to/file.png}}`

- Compress a PNG with the fastest compression:

`optipng -o{{0}} {{path/to/file.png}}`

- Compress a PNG and add interlacing:

`optipng -i {{1}} {{path/to/file.png}}`

- Compress a PNG and preserve all metadata (including file timestamps):

`optipng -preserve {{path/to/file.png}}`

- Compress a PNG and remove all metadata:

`optipng -strip all {{path/to/file.png}}`

