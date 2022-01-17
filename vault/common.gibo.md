---
id: common.gibo
title: Gibo
desc: ''
updated: 1642441815021
created: 1642441815021
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gibo

> Fetch gitignore boilerplates.
> More information: <https://github.com/simonwhitaker/gibo>.

- List available boilerplates:

`gibo list`

- Write a boilerplate to stdout:

`gibo dump {{boilerplate}}`

- Write a boilerplate to .gitignore:

`gibo dump {{boilerplate}} >>{{.gitignore}}`

- Search for boilerplates containing a given string:

`gibo search {{string}}`

- Update available local boilerplates:

`gibo update`

