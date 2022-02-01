---
id: linux.lrztar
title: Lrztar
desc: ''
updated: 1642441815101
created: 1642441815101
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lrztar

> A wrapper for `lrzip` to simplify compression of directories.
> See also: `tar`, `lrzuntar`, `lrunzip`.
> More information: <https://manned.org/lrztar>.

- Archive a directory with `tar`, then compress:

`lrztar {{path/to/directory}}`

- Same as above, with ZPAQ - extreme compression, but very slow:

`lrztar -z {{path/to/directory}}`

- Specify the output file:

`lrztar -o {{path/to/file}} {{path/to/directory}}`

- Override the number of processor threads to use:

`lrztar -p {{8}} {{path/to/directory}}`

- Force overwriting of existing files:

`lrztar -f {{path/to/directory}}`

