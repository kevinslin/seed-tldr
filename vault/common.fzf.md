---
id: common.fzf
title: Fzf
desc: ''
updated: 1623965016125
created: 1623965016125
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fzf

> Command-line fuzzy finder.
> Similar to `sk`.
> More information: <https://github.com/junegunn/fzf>.

- Start fzf on all files in the specified directory:

`find {{path/to/directory}} -type f | fzf`

- Start fzf for running processes:

`ps aux | fzf`

- Select multiple files with `Shift + Tab` and write to a file:

`find {{path/to/directory}} -type f | fzf --multi > {{filename}}`

- Start fzf with a specified query:

`fzf --query "{{query}}"`

- Start fzf on entries that start with core and end with either go, rb, or py:

`fzf --query "^core go$ | rb$ | py$"`

- Start fzf on entries that not match pyc and match exactly travis:

`fzf --query "!pyc 'travis"`

