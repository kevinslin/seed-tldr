---
id: common.loc
title: Loc
desc: ''
updated: 1642441815042
created: 1642441815042
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# loc

> Tool written in Rust that counts lines of code.
> More information: <https://github.com/cgag/loc>.

- Print lines of code in the current directory:

`loc`

- Print lines of code in the target directory:

`loc {{path/to/directory}}`

- Print lines of code with stats for individual files:

`loc --files`

- Print lines of code without .gitignore (etc.) files (e.g. two -u flags will additionally count hidden files and dirs):

`loc -u`

