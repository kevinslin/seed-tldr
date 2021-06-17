---
id: common.ls
title: Ls
desc: ''
updated: 1623965016135
created: 1623965016135
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ls

> List directory contents.
> More information: <https://www.gnu.org/software/coreutils/ls>.

- List files one per line:

`ls -1`

- List all files, including hidden files:

`ls -a`

- List all files, with trailing `/` added to directory names:

`ls -F`

- Long format list (permissions, ownership, size, and modification date) of all files:

`ls -la`

- Long format list with size displayed using human readable units (KiB, MiB, GiB):

`ls -lh`

- Long format list sorted by size (descending):

`ls -lS`

- Long format list of all files, sorted by modification date (oldest first):

`ls -ltr`

- Only list directories:

`ls -d {{*/}}`

