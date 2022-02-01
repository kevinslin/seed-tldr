---
id: common.sk
title: Sk
desc: ''
updated: 1642441815069
created: 1642441815069
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sk

> Fuzzy finder written in Rust.
> Similar to `fzf`.
> More information: <https://github.com/lotabout/skim>.

- Start skim on all files in the specified directory:

`find {{path/to/directory}} -type f | sk`

- Start skim for running processes:

`ps aux | sk`

- Start skim with a specified query:

`sk --query "{{query}}"`

- Select multiple files with `Shift + Tab` and write to a file:

`find {{path/to/directory}} -type f | sk --multi > {{filename}}`

