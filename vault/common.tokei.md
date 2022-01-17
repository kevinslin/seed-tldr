---
id: common.tokei
title: Tokei
desc: ''
updated: 1642441815077
created: 1642441815077
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tokei

> A program that prints out statistics about code.
> More information: <https://github.com/XAMPPRocky/tokei>.

- Get a report on the code in a directory and all subdirectories:

`tokei {{path/to/directory}}`

- Get a report for a directory excluding `.min.js` files:

`tokei {{path/to/directory}} -e {{*.min.js}}`

- Print out statistics for individual files in a directory:

`tokei {{path/to/directory}} --files`

- Get a report for all files of type Rust and Markdown:

`tokei {{path/to/directory}} -t={{Rust}},{{Markdown}}`

