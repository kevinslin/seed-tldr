---
id: common.colorls
title: Colorls
desc: ''
updated: 1642441815003
created: 1642441815003
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# colorls

> A Ruby gem that beautifies the terminal's ls command, with color and font-awesome icons.
> More information: <https://github.com/athityakumar/colorls>.

- List files one per line:

`colorls -1`

- List all files, including hidden files:

`colorls --all`

- Long format list (permissions, ownership, size, and modification date) of all files:

`colorls --long --all`

- Only list directories:

`colorls --dirs`

